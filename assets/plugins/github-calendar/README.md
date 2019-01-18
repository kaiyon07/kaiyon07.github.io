<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


# github-calendar.js

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Ask me anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/github-calendar.svg)](https://www.npmjs.com/package/github-calendar) [![Downloads](https://img.shields.io/npm/dt/github-calendar.svg)](https://www.npmjs.com/package/github-calendar)

> Embed your GitHub contributions calendar anywhere.


Everybody<sup><sup>well, haters gonna hate</sup></sup> loves GitHub and everybody loves stats. So, why not making the GitHub contributions calendar available for being embeded in your web pages? Now [you can](https://ionicabizau.github.io/github-calendar/example). :tada:


[![](http://i.imgur.com/S1h8XoB.jpg)](https://ionicabizau.github.io/github-calendar/example)


## :cloud: Installation


Check out the [`dist`](/dist) directory to download the needed files and include them on your page.

If you're using this module in a CommonJS environment, you can install it using `npm` or `yarn` and `require` it:

```sh
# Using npm
npm install --save github-calendar

# Using yarn
yarn add github-calendar
```


## :memo: Documentation


### `GitHubCalendar(container, username, options)`
Brings the contributions calendar from GitHub (provided username) into your page.

#### Params

- **String|HTMLElement** `container`: The calendar container (query selector or the element itself).
- **String** `username`: The GitHub username.
- **Object** `options`: An object containing the following fields:
 - `summary_text` (String): The text that appears under the calendar (defaults to: `"Summary of
   pull requests, issues opened, and commits made by <username>"`).
 - `proxy` (Function): A function that receives as argument an url (string) and should return the proxied url.
   The default is using [@izuzak](https://github.com/izuzak)'s [`urlreq`](https://github.com/izuzak/urlreq).
 - `global_stats` (Boolean): If `false`, the global stats (total, longest and current streaks) will not be calculated and displayed. By default this is enabled.
 - `responsive` (Boolean): If `true`, the graph is changed to scale with the container. Custom CSS should be applied to the element to scale it appropriately. By default this is disabled.

#### Return
- **Promise** A promise returned by the `fetch()` call.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![Buy me a book][badge_amazon]][amazon]—I love books! I will remember you after years if you buy me one. :grin: :book:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


## :cake: Thanks

 - Big thanks to [**@izuzak**](https://github.com/izuzak) for creating the [urlreq](https://github.com/izuzak/urlreq) project–the default proxy used by this library. :cake:
 - Part of the CSS code was taken from the GitHub profile page to offer the same experience. :art:



## :sparkles: Related

 - [`github-profile-languages`](https://github.com/IonicaBizau/github-profile-languages)—Create a nice pie chart with the user's programming languages from their GitHub profile.
 - [`github-org-members.js`](https://github.com/IonicaBizau/github-org-members.js)—A JavaScript library for fetching and rendering in HTML the members of a GitHub organization.
 - [`gh-contributions`](https://github.com/IonicaBizau/github-contributions)—A tool that generates a repository which being pushed into your GitHub account creates a nice contributions calendar.
 - [`github-emojify`](https://github.com/IonicaBizau/github-emojify#readme)—Emojify your GitHub repository descriptions.
 - [`github-stats`](https://github.com/IonicaBizau/github-stats)—Visualize stats about GitHub users and projects in your terminal.
 - [`github-labeller`](https://github.com/IonicaBizau/github-labeller#readme)—Automagically create issue labels in your GitHub projects.
 - [`cli-gh-cal`](https://github.com/IonicaBizau/cli-gh-cal)—GitHub like calendar graphs in command line.
 - [`gh-destroy`](https://github.com/IonicaBizau/gh-destroy#readme)—Delete multiple GitHub repositories.
 - [`ship-release`](https://github.com/IonicaBizau/ship-release#readme)—Publish new versions on GitHub and npm with ease.
 - [`github-calendar-legend`](https://github.com/IonicaBizau/github-calendar-legend#readme)—The GitHub contributions calendar colors.
 - [`github-pr-branch-links`](https://github.com/IonicaBizau/github-pr-branch-links)—Open in a new tab the clicked branch on a pull request page.
 - [`github-emoji-form-submit`](https://github.com/IonicaBizau/github-emoji-form-submit#readme)—Autocomplete selected Emoji when submitting forms on GitHub.com.
 - [`gh-repeat`](https://github.com/IonicaBizau/gh-repeat#readme)—Repetitive actions on multiple GitHub repositories.
 - [`gh-repos`](https://github.com/IonicaBizau/gh-repos#readme)—Get one or all the owner repositories from GitHub.
 - [`github-old-header`](https://github.com/IonicaBizau/github-old-header)—Brings the old header links back.
 - [`gh.js`](https://github.com/IonicaBizau/gh.js)—Tiny GitHub API wrapper for server and client.
 - [`ghcal`](https://github.com/IonicaBizau/ghcal)—See the GitHub contributions calendar of a user in the command line.
 - [`sort-github-user-repos`](https://github.com/IonicaBizau/sort-github-user-repos#readme)—Sort GitHub repositories by stars for user.
 - [`github-calendar-parser`](https://github.com/IonicaBizau/github-calendar-parser#readme)—Parses the GitHub contributions calendar SVG code into JSON.
 - [`gh-notifier`](https://bitbucket.org/IonicaBizau/gh-notifier#readme)—Receive desktop notifications from your GitHub dashboard.
 - [`octimatch`](https://github.com/IonicaBizau/OctiMatch#readme)—A matching game with GitHub's Octicons.
 - [`github-portfolio`](https://github.com/IonicaBizau/github-portfolio#readme)—A tool to generate a portfolio using data from your Github projects.
 - [`gh-polyglot`](https://github.com/IonicaBizau/node-gh-polyglot)—Get language stats about GitHub users and repositories.
 - [`cli-github`](https://github.com/IonicaBizau/cli-github)—A fancy GitHub client for command line.
 - [`github-calendar`](https://github.com/IonicaBizau/github-calendar#readme)—Embed your GitHub contributions calendar anywhere.
 - [`git-stats`](https://github.com/IonicaBizau/git-stats)—Local git statistics including GitHub-like contributions calendars.
 - [`repository-downloader`](https://github.com/IonicaBizau/repository-downloader)—Download all the repositories from BitBucket and GitHub, including your account, teams and where you created pull requests.
 - [`github-colors`](https://github.com/IonicaBizau/github-colors)—GitHub colors and file extensions mapping



## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2016#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md