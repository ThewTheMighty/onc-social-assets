# onc-social-assets

Rendered social cards for [Our Next Chapter](https://www.instagram.com/ournextchapterpodcast/).

**This repo is public on purpose.** The Instagram Graph API takes an `image_url` and will not
accept uploaded bytes, so every card has to be fetchable by Meta's servers before it can post.
`raw.githubusercontent.com` serves them without a User-Agent, which Meta's fetcher requires.

Only rendered PNGs belong here. No source, no credentials, no transcripts.
Cards are generated in `~/code/onc-social/`.
