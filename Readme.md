# ESLint Configurations Comparision Chart

## ESLint Recommended vs AirBnB vs Google vs Standard

Last edited: 06/14/2020

GitHub Gist: ([URL](https://gist.github.com/dannylee8/c1c98ab05b15e3071e2dd34f44d5ff61)) | Embed: `<script src="https://gist.github.com/dannylee8/c1c98ab05b15e3071e2dd34f44d5ff61.js"></script>`

A chart comparing which rules are set by each of these premade configs.  Rule names are linked to their doc pages on ESLint.org. Making the chart was useful for getting familiar with rules, switches, arguments, the choices made by each org, and an exercise in tedium and endurance to decipher the data from the config files to the chart.  

The easiest to work with was the AirBnB files, which were broken down into separate individual files, according to rule set (e.g. errors, styles, best practices, ecma6, etc).  The hardest to work with was standard, which was alphabetized across all the different rulesets.  Because my chart was separated by rule set, this took more time.  Google's ruleset looks like its neglected and its pretty basic.  ESLint's recommended is short and alphabetized across rules sets.


Another option for formatting or in conjunction with ESLint is Prettier ([repo](https://github.com/prettier)).  Its very popular, but it focuses on looks, not syntactical rules.

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
