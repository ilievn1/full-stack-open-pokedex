Python was chosen for the project

1. A quick google search reveals that popular linters in Python ecosystem are
   actually "combo-linters" (i.e. packets of multiple linters). This way a
   single linterenforces both logical and stylistic correctness. Examples
   included Flake8, Pylama and Pylint.

As far as testing goes, Python comes pre-packaged with 'unittest' which is both
a test runner and testing framework. Even thought, it is native to Python, it
supports abstractions in testing code that makes it difficult to interpret and
comes with a lot of boilerplate code. A better alternative would be PyTest,
which is supports unit testing, functional/integration testing and API testing.
Even though its propriety routines make compatibility with other frameworks next
to impossible, in exchange it offers compact and easy-to-use test suite and
large community support.

Python is interpreted language, hence no "build" concept exists. Just out of
curiosity I typed python build tools and a package with the name "PyBuilder"
came up. Its Github docs specify that it aims to simplify and automate the
process of building, testing, and packaging Python applications. The tool
enables developers to define a project's build configuration, afterwhich the
rest is handled by the tool. This includes dependency management, running tests,
generating documentation, and packaging the application for distribution. In
short, something similar to GitHub actions, but on a local configuration level.

2. Looking at job ads for DevOps engineers, tools of trade that could be
   considered alternatives are GitLab CI/CD, Azure Pipelines and CircleCI, all
   of which are cloud-based. CircleCI offers a variety of execution environments
   called "Executors" that you can choose from based on your requirements. These
   Executors are Docker-based and come in different sizes, allowing you to
   select the appropriate CPU, RAM, and disk configurations for your builds.
   Similar statement can be made for the other two cloud-based services.

3. Given that the team consists of only 6 people, as opposed to 6 teams or 6
   departments, cloud-based small/medium scale environment should be sufficient.
   Of course, due to the lack of any further context, such as resource demand
   and future plans of team expansion, cloud-based pipeline might be temporary
   solution
