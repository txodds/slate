# Errors

Included in each response is the following data structure which should contain a friendly error string as well as a unique error code:

```json
{
   "resp_status":{
   "message":"OK",
   "code":0,
   "errors":null
   }
}
```

The TXODDS Mobile API uses the following error codes:

Error Code | Meaning
---------- | -------
0000 | 'OK'
0001 | 'Invalid session'
1001 | 'Authentication Failed'
1002 | 'Login not provided'
1003 | 'Password not provided'
1004 | 'Invalid login and password'
1005 | 'No valid subscriptions'
1006 | 'User token not provided'
1007 | 'Invalid user token'
1008 | 'Field not provided'
1009 | 'Invalid device type'
1010 | 'Syntax error'
1011 | 'Email address not provided'
1012 | 'Registration failed'
1013 | 'First name not provided'
1014 | 'Last name not provided'
1015 | 'Login name is not available'
1016 | 'Email address is already in use'
1017 | 'Unique device Id not provided'
1018 | 'Too many registered devices'
1019 | 'No profile Id was provided'
1020 | 'Invalid profile Id'
1021 | 'Device type not provided'
9000 | 'Unknown error'
