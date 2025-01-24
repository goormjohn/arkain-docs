---
hidden: true
noIndex: true
---

# Spring-Maven

This is the build/run options settings for a Spring-Maven project.

The `project.build` described below refers to the `<project> <build></build> </project>` in the `pom.xml` file.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FuPutQHBPOpq5ttZ5CV8O%252Fimage.png%3Falt%3Dmedia%26token%3Da3753ed5-7bf2-4b55-afc4-fd3fd8a6a914&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=d102930d&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. pom.xml path - The path to the `pom.xml` file. The default setting is `pom.xml` in the top-level path of the project.
   * Automatically set `pom.xml` path when container runs - If checked, automatically locate and set the pom.xml location when accessing the container. The top-level `pom.xml` is prioritised.
   * The lower property values will be set automatically by changing the `pom.xml` path, saving the `pom.xml` file, or referencing the file when the project is run. At this time, the `project.properties` set in the `pom.xml` are also read and applied.
2. Deploy path - This is the path that `Tomcat` looks at when running the project. The \[Project]>\[Toggle Auto Build] feature will also compile and copy files based on this path. The path is set to `project.build.directory/project.build.finalName` in the `pom.xml`.
   * Command variable: `${java.set.deploy.path}`
3. Source path - set to `project.build.sourceDirectory` in the `pom.xml`.
   * Command variable: `${java.set.src_path}`
4. Build path - set to `project.build.outputDirectory` in the `pom.xml`.
   * Command variable: `${java.set.build.path}`
5. Log file path - Set the path to the log file.

The set in of the `pom.xml` are also available.

* Reads the `profile.properties` where `project.profiles.profile.activation.activeByDefault` is set to true.
* If the variable names are the same as those in the existing `project.properties`, the values set in `project.profiles` will take precedence.
