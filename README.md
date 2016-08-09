# ml-http2

## API

``` js

__http2({
  url:    //string
}, function(data) {
  // callback function
});

```

## Example

``` js
__wifi({
  mode: 'station', // default is station
  auth: 'PSK_WPA2',
  ssid: 'mcs',
  password: 'mcs12345678',
});

global.eventStatus.on('wifiConnect', function() {
  __http2({url: 'https://http2.akamai.com/'}, function(data){
    print(data);
  });
});

```
