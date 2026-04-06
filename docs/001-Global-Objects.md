# Global Objects

### Global Objects

The Global Objects represent the core entities within the system, defining the structure and relationships necessary for capturing and organizing software requirements\. From user authentication to the hierarchical Project Tree, these objects facilitate a seamless workflow for requirement management and AI\-driven software generation\.

- User \- authenticated user in the system
- Project \- a project created to store a tree of components and documents
- Project Tree \-  parent child relationship of components
- Component \- can store multiple documents
- Document \- a mark up text document
- User Settings \- settings applied for the user, can be shared with other users, and the value can be marked as secret\.
- App Settings \- application wide settings accessed by the admins only

Example Project Tree:

```markdown
RGI (project)
├── Overview (component)
│   ├── Project Vision (document)
│   └── Global Objects (document)
├── UI (group)
│   ├── Core UI (component)
│   │   ├── Theme (document)
│   │   └── UIElements (document)
└── Page Views
│   ├── Guest (component)
│   │   ├── LoginPage (document)
│   ├── Authenticated (component)
│   │   └── Dashboard (document)
│── Database (component)
│   └── DatabaseSchema (component)
│── Business Rules (component)
│   └── Business Rules (document)
```