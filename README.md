# Test Demo [![Build Status](https://travis-ci.org/tony19/mocha-test-demo.svg?branch=master)](https://travis-ci.org/tony19/mocha-test-demo)

> Stack to Demonstrates Mocha, Chai, Sinon, and Istanbul

### Quick start

Run these commands:

    yarn
    yarn test-cov

    or

    npm test
    npm run test-cov

Observe this output:

```shell
  Person
    ✓ should have field name and age
    ✓ should have a method introduce, introduce person with name and age
    Student
      ✓ should have field name, age and class number
      #introduce
        ✓ should overwrite Person introduce, introduce with name, age and class number
        ✓ should print Leader role, given student is leader
    Teacher
      ✓ should have field name, age and class number
      #introduce
        ✓ should overwrite Person introduce, introduce with name, age and class number, given teacher have class
        ✓ should overwrite Person introduce, introduce with name, age and class number, given teacher have no class

  Class
    #assignLeader
    #appendMemeber


  16 passing (50ms)

=============================================================================
Writing coverage object [/Users/jxzhong/work/twschool/OOCL-Train/nodejs/babel-mocha-stack/node-babel-mocha-stack/coverage/coverage.json]
Writing coverage reports at [/Users/jxzhong/work/twschool/OOCL-Train/nodejs/babel-mocha-stack/node-babel-mocha-stack/coverage]
=============================================================================

=============================== Coverage summary ===============================
Statements   : 94.29% ( 66/70 )
Branches     : 83.87% ( 26/31 )
Functions    : 84.62% ( 22/26 )
Lines        : 95.52% ( 64/67 )
================================================================================
✨  Done in 2.08s.
```


