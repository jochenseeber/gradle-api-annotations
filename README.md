# Gradle API Annotations

This project contains [external annotations](https://wiki.eclipse.org/JDT_Core/Null_Analysis/External_Annotations) for
[Gradle API](https://gradle.org/) version 3.1.

These annotations allow Eclipse to perform null analysis.

## Usage

To build the annotations JAR, run

```bash
gradle build
```

This will create the file `gradle-api-annotations-3.1-r.1.jar`. Attach this file to the
Gradle API library entry in your build path to have Eclipse use the annotations.