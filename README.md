# pm2-pns
this is a pm2 module for sending events &amp; logs from your pm2 process to SKP PNS 

## How to Use
### install
``
pm2 install pm2-pn2
``
### setting
* appKey from atmos.skaplanet.com
* pns_url : http://apis.skplanetx.com/pns/v1/noti 
* notificationId from http://wiki.skplanet.com/pages/viewpage.action?pageId=96541629
* slack_url from slack webhookURL key http://hooks.slack.com/services/[slack_url]

```
pm2 set pns:appKey [appKey]
pm2 set pns:pns_url [pns_url]
pm2 set pns:pns_url [pns_url]
pm2 set pns:notificationID [notificationId]
pm2 set pns:slack_url [slack_url]
```
## Acknowledgements
This application makes use of the following third party libraries:

### pm2-slack
The MIT License (MIT)

Copyright (c) 2015 Matt Atkinson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
