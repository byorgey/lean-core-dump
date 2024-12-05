# lean-core-dump

On my computer, `lake build && .lake/bin/lean-core-dump` crashes with
a segmentation fault.  If you comment out the `import
Aesop.Frontend.RuleExpr` in `Main.lean`, then it prints `hello
world` as expected.
