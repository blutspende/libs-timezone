# timezone
Contains a list of timezones.

###### Install
`go get github.com/blutspende/libs-timezone`

## Timezone

`TimeZone` has a `GetLocation()` method, or can be passed to `time.LoadLocation()` to get a `*time.Location`.

The package also contains some utility functions for time formatting and parsing.

```go
func FormatTimeStringToBerlinTime(timeString, format string) time.Time
func ParseBerlinTimeStringToUTCTime(timeString string) time.Time
```
