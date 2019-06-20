# interlok-install-builder
The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies. To be honest gradle is much easier to understand; and is our preferred build tool. Maven has its issues.

## Usage

* Update depedencies in `pom.xml`
    * Note that maven has trouble with the jetty-all artefact; so it is manually excluded, and re-injected later on. This can cause problems if you do not cross-reference the version that is actually in the POM file with the version in your dependencies.
    * If you are the type of person that doesn't want to manage that yourself; then you shouldn't be using maven, since both the `ant+ivy` and `gradle` branches _just work_.
* Execute maven package

```
./mvnw package
```

And after that you will have a interlok installation in target/install/interlok-install-builder. If you want to override the installation directory then `./mvnw -DinterlokInstallDirectory=/path/to/my/location package`

