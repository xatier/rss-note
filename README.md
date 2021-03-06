# RSS feeds note

My note for the RSS feed URLs of some websites.

## Medium.com

- Author feed: `https://medium.com/feed/@[user]`

- Publication feed: `https://medium.com/feed/[publisher]`

- Tagged pages in publications: `https://medium.com/feed/[publisher]/tagged/[tag]`

- Custom domains: `https://some.domain.com/feed`

## dev.to

- Main feed:`https://dev.to/feed/`

- Author feed: `https://dev.to/feed/[username]`

- Tag feed: `https://dev.to/feed/tag/[tag]`

## Matters.news

- Author feed: `https://rsshub.app/matters/author/[username]`

## Reddit

- Home page: `https://www.reddit.com/.rss`

- Subreddit feed: `https://www.reddit.com/r/[subreddit]/.rss`

- User feed: `https://www.reddit.com/user/[username]/.rss,`

- Combining multiple subreddits: `https://www.reddit.com/r/[sub1]+[sub2].rss`

- Follow domain: `https://www.reddit.com/domain/imgur.com/.rss`

- Top of the week: `https://www.reddit.com/r/[subreddit]/top.rss?t=week&limit=25`

- Sort by latest: `?sort=new`

## SoundOn

- `https://rss.soundon.fm/rss/tracks/[uuid]/feed.xml`

- `https://api.soundon.fm/v2/[uuid]/feed.xml`

  - Find `uuid` in `https://player.soundon.fm/p/[uuid]`

## SoundCloud

- `https://feeds.soundcloud.com/users/soundcloud:users:[uid]/sounds.rss`

  - Find `uid` in HTML meta tag

  - `<meta property="twitter:app:url:googleplay" content="soundcloud://users:[uid]">`

## open.firstory.me

- `https://open.firstory.me/rss/user/[user hash id]`

  - `https://open.firstory.me/user/[user hash id]`

  - `user hash id` is something like `ck4uoyyi7f27a0b264u9w8rcp`

## RSSHub

Convert website posts to RSS feeds. [Docs](https://docs.rsshub.app/).
