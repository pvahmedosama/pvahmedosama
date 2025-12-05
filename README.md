# Portfolio: Software Engineering & Database Architecture
**Author:** Ahmed Osama
**Role:** Computer Science Student | Aspiring .NET Full Stack Developer

---

## 1. Professional Profile
I am a dedicated **Computer Science Student** at **Menoufia National University**, passionately transitioning from a background in Data Analysis to **Backend Engineering**. My focus lies in designing robust **Database Architectures**, writing clean **C#** code, and mastering the **.NET ecosystem**. I combine mathematical logic with software engineering principles to build scalable solutions.

---

## 2. Technical Expertise
| Domain | Technologies & Skills |
| :--- | :--- |
| **Backend & Core** | C#, .NET Core (Learning), OOP, Data Structures, Algorithms |
| **Database Design** | SQL Server, MongoDB, Entity Relationship Diagrams (ERD), Normalization (1NF-3NF) |
| **Data & Tools** | Python, Pandas, Jupyter Notebooks, Git, GitHub, VS Code |

---

## 3. Architectural Case Study: NHL League System
**Project Type:** Conceptual Database Design (ERD)

### The Challenge
Designing a relational database for the National Hockey League (NHL) required handling complex recursive relationships and strict data integrity rules regarding team compositions and match history.

### Architectural Decisions & Logic
* **Recursive Captaincy Constraint (1:1):** Modeled the "Captain" logic as a recursive one-to-one relationship on the `Player` entity, ensuring strictly one captain per team.
* **Weak Entity Handling:** The `Injury_Record` was designed as a Weak Entity dependent on `Player`, ensuring that injury history cannot exist without a parent player record.
* **Match Logic (Home/Away):** Instead of a single "Game" link, I implemented two distinct relationships (`Hosts` and `Guests`) between `Team` and `Game`. This allows for precise querying of home-ground advantages and venue-specific statistics.

**[PLACEHOLDER: Insert NHL ERD Image Here]**

---

## 4. Architectural Case Study: University Registrar System
**Project Type:** Academic System Schema Design

### The Challenge
Modeling a university system necessitated handling Many-to-Many relationships with attributes (grades) and complex course prerequisite chains.

### Architectural Decisions & Logic
* **The "Enrollment" Associative Entity:** To solve the Many-to-Many relationship between `Student` and `Course_Offering`, I introduced an Associative Entity (`Enrolls`) that holds the `Grade` attribute. This adheres to Third Normal Form (3NF).
* **Recursive Prerequisites:** Modeled course dependencies (`Prerequisites`) as a recursive Many-to-Many relationship on the `Course` entity, allowing for infinite dependency chains (e.g., CS101 -> CS102 -> CS201).
* **Flexible Offerings:** Decoupled `Course` (static data) from `Course_Offering` (dynamic semester data) to allow the same course to be taught by different instructors in different terms.

**[PLACEHOLDER: Insert University ERD Image Here]**

---

## 5. Software Development Projects
* **Python Real-Time Chat App:** Developed a GUI-based chat application using Python, implementing socket programming for real-time message transmission and private messaging capabilities.
* **Nexus IoT Monitor:** Built a multi-threaded TCP/IP monitoring ecosystem for tracking sensor data, demonstrating proficiency in concurrency and network protocols.
* **Sales Data Analysis:** Conducted Exploratory Data Analysis (EDA) on superstore sales data using Pandas and Matplotlib to uncover profit trends and shipping bottlenecks.

---

## 6. Certified Credentials
My journey is backed by verified certifications from recognized institutions:

* **Introduction to MongoDB** – *Information Technology Institute (ITI)* (Nov 30, 2025).
* **AI Fundamentals** – *DataCamp* (Nov 29, 2025).
* **Introduction to Python** – *DataCamp* (Aug 01, 2025).
* **The Complete HTML Course** – *Udemy* (Oct 09, 2025).

**[PLACEHOLDER: Insert Certificate Images Here]**

---

## 7. Contact Information
* **GitHub:** github.com/pvahmedosama
* **LinkedIn:** linkedin.com/in/ahmed-osama-b4078b389
* **Email:** ahmed4real9@gmail.com
