# Changelog
## 2.0.0
- Package renamed to `gizmocraft/zendframework1-validate-sitemap` (fork of `diablomedia/zendframework1-validate-sitemap`).
- Requires PHP >= 8.5; CI runs on PHP 8.5 and 8.6.
- Depends on `gizmocraft/zendframework1-validate` ^2.0.0 and `gizmocraft/zendframework1-uri` ^2.0.0.
- Dev dependencies upgraded to PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95 and GrumPHP 2.27; `composer-require-checker` dropped.
- Tests migrated to PHPUnit 13 (`#[Group]` attributes instead of `@group` annotations).
- No public signature changes and no PHP 8.5/8.6 code fixes were needed.
