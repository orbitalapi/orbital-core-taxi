# orbital-core-taxi
The taxi project containing Orbital's core types for working with databases, kafka topics, etc.

Orbital includes this by default on startup.

However, to include a reference to this in your taxi project, declare a dependency in your `taxi.conf` file:

```
dependencies: {
   "com.orbitalhq/core" : "github:orbitalapi/orbital-core-taxi#0.34.0"
}
```

## Updates
This project is automatically updated as part of the Orbital build process.

## Versioning
A branch is maintained for each release, including snapshot builds
