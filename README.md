# datahacks-redirect

Serves `datahacks.ds3atucsd.com` on GitHub Pages and sends every request to the same path, query and hash on
`https://datahacks.ds3ucsd.com`, where DataHacks lives (`ucsdds3/datahacks`). `404.html` is the same page, so deep
links like `/portal/hacker` redirect too.

DNS (Namecheap, ds3atucsd.com): `CNAME datahacks -> ucsdds3.github.io.` The custom domain is set by `CNAME` here.
