This fork is used for performance testing.

It's a fork of the [4.0.0](https://github.com/apache/kafka/tree/4.0.0) tag.

Our changes are in the `build.gradle` file.

To test how [hone-maven-plugin](https://github.com/objectionary/hone-maven-plugin) works, run:

```
./gradlew --console=plain --no-parallel clean test
```
