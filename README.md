# MCP-Project-Scaffolder-
This mcp server generates a starter directory structure with the right files. All you need to do is to give it a project name and the language you'll be using.

## Environment and Tools
Python (FastMCP), Docker, Claude Code, Node.js, JSON-RPC over stdio.

## Approach
- Designed a lightweight MCP server with structured JSON outputs for reliable tool responses
- Chose stdio transport for simple, local integration with Claude Code
- Containerized the server with Docker to ensure reproducible environments
- Integrated via CLI instead of GUI to streamline development and reduce setup friction
- Prioritized security by validating inputs, isolating filesystem access, and accounting for known MCP vulnerabilities

## Results / Artifacts
- Built an MCP server that scaffolds projects in Python, Node, and Go
- Created a Dockerized workflow for consistent deployment
- Achieved seamless CLI integration with Claude Code
- Validated tool functionality through local testing and MCP Inspector

## Future Plans
- Add stronger input validation (e.g., prevent path traversal)
- Expand the toolset beyond scaffolding
- Implement automated tests for tool functions
- Publish the Docker container for easier reuse and distribution

