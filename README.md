# gscli
Google Spreadsheet CLI

## Usage

Simply read cell content and write to stdout

```bash
./gscli --spreadsheet :spreadsheet_id --worksheet :worksheet_title --cell 1,1
```

## Auth

Create an app and get application_id and secret, store in google_auth.json. See https://github.com/gimite/google-drive-ruby
