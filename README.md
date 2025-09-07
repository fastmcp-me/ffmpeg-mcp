[![Add to Cursor](https://fastmcp.me/badges/cursor_dark.svg)](https://fastmcp.me/MCP/Details/862/ffmpeg-media-tools)
[![Add to VS Code](https://fastmcp.me/badges/vscode_dark.svg)](https://fastmcp.me/MCP/Details/862/ffmpeg-media-tools)
[![Add to Claude](https://fastmcp.me/badges/claude_dark.svg)](https://fastmcp.me/MCP/Details/862/ffmpeg-media-tools)
[![Add to ChatGPT](https://fastmcp.me/badges/chatgpt_dark.svg)](https://fastmcp.me/MCP/Details/862/ffmpeg-media-tools)
[![Add to Codex](https://fastmcp.me/badges/codex_dark.svg)](https://fastmcp.me/MCP/Details/862/ffmpeg-media-tools)
[![Add to Gemini](https://fastmcp.me/badges/gemini_dark.svg)](https://fastmcp.me/MCP/Details/862/ffmpeg-media-tools)

# ffmpeg-mcp

A stdio MCP server to interact with ffmpeg for common media operations.

This project is sponsored by [ChatWise](https://chatwise.app) - All-in-one LLM Chatbot with MCP support.

## Usage

You need [ffmpeg](https://www.ffmpeg.org/) installed on your system first.

Then add the following command to your MCP client:

```
npx -y ffmpeg-mcp
```

By default it uses `ffmpeg` from your system path. You can also specify the path to `ffmpeg` by setting the `FFMPEG_PATH` environment variable, like:

```
FFMPEG_PATH=/path/to/ffmpeg
```

## Tools

View [tools.ts](./tools.ts)

More tools to come.

## License

MIT.
