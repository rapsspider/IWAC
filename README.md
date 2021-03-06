![IWAC](https://github.com/Themandunord/IWAC/blob/master/img/iwak.PNG?raw=true)

# IWAC

> Command line tool to create Watson Assistant Workspaces

## Install

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i iwac -g
```

> Keep in mind that Watson Assistant have a Rate Limit of 30 requests every 30 Minutes

## Usage

```js
iwac --help
iwac list|l
iwac create|c
iwac remove|r
iwac migrate|m
iwac d|dump
```

iwac create options :
- -y | --yml if you want to export to yaml
- -a, --url <url> Url of watson assistant
- -u, --username <username> Username of watson assistant
- -p, --password <password> Password of watson assistant
- -l, --languages <a>,<b> Languages of workspaces separated by a comma
- -t, --types <a>,<b> Types of workspaces separated by a comma

iwac dump options :
- -o | --output-directory *Mandatory* Specifies where to create dump files

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/Themandunord/IWAC/issues)

## Author

**Themandunord**

* [github/](https://github.com/Themandunord)
* [twitter/](https://twitter.com/lespagnolr)

## License

Copyright © 2018 [Themandunord](#Themandunord)
Licensed under the MIT license.
