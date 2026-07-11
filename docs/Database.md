# Database

## Target Platform
SQL Server is the primary persistent store for the platform.

## Data Design Principles
- Normalize transactional data where it matters
- Index based on common query paths
- Keep foreign key relationships explicit
- Separate reference data from user-generated data

## Planned Areas
- Identity and access data
- Course catalog and learning content
- Enrollment and progress tracking
- Assessment results and reporting
- Audit and operational metadata

## Maintenance Notes
- Version schema changes through migrations
- Back up database changes with rollback planning
- Review performance on growth-sensitive queries
