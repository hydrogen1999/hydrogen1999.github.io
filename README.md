# hydrogen1999.github.io

This repository publishes the academic website of Thinh Nguyen-Cong at
<https://hydrogen1999.github.io/>. The same website is also available at
<https://thinhnguyencong.github.io/>.

## Editing content

Edit the website in
[thinhnguyencong/thinhnguyencong.github.io](https://github.com/thinhnguyencong/thinhnguyencong.github.io),
usually `site/profile.js`. This repository's deployment workflow reads `main`
from that public repository, so the content has one source.

## Deployment

The workflow runs at minute 23 of each hour (UTC), when its configuration changes,
and through **Actions → Deploy mirrored site to Pages → Run workflow**.
For an immediate update after editing the source, run this workflow manually.
GitHub may delay scheduled runs during busy periods. GitHub also disables
scheduled workflows after 60 days without repository activity; re-enable the
workflow in Actions if that happens.

Only the built-in `GITHUB_TOKEN` is used. No personal access token or additional
repository secret is needed for deployments.

To restore an earlier website version, revert the content change in the source
repository, then run this workflow again. Pages must use **GitHub Actions** as
its publishing source in this repository's settings.
