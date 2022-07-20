# GitHub Action Readability Demo

Demo files for a GitHub Action that checks docs for readability. Derived 
from content at [mongodb/docs-realm](https://github.com/mongodb/docs-realm).

These files contain rST with some customizations for use with the 
MongoDB docs platform, [Snooty](https://github.com/mongodb/snooty).

This demo is intended to show extracting a subset of text from the rST, 
scoring that text for readability, and reporting that score on a MongoDB 
docs PR. We use only a subset of the text, throwing out elements that 
would skew the readability score, such as code examples and markup.

It uses a forked version of docdoctor available at
[dacharyc/docdoctor](https://github.com/dacharyc/docdoctor) in the 
[readabilty branch](https://github.com/dacharyc/docdoctor/tree/readability).
