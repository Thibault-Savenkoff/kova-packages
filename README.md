# Kova packages

The list `kova search` reads. It only helps people find a package: `import` never reads it, and a
package listed here has not been reviewed. Read a package before you use it.

To add yours, open a pull request adding one line to `index.txt`:

```
json github.com/ada/kova-json Reads and writes JSON
```

The name is what people will `import`, the address is a public git repository with a
`package.kova` at its root and at least one tag such as `v1.0.0`. Versions are read from your tags:
a new version needs no change here.

See [how packages work](https://thibault-savenkoff.github.io/kova/guide/modules/#packages).
