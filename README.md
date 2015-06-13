[![Unix Build Status][travis-image]][travis-link]
![License][license-image]
# SerializedDataConverter
Convert between serialized data formats (plist | bplist | json | yaml)

<img src="https://dl.dropboxusercontent.com/u/342698/SerializedDataConverter/Example.png" border="0">

# Third Party Libraries

- pyyaml: https://github.com/yaml/pyyaml
- plistlib: Sublime Text 3 currently uses Python 3.3, but Python 3.4 has a new version of plistlib that handles binary plists.  To get this functionality, we dropped the [Python 3.4 plistlib](https://hg.python.org/cpython/file/3.4/Lib/plistlib.py) directly into the plugin with minor changes to get it working in Python 3.3.  Eventually this will be removed if Sublime moves to Python 3.4.

# Documentation
http://facelessuser.github.io/SerializedDataConverter/

# License
MIT except for PYYAML and plistlib.  See LICENSE for more info.

[travis-image]: https://img.shields.io/travis/facelessuser/SerializedDataConverter/master.svg
[travis-link]: https://travis-ci.org/facelessuser/SerializedDataConverter
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
