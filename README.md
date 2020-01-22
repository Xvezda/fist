# Fist

The fast & easy gist uploader script.

## Usage

```sh
fist [files ...]
# or
echo 'something' | fist
```

## Options

```
usage: fist [-h] [--browser] [--verbose] [--silent] [--dry] [--user [USER]]
            [--token [TOKEN]]
            [files [files ...]]

positional arguments:
  files                 Files to upload.

optional arguments:
  -h, --help            show this help message and exit
  --browser, -b         Open web browser when gist uploaded.
  --verbose, -v         Print informations for debugging.
  --silent, -s          Ignore outputs, except gist url.
  --dry, -d             Dry run.
  --user [USER], -u [USER]
                        Set github user name.
  --token [TOKEN], -t [TOKEN]
                        Set github access token.
```
