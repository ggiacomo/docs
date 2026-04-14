# RemoteAgent.CHAT — Documentation

Documentation for [remoteagent.chat](https://remoteagent.chat), built with [Mintlify](https://mintlify.com).

## Preview locally

```bash
npm i -g mintlify
mintlify dev
```

Opens at `http://localhost:3000`.

## Structure

```
├── docs.json                  # Mintlify config (navigation, theme, colors)
├── introduction.mdx
├── getting-started/
│   ├── quickstart.mdx
│   ├── pairing.mdx
│   └── best-practices.mdx
├── runners/                   # One page per runner (claude-code, gemini, aider…)
├── bot/                       # Telegram bot usage
├── under-the-hood/            # Architecture, security, services
├── cli-reference.mdx
├── dashboard.mdx
├── pricing.mdx
└── faq.mdx
```

## Contributing

Edit the `.mdx` files and open a PR. Changes merged to `main` deploy automatically.
