# O-RAN-SC Non-RealTime RIC - A1 Controller (Experimental O-RAN-SC Module)

![Status: Not for Production](https://img.shields.io/badge/status-not--for--production-red)
![Status: Experimental](https://img.shields.io/badge/CVE%20Support-none-lightgrey)

> [!WARNING]
> This repository is pre-spec and not intended for production use. No CVE remediation or production guarantees apply.

SDNC-A1 controller provides a Northbound Interface for A1 operations to do policy management in Near-RealTime RICs.

It is a very lightweight version of ONAP SDNC.

Many features/components of SDNC that are not needed for A1 operations have been removed from both northbound and oam directories.

This makes it very fast to start the controller and also puts less load on the CPU.

Please see the documentation in the docs/ folder

For more information about the Non-RT RIC project please see the [project website](https://wiki.o-ran-sc.org/display/RICNR "O-RAN-SC Non-RT RIC project")

## License

Copyright (C) 2019-2023 Nordix Foundation.
Copyright (C) 2023-2025 OpenInfra Foundation Europe.
Licensed under the Apache License, Version 2.0 (the "License")
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

For more information about license please see the [LICENSE](LICENSE.txt) file for details.
