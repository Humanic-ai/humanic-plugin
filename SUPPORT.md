# Humanic Plugin Support

- Email: TODO (add the team support address)
- Docs: https://docs.humanic.ai
- Issues with the MCP connection (sign-in, tools not loading): email us with your client (Cursor, Claude, ChatGPT, etc.) and the time it happened.

## Troubleshooting
- **Sign-in loops or fails:** remove the Humanic connector and add it again; this restarts OAuth.
- **Tools return 401:** your access key expired (keys last 90 days). Reconnect to sign in again.
- **Campaign won't activate:** check sender domain DNS (SPF, DKIM, DMARC) in the Humanic app first.
