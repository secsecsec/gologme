# gologme

Ulogme is awesomesauce, but there are some not so great things. Namely
that I have to set it up on a bunch of computers and it requires multiple
tools running in the background and they don't always exit as cleanly as
they should. That and I can't compile logs in a single place. This is even
worse when considering android in the mix.

And mostly I want to practice go more :)

## Goals

- [x] Feature parity with ulogme (for the subset which I care about)
    - [x] Window Logging
    - [x] Key Logging
    - [x] Notes
    - [x] Blog
    - [x] lockscreen detection
        - [x] xscreensaver
        - [ ] PRs welcome!
    - [ ] cross platform logging
      - https://github.com/kavu/AyeAye/ maybe
      - PRs welcome since I don't have a mac.
- [x] Ulogme import/export. Near perfect roundtripping
- [ ] Android client
- [x] multi-user support (Why? Who knows. Seems easy to tack on)

## TODO

- [ ] TLS for server-connection [https://github.com/valyala/gorpc](valyala/gorpc)
- [ ] standalone mode

## LICENSE

AGPLv3
