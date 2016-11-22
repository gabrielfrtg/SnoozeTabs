# SnoozeTabs
An add-on to let you snooze your tabs for a while.

## How to run

* To lint: `npm run lint`
* To run: `npm test`
* To build for release: `npm run build`


## Architectural Questions / Decisions…

* Spec?
  * At [this link][spec].
* Assets?
  * Coming soon.
* Should we write this as a [WebExtension][webext]?
  * YES!

* Should we use a build step?
  * It would let us use [Flow][flow].
    * Should we even use Flow?
  * It would let us use [Sass][sass].
  * It would let us pull the info for the manifest from package.json.
  * It would let us `require` other javascript modules.
  * It would be more complicated, and I’m not sure we need it.
* Put the source in the root, or in a `src` subdirectory?
  * We could build into `dist`…
* Should we use a build tool?
  * [Gulp][gulp]?
  * [Grunt][grunt]?
  * Just [NPM][npm] scripts?
  * Nothing?


[flow]: https://flowtype.org/
[gulp]: http://gulpjs.com/
[grunt]: http://gruntjs.com/
[npm]: https://docs.npmjs.com/misc/scripts
[sass]: http://sass-lang.com/
[spec]: https://mozilla.invisionapp.com/share/MV9F846SY#/screens
[webext]: https://developer.mozilla.org/en-US/Add-ons/WebExtensions