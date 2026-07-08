# Upgrade to Silverstripe CMS 6

This document outlines the necessary changes to upgrade this module to be compatible with Silverstripe CMS 6.

## New Requirements

### Silverstripe CMS 6
⚠️ **BREAKING CHANGE**: Support for Silverstripe CMS versions `^4.0` and `^5.0` has been removed. This module now requires `silverstripe/recipe-cms: ^6.0`.

### Dependency `sunnysideup/dashboard` Removed
🚨 **CRITICAL REVIEW REQUIRED / RISKY**: The dependency on `sunnysideup/dashboard` has been removed from `composer.json` because no compatible stable release for Silverstripe CMS 6 is available. This is a significant breaking change. You will need to manually find a replacement or an alternative solution for the functionality previously provided by this package.
