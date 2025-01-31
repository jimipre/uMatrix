# µMatrix for Chromium

Forked and refactored from [HTTP Switchboard](https://github.com/gorhill/httpswitchboard).

Install [manually](https://github.com/gorhill/uMatrix/blob/master/doc/INSTALL.md) the [latest release](https://github.com/gorhill/uMatrix/releases), or from [Opera store](https://addons.opera.com/en-gb/extensions/details/umatrix/) (currently awaiting approval), [Chrome store](https://chrome.google.com/webstore/detail/µmatrix/ogfcmafjalglgifnmanfmnieipoejdcf).

You may contribute with translation work on Crowdin: [µMatrix on Crowdin](https://crowdin.com/project/umatrix).

[HTTP Switchboard's documentation](https://github.com/gorhill/httpswitchboard/wiki) is still relevant, except for [µMatrix's differences with HTTP Switchboard](https://github.com/gorhill/uMatrix/wiki/Changes-from-HTTP-Switchboard).

You may contribute with documentation: [µMatrix's wiki](https://github.com/gorhill/uMatrix/wiki).

## Warnings

#### Regarding broken sites

µMatrix does not guarantee that sites will work fine: it is for advanced users who can figure how to un-break sites, because essentially µMatrix is a firewall which works in block-all/allow-exceptionally mode out of the box: it is not unexpected that sites will break.

**So this means do not file issues to report broken sites when the sites are broken because µMatrix does its job as expected.** I will close any such issue without further comment.

I expect there will be community driven efforts for users to help each others. If µMatrix had a home, I would probably set up a forum, but I do not plan for such thing, I really just want to code, not manage web sites. If you need help to un-break a site when using µMatrix, you can try [Wilders Security](http://www.wilderssecurity.com/threads/umatrix-the-http-switchboard-successor.369601/), where you are likely to receive help if needed, whether by me or other users.

µMatrix can be set to work in [allow-all/block-exceptionally](https://github.com/gorhill/httpswitchboard/wiki/How-to-use-HTTP-Switchboard:-Two-opposing-views#the-allow-allblock-exceptionally-approach) mode with a single click on the `all` cell in the global scope `*`, if you prefer to work this way. This will of course break less sites, but you would then lose all the benefits which comes with block-all/allow-exceptionally mode.


## License

<a href="https://github.com/gorhill/umatrix/blob/master/LICENSE.txt">GPLv3</a>.
