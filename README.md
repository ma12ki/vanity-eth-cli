# Vanity-ETH-CLI

CLI version of https://github.com/bokub/vanity-eth

`npm i`

`npm run vanity -- <desired_chars> <isSuffix> <matchCase>`

e.g.

`npm run vanity -- abc` -> `0xAbc...`

`npm run vanity -- abc true` -> `...aBc`

`npm run vanity -- ABC false true` -> `0xABC...`
