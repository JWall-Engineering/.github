[![JWall Engineering](https://raw.githubusercontent.com/JWall-Engineering/jwall-engineering-branding/main/assets/banner/jwall-engineering-readme-banner.png)](https://github.com/JWall-Engineering)

**JWall Engineering runs the infrastructure for its projects on AWS**: static
sites, Lichess bots, research workloads and Databricks workspaces. Each one
gets the same governance, tagging, cost allocation and least-privilege CI
roles, and the monitoring and cost reporting at
[grafana.jwall.engineering](https://grafana.jwall.engineering) watch all of
them. It is built with [Jaws](https://github.com/Jaws-Platform/jaws), as
Jaws's first customer.

### What's here, and what's coming

[`platform`](https://github.com/JWall-Engineering/platform) is the hub that
takes the platform's configuration over from
[`Jaws-Platform/jaws`](https://github.com/Jaws-Platform/jaws). Until the
takeover, `jaws` holds and applies it. `platform` also holds JWall
Engineering's own image of Jaws and the workflows its projects call, and
JWall Engineering chooses the Jaws release it runs.

### Repositories

| Repository | What it is |
|---|---|
| [`platform`](https://github.com/JWall-Engineering/platform) | JWall Engineering's platform: its configuration and datasets, its image of Jaws, the workflows its projects call, and the owner's folders |
| [`jwall-engineering-branding`](https://github.com/JWall-Engineering/jwall-engineering-branding) | The wordmark and the JW monogram, the logo, the avatar, the README banner, the social preview, the favicons and the README header standard |

### GitHub Apps

| GitHub App | What it does |
|---|---|
| [`jwall-engineering-releases`](https://github.com/apps/jwall-engineering-releases) | Opens the Release Please pull requests, so CI runs on them |
| [`jwall-engineering-comments`](https://github.com/apps/jwall-engineering-comments) | Posts the platform's plan and preview comments |
| [`jwall-engineering-upgrades`](https://github.com/apps/jwall-engineering-upgrades) | Opens the pull request that upgrades the platform's Jaws release |
| [`jwall-engineering-deployments`](https://github.com/apps/jwall-engineering-deployments) | Moves the platform's `live` branch to each release, and back on a rollback |

### How every repository works

One-line Conventional Commits, every change through a pull request, squash or
rebase merges only, and a release cut by merging the Release Please pull
request. Everything is MIT licensed.
