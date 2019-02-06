# interlok-install-builder
The suggested name was `urban-eureka`

## Usage

1. Create `gradle.properties` file containing `interlokInstallDirectory` (default: `./build/install/interlok-install-builder`)

```
interlokInstallDirectory=C:/Adaptris/Interlok
```

2. Execute gradle build:

```
gradlew cleanInstall install
```