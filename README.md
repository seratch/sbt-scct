## A fork of sbt-scct

sbt 0.12 and 0.13 are supported. Available on sonatype oss and maven central repository.

## Usage

Basically same as original.

### project/plugins.sbt

```scala
addSbtPlugin("com.github.seratch.reaktor" % "sbt-scct" % "0.2.001")
```

### build.sbt

```
ScctPlugin.instrumentSettings
```
