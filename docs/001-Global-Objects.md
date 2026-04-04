# Global Objects

## Global Objects

- User \- authenticated user in the system
- Project \- a project created to store a tree of components and documents
- Component \- can store multiple documents
- Document \- a mark up text document
- Project Tree \-  parent child relationship of components

Example Project Tree:

```markdown
Mobile Banking App (project)
├── Overview (component)
│   ├── Summary (document)
│   └── Stakeholders (document)
├── Functional Requirements (group)
│   ├── Authentication (component)
│   │   ├── Login Flow (document)
│   │   └── MFA Requirements (document)
│   └── Payments (group)
│       ├── Transfer Rules (document)
│       └── Transaction Limits (document)
└── Technical Requirements (component)
    ├── Coding Standards (document)
    └── API Contracts (document)
```