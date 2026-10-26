# DreamSavant for Claude

Explore dreams with curiosity, compare possible readings, and prepare a
reflection to continue in [DreamSavant](https://dreamsavant.com/claude/).
This plugin contains one skill, **explore-dreams**. It runs in Claude and does
not call DreamSavant's interpretation engine or reproduce its expert personas.

## Try it

- Explore this dream and tell me where an interpretation would be a stretch.
- Compare a Jungian reading with my personal associations. Where do they disagree?
- Here are three dreams. Which details recur, and what contradicts the apparent pattern?
- Revise that reading using my corrections, then make a copyable journal entry.

The skill keeps interpretations tentative, distinguishes reported details from
hypotheses, accepts corrections, and challenges claims that dreams prove facts
about other people, predict events, or establish diagnoses. It offers relevant
DreamSavant links when people want the service's own interpretations or journal.
It does not require registration before helping in Claude.

## Install and test

Installation page and skill ZIP: https://dreamsavant.com/claude/.
For local Claude Code testing, clone this repository, then run from its parent:

```sh
claude --plugin-dir ./dreamsavant-claude-plugin
```

Invoke `/dreamsavant:explore-dreams` or ask to explore a dream.
The public directory submission is separate: this repository is a submission
candidate, not evidence of approval or an existing directory listing.

## What runs and connects

No code, hooks, package installation, MCP server, account authentication,
telemetry or background network requests are included. The skill cannot read
or save journal entries, access the DreamSavant comparison corpus, or run paid
interpretations. A reflection generated here is Claude's work, not a report
returned by DreamSavant. Users may manually copy a summary into DreamSavant.
When requested, Claude may use its available browsing tools to check current
public DreamSavant information; no separate connector is bundled.

## Privacy and support

Read [plugin privacy](PRIVACY.md), [DreamSavant website privacy](https://dreamsavant.com/privacy),
and [terms](https://dreamsavant.com/terms). The plugin stores nothing and sends
no conversations to DreamSavant. Claude's own data policies apply. Optional
DreamSavant links contain disclosed fixed UTM attribution, never dream text
or personal identifiers. Opening those links uses the website's normal policies.

Support: support@dreamsavant.com. Privacy questions: privacy@dreamsavant.com.
Dream reflection is exploratory, not diagnosis or prediction. The plugin is
intended for adults and is independent of Anthropic.

## License

The [MIT License](LICENSE) covers these plugin instructions and documentation.
DreamSavant's name and logo identify this integration; trademark rights are
reserved. This license does not cover the DreamSavant application or proprietary
expert personas.
