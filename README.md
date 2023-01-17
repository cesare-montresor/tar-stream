# tar-web

tar-web is patched version of tar-stream that runs in a web browser. The original project https://github.com/mafintosh/tar-stream provides a streaming tar parser and generator and nothing else. It operates purely using streams which means you can easily extract/parse tarballs without ever hitting the file system.

Note that you still need to gunzip your data if you have a `.tar.gz`. We recommend using [gunzip-maybe](https://github.com/mafintosh/gunzip-maybe) in conjunction with this.

```
npm install tar-web
```

Original tar-stream Documantation: 
https://github.com/mafintosh/tar-stream/

# Licence

MIT
