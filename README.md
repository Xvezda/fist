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
  files                 files to upload.

optional arguments:
  -h, --help            show this help message and exit
  --browser, -b         open web browser when gist uploaded.
  --verbose, -v         print informations for debugging.
  --silent, -s          ignore outputs, except gist url.
  --dry, -d             dry run.
  --user [USER], -u [USER]
                        set github user name.
  --token [TOKEN], -t [TOKEN]
                        set github access token.
```
