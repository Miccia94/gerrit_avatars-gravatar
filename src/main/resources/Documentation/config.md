Configuration
=============

The configuration of the @PLUGIN@ plugin is done in the `gerrit.config`
file.

```
  [plugin "@PLUGIN@"]
    type = identicon
```

<a id="type">
`plugin.@PLUGIN@.type`
:	Avatar type in www.gravatar.com service.

	Can be any type supported by the service
	(404, mm, identicon, monsterid, wavatar, retro, robohash, blank, ...).

	Default: identicon

<a id="rating">
`plugin.@PLUGIN@.rating`
:	Avatar rating in www.gravatar.com service.

	Can be any rating supported by the service
	(g, pg, r, x, ...).

	Default: pg

<a id="gravatarUrl">
`plugin.@PLUGIN@.gravatarUrl`
:	URL that provides the Gravatar API.

	Uses the same protocol (http, https) as gerrit.canonicalWebUrl.

	Default: www.gravatar.com/avatar/

<a id="changeAvatarUrl">
`plugin.@PLUGIN@.changeAvatarUrl`
:	Link to where the avatar can be changed as displayed in the profile settings.

	Default: http://www.gravatar.com
