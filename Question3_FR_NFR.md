# Question 3: Functional & Non-Functional Requirements

## Functional Requirements (FR)

### FR 1: User Authentication & Authorization
- The system shall allow users (admin, coach, player, tournament coordinator) to log in using secure credentials and access features according to their role.

### FR 2: Manage User Accounts
- The admin shall be able to create, update, deactivate, and assign roles to system users.

### FR 3: Player Profile Management
- The system shall allow coaches and admins to add, edit, and view player personal data, medical information, and training categories.

### FR 4: Training Schedule Management
- Coaches shall be able to create weekly training schedules and assign them to individual players or teams.

### FR 5: Training Attendance Recording
- Coaches shall be able to record and update player training attendance.

### FR 6: Player Performance Recording
- Coaches shall be able to record and update player performance metrics such as speed, agility, stamina, shooting accuracy, or custom criteria.

### FR 7: Performance Progress Visualization
- Players and coaches shall be able to view graphs and charts showing performance trends over time.

### FR 8: Tournament Creation and Management
- Tournament coordinators shall be able to create tournaments, define match fixtures, assign teams or players, and manage venues.

### FR 9: Match Score Entry & Ranking Update
- The system shall allow coordinators to submit match scores and automatically update leaderboards, rankings, or tournament brackets.

### FR 10: Injury & Medical Record Management
- Physiotherapists or coaches shall be able to log injury details, upload medical reports, and set training restrictions for players.

### FR 11: Notifications & Messaging System
- The system shall send notifications to players and coaches regarding schedules, tournament updates, and performance feedback.

### FR 12: Report Generation
- The system shall generate summary reports such as performance reports, attendance reports, and tournament results for printing or export.

---

## Non-Functional Requirements (NFR)

### NFR 1: Performance
- The system shall respond to user actions within 3 seconds under normal network conditions.

### NFR 2: Reliability & Availability
- The system shall provide 99% uptime and ensure all stored player performance data remains accessible at all times.

### NFR 3: Security
- The system shall use encrypted communication (HTTPS/SSL) and implement role-based access control to protect sensitive player data.

### NFR 4: Usability
- The system shall have a user-friendly interface that can be easily used by non-technical users such as coaches and players.

### NFR 5: Scalability
- The system shall support an increasing number of users, players, and tournaments without performance degradation.

### NFR 6: Maintainability
- The system shall be designed using modular architecture to simplify future updates, debugging, and enhancements.
