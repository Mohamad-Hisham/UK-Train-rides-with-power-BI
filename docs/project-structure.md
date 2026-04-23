# Phase 1 — Proposed Project Folder Structure

```txt
.
├── apps
│   ├── admin-web
│   │   └── src
│   │       ├── app
│   │       │   ├── (auth)
│   │       │   │   └── login
│   │       │   ├── (dashboard)
│   │       │   │   ├── dashboard
│   │       │   │   ├── sessions
│   │       │   │   ├── users
│   │       │   │   ├── students
│   │       │   │   ├── groups
│   │       │   │   ├── community
│   │       │   │   ├── tickets
│   │       │   │   ├── survey
│   │       │   │   ├── surveys
│   │       │   │   ├── quizzes
│   │       │   │   ├── assessments
│   │       │   │   ├── reports
│   │       │   │   └── settings
│   │       │   ├── api
│   │       │   ├── globals.css
│   │       │   └── layout.tsx
│   │       ├── components
│   │       │   ├── layout
│   │       │   ├── table
│   │       │   ├── forms
│   │       │   ├── charts
│   │       │   └── ui
│   │       ├── features
│   │       │   ├── auth
│   │       │   ├── dashboard
│   │       │   ├── sessions
│   │       │   ├── users
│   │       │   ├── students
│   │       │   ├── groups
│   │       │   ├── community
│   │       │   ├── tickets
│   │       │   ├── survey
│   │       │   ├── quizzes
│   │       │   ├── assessments
│   │       │   └── reports
│   │       ├── hooks
│   │       ├── lib
│   │       ├── providers
│   │       ├── styles
│   │       └── types
│   └── api
│       ├── prisma
│       │   ├── schema.prisma
│       │   ├── seed.ts
│       │   └── migrations
│       └── src
│           ├── config
│           ├── common
│           │   ├── dto
│           │   ├── middleware
│           │   ├── guards
│           │   └── utils
│           └── modules
│               ├── auth
│               ├── users
│               ├── roles
│               ├── permissions
│               ├── students
│               ├── groups
│               ├── sessions
│               ├── attendance
│               ├── community
│               ├── tickets
│               ├── surveys
│               ├── quizzes
│               ├── assessments
│               ├── reports
│               ├── imports
│               └── exports
├── packages
│   ├── ui
│   ├── config
│   └── types
└── docs
    ├── stitch-ui-structure.md
    ├── pages-components-inventory.md
    └── project-structure.md
```
