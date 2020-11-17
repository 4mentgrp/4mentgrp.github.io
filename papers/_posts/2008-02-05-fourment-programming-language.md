---
layout: papers
title: A comparison of common programming languages used in bioinformatics
authors: ['Fourment M', 'Gillings MR']
year: 2008
journal: BMC Bioinformatics
journalref: 9:82
doi: 10.1186/1471-2105-9-82
---

# Abstract

**Background.** The performance of different programming languages has previously been benchmarked using abstract mathematical algorithms, but not using standard bioinformatics algorithms. We compared the memory usage and speed of execution for three standard bioinformatics methods, implemented in programs using one of six different programming languages. Programs for the Sellers algorithm, the Neighbor-Joining tree construction algorithm and an algorithm for parsing BLAST file outputs were implemented in C, C++, C#, Java, Perl and Python.

**Results.** Implementations in C and C++ were fastest and used the least memory. Programs in these languages generally contained more lines of code. Java and C# appeared to be a compromise between the flexibility of Perl and Python and the fast performance of C and C++. The relative performance of the tested languages did not change from Windows to Linux and no clear evidence of a faster operating system was found.
Source code and additional information are available from http://www.bioinformatics.org/benchmark/

**Conclusion.** This benchmark provides a comparison of six commonly used programming languages under two different operating systems. The overall comparison shows that a developer should choose an appropriate language carefully, taking into account the performance expected and the library availability for each language.