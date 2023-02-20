netcat
------

A minimal and [secure](https://github.com/tuananh/netcat/security/advisories) container image for Debian port of OpenBSD's netcat, available in both `amd64` and `arm64`. To use run:

```
docker run --rm -ti ghcr.io/tuananh/netcat -zv google.com 443
```

![image](https://user-images.githubusercontent.com/627278/219961252-d4c7e0e6-7a1e-4fbc-936e-07527f7cbd89.png)

![image](https://user-images.githubusercontent.com/627278/219961484-63ab9f69-3e83-487c-9d82-24ba8e7e7c7a.png)


See [here](https://manpages.debian.org/unstable/netcat-openbsd/nc.1.en.html) for invocation details.

## NOTICE

This docker image includes

- Debian port of OpenBSD netcat, packaged for [Wolfi OS](https://packages.debian.org/sid/netcat-openbsd).
- [Wolfi OS](https://packages.debian.org/sid/netcat-openbsd) – maintained by Chainguard team.

## License

Copyright 2023 Tuan Anh Tran <me@tuananh.org>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
