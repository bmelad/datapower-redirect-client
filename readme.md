# HTTP redirection using GatewayScript

This little peace of code will make your IBM DataPower Gateway to respond to the client with "302 Moved Temporarily" and send the client to a predefined URL.


## How to use it?

1. Drag a GatewayScript processing action and select the 'datapower-redirect-client.js' file, set the Input of the action to the relevant value.

1. Go to the Advanced tab of the GatewayScript processing action and add a parameter named 'URL' with the relevant url for the redirection.

