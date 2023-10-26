PHP libraries and tools by Rubén Rubio 
 
PHP possesses a rich ecosystem, with plenty of libraries and tools. Here is a list of them that I consider interesting, beyond any framework.

At the end, I included some useful checks for Composer and Symfony to execute on a CI pipeline.

# Libraries
- brick/math: Arbitrary-precision arithmetic library for PHP
- openspout/openspout: Read and write spreadsheet files (CSV, XLSX and ODS), in a fast and  scalable way
- thecodingmachine/safe: All PHP functions, rewritten to throw exceptions instead of returning false
- azjezz/psl: PHP Standard Library - a modern, consistent, centralized, well-typed, non-blocking set of APIs for PHP programmers
- particle/validator: Particle\Validator is a validation library with an extremely clean API which makes validation fun!
- league/tactician: A small, flexible command bus.
- league/flysystem: Abstraction for local and remote filesystems
- golem-ai/messenger-kit: This command simulates consumer failures and prints a timeline of the events. It lets you check whether your retry strategy configuration does what you expect it to.
- swarrot/swarrot: A lib to consume message from any Broker
- ronanguilloux/isocodes: PHP library - Validators for standards from ISO, International Finance, Public Administrations, GS1, Manufacturing Industry, Phone numbers & Zipcodes for many countries
- php-units-of-measure/php-units-of-measure: A library for handling physical quantities and the units of measure in which they're represented.
- rawr/t-regx: PHP regular expression brought up to modern standards.
- mpratt/embera: A Oembed consumer library, that gives you information about urls. It helps you replace urls to youtube or vimeo for example, with their html embed code. It has advanced features like offline support, responsive embeds and caching support.
- spatie/geocoder: Geocode addresses to coordinates
- php-soap/wsdl-reader: A pure PHP wsdl metadata provider
- phpro/soap-client: A general purpose SOAP client for PHP
- eventsauce/backoff: Sophisticated back-off strategies for retrying operations.
- pontedilana/php-weasyprint: PHP library allowing PDF generation or snapshot from an URL or an HTML page. Wrapper for Kozea/WeasyPrint

# Parsers:
- cuyz/valinor: PHP library that helps to map any input into a strongly-typed value object structure.
- cerbero/json-parser: 🧩 Zero-dependencies lazy parser to read JSON of any dimension and from any source in a memory-efficient way.
- yzen.dev/plain-to-class: Class-transformer to transform your data into a typed object
- JanePHP: 🌱 Jane is a set of libraries to generate Models & API Clients based on JSON 
Schema / OpenAPI specs

# Time:
- brick/date-time: Date and time library for PHP
- fredbradley/easytime: A small class based package to help with human readable calculations of time
- flack/ranger: Formatter for date and time ranges with i18n support

# Money:
- brick/money: A money and currency library for PHP
- moneyphp: PHP implementation of Fowler's Money pattern

# Search:
- schranz-search/seal: Search abstraction over different search engines written in PHP. Currently implemented Elasticsearch, Opensearch, Algolia, Meilisearch, RediSearch, Solr, Typesense.
- loupe/loupe: A full text search engine with tokenization, stemming, typo tolerance, filters and geo support based on only PHP and SQLite.
Test libraries
- Infection: PHP Mutation Testing library. Plugins:
- roave/infection-static-analysis-plugin: Static analysis on top of mutation testing - prevents escaped mutants from being invalid according to static analysis
- bitexpert/captainhook-infection: Captain Hook Plugin to run InfectionPHP only against the changed files of a commit
- lulco/populator: Allows populate fake data to your database.
- league/openapi-psr7-validator: It validates PSR-7 messages (HTTP request/response) against OpenAPI specifications.
- PHPUnit: PHPUnit is a programmer-oriented testing framework for PHP. It is an instance of the xUnit architecture for unit testing frameworks. Extensions/tools:
- brianium/paratest: Parallel testing for PHPUnit
- johnkary/phpunit-speedtrap: Reports on slow-running tests in your PHPUnit test suite.
- robiningelbrecht/phpunit-pretty-print: Better PHPUnit CLI output with Collision
- roave/no-leaks: PHPUnit Plugin for detecting Memory Leaks in code and tests

