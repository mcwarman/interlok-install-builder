# interlok-install-builder
The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies. You are expected to have ant installed.
This branch is not kept up to date with version changes; so your mileage may vary. It is useful as a learning tool since ant does no magic, so you have to do everything yourself.

## Usage

1. Update depedencies in `ivy\ivy-interlok.xml`

2. Create `build.properties` containing `interlokInstallDirectory=/path/to/my/install/directory` (default: `./build/install/interlok-install-builder`)

```
interlokInstallDirectory=C:/Adaptris/Interlok
```

3. Execute ant install

```
ant install
```
