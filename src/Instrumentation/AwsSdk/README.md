[![Releases](https://img.shields.io/badge/releases-purple)](https://github.com/opentelemetry-php/contrib-auto-aws-sdk/releases)
[![Issues](https://img.shields.io/badge/issues-pink)](https://github.com/open-telemetry/opentelemetry-php/issues)
[![Source](https://img.shields.io/badge/source-contrib-green)](https://github.com/open-telemetry/opentelemetry-php-contrib/tree/main/src/Instrumentation/AwsSdk)
[![Mirror](https://img.shields.io/badge/mirror-opentelemetry--php--contrib-blue)](https://github.com/opentelemetry-php/contrib-auto-aws-sdk)
[![Latest Version](http://poser.pugx.org/open-telemetry/opentelemetry-auto-aws-sdk/v/unstable)](https://packagist.org/packages/open-telemetry/opentelemetry-auto-aws-sdk/)
[![Stable](http://poser.pugx.org/open-telemetry/opentelemetry-auto-aws-sdk/v/stable)](https://packagist.org/packages/open-telemetry/opentelemetry-auto-aws-sdk/)

This is a read-only subtree split of https://github.com/open-telemetry/opentelemetry-php-contrib.

# OpenTelemetry AWS SDK auto-instrumentation
Please read https://opentelemetry.io/docs/instrumentation/php/automatic/ for instructions on how to
install and configure the extension and SDK.

## Overview
Auto-instrumentation hooks are registered via composer.

* create spans automatically for each AWS SDK request that is sent

## Configuration

The extension can be disabled via [runtime configuration](https://opentelemetry.io/docs/instrumentation/php/sdk/#configuration):

```shell
OTEL_PHP_DISABLED_INSTRUMENTATIONS=aws-sdk
```
