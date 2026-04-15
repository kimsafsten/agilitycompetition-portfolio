# Technical Decisions

## Why React + TypeScript
Type safety and component-driven UI made it easier to keep multiple role-based views consistent and maintainable.

## Why ASP.NET Core + EF Core
Strong support for REST APIs, authentication/authorization, and robust data access patterns for business workflows.

## Why PostgreSQL
Reliable relational model for entities like competitions, classes, entries, and results.

## Why split frontend/backend/domain
- Frontend: user interaction and view state
- Backend: API orchestration and security
- Domain: reusable rules and business models

This separation improved clarity, testing potential, and long-term extensibility.
