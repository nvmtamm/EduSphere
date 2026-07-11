# Coding Convention

## General Rules
- Prefer clear naming over clever shorthand
- Keep functions small and focused
- Separate orchestration from business logic
- Avoid coupling UI, API, and persistence concerns

## Backend Conventions
- Use explicit request and response contracts
- Validate inputs at the boundary
- Keep domain logic framework-agnostic when possible
- Favor dependency injection for external services

## Frontend Conventions
- Keep components reusable and composable
- Centralize shared UI behavior where practical
- Use predictable state flow and naming
- Keep presentation logic separate from data access

## Review Standard
- Each change should be easy to test
- New files should match the tone and structure of existing documentation
- Public APIs and database changes should be documented
