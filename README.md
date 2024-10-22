[<img src="https://about.mappls.com/about/images/MAPPLS-MapmyIndia-logo.png" height="40"/> </p>](https://about.mappls.com/api/)

# HTTP Listener API

**API version:** 1.0

> **URL:** https://intouch.mappls.com/iot/api/events/pushData/

## **Authorization:** 
This API follows OAuth2 based security. To know more on how to create
your authorization tokens, please use our authorization token URL. More details available
`[here](https://developer.mappls.com/).

**The API leverages OAuth 2.0 based security. Hence, the developer would need to
send a request for access token using their client_id and client_secret to the
OAuth API. Once validated from the OAuth API, the access_token and the
token_type need to be sent as Authorization header with the value: "{"{token_type} {access_token}".**

------

***Authorization:*** token_type access_token.

>## **To Generate Token Refer:**
>
>[Click Here](https://www.mappls.com/api/advanced-maps/doc/authentication-api.php)

## **Header Parameter:**

| Content-Type  | Application/JSON                              |
| ------------- | --------------------------------------------- |
| trackingCode  | Unique identifier of the device (**Data Type:** String) |

<br>

## **Response Body Sample:**
```
[
{
"analogInput1": 0,
"analogInput2": 0,
"gsmlevel": 0,
"heading": 0,
"ignition": 0,
"panic": 0,
"ac": 0,
"latitude": 0,
"longitude": 0,
"numberOfSatellites": 0,
"timestamp": 0
}
]

```
> **Note:**  API supports multiple packets of the same device in a single request.



