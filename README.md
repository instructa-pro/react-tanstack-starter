# 🏝️ TanStack Starter Template + MCP

# Example MCP Project

# Prerequisites

https://nodejs.org/en

https://www.cursor.com/

https://www.docker.com/products/docker-desktop/

https://pnpm.io/installation

<aside>
<img src="https://www.notion.so/icons/info-alternate_blue.svg" alt="https://www.notion.so/icons/info-alternate_blue.svg" width="40px" />

Start Docker Desktop!

</aside>

# 1. Install the starter

```markdown
git clone git@github.com:instructa-pro/react-tanstack-starter.git
```

```markdown
pnpm install
```

# 2. Get Client Secrets & Add Credentials

| Github Client Secret | [https://github.com/settings/applications/new](https://github.com/settings/applications/new) |
| --- | --- |

Copy `.env.example` to `.env`

1. Generate Github Client Secret → `GITHUB_CLIENT_ID` & `GITHUB_CLIENT_SECRET`
2. Generate a Better Auth Secret: [`https://www.better-auth.com/docs/installation`](https://www.better-auth.com/docs/installation)

Add this to `.env`

```markdown
VITE_BASE_URL=http://localhost:3000

DATABASE_URL="postgresql://user:password@localhost:5432/tanstarter"
BETTER_AUTH_SECRET=<INSERT HERE>
GITHUB_CLIENT_ID=<INSERT HERE>
GITHUB_CLIENT_SECRET=<INSERT HERE>
```

# 3. Start Container and initialize DB

```markdown
pnpm db push
```

# 4. Docker Compose Up

```markdown
docker compose up
```

# 5. Start the dev server

```markdown
pnpm dev
```

# MCP Servers

```markdown
MCP Servers
https://github.com/mendableai/firecrawl-mcp-server
https://github.com/modelcontextprotocol/servers/tree/main/src/postgres
https://github.com/AgentDeskAI/browser-tools-mcp
```
