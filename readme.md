	$ composer require --dev stanislav-janu/phpstan
	$ vendor/bin/phpstan analyse dir -l 7
	
## phpstan.neon
```
includes:
	- vendor/phpstan/phpstan-nette/rules.neon
	- vendor/phpstan/phpstan-nette/extension.neon
	- vendor/phpstan/phpstan-strict-rules/rules.neon
	- vendor/phpstan/phpstan-deprecation-rules/rules.neon
	- vendor/thecodingmachine/phpstan-safe-rule/phpstan-safe-rule.neon
```