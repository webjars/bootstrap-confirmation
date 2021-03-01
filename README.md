# Bootstrap Confirmation WebJar (bootstrap-confirmation)

[Bootstrap Confirmation](https://bootstrap-confirmation.js.org/) is a simple [Bootstrap](https://getbootstrap.com/) box to confirm a task. This [WebJar](https://webjars.org) includes the corresponding JavaScript and CSS files. Bootstrap Confirmation is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

WebJars are usually built using a plain Maven POM. This WebJar uses the
[Apache Maven AntRun Plugin](https://maven.apache.org/plugins/maven-antrun-plugin/) to download the Bootstrap Confirmation files from
GitHub and puts them into the Java archive.

## Usage

Just include this WebJar into your project. For Maven, you can use the following snippet:

```xml
<dependency>
    <groupId>org.webjars</groupId>
    <artifactId>bootstrap-confirmation</artifactId>
    <version>2.3.1</version>
</dependency>
```

And here is a Gradle snippet for you:

```groovy
implementation 'org.webjars:bootstrap-confirmation:2.3.1'
```

## Building

Just call

    mvn clean install

and the Jar is built. You can check the output in the target folder. Please make sure that all
required files are included and have proper content.

## Contributing

I highly welcome your updates and improvements. Please open a pull request if you want to contribute
to the Bootstrap Confirmation WebJar. Thanks in advance!
