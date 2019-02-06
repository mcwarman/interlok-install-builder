# interlok-install-builder
The suggested name was `urban-eureka`

Project assits in creating local installation of Interlok with optional dependencies.

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
