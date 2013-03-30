SeedBoxer Ubuntu/Debian Repository
====================

See [SeedBoxer](http://seedboxer.github.com/seedboxer/).

## Usage

1. Add .deb packages repository

```shell
sudo echo "deb http://seedboxer.github.com/deb-repo binary/" > /etc/apt/sources.list.d/seedboxer.list
```

2. Update APT to get descriptions

```shell
sudo apt-get update
```

3. Install Seedboxer

```shell
sudo apt-get install seedboxer-standalone
```

## Binaries

The binaries are located in gh-pages branch.


## License

Copyright (c) 2012 SeedBoxer Team.

SeedBoxer is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

SeedBoxer is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with SeedBoxer.  If not, see <http ://www.gnu.org/licenses/>.
