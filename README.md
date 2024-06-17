# Martin's Course about Automated Program Repair

This repo contains the material of my course about automated program repair.

## Teacher

[Martin Monperrus](https://www.monperrus.net/martin/) is professor of software technology at KTH Royal Institute of Technology (Sweden).
He has been researching in the field of program repair for many years, see [past work](https://www.monperrus.net/martin/album?keywords=repair)

[Contact Martin](https://www.monperrus.net/martin/about+me) if you are interested in having this course.

## Past editions of the course

Program repair:
- 5 day version at [Escuela de Ciencias Informáticas 2015](http://dc.uba.ar/events/eci/2015/), see https://www.monperrus.net/martin/eci2015
- 1 day version at [EJCP'2024](https://gpl-ejcp.github.io/ejcp2024)

Related courses:
- [Lecture “Empirical Software Engineering” at EJCP’2015](https://www.monperrus.net/martin/ejcp2015)
- [Lecture “Empirical Software Engineering” at EJCP’2016](https://www.monperrus.net/martin/ejcp2016)


## Course goals

The course goals are:

-   You know the key concepts of automatic software repair.
-   You try a program repair tool by yourself.
-   You implement a simple repair system in your language of choice (optional).
-   You give a good presentation about automatic software repair.

Concepts:
- automatic program repair
  - core concept
  - code repair / runtime repair
  - repair operator
  - domain specific repair
- bug / defect / fault / error / failure
- specification, oracle, test case, regression
- fault class
- core repair algorithm

Examples:

- PHP bug <https://github.com/php/php-src/commit/1e91069>
- Apache Commons Math bug (also in [Defects4j](https://program-repair.org/defects4j-dissection/#!/)) <https://issues.apache.org/jira/browse/MATH-280>
 
## Course material

* [The Living Review on Automated Program Repair](https://hal.science/hal-01956501/document) (Martin Monperrus), Technical report hal-01956501, 2018-2023.
* [Automatic Software Repair: a Bibliography](http://arxiv.org/pdf/1807.00515) (Martin Monperrus), In ACM Computing Surveys, 2017.

For the record, see also the [2015 Course Notes](https://www.monperrus.net/martin/introduction-to-automatic-software-repair.pdf), which contain imtemporal bits.

### Teaching Philosophy

I'm an adept of active learning, where "active" means asking questions, reading, preparing and giving a presentation, writing code,
etc. In particular, I value [inquiry-based learning](https://en.wikipedia.org/wiki/Inquiry-based_learning) and [flipped classroom](https://en.wikipedia.org/wiki/Flipped_classroom  ). The best course is when it is only driven by student's questions.

## Program of EJCP 2024

Morning:
-   Presentation about myself (past, present)
-   Course

Afternoon:
- you try out a program repair tool, you can do the exercise
alone or in pair. 
- at the end, you prepare a short presentation about your experiment.
- Possible tools for the exercise:
  - Our own tools, see Github links at [this page](https://www.monperrus.net/martin/album?keywords=repair)
  - Other tools, see links in papers and [program-repair.org](https://program-repair.org/tools.html)
  - Industrial tools
    - [Jetbrains Qodana Quickfix](https://www.jetbrains.com/help/qodana/quick-fix.html)
    - [Github CodeQL autofix](https://github.blog/2023-11-08-ai-powered-appsec/)
    - [Mobb AI automated security vulnerability remediation](https://mobb.ai/)
    - [Snyk fix: Automatic vulnerability remediation from the Snyk CLI](https://snyk.io/blog/snyk-fix-automatic-vulnerability-remediation-snyk-cli/)
  - You implement your own LLM based program repair tool

## License

[Creative Commons - BY](https://creativecommons.org/licenses/by/4.0/) This license enables reusers to distribute, remix, adapt, and build upon the material in any medium or format, so long as attribution is given to the creator.

