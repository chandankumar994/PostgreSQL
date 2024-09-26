# Data Models

## ERD (Entity-Relationship Diagrams)
An **ERD (Entity-Relationship Diagram)** is a visual representation of how data is structured in a database. It shows the **entities** (things we want to store information about) and the **relationships** between them. 

### Here’s a simple breakdown:

1. **Entity**: An entity is anything you want to keep track of in your database. Think of it like a table. For example, in a school database, entities might be **Students**, **Courses**, and **Teachers**.
   - Each entity has **attributes**, which are the details or properties you store about that entity. For example, a **Student** entity might have attributes like **StudentID**, **Name**, and **Age**.

2. **Relationship**: This shows how entities are connected to each other. For example, a **Student** can **enroll** in a **Course**. The **enroll** part is the relationship between the **Student** and the **Course**.

3. **Cardinality**: It explains the type of relationship between entities:
   - **One-to-One**: One entity is related to only one other entity. Example: A **person** has one **passport**.
   - **One-to-Many**: One entity can be related to many entities. Example: A **teacher** can teach many **courses**.
   - **Many-to-Many**: Many entities are related to many others. Example: Many **students** can enroll in many **courses**.

### Example ERD:
- **Entities**: Students, Courses, Teachers.
- **Relationships**:
  - A **Student** can enroll in **Courses** (many-to-many relationship).
  - A **Teacher** can teach multiple **Courses** (one-to-many relationship).

### What It Looks Like:
An ERD usually consists of rectangles for entities, ovals for attributes, and diamonds for relationships. Lines are drawn between these shapes to represent how they are connected.

In simple terms, an ERD is like a blueprint or map for how the data in your database is structured and connected, making it easier to design and understand the database.

Example:

![image](https://github.com/user-attachments/assets/7a4a2079-bed6-47c9-a831-f83294d9be9f)

