# 🛠 yumemi-inc/phpcs-config
Customised configuration for PHPCodeSniffer.

> **Warning**  
> This is not an official product of YUMEMI Inc.

## 📦 Installation
```shell
composer require --dev yumemi-inc/phpcs-config
```

Write your `phpcs.xml` to enable the configuration:

```xml
<?xml version="1.0"?>
<ruleset name="Custom">
    <description>Custom coding standard.</description>
    <rule ref="vendor/yumemi-inc/phpcs-config/phpcs.xml" scope="path" />
</ruleset>
```

## ✅ Versioning
Version x.y.z of this package will work on PHP x.y (e.g. 8.1.x works on PHP 8.1).
On the ruleset changes, the z number will be increased.

| Package Version | PHP Version | Maintained? |
|-----------------|-------------|-------------|
| 8.2.x           | ^8.2        | Yes         |
| 8.1.x           | ^8.1        | Yes         |

## 🙌 Contributing
Contributes of adding new rules or resolving conflicts with our other packages (
[php-cs-fixer-config](https://github.com/yumemi-inc/php-cs-fixer-config),
[php-intellij-profiles](https://github.com/yumemi-inc/php-intellij-profiles)
) are welcome.
Other contributions may not be accepted such as changing the existing rules or removing them.
