# Important!

This software [has been sadly discontinued][theend] by its developers. I (victorpimentel) do not have anything to do with the original developers. I only forked it just at the right time. Incidentally, the source for RSS feeds (EZTV/EZRSS) has been down, but the application still works (or it would work if the source was not down).

It seems that in the near future I will continue its development, but in any case if you want to pick up or contribute in any way you are free to fork this repository. Just comply with the license.

## Download

The latest build is always available here:

[http://victorpimentel.com/tvshows/TVShows.zip][download]

That preference pane should work in Leopard and Snow Leopard. In the near future when I have time I will create a proper website.

## About
TVShows 2 is the next version of [TVShows][tvshows], the easiest way to download your favorite shows automatically. It includes a completely rewritten codebase as well as a major overhaul of the UI and a move to System Preferences.

No actual videos are downloaded by TVShows, only torrents which require other programs to use. It is up to the user to decide the legality of using any files downloaded by this application, in accordance with applicable copyright laws of their country.

<!-- ## Screenshots
<a href="http://embercode.com/blog/category/tvshows-news/" title="TVShows News">![Show List][preview-1]&nbsp;&nbsp;![Subscriptions][preview-2]&nbsp;&nbsp;![Show Info][preview-3]</a> -->

## Translations
<!--* Help localize TVShows 2 into your native language! [Click here][translate] ([more info][translate-info]) to be added to the translation team.-->
* Help localize TVShows 2 into your native language! [Click here][translate] to be added to the translation team.

## Collaboration Instructions
1. Checkout the repository:
    * `$ git clone http://github.com/victorpimentel/TVShows.git`
1. Download all the required submodules:
    * `$ cd TVShows`
    * `$ git submodule init`
    * `$ git submodule update`

## Collaboration Notes
* You can also use GitHub's forking feature to make changes and then send me a pull request.
* By default, the Debug configuration automatically installs TVShows into `~/Library/PreferencePanes/` each time it's built.
* Xcode 4 users will need to make sure the 10.5 SDK is in `/Developer/SDKs/`. Install Xcode 3 first if you do not have it, or change the target OS version.

## Roadmap
### Beta 6
* <strike>Fix performance bugs, improve responsiveness.</strike>
* <strike>Add a loading bar to the show list and show info window.</strike>
* <strike>Make it more obvious what's happening with SD/HD episodes.</strike>
* <strike>Add an option to mark by default the HD or SD versions of the show.</strike>
* <strike>Fade out "disabled" subscriptions.</strike>

### Beta 7
* Download episode names.
* Fade out subscribed shows from the show list.
* Fix the two shows who have no posters, but don't display the placeholder.
* Add a list view to the Subscriptions tab.
* Use NSTask for downloading torrents, posters, and descriptions.
* Consider additional sources for the RSS feeds.

## License
TVShows is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

For a copy of the GNU General Public License see &lt;[http://www.gnu.org/licenses/][license]&gt;.

[theend]:http://embercode.com/tvshows/the-end.html "Sad News"
[download]:http://victorpimentel.com/tvshows/TVShows.zip "Download TVShows"

[tvshows]:http://victorpimentel.com/tvshows/ "TVShows Website"
[translate]:https://webtranslateit.com/en/projects/1852-TVShows/invitation_request "Help Translate TVShows 2"
[translate-info]:http://embercode.com/blog/2010/help-translate-tvshows-2/ "Help Translate TVShows 2"

[preview-1]:http://embercode.com/_tvshows/screenshots/show-list_small.png "TVShows 2: Show List"
[preview-2]:http://embercode.com/_tvshows/screenshots/subscriptions_small.png "TVShows 2: Subscriptions"
[preview-3]:http://embercode.com/_tvshows/screenshots/show-info_small.png "TVShows 2: Show Info Window"

[license]:http://www.gnu.org/licenses/ "GNU General Public License"
