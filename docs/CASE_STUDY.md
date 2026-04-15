# Case Study

## Context
Agility clubs need a reliable way to handle registration, administration, and result publishing with minimal manual overhead.

## Goal
Build a fullstack system that supports the complete flow from registration to result publication, with role-specific interfaces.

## My responsibilities
- System design and architecture
- Backend API design and implementation
- Database modeling with EF Core + PostgreSQL
- Frontend implementation in React + TypeScript
- Deployment setup (Vercel/Render/Neon)

## Challenges and solutions
1. Challenge: Different user roles needed different workflows.
   Solution: Split UI into public/admin/secretary flows with clear boundaries and protected routes.

2. Challenge: Competition-day updates must be fast and safe.
   Solution: Dedicated secretary view with focused actions for run state updates.

3. Challenge: Keep domain logic maintainable.
   Solution: Shared domain layer and service boundaries for rules and query/command separation.

## Outcome
- End-to-end web application deployed in cloud
- Reduced manual handling by centralizing core competition workflows
- Improved maintainability through clear frontend/backend/domain structure

## Next steps
- Add analytics and event audit logs
- Expand automated tests for critical workflows
- Add export/reporting support for clubs
