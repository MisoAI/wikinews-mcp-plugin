# Example opening searches for the Wikinews archive

Good first calls to `ask_wikinews` (coverage is densest for 2005-2010):

- "2010 Eyjafjallajökull Icelandic volcano eruption air travel"
- "Cassini mission Saturn findings"
- "2010 Haiti earthquake relief effort"
- "2011 Fukushima Daiichi nuclear accident"

Tips:
- Lead with the event's common name plus a year; drop the year and retry if empty.
- For a person, pair the name with the event they're known for.
- After a hit, pass its id/URL to `get_wikinews_article` for the full text before quoting.
