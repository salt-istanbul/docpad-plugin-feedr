# History

- v2.7.0 January 10, 2013
	- Updated feedr dependency from ~2.6.0 ~2.7.6

- v2.6.0 October 2, 2013
	- Updated feedr dependency from ~2.5.0 ~2.6.0

- v2.5.0 May 27, 2013
	- Updated feedr dependency from ~2.4.1 ~2.5.0

- v2.4.2 March 7, 2013
	- Repackaged

- v2.4.1 February 1, 2013
	- Updated feedr dependency from 2.4.x to ~2.4.1

- v2.4.0 December 2, 2012
	- Updated feedr dependency from 2.3.x to 2.4.x

- v2.3.0 December 2, 2012
	- Updated feedr dependency from 2.2.x to 2.3.x

- v2.2.0 October 22, 2012
	- Abstracted out non docpad specific functionality into new [feedr](https://github.com/bevry/feedr) project
		- See the new configuration options [here](https://github.com/bevry/feedr#configuration)

- v2.1.0 August 19, 2012
	- Better handling of jsonp responses
	- Better handling of bad json responses
	- `"key": {"_content": "the actual value"}` inside responses will be converted to `"key": 'the actual value"` if `clean` is set to `true` inside the feed configuration

- v2.0.2 August 10, 2012
	- Re-added markdown files to npm distribution as they are required for the npm website
	- Fixed a caching conflict issue when two feeds have the same name across different projects
	- Added the configuration options `refreshCache` and `cacheTime`

- v2.0.1 July 8, 2012
	- Removed underscore dependency
	- Fixed path exists warning
	- Will now store cached files inside the operating systems actual tmp path, instead of always assuming it is `/tmp`
		- Customisable by the `tmpPath` configuration option

- v1.0.0 April 14, 2012
	- Updated for DocPad v5.0

- v0.2.0 April 6, 2012
	- Now exposes `@feedr.feeds` to the `templateData` instead of `@feeds`

- v0.1.0 March 23, 2012
	- Initial working version for [Benjamin Lupton's Website](https://github.com/balupton/balupton.docpad)