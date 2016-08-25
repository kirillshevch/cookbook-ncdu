# Cookbook ncdu

Chef cookbook for installing [ncdu](https://dev.yorhel.nl/ncdu)

Ncdu is a disk usage analyzer with an ncurses interface. It is designed to find space hogs on a remote server where you don't have an entire graphical setup available, but it is a useful tool even on regular desktop systems. Ncdu aims to be fast, simple and easy to use, and should be able to run in any minimal POSIX-like environment with ncurses installed.

## Usage

    cookbook 'ncdu', '~> 1.0.0'

Just include `ncdu` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[ncdu]"
  ]
}
```

License
-------------------
Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License.  You may obtain a copy of the
License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.  See the License for the
specific language governing permissions and limitations under the License.
