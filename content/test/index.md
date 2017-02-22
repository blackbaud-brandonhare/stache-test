---
layout: layout-panels
name: Test Page
description: This is a test page.
order: 80
myVar: This is a super awesome var.
---

# {{ name }}

This is a super awesome paragraph.

## Test Page Subheading

- Item 1
- <a href="{{ stache.config.base }}" target="_blank">Item 2</a>
- [Item 3]({{ stache.config.base }})
- {{ myVar }}
- {{ stache.config.product_name_long }}

