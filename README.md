# Compat.Configuration.Install

Forked from https://github.com/flamencist/Core.System.Configuration.Install.

### Builds

[![Windows](https://github.com/cklutz/Compat.Configuration.Install/workflows/Windows/badge.svg)](https://github.com/cklutz/Compat.Configuration.Install/actions?query=workflow%3AWindows)

### Notable Changes

This fork changes the following:

- Renamed to Compat.Configuration.Install
- Remove dependency on Newtonsoft.Json
    - Use NetDataContracterSerializer (from [Compat.Runtime.Serialization](https://github.com/cklutz/Compat.Runtime.Serialization)) instead
- Change TargetFramework to `net6.0-windows`
    - Update dependencies to .NET 6.0

### License

This software is distributed under the terms of the MIT License (MIT).

### Authors

Contributions and bugs reports are welcome.
