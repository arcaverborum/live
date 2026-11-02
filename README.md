# live.arcaverborum.org

Deploy-only repository. GitHub Pages here serves the **current `master`** of
[arcaverborum/arcaverborum](https://github.com/arcaverborum/arcaverborum) at
<https://live.arcaverborum.org>, with a banner showing the data revision and a
link to the latest release.

The main repository's CI builds the site bundle after every green `master`
build and attaches it to its rolling `live` pre-release (not a release). This
workflow checks for a new revision every 30 minutes and on demand, verifies
the bundle's checksum and deploys it. The deployed revision is published at
`/REVISION`.

For citable data, use the latest release at <https://arcaverborum.org>.
