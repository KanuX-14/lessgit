# lessgit

This script acts like git. Instead of using `git clone URL`, it gets the actual TAR.GZ file and extract, further removing the TAR.GZ file.
Useful for systems that use different kernel, such as Android.

## Usage ##

First, give permission for the script to run without problems:
```shell
$: chmod +x lessgit
```
Then you can run it:
```shell
$: ./lessgit URL
```

If you don't want to give permissions, run it with `bash` command:
```shell
$: bash lessgit URL
```

## Commands ##

The options of the script are simple.
```shell
-h: prints the help page.
-v: prints the version.
```
