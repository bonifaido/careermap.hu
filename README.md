# Career Map

The English site is built from the shared application in
[palyaterkep.hu](https://github.com/bonifaido/palyaterkep.hu), not from this
repository's placeholder page. Edit the application and English translations
in that repository.

The GitHub Pages workflow builds the shared repository's `main` branch daily
at 04:17 UTC, when this repository's `main` changes, or when manually run from
the Actions tab. Updates to the shared repository are not deployed here
immediately; run the workflow manually to publish them sooner.

In this repository's GitHub Pages settings, select **GitHub Actions** as the
build source and retain `careermap.hu` as the custom domain. The existing
`CNAME` file is copied into the generated site. The placeholder `index.html`
is not included in the generated site.
