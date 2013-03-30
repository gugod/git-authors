
# NAME

git-authors -- Show a gist of commit authors.

# USAGE

Show top 10 authors in a repository

```
[~/Projects/perlbrew/App-perlbrew]
> git authors | head -10
commits%  commits      +++      ---
  56.99%      530   +18350   -15322  Kang-min Liu <gugod@gugod.org>
   1.72%       16     +365     -240  Pedro Melo <melo@simplicidade.org>
   1.51%       14     +283      -77  Chris Prather <chris@prather.org>
   1.18%       11      +67      -21  Tatsuhiko Miyagawa <miyagawa@bulknews.net>
   1.18%       11      +28      -24  Randy Stauner <randy@magnificent-tears.com>
   0.97%        9     +100      -81  Yuki Ibe <yibe@yibe.org>
   0.65%        6     +340     -209  Mike Doherty <doherty@cs.dal.ca>
   0.65%        6     +315      -51  Rob Hoelz <rob@hoelz.ro>
   0.65%        6      +20      -13  Sawyer X <xsawyerx@cpan.org>
```

Show authors of a given file

```
[~/src/perl]
> git-authors ./README.tw
commits%  commits      +++      ---
  16.67%        2      +68      -68  Chia-liang Kao <clkao@clkao.org>
  16.67%        2       +2       -2  Nicholas Clark <nick@ccl4.org>
   8.33%        1      +45      -22  Jarkko Hietaniemi <jhi@iki.fi>
   8.33%        1       +6       -4  Audrey Tang <cpan@audreyt.org>
   8.33%        1       +1       -1  Leon Brocard <acme@astray.com>
   8.33%        1       +1       -1  Steffen Müller <0mgwtfbbq@sneakemail.com>
```

# Notice

Numbers are tricky :-)

# LICENCE

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="http://gugod.org">
    <span property="dct:title">Kang-min Liu</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">git-authors</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="NL" about="http://gugod.org">
  Netherlands</span>.
</p>
