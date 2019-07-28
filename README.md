# SMS2MQTT gateway on Android

## Example of command
```
payload="$destination_number|$message"
mosquitto_pub -h $host -u $user -P $password -t tele/home-mn356/mqtt2sms -m "$payload"
```
