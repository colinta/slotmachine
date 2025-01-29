slot(1) -- store or retrieve text from stdin/stdout
========

SYNOPSIS
-----

    # store for later
    echo -n "hello" | slot greeting

    # retrieve
    slot greeting > greeting.txt

DESCRIPTION
-----
`slot` is super simple. Store things by piping text into it, then retrieve them later. If you have used `pbcopy`/`pbpaste`, this is similar but doesn't interfere with your clipboard.

OPTIONS
-----

Slots are stored in `~/.config/slots/<name…>`. You can customize the location using environment variable `SLOT_MACHINE`

USAGE
-----
