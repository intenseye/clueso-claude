# clueso-claude

Instructions for Claude in Slack channels, starting with turning a product update (usually a #product-updates post) into a Clueso video plus a sales enablement brief.

- [Master prompt](master-prompt.md): paste this into the channel's Claude instructions (Claude configuration page for the channel). It tells Claude which instructions to follow for each kind of request.
- [Clueso product update video instructions](clueso-product-update-video-instructions.md): prerequisites, inputs, defaults, workflow, deliverable, and don'ts.

## Adding new instructions

1. Write them as their own `.md` file in this repo, like the Clueso one.
2. Add one row to the table in [master-prompt.md](master-prompt.md): when to use it on the left, a link to the new file's GitHub URL on the right.
3. If Claude in the channel can't open GitHub links, paste the new file's text into the channel's Claude instructions under the master prompt instead.

Intenseye-specific defaults in each file are marked so another team can swap them.
