<!--
  ~ Copyright (c) 2023-2024 Datalayer, Inc.
  ~
  ~ BSD 3-Clause License
-->

[![Datalayer](https://assets.datalayer.tech/datalayer-25.svg)](https://datalayer.io)

[![Become a Sponsor](https://img.shields.io/static/v1?label=Become%20a%20Sponsor&message=%E2%9D%A4&logo=GitHub&style=flat&color=1ABC9C)](https://github.com/sponsors/datalayer)

# 🪐 ✨ Jupyter MCP Server

[![Github Actions Status](https://github.com/datalayer/jupyter-mcp-server/workflows/Build/badge.svg)](https://github.com/datalayer/jupyter-mcp-server/actions/workflows/build.yml)
[![PyPI - Version](https://img.shields.io/pypi/v/jupyter-mcp-server)](https://pypi.org/project/jupyter-mcp-server)
[![smithery badge](https://smithery.ai/badge/@datalayer/jupyter-mcp-server)](https://smithery.ai/server/@datalayer/jupyter-mcp-server)

**Jupyter MCP Server** is a [Model Context Protocol](https://modelcontextprotocol.io) (MCP) server implementation that provides interaction with 📓 Jupyter notebooks running in any JupyterLab (works also with your 💻 local JupyterLab).

Key features include:

- ⚡ **Real-time control**: view the notebook change in real-time.
- 🔁 **Smart execution**: automatically adjusts when a cell run fails.
- 🤝 **MCP-Compatible**: compatible with any MCP clients like Claude Desktop, Cursor, Windsurf, and more.

![Jupyter MCP Server](https://assets.datalayer.tech/jupyter-mcp/jupyter-mcp-server-claude-demo.gif)

To get started:

- 📘 Follow the [Usage Guide](TODO) to use Jupyter-MCP-server with a MCP compatible client.
- 🧰 Dive into the [Tools](TODO) documentation section to understand the tools powering the server.

Looking for blog posts, videos or other resources related to Jupyter MCP Server? <br/>
👉 Check out the [Resources](TODO) documentation section.

## Building from Source

You can build the Docker image it from source.

```bash
make build-docker
```
