# Scoop bucket for acmd

acmd ([Agent Command](https://github.com/brettmostert/agent-command)) on Windows, with [Scoop](https://scoop.sh):

```powershell
scoop bucket add brettmostert https://github.com/brettmostert/scoop-bucket
scoop install acmd
```

On Windows acmd only connects to hosts: it runs no sessions of its own. See [Windows](https://github.com/brettmostert/agent-command/blob/main/docs/remote-sessions.md#windows) to pair it with one.

`bucket/acmd.json` is written by agent-command's release workflow. Don't edit it here: changes go in agent-command's `packaging/scoop/acmd.json.tmpl`.
