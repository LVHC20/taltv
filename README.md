# TalTV

A television for a playlist you already have.

Paste your own IPTV playlist — a link, or the playlist's contents — and watch it
in a browser, on a TV, with a remote. Nothing to install. No account. No tracking
of any kind. Your playlist stays in your browser and is never sent anywhere.

**https://lvhc20.github.io/taltv/**

## What this repository is

Only the built application — the same files your browser downloads when you open
the site. The source is not published.

`checksums.txt` lists the SHA-256 of every file served. You can check that the
file your browser ran is the file that was published:

    shasum -a 256 index.html

That detects a tampered delivery. It does **not** prove the code is honest —
nobody outside can verify what closed source does. Said plainly rather than
dressed up, because the app's first rule is that it never lies to you.
