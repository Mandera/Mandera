# ManderaGeneral
 - A collection of connected packages.
 - Violently updated with little regard for backwards compatability.
 - Automatic workflows to unittest, sync and publish.

## Information
| Package                                                              | Ver                                                | Latest Release        | Python                                                                                                                   | Platform        |   Lvl | Todo                                                        | Tests   |
|:---------------------------------------------------------------------|:---------------------------------------------------|:----------------------|:-------------------------------------------------------------------------------------------------------------------------|:----------------|------:|:------------------------------------------------------------|:--------|
| [generallibrary](https://github.com/ManderaGeneral/generallibrary)   | [2.8.5](https://pypi.org/project/generallibrary/)  | 2021-10-16 15:31 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/) | Windows, Ubuntu |     0 | [4](https://github.com/ManderaGeneral/generallibrary#Todo)  | 99.5 %  |
| [generalfile](https://github.com/ManderaGeneral/generalfile)         | [2.4.1](https://pypi.org/project/generalfile/)     | 2021-10-16 15:31 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/) | Windows, Ubuntu |     1 | [3](https://github.com/ManderaGeneral/generalfile#Todo)     | 100.0 % |
| [generalvector](https://github.com/ManderaGeneral/generalvector)     | [1.5.11](https://pypi.org/project/generalvector/)  | 2021-04-17 12:25 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/) | Windows, Ubuntu |     1 | [1](https://github.com/ManderaGeneral/generalvector#Todo)   | 100.0 % |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | [0.3.4](https://pypi.org/project/generalpackager/) | 2021-10-16 15:31 CEST | [3.8](https://www.python.org/downloads/release/python-380/), [3.9](https://www.python.org/downloads/release/python-390/) | Windows, Ubuntu |     2 | [5](https://github.com/ManderaGeneral/generalpackager#Todo) | 100.0 % |

## Todo
| Package                                                              | Module                                                                                                                                               | Message                                                                                                                                                                                                  |
|:---------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [generallibrary](https://github.com/ManderaGeneral/generallibrary)   | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/versions.py#L1'>versions.py</a>                                 | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/versions.py#L17'>Use Ver in each part of VerInfo.</a>                                                               |
| [generallibrary](https://github.com/ManderaGeneral/generallibrary)   | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/objinfo/objinfo.py#L1'>objinfo.py</a>                           | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/objinfo/objinfo.py#L19'>Recycle ObjInfo.</a>                                                                        |
| [generallibrary](https://github.com/ManderaGeneral/generallibrary)   | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/functions.py#L1'>functions.py</a>                               | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/functions.py#L35'>Remove classproperty once 3.8 is no longer supported.</a>                                         |
| [generallibrary](https://github.com/ManderaGeneral/generallibrary)   | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/diagram.py#L1'>diagram.py</a>                                   | <a href='https://github.com/ManderaGeneral/generallibrary/blob/master/generallibrary/diagram.py#L256'>[UnitTest] for Class: Storable</a>                                                                 |
| [generalfile](https://github.com/ManderaGeneral/generalfile)         | <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path.py#L1'>path.py</a>                                               | <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path.py#L22'>Binary extension.</a>                                                                                        |
| [generalfile](https://github.com/ManderaGeneral/generalfile)         | <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/optional_dependencies/path_spreadsheet.py#L1'>path_spreadsheet.py</a> | <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/optional_dependencies/path_spreadsheet.py#L106'>Support DataFrame and Series with spreadsheet.append()</a>                |
| [generalfile](https://github.com/ManderaGeneral/generalfile)         | <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_lock.py#L1'>path_lock.py</a>                                     | <a href='https://github.com/ManderaGeneral/generalfile/blob/master/generalfile/path_lock.py#L12'>Lock the optional extra paths.</a>                                                                      |
| [generalvector](https://github.com/ManderaGeneral/generalvector)     | <a href='https://github.com/ManderaGeneral/generalvector/blob/master/generalvector/general.py#L1'>general.py</a>                                     | <a href='https://github.com/ManderaGeneral/generalvector/blob/master/generalvector/general.py#L7'>Move most methods to _GeneralVector.</a>                                                               |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/packager.py#L1'>packager.py</a>                               | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/packager.py#L4'>Prevent workflow using pypi to install a general package.</a>                                     |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/packager_files.py#L1'>packager_files.py</a>                   | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/packager_files.py#L30'>Watermark generated files to prevent mistake of thinking you can modify them directly.</a> |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/api/pypi.py#L1'>pypi.py</a>                                   | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/api/pypi.py#L11'>Move download to it's own package.</a>                                                           |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/api/pypi.py#L1'>pypi.py</a>                                   | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/api/pypi.py#L65'>Find a faster fetch for latest PyPI version and datetime.</a>                                    |
| [generalpackager](https://github.com/ManderaGeneral/generalpackager) | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/api/local_repo.py#L1'>local_repo.py</a>                       | <a href='https://github.com/ManderaGeneral/generalpackager/blob/master/generalpackager/api/local_repo.py#L24'>Search for imports to list dependencies.</a>                                               |

<sup>
Generated 2021-10-16 16:04 CEST
</sup>
