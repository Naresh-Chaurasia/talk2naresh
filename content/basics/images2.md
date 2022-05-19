---
title: "images2"
date: 2022-04-15T10:55:16+05:30
draft: false
---

{{ $asset := resources.Get "/Hugo.png" }}
{{ $img := $asset.Fit "600x400" }}

<figure class="image is-3by2">
  <img alt="Yellow Duck" src="{{ $img.RelPermalink }}" />
</figure>
