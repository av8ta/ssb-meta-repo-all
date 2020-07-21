# awesome ssb meta repo

secure scuttlebutt is full of wonderful little (and big!) packages that do amazing things... they're just hard to find!
this repo is for all and anything ssb; come here to discover delights and browse creative scuttlers' code

this is a [meta](https://www.npmjs.com/package/meta) repo

from the meta docs:

```
meta is a tool for managing multi-project systems and libraries. It answers the conundrum of choosing between a mono repo or many repos by saying "both", with a meta repo!

meta is powered by plugins that wrap common commands, letting you execute them against some or all of the repos in your solution at once
```

# usage

```bash
npx meta git clone https://github.com/av8ta/ssb-meta-repo-all.git
```

meta will clone all of the repos contained in the [.meta](./.meta) file here in the root directory.

## adding ssb repositories

pull requests are very welcome! there are many more packages that didn't show up on a cursory npm search for the keyword ssb; so please feel free to add others and send a pull request :)

[meta](https://www.npmjs.com/package/meta) is awesome so please go install that first, but if you don't wish to, you can simply use npx

```bash
npx meta project create ssb-something https://somegitregistry
```

if you have git-ssb installed you can use ssb:// git repos too

for further documentation see [meta](https://www.npmjs.com/package/meta)
