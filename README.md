# protobuf-net 

Unity Package Manager compatible version of [mgravell/protobuf-net](https://github.com/mgravell/protobuf-net).

# Usage

As git packages are not yet supported in the Package Manager GUI you'll have to reference it yourself via `manifest.json`, located under `<project path>/Packages/manifest.json`.

Simply add this package as a new dependency using the syntax shown below.
```js
"de.cryma.protobuf-net": "https://github.com/Cryma/protobuf-net.git"
```

After restarting Unity the package can be used.

**Important:** If you use Assembly Definitions, don't forget to add `de.cryma.protobuf-net.Runtime` as a reference.
