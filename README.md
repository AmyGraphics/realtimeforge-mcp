# RealtimeForge MCP Server ⚡🔄📡

Universal Autonomous Real-Time Infrastructure, WebSocket/SSE, Multiplayer Presence & Pub/Sub Engine MCP Server for **Cursor, Claude Code, Windsurf, and Autonomous AI Agents**.

## 🌟 Core Capabilities:
- 👑 **Master 1-Shot Outcome Engine (`autonomous_realtime_architecture_and_stack_planner`):** Ingests the use case (chat app, live dashboard, multiplayer editor, IoT telemetry) and expected concurrent users to synthesize an entire production realtime stack in one call: transport selection matrix (WebSocket vs SSE vs WebRTC), ASCII topology diagram, channel/room design, scale-out fan-out plan, and deployment guide.
- 🔌 **WebSocket Gateway Generator (`generate_websocket_gateway_server`):** Production-ready Cloudflare Durable Objects or Node ws gateway with JWT handshake, heartbeat keep-alive, room broadcasting, plus a typed React `useRealtimeRoom` hook with exponential-backoff auto-reconnect.
- 🖱️ **Presence & Live Cursors Builder (`build_presence_and_live_cursors`):** Figma-style multiplayer layer using the Y.js awareness protocol: throttled cursor broadcasting, online avatars, typing indicators, and stale-peer cleanup with IndexedDB offline persistence.
- 📡 **SSE Stream Endpoint Deployer (`deploy_sse_stream_endpoint`):** Server-Sent Events endpoints with ReadableStream backpressure handling, Last-Event-ID resume replay, keep-alive frames, and a matching `useEventSource` React hook.
- 📣 **Pub/Sub Channel Orchestrator (`orchestrate_pubsub_channels_and_rooms`):** Designs the cross-server fan-out backbone (Redis pub/sub & Streams, Durable Objects, Ably/Pusher comparison) with channel naming conventions, envelope versioning, and dead-letter retry policy.

## 🚀 Server URL
`https://realtimeforge-api.agentweb-hub.workers.dev/mcp`
