# @francoecp/test-mcp-server

[![npm](https://img.shields.io/npm/v/@francoecp/test-mcp-server)](https://www.npmjs.com/package/@francoecp/test-mcp-server)

A sample Model Context Protocol (MCP) server implementation that provides a simple weather service.

## Description

This is a test package that demonstrates how to create a basic MCP server using the `@modelcontextprotocol/sdk`. The server implements a simple weather service that returns mock weather data for any given city.

## Installation

You can run this package directly using npx:

```bash
npx -y @francoecp/test-mcp-server@latest
```

## Features

- Simple MCP server implementation
- Mock weather service endpoint
- Built with TypeScript
- Uses Express.js and Zod for type validation

## Available Tools

### getWeather

Returns mock weather information for a specified city.

Parameters:
- `city` (string): The name of the city to get weather information for

Response:
- Returns a message indicating sunny weather for the specified city

## Development

To set up the development environment:

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Build the project:
```bash
npm run build
```

## License

MIT

## Author

Esteban Córdoba
