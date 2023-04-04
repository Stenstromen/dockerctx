# DockerCTX

Rewrite of ahmetb's "kubectx" utility. [https://github.com/ahmetb/kubectx](https://github.com/ahmetb/kubectx)
<br>
To allow switching Docker Context

## Missing functionality compared to KubeCTX
### Rename Context
The docker context command does not allow context renaming, therefore this feature is omitted from DockerCTX.
### unset_context() func
The docker context command does not allow context unset, therefore this feature is omitted from DockerCTX.

## Installation via Homebrew
```
brew install stenstromen/tap/dockerctx
```

## Download and Run Script
* For **MacOS** and **Linux**: Checkout and download the latest script from [Releases page](https://github.com/Stenstromen/dockerctx/releases/latest/)

## Example Usage
```
USAGE:
  dockerctx                       : list the contexts
  dockerctx <NAME>                : switch to context <NAME>
  dockerctx -                     : switch to the previous context
  dockerctx -c, --current         : show the current context name
  dockerctx -d <NAME> [<NAME...>] : delete context <NAME> ('.' for current-context)

  dockerctx -h,--help             : show this message
```