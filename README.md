# scoop-bucket

A [Scoop](https://scoop.sh) bucket for my tools on Windows.

## xfer — unified transfer monitor

```powershell
scoop bucket add redswoop https://github.com/redswoop/scoop-bucket
scoop install xfer
```

This pulls in [`aria2`](https://aria2.github.io/) automatically (xfer's download
engine). Manifests under [`bucket/`](bucket/) are generated and updated
automatically by the [xfer release workflow](https://github.com/redswoop/xfer);
don't edit them by hand.

Upstream project: <https://github.com/redswoop/xfer>
