<p align="center">
  <img src="https://static.cdn.nolio.io/nolio/images/nolio_logo_circle.png" alt="Nolio" width="96">
</p>

# Nolio MCP server (official)

Official MCP server for the [Nolio](https://www.nolio.io) app, the training platform for endurance coaches, clubs and athletes. Plan, analyze and coach endurance, strength and Hyrox training from ChatGPT, Claude or any MCP client, in plain language.

This repository only documents the server. Nolio hosts and runs it, so there is nothing to install or deploy.

```
https://mcp.nolio.io/mcp
```

Transport: Streamable HTTP. Authentication: OAuth 2.1, you sign in with your Nolio account.

## What you can do

- Read the planned and completed calendar, yours or your athletes': workouts, races, training cycles, notes and questionnaires.
- Compare what was planned with what was done: duration, distance, RPE and the athlete's debrief.
- Plan workouts for one athlete or a whole group, including structured workouts that Nolio can send to compatible watches.
- Apply workout templates from your library and create new ones.
- Follow training load, metrics (HRV, resting heart rate, sleep, weight) and intensity zones.
- Undo a creation or a deletion.

## Connect

**Claude**: install Nolio from the [Claude connector directory](https://claude.ai/directory/nolio).

**ChatGPT and other MCP clients**: add a custom connector (remote MCP server) with the URL above, then sign in with your Nolio account.

## Access and safety

- You choose what the assistant may do when you sign in: read, create, update, delete.
- A coach only sees the athletes they coach. A team can restrict what its coaches can do.
- Deletions and multi-event changes go through a server-side preview step before anything is saved.
- Data from some connected services is not passed on to AI assistants, in line with those services' terms.

Requires a paid Nolio account, coach or athlete.

## Official listings

- MCP Registry: `io.nolio/nolio`
- Claude: [claude.ai/directory/nolio](https://claude.ai/directory/nolio)

Other "Nolio" MCP servers are built by third parties and are not supported by Nolio.

## Support

[www.nolio.io](https://www.nolio.io)
