# api

UR: `/v1/setup`

## Requst Headers
`Content-Type: application/json`

`Authorization: Bearer [token]`

## Requst Body:
```json
{
	properties: ["wifi","on/off","temp",...]
}
```

## Requst Headers


## Example Response:
```json
{
	hostname: "hostname",
	sleep: 60
}
```