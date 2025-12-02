# Architecture

### Reasons for Choosing a 3-Tier Architecture

## Clear separation of responsibilities

# Each layer handles a well-defined role:

- Front-end → user interface & interactions

- API → communication, security, access control

- Back-end → business logic & data processing

- This structure keeps the code organized, readable, and easier to maintain.

---

### Enhanced security

# Sensitive operations and data are isolated:

- The client can never access the database directly.

- The API checks tokens and validates permissions.

--- 

### Easier maintenance

# Because layers are independent, you can:

- fix issues without affecting other parts

---

### Technological flexibility

# Each layer can use the most appropriate technology:

- Front-end: HTML/CSS/JavaScript/React

- API: Node.js

- Back-end: Node.js or Java Spring

- Databases: SQL + NoSQL

---