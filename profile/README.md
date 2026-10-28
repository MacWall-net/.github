# MacWall

**See what your AI tools send.**

MacWall is a network monitor and firewall for macOS. It shows every network connection your Mac makes (which app made it, where it goes, which country the server is in, and how much data went out) and lets you decide which ones are allowed.

> **Status: beta.** MacWall is in active development. When it's released, the app will be open-sourced.

- **See every connection:** a live log of TCP and UDP connections with the app, process chain, remote host, country and byte counts
- **Block, Allow and Ask rules** written as short queries, such as `proc = "curl" AND dir = out`
- **FQL**, a readable query language for your traffic
- **Built-in MCP server and CLI**, so AI agents and scripts can query connections and manage rules
- **Private by design:** logs and rules stay on your Mac. No account, analytics or tracking.

[macwall.net](https://macwall.net/) · [Support](https://macwall.net/support/) · [Privacy Policy](https://macwall.net/privacy/)

## Contributing

Found a bug, or have an idea for MacWall? [Open an issue](https://github.com/MacWall-net/macwall.net/issues). Bug reports, feature requests and feedback on the beta are all welcome.

## Repositories

- [macwall.net](https://github.com/MacWall-net/macwall.net): the website
