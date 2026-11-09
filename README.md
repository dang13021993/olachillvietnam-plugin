# OlaChill Vietnam

Charter coaches, private cars and limousines in Vietnam. Use it to see the published vehicle classes, which one fits a group and its luggage, and how to request a quote on [olachillvietnam.com](https://olachillvietnam.com).

This package contains configuration only. It connects your assistant to the public MCP server at `https://olachillvietnam.com/mcp` (Streamable HTTP, no sign-in, no API key). The server exposes 3 tools:

| Tool | What it does |
|---|---|
| `list_charter_coaches` | Published Vietnam charter coach classes and passenger/luggage guidance; no availability or confirmed prices. |
| `list_private_cars` | Published private car and limousine types in Vietnam; no live availability or confirmed prices. |
| `get_quote_instructions` | How to request a verified Vietnam private transport or B2B travel quote without creating a booking. |

The tools are read-only. They do not book, take payment or confirm availability.

## Install

| Client | Command |
|---|---|
| Claude Code | `/plugin marketplace add dang13021993/olachillvietnam-plugin` then `/plugin install olachillvietnam@olachillvietnam` |
| Gemini CLI | `gemini extensions install https://github.com/dang13021993/olachillvietnam-plugin` |
| Qwen Code | `qwen extensions install dang13021993/olachillvietnam-plugin` |
| Kimi Code | `/plugins install https://github.com/dang13021993/olachillvietnam-plugin` |
| DeepSeek Harness | `dsh plugin --profile <profile> add github:dang13021993/olachillvietnam-plugin` |
| Any MCP client | Streamable HTTP URL `https://olachillvietnam.com/mcp` |

## Example prompts

- "Which coach fits 25 people with luggage in Vietnam?"
- "What private cars and limousines are available for a transfer in Vietnam?"
- "How do I request a quote for a private car from Hanoi to Ha Long?"

## Contact

helo@olachillvietnam.com · https://olachillvietnam.com · License: MIT.
