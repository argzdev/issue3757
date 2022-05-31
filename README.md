# issue 3757
### Summary
- Remote Config fetch fails when app is on RTL language. (e.g. Arabic, Urdu, Persian)
### Prerequisite
- Add google-services.json
- Enable Remote Config in Firebase Console
    - Add `loading_phrase` of type String of any value
    - Add `welcome_message` of type String of any value
    - Add `welcome_message_caps` of type Boolean of either true/false.
### Steps to reproduce
- Go to phone Settings > System > Language & Input > Languages > Change to Arabic (Steps may differ according to Android version)
- Open app
- Click `FETCH REMOTE WELCOME` button, `Fetch failed` is displayed.
