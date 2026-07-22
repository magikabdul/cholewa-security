# cholewa-security

[![CI](https://github.com/magikabdul/cholewa-security/actions/workflows/CI.yml/badge.svg)](https://github.com/magikabdul/cholewa-security/actions/workflows/CI.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=magikabdul_cholewa-security&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=magikabdul_cholewa-security)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=magikabdul_cholewa-security&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=magikabdul_cholewa-security)

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=magikabdul_cholewa-security&metric=coverage)](https://sonarcloud.io/summary/new_code?id=magikabdul_cholewa-security)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=magikabdul_cholewa-security&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=magikabdul_cholewa-security)
![Java](https://img.shields.io/badge/java-21-yellow?style=plastic)
![SpringBoot](https://img.shields.io/badge/SpringBoot-4.1.0-blue?style=plastic)

![GitHub issues](https://img.shields.io/github/issues/magikabdul/cholewa-security?style=plastic)
![GitHub contributors](https://img.shields.io/github/contributors/magikabdul/cholewa-security?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/magikabdul/cholewa-security?style=plastic)

![GitHub release](https://img.shields.io/github/v/release/magikabdul/cholewa-security?style=plastic)
![GitHub release date](https://img.shields.io/github/release-date/magikabdul/cholewa-security?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/magikabdul/cholewa-security?style=plastic)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/magikabdul/cholewa-security?style=plastic)

Shared security/auth building blocks for reactive (WebFlux) Spring Boot services.
Kept as a foundation for future authentication/authorization in
[`api-gateway-service`](https://github.com/smart-home-automation-system/api-gateway-service);
it currently has **no consumers** and exposes no public API yet.

## Installation

The artifact is published to GitHub Packages:

```xml
<dependency>
    <groupId>cloud.cholewa</groupId>
    <artifactId>cholewa-security</artifactId>
    <version>1.0.0</version>
</dependency>
```

```xml
<repositories>
    <repository>
        <id>github-prv</id>
        <url>https://maven.pkg.github.com/magikabdul/*</url>
    </repository>
</repositories>
```

GitHub Packages requires authentication even for public artifacts — configure a
`github-prv` server with a token (`read:packages`) in your Maven `settings.xml`.
