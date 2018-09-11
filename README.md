# Secure Passphrase Generator

A cryptographically secure passphrase generator based on the [crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Window/crypto).

For more information why it's a good idea to use a passphrase check the following links:

- [https://www.eff.org/dice](https://www.eff.org/dice)
- [https://www.useapassphrase.com/](https://www.useapassphrase.com/)
- [https://xkcd.com/936/](https://xkcd.com/936/)

## Usage

This generator is a progressive web app and get's cached locally. Therefore you can use it offline after you visited the page once. The page consists of a single HTML file containing all code. It's commented carefully for full transparency. On page load the passphrase is selected automatically to be copied. To generate a new passphrase simply reload the page. It's should reload pretty fast as it's cached.
