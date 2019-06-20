# interlok-install-builder
The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies. This branch is kept up to date by `dependabot`; and is the preferred way for you to build your installation which is why it's the default branch...

## Usage

1. Update depedencies in `build.gradle`
2. Create `gradle.properties` containing `interlokInstallDirectory` (default: `./build/install/interlok-install-builder`)

```
interlokInstallDirectory=C:/Adaptris/Interlok
```

3. Execute gradle build:

```
.\gradlew.bat cleanInstall install
```
