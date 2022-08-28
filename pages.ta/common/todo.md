# todo

> ஒரு எளிய, தரநிலை அடிப்படையிலான, cli todo மேலாளர்.
> மேலும் விவரத்திற்கு: <https://todoman.readthedocs.io>.

- தொடங்கக்கூடிய பணிகளை பட்டியலிடுங்கள்:

`todo list --startable`

- பணி பட்டியலில் புதிய பணியைச் சேர்க்கவும்:

`todo new {{செய்ய_வேண்டியவை}} --list {{வேலை}}`

- கொடுக்கப்பட்ட ஐடியுடன் பணிக்கு இருப்பிடத்தைச் சேர்க்கவும்:

`todo edit --location {{இருப்பிட_பெயர்}} {{பணி_ஐடி}}`

- ஒரு பணியைப் பற்றிய விவரங்களைக் காட்டு:

`todo show {{பணி_ஐடி}}`

- குறிப்பிட்ட ஐடிகளுடன் பணிகளை முடித்ததாகக் குறிக்கவும்:

`todo done {{பணி_ஐடி1 பணி_ஐடி2 ...}}`

- ஒரு பணியை நீக்கு:

`todo delete {{பணி_ஐடி}}`

- செய்த பணிகளை நீக்கி, மீதமுள்ள பணிகளின் ஐடிகளை மீட்டமைக்கவும்:

`todo flush`