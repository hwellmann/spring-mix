spring-mix 
==========

## About

spring-mix is a self-contained subset of annotations and utilities
from various Spring Framework components, taken from 3.1.0.RELEASE.

The only external dependency is slf4-api, which replaces
commons-logging. Except for this change, the sources are unmodified
copies of the original Spring Framework sources.

## Status

Experimental. This is a private effort open for community
contributions. It is not in any way related to SpringSource or VMware.

## Purpose

This is the basis for an attempt to factor out substantial parts of
Spring Data, free them from tight coupling with Spring Core and make
them work with other Dependency Injection Containers. The primary
target is CDI with or without a full Java EE container.

## Naming

During the proof-of-concept phase and as long as there is some
potential of seeing the results of these activities being reintegrated
into the official SpringSource projects, the original package names of
org.springframework.* will be maintained.

Should this experiment ever leave the incubation status, then it would
be time to change package names.

