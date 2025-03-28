# MCP Client TypeScript

A TypeScript implementation of the Model Context Protocol (MCP) client that integrates with Claude AI for natural language processing and tool execution.

## Features

- Integration with Claude AI for natural language processing
- Support for executing MCP tools
- Interactive chat interface
- TypeScript support for better type safety

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Anthropic API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mcp-client-typescript.git
cd mcp-client-typescript
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your Anthropic API key:
```
ANTHROPIC_API_KEY=your_api_key_here
```

## Usage

1. Build the project:
```bash
npm run build
```

2. Run the client with a server script:
```bash
node build/index.js <path_to_server_script>
```

The server script should be a Python or JavaScript file that implements the MCP server protocol.

## Development

- `npm run build`: Compiles TypeScript to JavaScript
- `npm test`: Runs tests (currently not implemented)

## License

ISC 