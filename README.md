Chef Bootstrap Templates
========================

This is collection of Chef bootstrap templates for nonstandard OSes, or for folks that want to do different things than the out-of-the-box templates do.

Usage
-----

Put the relevant template in your `$HOME/.chef/bootstrap` directory; then you can bootstrap a node with the --distro flag, e.g.

```shell
$ knife bootstrap 1.2.3.4 --distro template-name
```

Note that `template-name` is the filename of the template without the `.erb` extension.

License & Authors
-----------------

- Author:: Julian C. Dunn (<jdunn@aquezada.com>)

```text
Copyright 2014, Julian Dunn.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
