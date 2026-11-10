# grok-bot-releases

Public release notes for SpaceXSI Grok Bot Marketplace templates.

Each bot has one small JSON file here. A bot's weekly `check-for-template-update` routine reads its file, compares `version` to its own "Template version" memory, and tells its owner when a newer version exists. It never updates itself; the owner says yes first.

Fields: `version` (number), `released` (YYYY-MM-DD), `changelog` (short lines), `template_link` (where to re-add the bot; filled when the version is published).

Nothing private lives in this repo.
