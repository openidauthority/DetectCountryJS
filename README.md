# DetectCountryJS
Determine user's country in JS from their time zone setting

A user's timezone is available from `Intl.DateTimeFormat().resolvedOptions().timeZone`

Since these time zones map to countries, a user's country can be determined from their time zone, if their time zone is set correctly.

## Usage

```
console.log(getUsersCountry('unknown'));
```