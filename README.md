# fax.txt

This is a curated collection of quotes from the [iDevGames](https://www.idevgames.com/) community chat. Historically, that was `#idevgames` on the freenode IRC network. In the early 2020s, the community migrated from IRC to [Discord](https://discord.gg/r6fxVBH). Owing to its history, iDevGames is comprised mostly of indie Mac game developers. However, anyone is welcome to join!

This repository is so named because it was originally a plain text file on [@raws](https://github.com/raws)'s computer, containing choice bits of wisdom from channel regular Ed, whose nickname (and several derivative nicknames) was `fax`.

## fax.md

This is the human-readable source of truth. If you want to add a new quote, please submit a pull request that modifies `fax.md`, adhering to its established style conventions.

## fax.json

Upon submitting a pull request, a GitHub Actions workflow will automatically trigger, regenerating `fax.json` using `bin/generate-json`. It parses `fax.md` and creates structured output, ready for consumption by whatever horrific machination you might dream up.

## License

The contents of this repository are licensed under the [Creative Commons CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license, which waives copyright and places it in the public domain. See `LICENSE` for the full text.
