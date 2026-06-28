[![Website](https://img.shields.io/badge/Website-pink?style=plastic)](https://mldchan.dev)
[![Discord](https://img.shields.io/discord/1362400131206348930?style=plastic&label=Discord&color=%235762F0)](https://discord.gg/aE2MXH5Qp6)
[![Static Badge](https://img.shields.io/badge/Fediverse-%40luna%40fedi.mldchan.dev-pink?style=plastic)](https://fedi.mldchan.dev/users/luna)
[![Gitea Issues](https://img.shields.io/gitea/issues/open/luna/uwurandom-rs?gitea_url=https%3A%2F%2Fgit.mldchan.dev&style=plastic)](https://git.mldchan.dev/luna/uwurandom-rs/pulls)
[![Gitea Pull Requests](https://img.shields.io/gitea/pull-requests/open/luna/uwurandom-rs?gitea_url=https%3A%2F%2Fgit.mldchan.dev&style=plastic)](https://git.mldchan.dev/luna/uwurandom-rs/issues)

# uwurandom-rs

A Rust version of [Bread's uwurandom.php](https://github.com/BreadTeleporter/uwurandom.php).

## Usage

```rs
use mldkyt_uwurandom_rs::Uwurandom;

fn main() {
    Uwurandom::generate(1000);
}
```
