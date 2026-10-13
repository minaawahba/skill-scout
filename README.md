# skill-scout

A Claude skill that finds, vets and offers the best skill for a task: once per topic, trusted sources first, no duplicate skills.

- **Triggers:** "find a skill", "is there a skill for", `/skill-scout`, or a new deliverable type / specialist domain that no installed skill covers.
- **Searches:** your org catalog, then Anthropic's official sources, then the wider web.
- **Vets:** reads every file, ranks by publisher trust, and rejects red flags (data exfiltration, hidden actions, obfuscated scripts).
- **Installs:** only with user approval.

## Install
Copy the `skill-scout/` folder into your skills directory, or upload `SKILL.md` at claude.ai under Settings > Capabilities > Skills.
