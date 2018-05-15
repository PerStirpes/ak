# hs-kibana


## search for rate limits 
`host:"api.helpshift.com" AND code:"429"`


## ability to see more API requests than the configured RPM limit
`host:"api.helpshift.com" AND path:"zynga-sandbox"`


## Android
`st:"java.lang.IllegalStateException: sender id not provided in Helpshift registerGcmKey method"`

## 408
`path:"/websdk/dazzle/preissues/" && method:"POST" && NOT path:"messages"`

```
:time-of-request
:request-route
:request-params
:response
:http-code
```

In future, if there are any API errors, we need the following information to investigate the issue:  Plain text logs of the API errors and screenshots would be preferable to Fiddler trace files. We tried installing Fiddler, but it can't be easily installed on OS X.


## HA-proxy 2602
