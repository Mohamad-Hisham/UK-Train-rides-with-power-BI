# Phase 1 — Pages & Components Inventory

## Route map (Admin LMS)

### Public
- `/login`

### Protected
- `/dashboard`
- `/sessions`
- `/sessions/[id]`
- `/users`
- `/students`
- `/students/[id]`
- `/groups`
- `/groups/[id]`
- `/community`
- `/tickets`
- `/tickets/[id]`
- `/survey`
- `/survey/[id]`
- `/surveys`
- `/quizzes`
- `/quizzes/[id]`
- `/assessments`
- `/assessments/[id]`
- `/reports`
- `/settings/roles`
- `/settings/permissions`
- `/settings/profile`

## Shared components
- `AppShell`
- `SidebarNav`
- `Topbar`
- `PageHeader`
- `StatCard`
- `StatusBadge`
- `DataTable` (TanStack wrapper)
- `DataToolbar` (search/filter/actions)
- `FormDialog`
- `ConfirmDialog`
- `EmptyState`
- `ErrorState`
- `LoadingState`
- `ExportButton`
- `ImportDropzone`
- `LanguageToggle`

## Module components

### Dashboard
- `KpiGrid`
- `SessionsTrendChart`
- `AttendanceChart`
- `RecentActivityList`

### Sessions
- `SessionFilters`
- `SessionForm`
- `SessionAttendanceSheet`
- `SessionExportPanel`

### Users
- `UserForm`
- `UserRoleMatrix`
- `UserImportDialog`

### Students
- `StudentForm`
- `StudentAttendanceHistory`
- `StudentImportDialog`

### Groups
- `GroupForm`
- `GroupAssignmentPanel`
- `GroupMembersTable`

### Community
- `PostComposer`
- `PostCard`
- `ModerationQueue`

### Tickets
- `TicketFilters`
- `TicketThread`
- `TicketReplyBox`

### Survey
- `SurveyBuilder`
- `QuestionEditor`
- `SurveyResponsesTable`
- `SurveyAnalyticsChart`

### Quizzes / Assessments
- `QuizForm`
- `AssessmentForm`
- `SubmissionTable`
- `PerformanceChart`

### Reports
- `ReportGenerator`
- `ExportHistoryTable`

## Cross-cutting infrastructure components
- Auth guard + permission guard
- Pagination + sorting helpers
- Query key factory
- Zod schema + form adapters
- File upload parser (CSV/Excel)
