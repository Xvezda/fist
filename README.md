# Fist
![License](https://img.shields.io/github/license/Xvezda/fist)

The fast & easy gist uploader script. Derieved from [shhhh](https://github.com/xvezda/shhhh) project.

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


## Setting

```
export GITHUB_USERNAME=[YOUR_USERNAME_HERE]        # Or, fist --user USERNAME
export GITHUB_TOKEN_FIST=[YOUR_ACCESS_TOKEN_HERE]  # Or, fist --token TOKEN
```


## How to get token

Go to [settings > profile](https://github.com/settings/profile) > [Developer settings](https://github.com/settings/apps) > [Personal access tokens](https://github.com/settings/tokens).

Then, click *Generate new token* and check `gist` checkbox for permission.


## See also
* [shhhh](https://github.com/xvezda/shhhh)
