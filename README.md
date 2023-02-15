[![Maven Central](https://maven-badges.herokuapp.com/maven-central/edu.hm.hafner/codingstyle-pom/badge.svg)](https://maven-badges.herokuapp.com/maven-central/edu.hm.hafner/codingstyle-pom)
[![GitHub Actions](https://github.com/uhafner/codingstyle-pom/workflows/GitHub%20CI/badge.svg?branch=master)](https://github.com/uhafner/codingstyle-pom/actions)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/license/MIT)

Each Java project should follow a given coding style. I.e., all contributions to the source code should use the same 
formatting rules, design principles, code patterns, idioms, etc. I published such a coding style in my 
[GitHub project 'codingstyle'](https://github.com/uhafner/codingstyle). I am using this coding style in my lectures about 
software development at Munich University of Applied Sciences and in all of my open source projects.  

If you want to use this coding style as well you can use this [Maven POM](pom.xml) as parent of you own POM. Then you
get the configuration of the following tools for free:
- [Java Compiler](https://openjdk.java.net/groups/compiler/)
- [JavaDoc Tool](https://www.oracle.com/technetwork/java/javase/documentation/javadoc-137458.html)
- [Checkstyle](https://checkstyle.org)
- [PMD](https://pmd.github.io/)
- [SpotBugs](https://spotbugs.github.io)
- [Find Security Bugs](https://find-sec-bugs.github.io)
- [Error Prone](https://errorprone.info)
- [NullAway](https://github.com/uber/NullAway)
- [JaCoCo Code Coverage](https://www.jacoco.org/jacoco/index.html)
- [ArchUnit Architecture Tests](https://www.archunit.org) 
- [RevAPI API Checker](https://revapi.org)
- [PIT Mutation Testing](https://pitest.org)


