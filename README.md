# huge-rss-list

I was looking for the biggest list of RSS URLs that I could find, but couldn't find a very large data set. I assembled a larger list than I could find elsewhere by listening to the Bluesky jetstream (firehose) for every post that contained a URL. For each unique domain, I retrieved one URL from that domain and looked for an RSS/Atom URL in its meta tags.

This list is curated in the sense that only URLs that are recently active are included, but uncurated with regards to content. I can't check every feed to apply consistent moderation, but I am generally excluding (if I see them) links from categories that aren't articles or general content, e.g. ecommerce, porn, spam.

For a more curated collection of feeds, check out https://ooh.directory/.

This list isn't comprehensive even for the domains that have been checked, because for now only one link is checked per domain. This misses the multiple feeds on a single domain like Youtube.

Fields:
* url
* title
* subtitle
* site_href
* timestamp of most recent successful retrieval
* timestamp of most recent published article
