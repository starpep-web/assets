# Assets

This repository contains the binary assets served by the [static-file-server](https://github.com/starpep-web/static-file-server).

## Requirements

In order to develop for this repository you need:

* Have [env-development](https://github.com/starpep-web/env-development) running locally.

## Development

First, clone this repository:

```bash
git clone https://github.com/starpep-web/assets
```

And pull LFS archives:

```bash
git lfs pull
```

Now, if you have [env-development](https://github.com/starpep-web/env-development) cloned, make sure to point the `files` folder to the `STATIC_FILES_LOCATION` env variable in its `.env` file.

Keep in mind that this repository might be a bit large since there's +100.000 files.
