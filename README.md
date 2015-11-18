## About

This is a pre commit script that check commits.

You can find more information about how to use this [here](http://qiita.com/DaikiMaekawa). (in Japanese)

## Installation

```sh
$ sudo ./install.sh
```

## Usage

```bash
$ git commit -m "msg"

Author = USER_NAME <USER_EMAIL>
```

```bash
Do you want to me to keep it this way? [y/n] n
Username:NEW_USER_NAME
Email:NEW_USER_EMAIL
Please commit that again...
```

```bash
$ git commit -m "msg"

Author = NEW_USER_EMAIL <NEW_USER_EMAIL>
```

Note that this function applies to newly created repositories after installing the scripts.

## License

Copyright (c) 2013 - 2014, [Daiki Maekawa](http://daikimaekawa.strikingly.com/). (MIT License)

See LICENSE for more info.

