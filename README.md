# UK-Selenium

Automated UI tests for [olx.bg](https://www.olx.bg), written in Selenium IDE as a university software quality project.

The project has 104 tests grouped into suites:

| Suite | Tests | What it covers |
|---|---|---|
| LogInSuite | 9 | Valid login, wrong password, unregistered email, invalid formats, empty fields |
| RegisterSuite | 6 | Registration, already registered email, weak or invalid passwords |
| SocialLoginSuite | 3 | Facebook, Apple and Google login buttons |
| NavigationSuite | 14 | Home button, pages that need login, error page, language and cookie settings |
| ListingSuite | 22 | Listing images, phone number, location, reporting, favourites, recommendations |
| MyProfileSuite | 10 | Listing statuses, chats, payments, balance top-up, delivery |
| SearchSuite | 2 | Search for existing and non-existing items |
| FilterSuite | 25 | Price range, condition, region, seller type, category filters, sorting |
| SettingsSuite | 11 | Account, password, email, 2FA, notifications |

## Running the tests

1. Install the Selenium IDE extension for Chrome or Firefox.
2. Open `UK-OLX-Testing.side` in Selenium IDE.
3. Pick a suite and run it.

Some tests need a registered olx.bg account. The site changes over time, so a few locators may no longer match.
