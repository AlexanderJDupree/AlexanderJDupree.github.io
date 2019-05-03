---
title: "Big Int"
---

Built With: **C**, **Catch2**, **Premake5**, **Travis-CI**
Skills Learned: **CPU Numeric Representation**, **Inline Assembly**, **Arithmetic Algorithms**

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/52406353f564468e9e301645f02127a3)](https://www.codacy.com/app/AlexanderJDupree/File_Reader?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=AlexanderJDupree/File_Reader&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.com/AlexanderJDupree/BigInt.svg?branch=master)](https://travis-ci.com/AlexanderJDupree/BigInt.svg?branch=master)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/AlexanderJDupree/BigInt/blob/master/LICENSE)

**BigInt** is a numeric type that can represent integers with arbitrary precision. This allows the user to safely store and perform arithmetic on numbers greater than the CPU architecture limit without risk of overflow. At least, this will be the case when the project is fully implemented. 

Project Goals
1. First and foremost, accuracy. 
2. Optimize until BigInt is blazing fast.
3. Support for x86 and x64 architechtures. 
4. Port to C++ to make use of operator overloads.

Feature Roadmap
1. ~~Implement reserve, value, and string parsing constructor~~ PR #1
2. ~~Implement addition operations~~ PR #4
3. ~~Implement subtraction operations~~ PR #5
4. Implement multiplication operations
5. Implement division operations 
6. Implement exponention operations
7. Release version 1.0.0!

Check out the full repsitory [here](https://github.com/AlexanderJDupree/BigInt)

