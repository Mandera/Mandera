# ManderaGeneral
 - Modularized platform for managing future products.
 - Automatic workflows to unittest, sync and publish.

## Dependency Diagram for ManderaGeneral
```mermaid
flowchart LR
2([library]) --> 5([packager])
1([tool]) --> 2([library])
2([library]) --> 4([vector])
0([import]) --> 3([file])
2([library]) --> 3([file])
3([file]) --> 5([packager])
0([import]) --> 2([library])
click 0 "https://github.com/ManderaGeneral/generalimport"
click 1 "https://github.com/ManderaGeneral/generaltool"
click 2 "https://github.com/ManderaGeneral/generallibrary"
click 3 "https://github.com/ManderaGeneral/generalfile"
click 4 "https://github.com/ManderaGeneral/generalvector"
click 5 "https://github.com/ManderaGeneral/generalpackager"
```

## Information
| Package                                                              | Ver                                                | Latest Release        | Python                                                                                                                                                                                                                                                 | Platform        | Cover   |
|:---------------------------------------------------------------------|:---------------------------------------------------|:----------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------|:--------|
| [generalfile](https://github.com/ManderaGeneral/generalfile)         | [2.5.14](https://pypi.org/project/generalfile/)    | 2022-10-27 16:21 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/), [3.10](https://www.python.org/downloads/release/python-3100/), [3.11](https://www.python.org/downloads/release/python-3110/) | Windows, Ubuntu | 72.1 %  |
| [generalimport](https://github.com/ManderaGeneral/generalimport)     | [0.3.1](https://pypi.org/project/generalimport/)   | 2022-10-27 16:21 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/), [3.10](https://www.python.org/downloads/release/python-3100/), [3.11](https://www.python.org/downloads/release/python-3110/) | Windows, Ubuntu | 96.7 %  |
| [generallibrary](https://github.com/ManderaGeneral/generallibrary)   | [2.9.12](https://pypi.org/project/generallibrary/) | 2022-10-27 16:21 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/), [3.10](https://www.python.org/downloads/release/python-3100/), [3.11](https://www.python.org/downloads/release/python-3110/) | Windows, Ubuntu | 92.8 %  |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | [0.5.7](https://pypi.org/project/generalpackager/) | 2023-02-02 13:29 CET  | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/), [3.10](https://www.python.org/downloads/release/python-3100/), [3.11](https://www.python.org/downloads/release/python-3110/) | Windows, Ubuntu | 67.8 %  |
| [generaltool](https://github.com/ManderaGeneral/generaltool)         | [0.1.0](https://pypi.org/project/generaltool/)     | 2023-02-02 13:29 CET  | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/), [3.10](https://www.python.org/downloads/release/python-3100/), [3.11](https://www.python.org/downloads/release/python-3110/) | Windows, Ubuntu | 99.1 %  |
| [generalvector](https://github.com/ManderaGeneral/generalvector)     | [1.5.112](https://pypi.org/project/generalvector/) | 2022-10-27 16:21 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/), [3.10](https://www.python.org/downloads/release/python-3100/), [3.11](https://www.python.org/downloads/release/python-3110/) | Windows, Ubuntu | 52.3 %  |

## Contributions
Issue-creation, discussions and pull requests are most welcome!

<sup>
Generated 2023-05-16 01:50 CEST
</sup>
