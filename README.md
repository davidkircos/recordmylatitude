record my latitude
==================

recordmylatitude records iOS's location information to Google latitude service. original idea comes from [playnice][2] 
(not yet implemented)

findmyiphone
------------

findmyiphone is unofficial api client for find my iphone service of apple me.com.
original source code comes from [Sosumi][1]

authsub
-------

[AuthSub][3] is google's own 3rd party authorization api.
latitude api documentation [says][4] "In order to access a user's location data, you need to obtain their authorization using the OAuth protocol" but seems only authsub is supported now.so i did wrote code for easily create authsub client.

googleapi
---------

contains only latitude api client now.

LICENSE
-------

The MIT License

Copyright (c) 2011 comfuture

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


[1]: https://github.com/tylerhall/sosumi
[2]: https://github.com/ablyler/playnice
[3]: http://code.google.com/intl/ko/apis/accounts/docs/AuthSub.html
[4]: http://code.google.com/intl/ko/apis/latitude/v1/using_rest.html#auth
