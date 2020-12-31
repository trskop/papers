# Papers

Repository of academic and other papers.


## Initialise Local Copy

```bash
git clone https://github.com/trskop/papers.git ~/Documents/Papers
git -C ~/Documents/Papers config remote.origin.annex-readonly true
git -C ~/Documents/Papers config annex.security.allowed-http-addresses all
git -C ~/Documents/Papers annex init
```

## Fetch File Content

Fetch contents of individual files:

```bash
git -C ~/Documents/Papers annex get FILE [...]
```

Or everything:

```bash
git -C ~/Documents/Papers annex get .
```
