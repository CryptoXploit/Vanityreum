  Vanityreum
===========

Vanityreum is an Ethereum single address wallet generator fully written in python.

* Pure Python code
* Cross-platform code
* No-dependencies
* Generates addresses the easiest way


## Using Vanityreum

You need Python 2.7 (not tested on 3.x).

Just launch Vanityreum.py to generate a single wallet address.

You can enter an optional argument, the argument must be a hexadecimal string shorter than 11 chars.

Example:

    python2.7 Vanityreum.py 02f

will search for an address starting with "02f"

And finally saves a "priv.prv" file with the private key.

Then key can be imported in geth:

    geth account import priv.prv


Random source for key generation :

* CryptGenRandom in Windows
* /dev/urandom   in Unix-like

License :
----------
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
