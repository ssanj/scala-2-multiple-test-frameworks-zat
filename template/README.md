## SBT project compiled with Scala 3

This project a port of [scala3.g8](https://github.com/scala/scala3.g8) for [Zat](https://github.com/ssanj/zat).

# Usage

You can process this template with Zat with the following:

```
zat process-remote --repository-url https://github.com/ssanj/basic-scala3-zat --target <YOUR_TARGET_DIRECTORY>
```

Once in `YOUR_TARGET_DIRECTORY`  you can do the steps below.

## Compile

You can compile the code with:

```
sbt compile
```

## Run tests

You can run tests with:

```
sbt test
```


## Interactive console

You can jump into an interactive Scala 3 REPL with:

```
sbt console
```

## Variables

|Variable| Description|
|-|-|
|`project`| The name of the executable |
|`scala_3_version`| Scala 3 version. Defaults to `3.3.1` |
|`munit_version`| munit version. Defaults to `0.7.29` |
