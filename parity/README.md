# Parity with Nix

`report.md` is the result of evaluating every attribute of nixpkgs'
`ci/eval/outpaths.nix` with nix-eval-jobs and with jinx on this revision
and comparing drvPaths (jinx's docs/verification.md). `joined.tsv.gz` has
one line per attribute: the attribute path as JSON, Nix's drvPath or
`ERROR: <message>`, and jinx's.
