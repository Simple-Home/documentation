URL: `/v1/setup`

## Requst Headers
`Content-Type: application/json`

`Authorization: Bearer [token]`

## Requst Body
```json
{
	properties: ["wifi","on/off","temp",...]
}
```
* Each string in Array is value whitch will be registered for publication in `/data` entripoint not published vlues wond be settable/gettable!

## Response Headers

## Response Body
```json
{
	hostname: "hostname",
	sleep: 60
}
```