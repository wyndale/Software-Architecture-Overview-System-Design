# Software Architecture Overview & System Design

## 🚀 Introduction  
This repository demonstrates the **complete implementation** of a Software Architecture Overview & System Design designed to fulfill all requirements outlined in the project activity. Below is a breakdown of how each task was addressed, along with deliverables and artifacts.

---

## ✅ Tasks Completed  
### 1. **Architectural Style Analysis**  
   - Reviewed different software architectural styles
   - Summarized their advantages and disadvantages in a table format.
   - (/docs/Software-Architectural-Styles.pdf)

   - Select an existing software system [Facebook]
   - Identified and describe the architecture style it follows.
   - Created a basic block diagram illustrating its components and interactions.
   - (/docs/Software-System---Facebook.pdf)

   - Choose a software application we use daily [Spotify]
   - Identified its key components and their relationships.
   - Created a UML component diagram showcasing its architecture.
   - (/docs/Software-Application---Spotify.pdf)
   - UML Component Diagram (/docs/Spotify---UML-Component-Diagram.pdf)

### 2. **Library System Design**  
   - Designed a simple library management system.
   - Identified the functional and non-functional requirements of the system.
   - Break down the system into smaller subsystems.
   - Defined parameters such as max books borrowed per user, database scalability needs, and performance considerations.
   - Compared different database models (Relational vs NoSQL) and discuss trade-offs.
   - Justified the chosen database model based on scalability and maintainability.
   - (/docs/Library-Management-System---Design.pdf)

### 3. **High-level Prototype UI**  
   -  Sketch a simple high-level prototype UI for book search and borrowing.
   -  (/sketch/Library-Management-System.pdf) - PDF of the sketch.
   -  (/sketch/Library-Management-System.vis) - Visily file.

### 4. **UML Diagrams for the library management system**  
   - **Use Case Diagram**: Actors (User, Librarian) and core interactions.  
   - **Class Diagram**: User, Book, Loan classes with relationships.  
   - **Sequence Diagram**: Book borrowing workflow.  
   - **Component Diagram**: System components and their interactions.

### 5. **Entity Relationship Diagram**
- Though ERD is not a UML diagram I included the Entity
Relationship Diagram (ERD) to visually represent the
structure and relationships of the Library Management
System. It clearly defines how key entities like Users,
Books, Loans, and Fines interact, ensuring efficient data
management for borrowing, returning, and tracking
overdue penalties. This helps in designing a
well-organized system that is easy to develop, maintain,
and scale.

---

## Project Structure
- `diagrams/`: UML Diagrams and ERD
- `docs/`: Documents (report) and Analysis
- `sketch/`: Prototype UI
