# LibraTrack — Lesson 9 (Auth, JWT, RBAC)

Secured REST API: bcrypt, JWT (`JWT_SECRET`), roles reader/librarian/admin.

Public: register, login, GET books.
Protected: GET /api/v1/me/loans
Staff: POST /api/v1/staff/books
Admin: users list and role update

See `security_design.txt`, `security_audit.md`, `prompts.txt`.
