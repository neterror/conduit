# 3.1.0

# 3.0.11

# 3.0.10

# 3.0.9

# 3.0.8

# 3.0.7
uptick version for multi release

# 3.0.5
Stable Conduit Release

# 2.0.0-b9
Fixed a bug with the conduit build command. We had left in dep overrides 
which should only be used for conduit internal dev.

# 2.0.0-b8
3rd attempt at first release.

# Conduit

# 2.0.0-b1

- Tooling works with conduit

# 2.0.0-a3
- broadened the version no. so works with any 2.0 version of conduit.
- Updated pubspec to pull conduit_test from pub.dev now that it is published.

## 2.0.0-a2

- Version bumps

## 2.0.0-a1

- Alpha release for Conduit NNBD included

# Conduit

## 1.0.1

- Fixes analysis warnings for Dart 2.1.1

## 1.0.0+1

- Bumps some dependency constraints to be more permissive

## 1.0.0

- Initial version from `package:conduit`.
- Adds `TestHarness` base class for test harnesses.
- Adds `TestHarnessORMMixin` for testing ORM applications.
- Adds `TestHarnessAuthMixin` for testing OAuth2 applications.
- Renames `TestClient` to `Agent` and adds methods for executing requests without constructing a `TestRequest`.
- Adds default parameters to `Agent` for its requests.
