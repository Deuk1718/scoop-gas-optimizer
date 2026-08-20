# scoop-gas-optimizer

Scoop bucket for [GAS-Optimizer](https://github.com/Deuk1718/GAS-Optimizer).

```powershell
scoop bucket add gas-optimizer https://github.com/Deuk1718/scoop-gas-optimizer
scoop install gas-optimizer
gas-optimizer install
```

This bucket installs only the `gas-optimizer` launcher and the versioned skill bundle. It does not copy files into host skill directories such as `~/.agents/skills` or `~/.claude/skills`. After the package is installed, run `gas-optimizer install` to copy the skill into a host location.

The manifest in `gas-optimizer.json` is generated from GAS-Optimizer GitHub Release assets. After a new GAS-Optimizer release, copy the published `gas-optimizer.json` asset into this repository.
