# ESLint Configurations Comparision Chart

## ESLint Recommended vs AirBnB vs Google vs Standard

Last edited: 06/14/2020

GitHub Gist: ([URL](https://gist.github.com/dannylee8/c1c98ab05b15e3071e2dd34f44d5ff61)) | Embed: `<script src="https://gist.github.com/dannylee8/c1c98ab05b15e3071e2dd34f44d5ff61.js"></script>`

A chart comparing which ESLint rules ([list of all rules](https://eslint.org/docs/rules/)) are set by each of the premade configuration files provided by ESLint (recommended), AirBnb ([style guide](https://airbnb.io/javascript/), [GitHub repo](https://github.com/airbnb/javascript)), Google ([style guide](https://google.github.io/styleguide/jsguide.html), [GitHub repo](https://github.com/google/eslint-config-google/)), Standard JS ([style guide](https://standardjs.com/rules.html), [GitHub repo](https://github.com/standard/eslint-config-standard))

ESLint rule names (in the first column) are linked to their respective document pages on ESLint.org. The experience of researching, compiling the choices from each org and getting familiar with rules, switches and arguments was enlightening.  The process was also  an exercise in tedium and a test of endurance and patience.

The easiest configuration to work with was AirBnB.  The settings were broken down into separate individual files, according to rule set (e.g. errors, styles, best practices, ecma6, etc).  The hardest to work with was Standard JS, which was alphabetized, and collected into one set, across all the different rulesets.  Because of the way my chart was designed (i.e. separated by rule set) it took me much more time and effort to navigate through a consolidated ruleset in alphabetical order. Google's ruleset looks like its neglected and its pretty basic, however it IS separated by rule set category and was easy to navigate.  It was also the quickest to work through.  ESLint's recommended is also short, but it was alphabetized across rules sets, however if you work from the [ESLint Rules page](https://eslint.org/docs/rules/) "recommended" rules are marked with a checkmark.

(As an aside: There is another option which can be used in leiu or in conjunction with ESLint, which is very popular--Prettier ([repo](https://github.com/prettier)).  It focuses more on looks, rather than syntactical rules, but is worth investigating.

---

#### Config file links:

- [ESLint recommended configuration file](https://github.com/eslint/eslint/blob/master/conf/eslint-recommended.js)
- [Airbnb base configurations directory](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base/rules)
- [Google configuration file](https://github.com/google/eslint-config-google/blob/master/index.js)
- [Standard JS configuration file](https://github.com/standard/eslint-config-standard)

#### To Do:

- Add footnotes or tooltips to show details for rules in which a particular option is specified.
- Add rollover tooltip to show a sample of a rule's syntax.
- Do an audit to make sure I've gotten all the config files for each org.
- Edit config files for ESLint's recently deprecated options and make pull request.
- Create PDF version
