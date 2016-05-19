## Archive Scripts

* [BASC Archiver](https://github.com/bibanon/BASC-Archiver) - Tool that downloads an entire 4chan thread, it's JSON, and all images.
* [Wget](http://github.com/baslqc/baslqc/wiki/Wget) - The internet archivist's swiss army knife. Grab any website, and all public data on it for offline viewing (or into WARC format).
* [youtube-dl](https://github.com/rg3/youtube-dl) - Download videos off of YouTube and other streaming sites. [[Here are some recommended commands.|Youtube-dl]]
* [Imgur Album Downloader](https://github.com/alexgisby/imgur-album-downloader) - To save choice albums for later viewing.
* [Wikiteam - Mediawiki Dump Generator](http://archiveteam.org/index.php?title=WikiTeam#Tools_and_source_code) - Archive an entire backup of a MediaWiki-based wiki, all pages, all history, and all images. You can use Special:Import to restore this XML backup.
* ~~[Plowshare](https://github.com/plowshare/plowshare) - Oh no! Was OP a faggot and gave you 10 split Mediafire links? Not to worry, you can use this automated download script to scrape from any download site in an automated manner. Though sometimes, you'll still have to solve captchas.~~404'ed
* [Bdom's Tumblr Backup](https://github.com/bdoms/tumblr_backup) - This python script backs up an entire Tumblr blog with all posts and images. Just in case the author decides to delete their blog...
  * Unfortunately, it doesn't grab a list of reblogs/comments or the Tumblr theme. Might be a good project to work on.

### Quick and dirty archive snapshot

Just click a bookmarklet to archive a page for later! Great for source links and Google Cache, because you can bet that they will be gone within 5 years.

* [Archive.today](http://archive.today/) - An improved version of WebCite, optimized for pesky "Web 2.0" sites that dump a lot of extra CSS and other content that is tricky to archive.
* [Webcite](http://webcite.org) - The original tried-and-true website snapshot archiver, for research paper citations.

## Markdown Conversion

* [Pandoc](http://johnmacfarlane.net/pandoc/) - The Swiss Army knife of markup language converters. Convert anything to Markdown, and convert markdown to anything. Great for turning HTML into a readable format.
* [gdoc2md](http://lifehacker.com/this-script-converts-google-documents-to-markdown-for-e-511746113) - A quick and dirty script used to convert a Google Doc into Markdown. Great for importing collaborative projects.

## Regular Expressions

* [Regexr](http://www.regexr.com/) - Create and share Regular Expressions for everyone to use. Great for learning how to make them.

## Programming Guidelines

* **Use the GPLv3 for programs/scripts.** - This ensures that the source code of our programs stay open-source, and any derivatives are open source.
* **Use the LGPLv3 for libraries.** - This ensures that the source code of our libraries stay open source. Unlike the GPL, however, the LGPL allows statically linked (`import library`) programs to use any license they want.
  * The only exception is the BASC-py4chan wrapper, which uses the WTFPL. This is a humorous tradition inherited in honor of Edgeworth E. Euler.