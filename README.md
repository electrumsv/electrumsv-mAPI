ElectrumSV-mAPI
================

    Licence: The Open BSV License
    Maintainers: Roger Taylor, AustEcon
    Project Lead: Roger Taylor
    Language: None.
    Homepage: https://electrumsv.io/


Overview
========

This repository has one single purpose: To compile unofficial binaries of 
the Bitcoin SV merchant api (mAPI) reference implementation for Linux, MacOS and Windows. These are used in the 
[ElectrumSV SDK](https://pypi.org/project/electrumsv-sdk) project which aims
to provide a first-class RegTest developer experience for running a local
(or cloud / pipelines-based) node and mAPI instance as well as other relevant
services that many bitcoin applications depend on.

These binaries will never be supported for mainnet usage. They are packaged so that they can be extracted and
run in place, with all necessary setup and configuration done on behalf of the user by the ElectrumSV SDK.
