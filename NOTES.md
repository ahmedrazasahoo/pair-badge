# Pair Programming Notes

Working notes kept while pairing.

## Handy git trailers

Credit a pairing partner on a commit:

```
Co-authored-by: Name <ID+username@users.noreply.github.com>
```

The `ID+username@users.noreply.github.com` form links the co-author to their
GitHub account even when that account keeps its email addresses private, which
a plain address does not.

## Never share a personal access token

A `Co-authored-by:` trailer is plain text in a commit message. It needs no
authentication from the co-author, so pairing never requires anyone to hand
over a token. If a token does get shared, revoke it at
https://github.com/settings/tokens and issue a fresh one.
