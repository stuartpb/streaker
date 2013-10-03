# streaker

Translates GitHub activity feeds into contribution streak status feeds.

(NOTE: README-driven development, doc state does not reflect code state)

## Update

Development on this project as described, beyond the initial planning stage, was discontinued in favor of a self-contained [on{x} recipe](https://www.onx.ms/#!recipeEditPage?scriptId=1380788571578731581&isPublished=true).

## How would this have worked?

GET a route in the app, the server will read your current GH activity feed and return an RSS item representing your current streak status. (Yes, _an_ item. It's ephemeral data- this only cares about whether you're streaking or you're not, the past is inconsequential.)

## What would it have been used for?

Plug your feed URL into the app as the input to an externally managed feed reader so you can get ghetto notifications about when your GitHub streak is in danger.

## Why?

Because I have a pigheaded sense of pride about my GitHub streak, and I want notifications when I'm in danger of breaking it, so I don't just absentmindedly forget to contribute one day and kill my streak (as I did on [March 22](https://github.com/stuartpb?tab=contributions&from=2013-03-22) or [September 29, 2013](https://github.com/stuartpb?tab=contributions&from=2013-09-29)).
