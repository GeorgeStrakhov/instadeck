# Instadeck
_turn plain email into a gorgeus slidedeck in seconds_
(one line per slide)

## User scienario

* visit landing, undrestand the value
* click "try now" button
* use pre-filled textarea input with one line per slide (and sometimes an image and a video)
* click "see it" and see the deck rendered from his input below (opens in a new tab).
* next time when in need - send an email to now@instadeck.red with deck title in the subject and one line per slide in the body
* in 30 seconds receive back an email with a link to the ready deck, where each line has been transformed into a separate slide, beautiful background pictures auto-filled and video links turned into embedded videos

## Routes

* `/` - landing (possibly - redirect to a deck?) + possibly live demo with input (try now button)
* `/deck/{uid}/{designParams}` - single deck

## Components

* Framework: Rails / Django / Laravel (?)
* Parser: Showdown++
* Email: [Mandrill](http://mandrill.com/)
* Online presentation: [Reveal](https://github.com/hakimel/reveal.js/)
* Good free pics: [Unsplash](https://source.unsplash.com/)

## TODO
* finalize technology map / architecture [p]
* communication (landing page) [g]
* domain name [g]
* custom reveal theme

## DONE
* github repo

-----------------

## Other thoughts

* URL params to change design params explicitly (presentable)

## Maybe (concerns)

* Presentation diff & versioning
* Deterministic slide backgrounds (based on text)
