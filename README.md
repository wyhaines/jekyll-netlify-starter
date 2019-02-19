# jekyll-netlify-starter

Jekyll is great for making static web sites.

https://jekyllrb.com/

Netlify CMS is a very nice, simple, easy to use CMS system (and CMS construction kit) that uses a git repo as it's backing store.

https://www.netlifycms.org/docs/add-to-your-site/

The combination of the two enables simple, effective management of a site's content via Netlify, all generated via Jekyll.

If you make use of Github/Gitlab deploy hooks, via Serf/serf-handler

https://github.com/wyhaines/serf-handler

https://sourcediving.com/diy-git-autodeployment-infrastructure-with-serf-and-ruby-c8bc9272194e

Or wire up some other deploy mechanism, the `bin/rebuild` script will regenerate the site for you, keeping a configurable number of past copies of the site, and utilizing a lock so that if the rebuild is triggered externally, there will never be two rebuilds running simultaneously.

This is a very basic set of starter files. It makes no framework assumptions, and provides the bare minimum of configuration to get you going.

Please file an issue with any requests or changes.
