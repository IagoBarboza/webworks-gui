webworks-ui
===========

GUI for the BlackBerry WebWorks SDK

Usage
=====

1) Run npm install

2) Copy contents into the webworks-ui directory within a WebWorks installation

3) Run `bin/start-ui`

A node server will be started at the port specified in config.json.

The script will also open the UI (public/index.html) in the browser.

Development Environment
=======================

1) Run npm install -d `This will install package.json dependencies`

2) Run npm install -g grunt-cli (May need sudo) `This will install grunt`

3) Run grunt `This will build all the lib/ui js files into one file`

4) Build output will be /public/js/webworks-ui.js

