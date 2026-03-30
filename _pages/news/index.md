---
layout: page
title: News
permalink: /news/
toggle: on
rank: 6
---

## Latest Updates

<div id="mt-container" class="mt-container">
  <div class="mt-body" role="feed">
    <div class="mt-loading-spinner"></div>
  </div>
</div>

<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@idotj/mastodon-embed-timeline@4.4.2/dist/mastodon-timeline.min.css"
/>
<script src="https://cdn.jsdelivr.net/npm/@idotj/mastodon-embed-timeline@4.4.2/dist/mastodon-timeline.umd.js"></script>

<script>
new MastodonTimeline.Init({
  instanceUrl: "https://mastodon.social",
  timelineType: "profile",
  profileName: "@weberam2",
  maxNbPostFetch: "5",
  maxNbPostShow: "5",
});
</script>

<p><a href="https://mastodon.social/@weberam2" target="_blank" rel="noopener">View all posts on Mastodon</a></p>