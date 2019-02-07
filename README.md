# interlok-install-builder
The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies.

## Usage

1. Update depedencies in `pom.xml`

2. Execute maven package

```
./mvnw package
```

And after that you will have a interlok installation in target/install/interlok-install-builder. If you want to override the installation directory then `./mvnw -DinterlokInstallDirectory=/path/to/my/location package`

