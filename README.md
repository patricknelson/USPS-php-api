USPS PHP API
===========

This wrapper allows you to perform some basic calls to the USPS api. Some of the features currently supported are:

- Rate Calculator (Both domestic and international)
- Zip code lookup by address
- City/State lookup by zip code
- Verify address

Requirements
============

- Apache 2 Web Server 
- PHP 5.x configured with the following extensions:
- cURL
- USPS API Username

Examples
=======

To incorporate into your project using `composer`, see the following example `composer.json` file:


	{
		"require": {
			"alexanderreiff/usps-php-api": "dev-master"
		},
		"repositories": [
			{
				"type": "git",
				"url": "git://github.com/patricknelson/USPS-php-api.git"
			}
		]
	}

Then run `composer install` from the root directory of your project.

Authors
=======
Vincent Gabriel <http://vadimg.com>

Thanks
======

License
=======

The MIT License

Copyright (c) 2012

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.