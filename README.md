# Protos for CNDB client testing

This repository contains the protos for cloud native database client test framework.
These protos will serve as an interface between test driver and client proxies.
To use these protos, cloud client should implement proxy code to convert these
protos into client API calls, then the test driver can generate messages through
these protos to test the behavior of clients. All clients of different programming
languages share the same set of protos.

These protos are ONLY used in CNDB client testing, not part of the public client API.

