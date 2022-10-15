# Dattas Module

## Overview

Dattas is an example module for keeping track of account names on-chain. It makes no effort to
create a name hierarchy, be a DNS replacement or provide reverse lookups. 

## Interface

### Dattas Functions

* `set_name` - Set the associated name of an account; a small deposit is reserved if not already taken.
* `clear_name` - Remove an account's associated name; the deposit is returned.
* `kill_name` - Forcibly remove the associated name; the deposit is lost.

License: Apache-2.0
