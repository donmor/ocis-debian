# ocis-debian

[![Debian Build Bot](https://github.com/donmor/ocis-debian/actions/workflows/dpkg-buildpackage.yml/badge.svg?event=release)](https://github.com/donmor/ocis-debian/actions/workflows/dpkg-buildpackage.yml)

Unofficial Debian packaging scripts for [ownCloud Infinite Scale](https://github.com/owncloud/ocis).

You may want to pin to specific stable versions (e.g. 7.1.x).

``` bash
# tee /etc/apt/sources.list.d/ocis.list <<EOF
deb [trusted=yes] https://github.com/donmor/ocis-debian/releases/latest/download /
# deb-src [trusted=yes] https://github.com/donmor/ocis-debian/releases/latest/download /
EOF
```
Gitee mirror (newest 5 versions only)
``` bash
# tee /etc/apt/sources.list.d/ocis.list <<EOF
deb [trusted=yes] https://gitee.com/donmor/ocis-debian/releases/download/latest /
# deb-src [trusted=yes] https://gitee.com/donmor/ocis-debian/releases/download/latest /
EOF
```
