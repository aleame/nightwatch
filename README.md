# README Nightwatch

You can run your tests now on your Android Emulator's Chrome browser.

Closing emulator...
Emulator will close shortly. If not, please close it manually.

Success! All requirements are set.
You can go ahead and run your tests now on an Android device/emulator.

IMPORTANT
Please set the credentials required to run tests on your cloud provider, by setting the below env variables:
- BROWSERSTACK_USERNAME
- BROWSERSTACK_ACCESS_KEY
(.env files are also supported)


✨ SETUP COMPLETE

  Nightwatch:
    version: 3.4.1
    changelog: https://github.com/nightwatchjs/nightwatch/releases/tag/v3.4.1

💬 Join our Discord community to find answers to your issues or queries. Or just join and say hi.
   https://discord.gg/SN8Da2X

🚀 RUN EXAMPLE TESTS

To run all examples, run:
  npx nightwatch ./nightwatch

To run a single example (github.ts), run:
  npx nightwatch ./nightwatch/github.ts

🚀 RUN MOBILE EXAMPLE TESTS

▶ To run an example test on Android Emulator
  For mobile web tests, run:
    npx nightwatch ./nightwatch/github.ts --env android.emulator.chrome
  For mobile app tests, run:
    npx nightwatch ./nightwatch/mobile-app-tests/wikipedia-android.ts --env app.android.emulator

Note: Nightwatch collects anonymous usage data to improve user experience. You can turn it off in nightwatch.conf.js