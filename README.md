# code-workspace

generate code-workspace from file

Example

```shell
➜ ls github
code-workspace  crd  docker-registry-proxy  linux  mtproxy  nvide  shadowray  UDPping
➜ code-workspace github
code-workspace: github.code-workspace sycned
➜ work cat github.code-workspace 
{
    "folders": [
        {
            "path": "github/linux"
        },
        {
            "path": "github/code-workspace"
        },
        {
            "path": "github/UDPping"
        },
        {
            "path": "github/crd"
        },
        {
            "path": "github/docker-registry-proxy"
        },
        {
            "path": "github/mtproxy"
        },
        {
            "path": "github/nvide"
        },
        {
            "path": "github/shadowray"
        }
    ]
}
```