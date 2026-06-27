<!DOCTYPE html>
<html>
<head>
    <title>AI Study Planner</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>📚 AI Study Planner</h1>

<div class="box">

    <input id="task" placeholder="Enter study topic">

    <input id="time" type="time">

    <button onclick="addTask()">Add Task</button>

    <h3>📅 Your Schedule</h3>
    <ul id="list"></ul>

    <h3>🧠 Smart Suggestion</h3>
    <p id="suggestion">Add a task to get suggestion</p>

</div>

<script src="script.js"></script>
</body>
</html>
