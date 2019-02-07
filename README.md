# interlok-install-builder
The suggested name was `urban-eureka`

Project assists in creating local installation of Interlok with optional dependencies. You are expected to have ant installed.

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
