# datahacks-redirect

Serves `datahacks.ds3ucsd.com` on GitHub Pages and sends every request to the same path, query and hash on
`https://datahacks.ds3atucsd.com`, where DataHacks lives now (`ucsdds3/datahacks`). `404.html` is the same page,
so deep links like `/portal/hacker` redirect too. ds3ucsd.com is registered under an account DS3 lost; this keeps
old links working until that domain lapses (April 2027) or is recovered.
