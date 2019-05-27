
# ProbLog

[![CircleCI](https://circleci.com/gh/ML-KULeuven/problog/tree/master.svg?style=svg)](https://circleci.com/gh/ML-KULeuven/problog/tree/master) *(master)* 
[![CircleCI](https://circleci.com/gh/ML-KULeuven/problog/tree/develop.svg?style=svg)](https://circleci.com/gh/ML-KULeuven/problog/tree/develop) *(develop)* 
[![codecov](https://codecov.io/gh/TechnionYP5777/project-name/branch/master/graph/badge.svg)](https://codecov.io/gh/TechnionYP5777/project-name)


ProbLog 2 is a **Probabilistic Logic Programming toolbox**.
It allows to intuitively build programs that do **not only encode complex interactions** between a large sets of heterogenous components,
but also the **inherent uncertainties** that are present in real-life situations.

Probabilistic logic programs are **logic programs** in which some of the facts are annotated with **probabilities**.

The engine tackles several tasks such as **computing the marginals given evidence** and **learning from (partial) interpretations**.
ProbLog is a suite of efficient algorithms for various **inference tasks**.
It is based on a conversion of the program and the queries and evidence to a **weighted Boolean formula**.
This allows us to reduce the inference tasks to well-studied tasks such as **weighted model counting**,
which can be solved using state-of-the-art methods known from the **graphical model** and **knowledge compilation literature**.

## Installation

ProbLog is a Python package and can be embedded in Python or Java.
Its knowledge base can be represented as Prolog/Datalog facts, CSV-files, SQLite database tables,
through functions implemented in the host environment or combinations hereof.

ProbLog 2.1 works out of the box on systems with Python. It has been
tested on Mac OSX, Linux and Windows.

ProbLog supports optional components which can be installed separately.
See the file INSTALL for detailed installation instructions.

### Prerequisites

ProbLog 2.1 requires Python 3.6+.
*(Python 2.7+ support has been dropped since ProbLog 2.1.0.36.)*


## Documentation

### Tutorial
To get started with ProbLog, follow the [ProbLog Tutorial](https://dtai.cs.kuleuven.be/problog/tutorial.html).

### Extensive Documentation
[Problog documentation](http://problog.readthedocs.org/en/latest/cli.html)




## License

Copyright 2015 KU Leuven, DTAI Research Group

Licensed under the Apache License, Version 2.0 (the "License"); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.