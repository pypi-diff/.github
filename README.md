# .github
Daily generated diffs for pypi package releases

processes the pypi changelog and if a new release for a package is published, attempts to create diffs between old and new version using diffoscope, output formats:

html
text
markdown
Projects with artifacts > 10 MB are ignored and some "special cases" are not handled yet: no guarantee that all packages are tracked.

Changes are pushed to daily created repositories.
