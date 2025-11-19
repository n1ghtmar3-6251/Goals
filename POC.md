### Virgin Mobile :

 1.

```
POST /securitymanagement/login_by_device_id HTTP/1.1
Host: wsc.virginmobile.ae
Content-Type: application/x-www-form-urlencoded
User-Agent: VirginMobile/3.2.4(1319) - (Android 13; API Level 33)
Virgin-App-Version: 3.2.4
Virgin-Device-Os: Android
Virgin-Device-Id: ebf48f98-3a27-3b2f-b119-1ec4e2d0b594
Accept: application/json
Virgin-Lang: en
Accept-Version: v35
Virgin-Api-Version: 6.0.0
Virgin-Account-Number: 
Content-Length: 0
Accept-Encoding: gzip, deflate, br
Connection: keep-alive


```

 2. 

```
GET /me/summary?account_number=ACC-01329156&number=0 HTTP/1.1
Host: wsc.virginmobile.ae
User-Agent: VirginMobile/3.2.4(1319) - (Android 13; API Level 33)
Virgin-App-Version: 3.2.4
Virgin-Device-Os: Android
Accept: application/json
Virgin-Lang: en
Accept-Version: v35
Virgin-Api-Version: 6.0.0
Session-Id: 878936c4-7bc5-4091-b9cc-911cf646f377
Virgin-Account-Number: ACC-01329156
Accept-Encoding: gzip, deflate, br
Connection: keep-alive


```

 3.

```
POST /sapi/customers/auth/ HTTP/2
Host: desk-api-43deb9b1-7e2d-4e7e-8678-27839cdf2791.sendbird.com
Accept: application/json
User-Agent: Dand/1.1.4
Sendbirddesk: Android,33,1.1.4,43DEB9B1-7E2D-4E7E-8678-27839CDF2791
Sendbirdaccesstoken: 
Content-Type: application/json; charset=utf-8
Content-Length: 100
Accept-Encoding: gzip, deflate, br

{"sendbirdAppId":"43DEB9B1-7E2D-4E7E-8678-27839CDF2791","sendbirdId":"ACC-01329156@virginmobile.ae"}
```

 4. 

```
GET /sapi/tickets/?sendbirdAppId=43DEB9B1-7E2D-4E7E-8678-27839CDF2791&offset=0&limit=10 HTTP/2
Host: desk-api-43deb9b1-7e2d-4e7e-8678-27839cdf2791.sendbird.com
Accept: application/json
User-Agent: Dand/1.1.4
Sendbirddesk: Android,33,1.1.4,43DEB9B1-7E2D-4E7E-8678-27839CDF2791
Sendbirddesktoken: 2ae0ce1bc2cd5fe094807d656d889386ccb0f310
Accept-Encoding: gzip, deflate, br


```

 5. 

```
GET /v3/group_channels/sendbird_group_channel_10090318_a2c0068042a6934a83a2fc8b325c911b32c5dd43/messages?include=false&custom_types=*&next_limit=0&include_poll_details=true&include_reply_type=none&is_sdk=true&reverse=false&message_ts=9223372036854775807&prev_limit=30 HTTP/2
Host: api-43deb9b1-7e2d-4e7e-8678-27839cdf2791.sendbird.com
Accept: application/json
User-Agent: Jand/4.14.1
Sb-User-Agent: Android/c4.14.1
Sb-Sdk-User-Agent: main_sdk_info=chat/android/4.14.1&device_os_platform=android&os_version=33&extension_sdk_info=desk/android/1.1.4
Sendbird: Android,33,4.14.1,43DEB9B1-7E2D-4E7E-8678-27839CDF2791
Request-Sent-Timestamp: 1763577356459
Session-Key: f359ed14b675ea998678ba57ea6278745d83ab32
Accept-Encoding: gzip, deflate, br


```

 6. 

```
POST /v1/users/ACC-00024032%40virginmobile.ae/login HTTP/2
Host: api-43deb9b1-7e2d-4e7e-8678-27839cdf2791.calls.sendbird.com
User-Agent: calls-android/1.11.11
Sendbird: android,33,1.11.11
Sbcall-Client-Id: 0811bb39-5e98-4a8c-b1f7-be4abc015cf5
Content-Type: application/json; charset=utf-8
Content-Length: 49
Accept-Encoding: gzip, deflate, br

{"app_id":"43DEB9B1-7E2D-4E7E-8678-27839CDF2791"}
```
