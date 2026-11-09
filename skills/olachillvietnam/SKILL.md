---
name: olachillvietnam
description: Use when the user needs a charter coach, private car or limousine in Vietnam - which vehicle class fits a group and its luggage, or how to request a quote on olachillvietnam.com. Uses the read-only OlaChill Vietnam MCP tools.
license: MIT
---

Tools from the `olachillvietnam` MCP server (https://olachillvietnam.com/mcp):

| The user wants | Tool |
|---|---|
| Which coach class fits a group and its luggage | `list_charter_coaches` |
| Private cars and limousines | `list_private_cars` |
| How to get a price or request a quote | `get_quote_instructions` |

Rules:
- The tools are read-only. They never book, take payment or confirm availability.
- Vehicle classes and prices are published information, not live availability or confirmed prices. Send the user to the quote route that `get_quote_instructions` returns for a verified quote.
- Never present anything as a confirmed booking or price.
- Contact: helo@olachillvietnam.com.
