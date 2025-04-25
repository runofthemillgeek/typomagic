# typomagic

## Usage

In your own Hugo site/project directory, add both typo and this theme as git submodules:

```
git submodule add \
  --branch main \
  https://github.com/tomfran/typo.git \
  themes/typo

git submodule add \
  --branch main \
  https://github.com/runofthemillgeek/typomagic.git \
  themes/typomagic
```

Then edit your `hugo.toml` file and change the theme config to the following:

```toml
theme = ['typomagic', 'typo']
```

Now you can build/run dev server and the changes from my theme should be ported over.

For more details on how this works, check the [theme components](https://gohugo.io/hugo-modules/theme-components/) section of Hugo docs.

## Contributing

**I highly recommend forking this and making your own customizations as this is just meant for users of typo who are interested in the custom stuff I have going on in my blog.**

Otherwise, if you find any minor issues:

1. See if this is an issue in the core tomfran/typo theme.
2. If not and if it is related to my customizations, feel free to raise an issue.

I'm not taking requests or PRs for big feature additions. Once again, feel free to fork and make changes as you please.

## License

Most of the custom code unless otherwise specified in this project is MIT licensed.

However, since I'm lazy, I've also committed some of the vendored stuff like fonts. Please check the respective licenses of those projects:

1. https://github.com/rsms/inter
2. https://commitmono.com
