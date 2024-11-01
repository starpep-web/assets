# Assets

This repository contains the binary assets served by the [static-file-server](https://github.com/starpep-web/static-file-server).

This repository is mainly here for documentation reasons. The assets are saved in the following [Google Drive](https://drive.google.com/drive/folders/1TtmM0-oiNAfwT34dOYWZlgIKScw8vHP9?usp=sharing) folder.

## Requirements

In order to develop for this repository you need:

* Have [env-development](https://github.com/starpep-web/env-development) running locally.

## Development

First, clone this repository:

```bash
git clone https://github.com/starpep-web/assets
```

Download the `files` folder from the aforementioned *Google Drive* link and place it somewhere on your computer.

Now, if you have [env-development](https://github.com/starpep-web/env-development) cloned, make sure to point the `files` folder to the `STATIC_FILES_LOCATION` env variable in its `.env` file.

Keep in mind that the shared folder is very heavy and contains over 300.000 files.