# Tools
- Deptrac: Keep your architecture clean.
- PHP Architecture Tester: Easy to use architectural testing tool for PHP
- PHPArkitect: Put your architectural rules under test!
- PHP Insights: Instant PHP quality checks from your console
- GrumPHP: A PHP code-quality tool.
- churn-php: Discover files in need of refactoring.
- scheb/tombstone: Dead code detection with tombstones for PHP
- PHP Magic Number Detector: a tool that aims to help you to detect magic numbers in your PHP code.
- shipmonk/name-collision-detector: Fast & simple tool to find classname collisions within your project.
- Robo: Modern Task Runner for PHP
- CaptainHook: Very flexible git hook manager for php developers
- Whisky: Whisky is the simplest, framework agnostic, CLI tool for managing and enforcing a php project's git hooks across an entire team.
- PHP_Depend: PHP_Depend is an adaptation of the established Java development tool JDepend. This tool shows you the quality of your design in terms of extensibility, reusability and maintainability.
- PHPMD - PHP Mess Detector: PHPMD is a spin-off project of PHP Depend and aims to be a PHP equivalent of the well known Java tool PMD. PHPMD can be seen as an user friendly frontend application for the raw metrics stream measured by PHP Depend.
- vcian/php-db-auditor: Audit your mysql database -Database DB Auditor provide leverage to audit your MySql database standards and also provide options to add constraints in table
- Psalm: A static analysis tool for finding errors in PHP applications. Plugins:
- boesing/psalm-plugin-stringf: Psalm plugin to provide more details for sprintf, printf, sscanf and fscanf functions.
- hectorj/safe-php-psalm-plugin: vimeo/psalm plugin for thecodingmachine/safe.
- marartner/psalm-no-empty: Psalm plugin to detect usage of empty().
- marartner/psalm-strict-equality: Psalm plugin to enforce strict equality.
- psalm/plugin-phpunit: A PHPUnit plugin for Psalm.
- psalm/plugin-symfony: Psalm Plugin for Symfony.
- weirdan/doctrine-psalm-plugin: Stubs to let Psalm understand Doctrine better.
- ghostwriter/psalm-plugin: Provides an ALL-IN-ONE plugin for Psalm
- PHPStan: PHP Static Analysis Tool - discover bugs in your code without running it!  

# Plugins:
- ergebnis/phpstan-rules: Provides additional rules for phpstan/phpstan.
- spaze/phpstan-disallowed-calls: PHPStan rules to detect disallowed calls and constant & namespace usages
- roave/no-floaters: static analysis rules to prevent IEEE-754 floating point errors.
- dave-liddament/php-language-extensions: Attributes to define PHP language extensions (to be enforced by static analysis)
- sidz/phpstan-rules: Additional rules for phpstan/phpstan.
- staabm/phpstan-baseline-analysis: Analyzes PHPStan baseline files and creates aggregated error trend-reports

# More extensions
## Performance frameworks
- Hyperf: 🚀 A coroutine framework that focuses on hyperspeed and flexibility. Building microservice or middleware with ease.
- Flow PHP: Flow PHP - strongly typed data processing framework
- PHPTokio: Use any async Rust library from PHP!
## Composer tools
- ComposerRequireChecker: A CLI tool to check whether a specific composer package uses imported symbols that aren't part of its direct composer dependencies
- composer-unused: Show unused composer dependencies by scanning your code
- composer-normalize: Provides a composer plugin for normalizing composer.json.
## Security
- roave/security-advisories: Security advisories as a simple composer exclusion list, updated daily 
- roave/backward-compatibility-check: Tool to compare two revisions of a class API to check for BC breaks
- Local PHP Security Checker: PHP security vulnerabilities checker
## CI checks
### Lints (for Symfony):
 - PHP: find src public bin -name "*.php" -print0 | xargs -0 -n1 php -l
 - Container: bin/console lint:container
 - YAML: bin/console lint:yaml config src
 - Twig: bin/console lint:twig src
### Symfony + Doctrine:
 - Deprecations: bin/console debug:container --deprecations (even if it fails, it returns 0 as exit code)
 - Doctrine schema: bin/console doctrine:schema:validate --skip-sync
### Composer
 - Audit (The audit command checks for security vulnerability advisories for installed packages.): composer audit
 - Outdated (The outdated command shows a list of installed packages that have updates available, including their current and latest versions): composer outdated --minor-only --direct --strict
 - Validate (It will check if your composer.json is valid): composer validate --strict

## Sources
This list is inspired (and based to some extent) by:

https://twitter.com/ramsey/status/1396592906102722561
https://twitter.com/lulco/status/1397813303037079553
https://twitter.com/ArkadiuszKondas/status/1338485275002068993
https://twitter.com/ArkadiuszKondas/status/1596232242627366912
Aggressive PHP Quality Assurance in 2019 | https://youtu.be/8rdTSYljts4

#Source:
https://dev.to/rubenrubiob/php-libraries-and-tools-4bk3
