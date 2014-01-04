## 0.5.0 (unreleased)

Features:

  - Added Client Credentials Grant

## 0.4.0

Features:

  - Added support for refresh tokens

## 0.3.2

Bugfixes:

  - Fixed a bug where MemcacheTokenStore saved objects instead of dictionaries.

## 0.3.1

Bugfixes:

  - Fixed a bug causing a supplied redirect uri being ignored if it is not the first entry in the list of a client object.

## 0.3.0

Features:

  - Headers of a response are returned as a dictionary
  - Status code of a response is an integer
  - Streamlining the integration of storage classes and site adapters by requiring them to raise specified errors

## 0.2.0

Features:

  - Support for scopes
  - Local token and client stores
  - Memcache token store
  - Support for Python 2.6, 3.2 and 3.3

## 0.1.0

Features:

  - Working implementation of Authorization Code Grant
  - Working implementation of Implicit Grant
  - Working implementation of Resource Owner Password Credentials Grant