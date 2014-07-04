
# The ExpressJS Organization

The [ExpressJS][expressjs] Organization is a collection
of community-owned node.js web modules with shared maintenance.
Refactored from [Connect][connect], [Express][express], and [Koa][koa],
these modules aim to be small, well-tested, focused, RFC-compliant,
and usable by _any_ node.js framework or middleware.

Please let us know if you're interested in:

- Maintaining some modules in the organization
- Moving popular libraries into the organization

## Background

Most of these libraries are based on many of [TJ Holowaychuk](https://github.com/visionmedia)'s work.
Maintainers were slowly added to his projects to keep up with the maintenance burden.
But code maintenance isn't the sole issue;
maintaining the repositories themselves as well their maintainers is just as difficult.

GitHub organizations allow easy administration of multiple repositories,
their maintainers, as well as maintenance of their code.
With [TJ Holowaychuk's retirement from node.js](https://twitter.com/tjholowaychuk/status/484897639033368576),
a robust framework to maintain his still widely-used modules is needed
by the community, and GitHub organizations are the answer.
With the ability to [share npm publishing rights](https://github.com/repo-utils/npm-org-rights)
very easily, no (still useful) module will be left behind.

With organizations comes a change in node's open source authorship philosophy.
npm places emphasis on the owner and author of a package.
Instead, we believe open source software should be community owned and maintained
as the original author is largely irrelevant if s/he no longer maintains the project.
With organizations, users won't have to worry about code rot,
ignored pull requests, or a single, overbearing czar.

## Team

These are the core team members, those that actively maintain more than one module.
You can also view all the public [team members](https://github.com/orgs/expressjs/members).

- [dougwilson](https://github.com/dougwilson) - current lead maintainer of [Express][express]
  and [Connect][connect]. Maintains much of Connect 2.x/Express 3.x's middleware
  as well as many tiny modules. A stickler for RFC-compliance, tests, and code-coverage.
- [jonathanong](https://github.com/jonathanong) - maintains many of the core modules
  as well as [Koa][koa]
- [fishrock123](https://github.com/fishrock123) - administrates and book-keeps
  many of the modules as well as maintains the mime-type-related libraries.
- [defunctzombie](https://github.com/defunctzombie)
- [mscdex](https://github.com/mscdex)

### Honorary Members

- [visionmedia](https://github.com/visionmedia) - maintains [koa][koa]
  and [co](https://github.com/visionmedia/co)-related libraries

## Frameworks

These frameworks are actively maintained by members of the Organization.

- [Connect][connect]
- [Express][express]
- [Koa][koa]

## Core Modules

Building a node.js web framework?
These are the modules you should be particularly interested in:

- [accepts](https://github.com/expressjs/accepts) - high-level content negotiation
- [csrf-tokens](https://github.com/expressjs/csrf-tokens) - the logic behind CSRF tokens
- [cookies](https://github.com/expressjs/cookies) - cookie management with
  support for signed, base64-encoded, and encrypted cookies
- [compressible](https://github.com/expressjs/compressible) - check whether a specific mime type is compressible
- [finished](https://github.com/expressjs/finished) - make sure you don't leak file descriptors
- [media-typer](https://github.com/expressjs/media-typer) - RFC-compliant media type parser
- [mime-types](https://github.com/expressjs/mime-types) - essentially a fork of [mime](https://github.com/broofa/node-mime)
- [path-to-regexp](https://github.com/component/path-to-regexp) - path parser used by [Express][express]. Also supports the browser.
- [resolve-path](https://github.com/expressjs/resolve-path) - check for malicious paths
- [statuses](https://github.com/expressjs/statuses) - status code utility
- [type-is](https://github.com/expressjs/type-is) - high-level `Content-Type` checking
- [vary](https://github.com/expressjs/vary) - `Vary`-header management

## Related Organizations

Our goal for open source software is to organize modules well as well as
share the maintenance burden so that no one has to worry about code rot.
The ExpressJS Organization is focused with node web modules,
but there are multiple organizations maintained in a similar manner.

If you're interested in joining or collaborating with these organizations,
please let us know!

- [CoJS](https://github.com/cojs) - [co](https://github.com/visionmedia/co)-related modules
- [Component](https://github.com/component) - browser components
- [KoaJS](https://github.com/koajs) - [koa][koa] and associated middleware
- [ReworkCSS](https://github.com/reworkcss) - the [rework](https://github.com/reworkcss/rework)
  CSS preprocessor and associated plugins

Organizations for tiny utilities:

- [css-utils](https://github.com/css-utils) - generic CSS utilities
- [crypto-utils](https://github.com/crypto-utils) - node cryptography-related modules
- [fs-utils](https://github.com/fs-utils) - file-system-related node modules
- [math-utils](https://github.com/math-utils) - math utilities for both the server and the browser
- [mongodb-utils](https://github.com/mongodb-utils) - mongodb-related utilities
- [repo-utils](https://github.com/repo-utils) - utilities for repositories and packages
- [stream-utils](https://github.com/stream-utils) - node stream utilities

Other organizations you might be interested in:

- [detects](https://github.com/detects) - browser feature detects as tiny modules
- [node-modules](https://github.com/node-modules) - generic node modules
- [normalize](https://github.com/normalize) - package management-less,
  build-less, and specification-compliant web development
- [polyfills](https://github.com/polyfills) - browser polyfills and
  user-agent-based polyfill combinations


[expressjs]: https://github.com/expressjs
[express]: http://expressjs.com
[connect]: http://www.senchalabs.org/connect/
[koa]: https://koajs.com
