# -IBCITC-DBMS-Project
This repository contains the design and implementation of a database management system for IBC International Training Center (IBCITC). The project covers database design, an ER diagram, relational modeling, and SQL commands to streamline operations, manage employee records, and optimize training programs.

This project focuses on the development and implementation of a database management system (DBMS) for the IBC International Training Center (IBCITC). The objective of the system is to streamline the management of educational and logistical operations across multiple programs and locations. The project involves creating an efficient database for scheduling training sessions, booking rooms, managing employee records, and optimizing resource allocation.

The database has been designed to support various stakeholders, including instructors, administrative staff, program coordinators, and IT staff, and aims to improve the decision-making processes and operational efficiency of the organization.

### Objectives
1. **Management of Employee Records:** Including instructors and administrative staff.
2. **Course Scheduling and Room Allocation:** Ensuring conflict-free booking of rooms and timeslots for training programs.
3. **Resource Management:** Optimizing the use of technologies, training rooms, and tools based on instructors’ expertise and program requirements.
4. **Program and Event Coordination:** Supporting the planning, scheduling, and execution of training sessions and program-related events.

### Features
1. **Referential Integrity:** The use of foreign keys and constraints ensures strong referential integrity between related tables, reducing anomalies and maintaining accurate relationships between entities.
2. **Scalability:** The database is structured to easily accommodate new programs, locations, and employees.
3. **Detailed Record Keeping:** Comprehensive records for instructors, including their expertise in technological tools, allow for better resource allocation and customized training plans.
4. **Modularity:** The design allows for future improvements, such as tracking historical performance data of instructors and optimizing program scheduling.

### Improvements Suggested
1. **Refining Relationships:** Refining the relationships between entities to capture more granular information, such as tracking the performance and feedback of instructors across multiple programs.
2. **Optimized Attributes:** Reviewing and optimizing the attributes stored for each entity to ensure they meet the most frequent query requirements.
3. **Access Control:** Implementing dynamic access control based on relationships between entities, ensuring secure and streamlined resource allocation.

### Impact on Stakeholders
1. **Instructors:** The database improves their ability to manage schedules, allocate rooms, and access tools needed for training sessions.
2. **Administrative Staff:** Enhanced data structures and efficient scheduling reduce their workload, allowing them to focus on higher-level strategic activities.
3. **IT Staff:** Simplified system management through improved data integrity, reducing errors and downtime.
4. **Management:** Allows for better decision-making with more detailed reporting on program performance, instructor efficiency, and resource utilization.

### Repository Structure
- `Detailed_Report.pdf` - Full project report, including objectives, assumptions, ER diagrams, relational models, and SQL commands.
- `ER_Diagram.png` - The entity-relationship (ER) diagram illustrating the relationships between different entities in the database.
- `Relational_Model.png` - A PDF detailing the relational model derived from the ER diagram.
- `SQL_Commands.txt` - A list of SQL commands used for creating tables, querying the database, and performing other operations.

  ### Findings
1. **Enhanced Resource Management:** The database optimizes the allocation of resources, including rooms, tools, and instructor availability, reducing conflicts in scheduling.
2. **Improved Data Integrity:** The use of foreign keys and constraints maintains strong referential integrity, ensuring accurate and consistent data across the system.
3. **Customizable Reporting:** The detailed structure of the database allows management to generate customized reports on instructor performance, program efficiency, and resource utilization.
4. **Operational Efficiency:** Administrative tasks such as scheduling and room booking are streamlined, significantly reducing manual effort and the possibility of human error.

### Conclusion
This database management system provides a scalable and efficient solution for managing the logistical and operational requirements of IBCITC. By improving scheduling, resource management, and program coordination, the database system helps reduce administrative workload, improve decision-making, and ensure the effective use of available resources.


### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/-IBCITC-DBMS-Project.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com

