# Set up @leikum_gaming in Claude

This repository is configured for a multi-game gaming channel with natural Hinglish commentary.

## A. Install the skill in Claude

1. Open Claude: https://claude.ai/
2. In a Claude conversation, paste:

   ```text
   https://github.com/voltryx-0408/youtube-agent-skill

   Install this skill, then confirm /yt-script works.
   ```

3. If Claude cannot install the skill from an ordinary chat, use Claude Code and follow the repository's installation instructions in README.md.

## B. Set the voice profile

The profile is in `templates/voice.md`. Claude Code users should copy it to:

```text
~/.claude/youtube/voice.md
```

If using a phone or standard Claude chat, open `templates/voice.md` in GitHub and paste its content into the conversation as the channel's standing instructions. The exact persistent setup depends on which Claude features your account supports.

## C. First test

Run `/yt-script` (if slash commands are installed), or ask Claude:

```text
Use the @leikum_gaming voice profile. Help me script a gaming video in natural Hinglish.
First ask which game, whether this is a Short or long-form video, and what actually happens in my footage.
Give me five distinct hooks, the strongest two, a spoken script with [ON SCREEN] edit cues,
three honest title options, and one thumbnail concept. Do not invent footage or analytics.
```

## D. Useful commands

- `/yt-script` — hooks and commentary
- `/yt-shorts` — identify short clips from long gameplay
- `/yt-package` — title and thumbnail pairing
- `/yt-plan` — upload plan
- `/yt-edit` — edit decision list from a transcript
- `/yt-seo` — description and search terms
- `/yt-audit` — prioritize a channel improvement

## E. YouTube connection and publishing

This skill pack creates drafts and plans; it does not itself install into YouTube Studio or automatically publish videos. Connect a YouTube channel to a supported analytics tool separately if you want channel stats or analytics-based recommendations. Review every title, description, thumbnail, and upload before publishing.

## F. Improve the voice profile

After you have three real videos, provide their transcripts or links to Claude and ask it to refine `templates/voice.md` based on your actual speaking style. Never claim the initial profile is an exact imitation until this has been done.
