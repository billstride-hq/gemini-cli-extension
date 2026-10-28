# Billstride for Gemini CLI

This extension connects [Gemini CLI](https://github.com/google-gemini/gemini-cli) to [Billstride](https://billstride.com/mcp), pay-per-invoice invoicing. Create, send and track invoices from a conversation: reuse last month's invoice, chase overdue payments, see revenue, and export e-invoices (ZUGFeRD, XRechnung) and DATEV.

It adds one remote MCP server, `https://billstride.com/api/mcp` (streamable HTTP), with 27 tools. Billstride serves 25 countries, including the US, Canada and the EU.

## Install

```bash
gemini extensions install https://github.com/billstride-hq/gemini-cli-extension
```

## Sign in

Nothing to configure and no API key. The first time Gemini CLI connects, the server answers with a sign-in request and the CLI opens your browser to sign in to Billstride over OAuth. Gemini CLI keeps the token for later sessions. If the browser does not open, run `/mcp auth billstride`.

Sign-up is open. Your first invoice is free, then each finalized invoice is paid from prepaid credit, with no subscription. New invoices are drafts, and invoices and payment reminders are emailed to your clients only when you ask.

## Links

- Docs: https://billstride.com/mcp
- Privacy: https://billstride.com/en/privacy
- Support: https://billstride.com/en/support
- Official MCP Registry: `com.billstride/billstride`
