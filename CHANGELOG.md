# Yii Injector Change Log

## 1.0.5 under development

- Enh #56: Declare return value in `Injector::make()` and improve psalm annotations (vjik)

## 1.0.4 March 10, 2021

- Enh #46: Support PSR Container v1.1 and v2.0 (roxblnfk)

## 1.0.3 November 05, 2020

- Bug #27: Fix PHP 8 compatibility when passing arguments by reference (roxblnfk)
- Bug #28: Fix injecting referenced arguments that were unset, internal refactoring (roxblnfk)

## 1.0.2 August 28, 2020

- Enh #17: Support PHP 8 Union Types (roxblnfk)
- Bug #19: Fix PHP 8 compatibility in ArgumentException (roxblnfk)
- Bug #19: Remove unneeded passing PHP 8 internal classes as trailing arguments (roxblnfk)

## 1.0.1 May 17, 2020

- Enh #15: Support PHP 8 (samdark)

## 1.0.0 May 03, 2020

- Initial release.
