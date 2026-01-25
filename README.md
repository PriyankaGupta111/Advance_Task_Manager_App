## 🔁 Application Flow

Application Load

User browser me application open karta hai

React app render hoti hai

Existing tasks localStorage se fetch hoke UI me display hote hain

2️⃣ Add New Task

User task input field me task likhta hai

“Add Task” button click karta hai

Task React state me add hota hai

Updated task list localStorage me save ho jaati hai

UI automatically re-render hoti hai

3️⃣ View Tasks

Saare tasks list ke form me dikhte hain

Har task ka apna status hota hai (pending / completed)

4️⃣ Update / Edit Task

User kisi task ko edit karta hai

Task state update hota hai

Updated data dubara localStorage me store hota hai

UI bina page reload ke update hoti hai

5️⃣ Delete Task

User delete button click karta hai

Selected task state se remove ho jaata hai

localStorage update hoti hai

Task list UI se hat jaati hai instantly

6️⃣ Data Persistence

localStorage use hone ki wajah se:

Page refresh ke baad bhi tasks delete nahi hote

Data browser me persist rehta hai
