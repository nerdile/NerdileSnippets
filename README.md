# NerdileSnippets

This repo hosts a bunch of tiny helper libraries.

## Goals for snippets libraries
 * Broad reusability: To make sure each library can be trivially reused,
   they should impose as few restrictions as possible on consumers.  For example,
   build against the lowest practicable version of .NET Standard, do one thing
   really well, and bring in the minimal number of external dependencies.
 * Independent: Libraries should be in subrepos so that they
   can be versioned and built separately.


