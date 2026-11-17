# Backup Crew

Backup Crew is an anti-bullying web app for students. When someone sees a post where a person is being bullied, they nominate it to the crew. Crew members then go to the original post and leave kind, supportive comments, so the person being targeted sees support instead of only cruelty.

**Live app:** https://backupcrew.staticdomains.app/

Built solo by Cheyenne Galler for the 2026 Congressional App Challenge. Code written with help from Claude; crew artwork made with Grok.

## How it works
1. A student spots a post where someone is being bullied.
2. They nominate the post to Backup Crew.
3. Crew members leave kind and inspriational comments on the original post (without mentioning Backup Crew).
4. The person being bullied sees support instead of only cruelty.

## Project structure
- `www/` – the web app (HTML, CSS, JavaScript)
- `android/` and `ios/` – native app wrappers built with Capacitor
- `codemagic.yaml` – build setup for the Google Play release

## How to run it
**Web:** Open the live link above, or download this repo and open `www/index.html` in a browser.

**Android:**
1. Install Node.js and Android Studio.
2. In this folder, run `npm install`
3. Run `npx cap sync android`
4. Run `npx cap open android`, then press Run in Android Studio.

## License
MIT
