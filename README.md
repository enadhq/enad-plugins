# Enad MCP

Use Enad from Claude Code or Codex to search Enad documentation and work with the product catalog in an Enad app you can access.

## Claude Code

```bash
claude plugin marketplace add enadhq/enad-plugins
claude plugin install enad-mcp@enad
```

Start a new Claude Code session and open `/mcp`. Select **Enad** to authenticate.

## Codex

```bash
codex plugin marketplace add enadhq/enad-plugins
codex plugin add enad-mcp@enad
```

Start a new Codex session. Use `/mcp` in the CLI or the plugin's connection controls in the desktop app to check the connection. Sign in when prompted.

## Connect your Enad app

Sign in with your Enad account and choose the app you want to connect. The available catalog operations depend on the access you grant and your app's settings.

Try asking **“Use Enad to find the documentation on attribute templates.”**

If you already configured Enad MCP directly in the same client, you can keep using that connection. Both setup methods use the same service at `https://mcp.enad.io/mcp`.

## Support

For Enad questions, email [support@enad.io](mailto:support@enad.io).
