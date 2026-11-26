# ALLYK Diagnostics for Claude

ALLYK Diagnostics gives founders and entrepreneurs a focused next customer check before they build, price, or change an offer.

The plugin connects Claude to ALLYK's public Diagnostics MCP service. It can:

- preview an advisory diagnostic from the business context you provide;
- save a review to a task you choose in ALLYK Roadmap;
- show bounded history for the task you selected.

The service exposes only Diagnostics operations. It does not expose ALLYK conversations, files, credentials, private calculations, internal agents, billing data, or arbitrary actions. Results are advisory and do not verify evidence or execute work.

## Access and privacy

Sign in through ALLYK's OAuth consent screen when Claude asks. Do not paste passwords, API keys, workspace tokens, cookies, or private credentials into chat. The host sends the diagnostic context and receives the returned review; ALLYK stores saved reviews under the account and task you select.

Diagnostics assessments use no ALLYK credits and do not require a model key. An eligible ALLYK trial or paid plan and normal service limits still apply. Host usage charges, if any, are controlled by Claude or your provider.

You can revoke a connection from [ALLYK plugin connections](https://allyk.app/plugins/connections). Read the [privacy policy](https://allyk.app/privacy) and [terms](https://allyk.app/terms) before installing.

## Distribution

This repository is both the plugin and its Claude Code marketplace. To install it in Claude Code after reviewing its files:

```
claude plugin marketplace add mayayaiinfra/allyk-diagnostics-claude-plugin
claude plugin install allyk-diagnostics@allyk-diagnostics
```

Inside a Claude Code session you can use `/plugin marketplace add mayayaiinfra/allyk-diagnostics-claude-plugin` instead. Availability in Anthropic's plugin directory is subject to Anthropic review.

## License

This package is proprietary to MAYAYAI. See [LICENSE](LICENSE).
