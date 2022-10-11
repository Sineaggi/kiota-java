# To-do

- [ ] checkstyles
- [ ] spotbugs
- [ ] javadoc
- [ ] cobertura

## Using the Text Serialization implementations

1. In `build.gradle` in the `repositories` section:

    ```Groovy
    maven { url 'https://oss.sonatype.org/content/repositories/snapshots' }  
    ```

1. In `build.gradle` in the `dependencies` section:

    ```Groovy
    implementation 'com.microsoft.kiota:microsoft-kiota-serialization-text:0.0.4-SNAPSHOT'
    ```
