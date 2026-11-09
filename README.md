[![Website](https://img.shields.io/badge/Website-pink?style=plastic)](https://mldkyt.com)
[![Discord](https://img.shields.io/discord/1362400131206348930?style=plastic&label=Discord&color=%235762F0)](https://discord.gg/aE2MXH5Qp6)
[![Static Badge](https://img.shields.io/badge/Fediverse-%40luna%40fedi.mldkyt.com-pink?style=plastic)](https://pl.mldkyt.com/users/mldkyt)
[![Forgejo Issues](https://img.shields.io/gitea/issues/open/mldkyt/uwurandom-rs?gitea_url=https%3A%2F%2Fgit.mldkyt.com&style=plastic)](https://git.mldkyt.com/mldkyt/uwurandom-rs/pulls)
[![Forgejo Pull Requests](https://img.shields.io/gitea/pull-requests/open/mldkyt/uwurandom-rs?gitea_url=https%3A%2F%2Fgit.mldkyt.com&style=plastic)](https://git.mldkyt.com/mldkyt/uwurandom-rs/issues)

# uwurandom-rs

A Rust version of [Bread's uwurandom.php](https://github.com/BreadTeleporter/uwurandom.php).

## Usage

```rs
use mldkyt_uwurandom_rs::Uwurandom;

fn main() {
    Uwurandom::generate(1000);
}
```
