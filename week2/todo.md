# CODE!
>main.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Multi-Task To-Do List</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h2>To-Do List</h2>

  <input id="taskInput" type="text" placeholder="Enter tasks separated by commas" />
  <button id="addBtn">Add Tasks</button>

  <ul id="taskList"></ul>

  <script src="script.js"></script>
</body>
</html>
```
>style.css
```
body {
  font-family: Arial, sans-serif;
  padding: 20px;
  max-width: 600px;
  margin: auto;
}

input {
  width: 70%;
  padding: 10px;
  font-size: 16px;
  margin-right: 10px;
}

button {
  padding: 10px 16px;
  font-size: 16px;
}

ul {
  list-style: none;
  padding-left: 0;
  margin-top: 20px;
}

li {
  background: #f8f8f8;
  padding: 12px;
  margin: 8px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-radius: 4px;
}

li.done {
  text-decoration: line-through;
  color: gray;
  background-color: #e0ffe0;
}

.btn {
  margin-left: 10px;
  padding: 5px 10px;
  border: none;
  cursor: pointer;
  border-radius: 4px;
}

.done-btn {
  background-color: green;
  color: white;
}

.remove-btn {
  background-color: red;
  color: white;
}

.done-msg {
  color: green;
  font-style: italic;
  margin-left: 10px;
}
```
>script.js
```
document.getElementById("addBtn").onclick = function () {
  const input = document.getElementById("taskInput");
  const tasks = input.value.split(',').map(task => task.trim()).filter(task => task !== "");

  const taskList = document.getElementById("taskList");

  tasks.forEach(taskText => {
    const li = document.createElement("li");

    const taskSpan = document.createElement("span");
    taskSpan.textContent = taskText;

    const doneMsg = document.createElement("span");
    doneMsg.className = "done-msg";

    // Done button
    const doneBtn = document.createElement("button");
    doneBtn.textContent = "Done";
    doneBtn.className = "btn done-btn";
    doneBtn.onclick = function () {
      li.classList.toggle("done");
      doneMsg.textContent = li.classList.contains("done") ? "This task is done!" : "";
    };

    // Remove button
    const removeBtn = document.createElement("button");
    removeBtn.textContent = "Remove";
    removeBtn.className = "btn remove-btn";
    removeBtn.onclick = function () {
      li.remove();
    };

    li.appendChild(taskSpan);
    li.appendChild(doneBtn);
    li.appendChild(removeBtn);
    li.appendChild(doneMsg);

    taskList.appendChild(li);
  });

  input.value = "";
  input.focus();
};
```
>OUTPUT
![image](https://github.com/user-attachments/assets/05e7ae85-f52f-4bdc-a20d-a04a175923d8)
![image](https://github.com/user-attachments/assets/2afdfd23-6cad-4d5a-8f71-9db9cc441efe)

