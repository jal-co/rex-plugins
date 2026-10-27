# Provenance

The task runtime, shared CLI/MCP tools, adapter boundary and nested task panels were written for this repository. They do not copy or depend on the bundled pi-herdr-agents host.

`plugins/session-pins/session-pins.mjs`, its tests and the Lua event subscription were extracted from the existing personal dotfiles Rex plugin at the owner's request. The extraction changes executable discovery, configuration paths and state defaults so they no longer depend on the personal installation. The action names are prefixed to avoid collisions. The original installed files are unchanged.

The current Pi-specific coordinator remains in dotfiles. Its runtime records, private session transcripts, PR database, Git checkouts, credentials and personal configuration were not copied into this repository.

This is a private repository. A distribution license and upstream attribution review are required before public redistribution, especially if later stages reuse code from the existing Herdr-derived host.
