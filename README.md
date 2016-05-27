# OpenID Connect Examples

## Warning
**This code is not supported by ForgeRock and it is your responsibility to verify that the software is suitable and safe for use.**

## About

Here is a very simple OpenID Connect sample client.

The examples are not secure. Instead they are completely transparent,
showing the requests and the steps for the Implicit Profile.

Configure OIDC and modify this HTML file to point to the configured instance.
This HTML only needs to be hosted on some web-server.

One option for a simple test would to be leverage an simple web server built into Python.  To perform that option...

mkdir /web
cd /web
download this HTML and place into /web
python -m SimpleHTTPServer 8000

Now point a browser to http://localhost:8000 to perform the test of the OIDC client.

* * *
This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at http://mozilla.org/MPL/2.0/.

Copyright 2016 ForgeRock AS.
