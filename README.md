# MongoDB
I try to learn about CURD OPERATION on MongoDB
#  MongoDB Database Project

##  Description
This project demonstrates how to create and manage a database using MongoDB. It includes basic database operations such as inserting, reading, updating, and deleting data.

---

##  Features
- Create and use databases:<img width="1881" height="983" alt="Screenshot 2026-03-26 105850" src="https://github.com/user-attachments/assets/b572deaa-2462-4f86-8112-bed352d9405b" />
-insert:<img width="1881" height="983" alt="Screenshot 2026-03-26 105850" src="https://github.com/user-attachments/assets/482fc652-e103-4c63-8c41-46b2335480c4" />
-read:<img width="1881" height="983" alt="Screenshot 2026-03-26 105850" src="https://github.com/user-attachments/assets/9c41c80a-1bf2-45b1-aadb-bae951aa2723" />
- update:<img width="1902" height="998" alt="Screenshot 2026-03-26 105943" src="https://github.com/user-attachments/assets/389cb34b-8dc4-4fce-9c2f-f70986d4cf92" />

- delete:<img width="1901" height="1000" alt="Screenshot 2026-03-26 110002" src="https://github.com/user-attachments/assets/935a231e-5fba-4d97-ab0b-dbdf36fc2cbc" />

- drop:<img width="1872" height="995" alt="Screenshot 2026-03-26 110111" src="https://github.com/user-attachments/assets/4bf14215-75dd-4387-b4b0-aea713cb60c1" />


---

##  Requirements
- MongoDB
- MongoDB Shell (mongosh)

---

##  Installation & Setup

1. Install MongoDB on your system

2. Start MongoDB server:
   mongod

3. Open MongoDB shell:
   mongosh

4. Create or switch to a database:
   use myDatabase

---

##  Project Structure
Database: myDatabase

Collections:
- users
- products
- orders

---

##  Sample Document

{
  "name": "John Doe",
  "age": 25,
  "email": "john@example.com"
}

---

##  CRUD Operations

### Insert
db.users.insertOne({ name: "Alice", age: 22 })

### Read
db.users.find()

### Update
db.users.updateOne(
  { name: "Alice" },
  { $set: { age: 23 } }
)

### Delete
db.users.deleteOne({ name: "Alice" })

---

##  Objective
- Learn MongoDB basics  
- Understand NoSQL database structure  
- Perform database operations  

---

##  License
This project is for educational purposes.
#project
-your name:mallikarjun
