# swamp-linear-activity

[swamp](https://swamp.club) extension `@mgreten/linear-activity` — gather a
Linear user's daily activity (issues completed, moved to review, created,
comments authored, in-flight assignments) for EOD reports and standup summaries.

## Extension documentation

See [extensions/models/README.md](extensions/models/README.md) for full usage,
installation, auth setup, and output schema details.

## Install

```bash
swamp extension pull @mgreten/linear-activity
```

## Repository layout

```
swamp-linear-activity/
  extensions/models/
    linear_activity.ts    # Model source code
    manifest.yaml         # Extension manifest
    README.md             # Extension documentation
    LICENSE.txt           # MIT license
  README.md               # This file
```

## License

MIT — see [extensions/models/LICENSE.txt](extensions/models/LICENSE.txt).
