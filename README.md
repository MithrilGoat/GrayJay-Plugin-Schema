
# GrayJay Plugin Schema

Community maintained JSON schema for GrayJay plugin configs.

<br/>

## Integration

Simply add the following schema property to your config.

```json
    "$schema" : "https://raw.githubusercontent.com/MithrilGoat/GrayJay-Plugin-Schema/refs/tags/<Version>/Source/Schema.json" ,
```

```json
    "$schema" : "https://raw.githubusercontent.com/MithrilGoat/GrayJay-Plugin-Schema/refs/tags/278.0/Source/Schema.json" ,
```

Where `<Version>` is whatever [Release] you want to use , though  
generally it is recommended to use the latest version available.

<br/>

## Versioning

The [Release] versions are made up of the [GrayJay Release]  
number and a build / fix subversion in the following form:

```txt
<GrayJay Release>.<Build / Fix>
```

```txt
278.0
```



[GrayJay Release]: https://gitlab.futo.org/videostreaming/grayjay/-/tags
[Release]: https://github.com/MithrilGoat/GrayJay-Plugin-Schema/releases
