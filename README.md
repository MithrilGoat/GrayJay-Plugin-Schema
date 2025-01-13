
# GrayJay Plugin Schema

Community maintained [JSON Schema] for [GrayJay Plugin] configs.

<br/>

## Integration

Simply add one of the following schema properties to your config.

### Latest

This links the latest version of the schema.

```json
    "$schema" : "https://github.com/MithrilGoat/GrayJay-Plugin-Schema/releases/latest/download/Schema.json" ,
```

### Specific

This links a named version of the schema.

```json
    "$schema" : "https://github.com/MithrilGoat/GrayJay-Plugin-Schema/releases/download/<Version>/Schema.json" ,
```

`<Version>` is whatever [Release] you want to use.

```json
    "$schema" : "https://github.com/MithrilGoat/GrayJay-Plugin-Schema/releases/download/278.2/Schema.json" ,
```



<br/>

## Versioning

The [Release] versions are made up of the [GrayJay Release]  
number and a build / fix subversion in the following form:

```txt
<GrayJay Release>.<Build / Fix>
```

```txt
278.2
```



[GrayJay Release]: https://gitlab.futo.org/videostreaming/grayjay/-/tags
[GrayJay Plugin]: https://plugins.grayjay.app/
[JSON Schema]: https://json-schema.org/
[Release]: https://github.com/MithrilGoat/GrayJay-Plugin-Schema/releases
