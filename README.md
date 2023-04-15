# Timed_comments_on_youtube
Timed comments for YouTube (like the existing beta which doesn't seem likely to rollout soon). Basically, I want a way to embed YouTube videos and to show an auto-scrolling comments board beneath it, on my Jekyll site. There should be a way to

Use the Youtube API to get the current second that the user is at in the video.
Scrape all of the comments from that video and show them beneath the video. Prioritize timestamped comments, and show the ones closest to the current timestamp first.
It should show each YouTube comment thread in a default-collapsed style, where only the highest rated comment is shown, and there are ways for me to add a comment either to any thread or to the top level. The UI can look like YouTube comments or SoundCloud comments.
It should be possible for me to comment on any thread or post my own comment, and that comment should be posted to Youtube along with the current timestamp that I'm at.
If someone likes or responds, should just like or respond the analogous comment from their logged in YouTube account. If they are not logged in to our website, it should just send it to a server to be posted from our own Youtube account for all visitors, after spam filtering.
To summarize, a scraper gets all the comments, extracts timestamps, and like Soundcloud, displays previews of relevant comments that are shown underneath the video as you watch. If not fullscreeen, each comment thread at the timestamp can scroll by on the side in place of the next video suggestion, like an auto-scrolling Khan Academy comments board. It should work on our own embedded youtube video on our own website.
