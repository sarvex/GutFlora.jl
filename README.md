# GutFlora

[![Build Status](https://travis-ci.org/one-more-minute/GutFlora.jl.svg?branch=master)](https://travis-ci.org/one-more-minute/GutFlora.jl)

```julia
Pkg.clone("https://github.com/one-more-minute/GutFlora.jl")
```

*GutFlora.jl* provides Julia with digestive functions. Contains a pure-Julia
implementation of the MD5 checksum, available as `md5(::IO)` or `md5file("file")`.

MD5 is just over 2x slower than the built in `md5` command on my machine
(performance improvements by PR very welcome).
