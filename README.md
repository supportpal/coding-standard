# coding-standard

SupportPal PHPCS coding standard.

## Installation

`composer require supportpal/coding-standard --dev`

## Usage

### Default ruleset

`phpcs standard=../../vendor/supportpal/coding-standard .`

### Custom ruleset

Create a `phpcs.xml` file:

```xml
<?xml version="1.0"?>
<ruleset name="CustomSupportPal">
    <description>Custom PHPCS config based on the SupportPal coding standard.</description>

    <rule ref="vendor/supportpal/coding-standard" />
</ruleset>
```