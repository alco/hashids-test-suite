Hashids Test Suite
==================

This repository contains test data for [Hashids][1]. Any of the ports may use it to ensure
conformance with the original implementation in JavaScript.

Files in the `base` directory contain sample identifiers and their encoding. Those tests should pass
for every conformant implementation.

Files in the `large` directory contain tests for implementation that support arbitrarily large
integers.

  [1]: http://www.hashids.org/
