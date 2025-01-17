# @yskszk63/throw-error-on-load

```bash
$ node -e 'import("@yskszk63/throw-error-on-load/throw.js")'
file:///.../throw-error-on-load/throw.js:1
throw new Error("🙈");
      ^

Error: 🙈
    at file:///.../throw-error-on-load/throw.js:1:7
    at ModuleJob.run (node:internal/modules/esm/module_job:271:25)
    at async onImport.tracePromise.__proto__ (node:internal/modules/esm/loader:547:26)
    at async importModuleDynamicallyWrapper (node:internal/vm/module:436:15)

Node.js v23.4.0
```
