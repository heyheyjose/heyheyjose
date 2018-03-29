#### Site Source

This is the source for my site. I redid the site recently and did away with the build/dev/deploy process that was unnecessarily complex for a simple personal site like this one.

To deploy:

* copy files into build directory (just the changed files)
* git loop (to push master branch containing everything to dev remote)
* git subtree push --prefix build prod master (to push only "build" directory to prod remote)

\- Jose
