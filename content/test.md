Test för att få in ny sida på menyn
==============================================

Detta är ett test för att få in en ny sida.

* To be used in teaching the [dbwebb course design](http://dbwebb.se/design).

The source for this site is available on GitHub in [canax/anax-flat](git@github.com:canax/anax-flat.git).

This site is produced by [Mikael Roos](https://mikaelroos.se) (mos@dbwebb.se).

---
views:
    byline:
        region: after-main
        template: default/content
        sort: 1
        data:
            meta:
                type: content
                route: block/byline
...
