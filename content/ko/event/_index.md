---
title: TMI
# Listing view
view: compact

# Optional header image (relative to `assets/media/` folder).
banner:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/)'
  image: 'information.jpg'
---

<h2><span style="font-size:70%">인생곡 PLAYLIST</span></h2>

{{ range (where .Site.Pages "Section" "event/song") }}
  {{ partial "views/community/custom_compact.html" (dict "item" .) }}
{{ end }}
