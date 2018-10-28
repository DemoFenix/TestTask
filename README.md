test-page
========================

The `app` directory contains source files for Stylesheets, and Images.

Development
-----------

When running for the first time, run

    npm install

This will install the NPM dependencies. You should have NodeJS with NPM
installed and working.

In order to repeatedly build when changes occur, run

    gulp

Now you can browse the site on http://localhost:3000/

Deployment
----------

Deployment is simple static upload via rsync. Can be done by using gulp-task:

    gulp rsync
