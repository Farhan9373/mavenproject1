# Maven Practical

## Commands used
- mvn clean
- mvn compile
- mvn package
- mvn site

## Clean Lifecycle vs Default Lifecycle

### Clean Lifecycle
The Clean Lifecycle is responsible for cleaning the project workspace.
- Main goal: `clean`
- What it does: Deletes the `target/` directory (removes compiled classes, packaged jars, reports, etc.)
- Typical use: Start fresh before a new build

Example:
```bash
mvn clean