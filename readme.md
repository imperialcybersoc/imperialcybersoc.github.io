# website docs 



## How to add event?

go to `/content/events/[year]/` and make a new md file.

then, place:

```
---
title: "This is my title!"
categories: ["workshop"]
date: 2024-01-01T00:00:00
end: 2024-01-01T01:00:00
---

This is an event that will cover xyz
```

`end` and `categories` are optional but recommended

You can put any markdown inside, start with l2 headings though


## How to make new page?

go to `/content/events/[year]/` and make a new md file. (optionally place in subfolder)

```
---
title: "My Page"
url: "mypage"
---

Content here!

```

The title will be displayed at the top of the page, the url can be chosen!
