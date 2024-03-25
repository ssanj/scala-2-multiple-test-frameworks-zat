## Basic Scala 3 Project with Latest Dependencies

This project a port of [scala3.g8](https://github.com/scala/scala3.g8) for [Zat](https://github.com/ssanj/zat). This project uses the latest stable versions of [Scala 3](https://www.scala-lang.org) and [SBT](https://www.scala-sbt.org/). You can also choose between using the [ScalaTest](https://www.scalatest.org/) or [MUnit](https://scalameta.org/munit/) test frameworks.


# Prerequisites

You need to install the [scala-deps](https://github.com/ssanj/scala-deps-zatp) Zat plugin to use this template. If you don't want to setup `scala-deps` or just want to specify your dependencies manually use the [basic-scala3](https://github.com/ssanj/basic-scala3-zat/) Zat template instead.

# Usage

You can process this template with Zat with the following:

```
zat process-remote --repository-url https://github.com/ssanj/scala-2-multiple-test-frameworks-zat --target-dir <YOUR_TARGET_DIRECTORY>
```

## Variables

|Variable| Description|
|-|-|
|`project`| The name of the example main and test file |
|`sbt_version`| The SBT version. Defaults to the latest stable version, which can be overridden |
|`scala_3_version`| Scala 3 version. Defaults to the latest stable version, which can be overridden |
|`munit_version`| MUnit version. Defaults to the latest stable version, which can be overridden |
|`scalatest_version`| MUnit version. Defaults to the latest stable version, which can be overridden |
