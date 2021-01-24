Wang Hai
============

----

> <michaelwang.sh@outlook.com> • +86 15201928456

>  Senior full-stack developer & team leader. Professional with *OOP*, *Design Pattern*, *Java* and *Spring*.

----

Skill Sets
----------
**Professional**
:   OOP, Design Patter, Java, Spring(IoC, AOP)

**Experienced**
:   CI/CD, TDD, Scrum, Vue, Rest API, Spring Batch

**Worked With**
:   TypeScript, AWS, K8S, Oracle Database, Docker, Shell Script, Spring Security, Ngix, etc.

**Know How**
:   Kotlin, Prometheus, Grafana, AppDynamics, etc.


Experience in Works Applications Co., Ltd.
----------

**AC Employee Service**

:   **Department Manager, AC Department**, 4 months

    **Group Manager, Expense Shanghai Group**, 21 months

    *AC Employee Service* is a large, lagend, web-based platform providing employee oriented features for accouting related products.
    Different teams in differnt locations are working on the same code base for this product.
    Expense Shanghai Group (which becomes AC Department last year) works mainly in Expense application as well as some common features for the platform.

    The team consists of 8-10 members including a product owner, an UIUX designer, a tester and 5-7 developers.
    With the effort of the team, we managed to

    * saperate the team's code base from the large one makes it easir to develop, build and cooperate with other teams.
    * introduced a good way to migrate from old technology to new ones gradually. This includes mirgrate the renderring from back-end based string concatnation to front-end renderring technology (*Vue* + *TypeScript*). It also includes introducing *Spring Framework* working tegother with the raw servlet code without breaking the legend features.
    * implement rich features including excel-like grid with rich column type specific features, integrating with multiple external services and refactor the entire mobile web application form to provide rich and consistent user experience with PC pages.

    As senior and team leader, I also

    * created a *Scrum* based team making the in-team cooperation with high efficiency.
    * established a good enough *CI/CD* flow used by both devlopers and non-developers. The CI/CD flow makes it easy to test, integrate and deploy testing environments. Changes can be build and deployed less than 10 minutes automatically.
    * works mainly on reviewing code, solving critical issues and making design decisions. I designed sub-systems including a OCR integration system, a front-end application state management system, batch-based data importing/exporting system with *Spring Batch*, etc.
    * building helpful libraries assiting in feature development, including rest client framework, OpenAPI DSL and business specific abstract super classes.

**SLI Provider**

:   **Group Manager, HR TechLead Group**, 6 months

    *SLI Provider* is a tool to generate SLI (Service Level Indicator) by aggregating gateway logs which contains status and latency information.
    
**SRE**

:   **Group Manager, MinEnv Group**, 6 months

    **Member, SRE Shanghai Department**, 12 months

    In SRE, I participated and lead in different topics including *Environment Cost Reduction*, *AWS Key Provider*, *EC2 Scaling Scheduler*, etc:

    * *Environment Cost Reduction* is a project to reduce the AWS environment cost by reducing replica of middlewares and limiting resources usage of each MSA through K8S.
    * *AWS Key Provider* is a project to build a system make the usage of AWS keys in a more secured way, especially in on-promise environment.
    * *EC2 Scaling Scheduler* is a project to build a scheduling system used to scale EC2 instances by schedule.

**Quality & Flow Improvement**

:   **Member, Quality Engineering Department**, 3 months

    In *Quality & Flow Improvement* project, I was mainly working on topics related to static code analysis via SonarQube & FindBugs(SpotBugs) and integration in CI flow.


My Side Projects
--------------------

Easy Rest Clint (Internal)
:   Use reflection to generate Spring RestTemplate based rest client.

    * The first version is based on class extention and command pattern. It is already used in production well.
    * The second version is based on proxy and spring bean like `JPARepository`. It is still under development.

OpenAPI DSL (Internal)
:   It is a Kotlin-based DSL for OpenAPI in order to provide better way to write OpenAPI definition and code generation.
    I started this project when thinking of a good way of interface-first developing style. 
    This projects contains 2 sub-modules:

    * DSL: the basic functions of DSL is alreadys implemented.
    * Code Generation: this is still in design phase. It will include build tool integration which is still in desgin phase.

[HiMock][ref]
:   It is a practice project of a test mocking framework.
    Basic mocking features were implemented.
    This project is developed in a TDD way which makes it contains rich number of unit tests by natural.

[ref]: https://github.com/MichaelHai/himock

----

Education
---------

2019-2013
:   **Bachelor of Software Engineering**; Fudan University

2013-2016
:   **Master of Computer Software**; Fudan University