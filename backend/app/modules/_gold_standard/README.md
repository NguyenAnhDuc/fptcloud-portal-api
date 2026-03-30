# Gold Standard Module — STUB

> This is a placeholder. Gold standard will be the first well-reviewed
> Flask module after POC completion (target: customer-feedback module itself).
>
> For now, follow rules in .claude/rules/ directory.

## Pattern to follow (stub)

1. Blueprint-based Flask module
2. SQLAlchemy model with UUID PK, created_at/updated_at
3. Service layer separates business logic from routes
4. Input validation on all endpoints
5. Standardized error responses: {"error": "CODE", "message": "..."}
6. pytest coverage: happy path + validation error + auth error
