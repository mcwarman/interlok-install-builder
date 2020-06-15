# interlok-install-builder

The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies. This branch is monitored by [dependabot](https://dependabot.com); and is the preferred way for you to build your installation which is why it's the default branch...

## Usage

1. Update dependencies in `build.gradle`
2. Create `gradle.properties` containing `interlokInstallDirectory` (default: `./build/distribution`)

    ```properties
    interlokInstallDirectory=C:/Adaptris/Interlok
    ```

3. Execute gradle build:

    ```shell
    ./gradlew cleanInstall install
    ```
