# My personal bucket for Scoop

[![Tests](https://github.com/nisijon/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/nisijon/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/nisijon/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/nisijon/scoop-bucket/actions/workflows/excavator.yml)

My personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add <bucketname> https://github.com/nisijon/scoop-bucket
scoop install <bucketname>/<manifestname>
```
