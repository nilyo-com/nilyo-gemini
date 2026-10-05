# Nilyo for Gemini CLI

Search and read your own LinkedIn, WhatsApp, Instagram, Telegram and Email accounts through Nilyo's common remote MCP. Selected read tools only; provider/account capabilities and limits apply.

Create an individual personal token at https://nilyo.com/account and connect your accounts there. Install with `gemini extensions install https://github.com/nilyo-com/nilyo-gemini`. The installation setting requests your Nilyo token as a sensitive value; do not enter it into a model conversation. Never use a Unipile key. Restart Gemini CLI, inspect `/mcp`, and ask “Which accounts are connected to Nilyo?”

No xAI or Gemini API credential is embedded in this package. Gemini CLI uses its own configured model access. The extension sends the Nilyo token only to `https://nilyo.com/mcp`; the runtime controls model processing/history. Review results privately. Disconnect accounts or revoke the token from your Nilyo account to stop future access.

Examples:

- Which accounts are connected to Nilyo?
- Read the LinkedIn profile at this URL.
- Summarize the latest email from Sarah after resolving the correct message.
- Summarize WhatsApp messages received today and tell me whether the result is complete.

Documentation: https://nilyo.com/setup-for-agents · Support: https://nilyo.com/support · Privacy: https://nilyo.com/privacy · Terms: https://nilyo.com/terms

Prepared package version 0.1.0. Manifest/contracts are checked locally; installation, secret expansion/keychain behavior and real read/revocation tests in Gemini CLI remain release gates. This package is not yet published or certified by Google.

## Release status

Preview 0.1.0. Public preview submitted for automatic Gemini CLI gallery discovery. Appearance in the gallery depends on Google crawler validation. Real Gemini CLI installation, token expansion/keychain behavior, bounded reads and revocation remain validation gates.
