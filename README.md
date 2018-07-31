# Google Sheets Unity 

Get data from your private Google Sheets to Unity!! (Read-only)

## How to use

1. `new` an instance of `GoogleSpreadsheet` with necessary data.
2. Call `Get` on it. Voila!

## Dependencies

- Google.Apis.Auth.dll
- Google.Apis.Core.dll
- Google.Apis.Sheets.v4.dll
- Google.Apis.dll
- Newtonsoft.Json.dll
- .NET 4.x

They are based on the newest version as of July 31, 2018.
If `Newtonsoft.Json.dll` conflict with the one in your project you will have to remove one of them I think.
Please follow the license agreement of each one accordingly.

## Bonus

There is a `package.json` so you can include this in your project with UPM.