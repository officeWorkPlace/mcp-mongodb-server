# mcp-mongodb-server

Java + Maven scaffold for a MongoDB MCP server.

## Prerequisites
- Java 17+
- Maven 3.9+

## Build
```powershell
mvn -q clean package
```

## Run
```powershell
java -jar target/mcp-mongodb-server-0.1.0-SNAPSHOT.jar
```

## Test
```powershell
mvn -q test
```

## Next steps
- Wire up MongoDB driver and MCP protocol handling.
- Add configuration (connection string, DB name) via env vars or CLI flags.
- Implement MCP tools/resources for MongoDB operations.
