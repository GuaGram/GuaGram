<img src="https://github.com/GuaGram/GuaGram/blob/main/telegramm.jpg" width="150" align="left"/>

## GuaGram
*[Licensed under the GNU General Public License v2.0](https://github.com/GuaGram/GuaGram/blob/main/LICENSE)*

Experimental **third-party** Telegram client based on [exteraGram](https://github.com/exteraSquad/exteraGram).

[![Channel](https://img.shields.io/badge/Channel-Telegram-blue.svg)](https://t.me/GuaGram)

## Importing API hash and keys
- You should get **YOUR OWN API KEY AND HASH** here: https://core.telegram.org/api/obtaining_api_id and create a file called `API_KEYS` in the source root directory.
- Also you should get **YOUR OWN MAPS API KEY** here: https://console.cloud.google.com/google/maps-apis/credentials and add it to this file.
- And you need to generate **SIGNING KEY**: https://developer.android.com/studio/publish/app-signing#generate-key

The file content should look like this:
```
APP_ID = 123456
APP_HASH = abcdef0123456789 (32 chars)
MAPS_V2_API = abcdef01234567-abcdef012345678910111213

SIGNING_KEY_PASSWORD = A1BcDEFHJ2KLMn3oP
SIGNING_KEY_ALIAS = abcdefghjklm
SIGNING_KEY_STORE_PASSWORD = Z9yXDEFHJ6KRqn7oP
```

## Compilation Guide
1. Open the official Telegram channel of [GuaGram`a](https://t.me/GuaGram) and download the archive of the latest version.
2. Fill out values in `API_KEYS` like [here](https://github.com/GuaGram/GuaGram/tree/main?tab=readme-ov-file#importing-api-hash-and-keys)
3. Open the project in Android Studio. It should be opened, **not imported**
4. You are ready to compile `GuaGram`

- **GuaGram** can be built with **Android Studio** or from the command line with **Gradle**:
```
./gradlew assembleAfatRelease
```
 ## Thanks to:
- [exteraGram](https://github.com/exteraSquad/exteraGram)
