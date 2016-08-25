# ncdu сookbook

Setup ncdu - is a disk usage analyzer with an ncurses interface.

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
