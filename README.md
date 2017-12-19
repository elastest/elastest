[![License badge](https://img.shields.io/badge/license-Apache2-green.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Documentation badge](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://elastest.io/docs/)
[![Build Status](https://ci.elastest.io/jenkins/buildStatus/icon?job=elastest-torm/etm)](https://ci.elastest.io/jenkins/job/elastest-torm/job/etm)
[![Quality Gate](https://sonarcloud.io/api/badges/gate?key=io.elastest:torm)](https://sonarcloud.io/dashboard/index/io.elastest:torm)
[![codecov](https://codecov.io/gh/elastest/elastest-torm/branch/master/graph/badge.svg)](https://codecov.io/gh/elastest/elastest-torm)

[![][ElasTest Logo]][ElasTest]

Copyright © 2017-2019 [Universidad Rey Juan Carlos]. Licensed under
[Apache 2.0 License].

What is ElasTest
-----------------

[ElasTest] is a platform aimed to ease end to end testing of distributed systems. The two key features of the platform are: 1) Provide an easy deployment process and easy access to the necessary services usually involved in an end to end test and 2) Provide easy-to-use tools to show and analyze logs and metrics of all elements involved in an end to end test.</p><p>For example, suppose a typical three tier web application with a database. A basic e2e test has the following components: the test itself, web browser, web application and database. All those elements have to be properly deployed, linked and executed, and all of them can generate logs and metrics of several types (CPU, memory, network packets…). A test being executed in ElasTest can make direct use of multiple integrated services (such as Web Browsers), and the tester can see all that monitoring information in the same graphical user interface and with advanced analysis features.

Documentation
-------------

ElasTest provides detailed documentation including tutorials,
installation and development guide. You can check it out [here](http://elastest.io/docs/).

Source
------

Source code for other ElasTest projects can be found in the [GitHub ElasTest
Group].

News
----

Follow us on Twitter [@elastestio].

Licensing and distribution
--------------------------

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Contribution policy
-------------------

You can contribute to the ElasTest community through bug-reports, bug-fixes,
new code or new documentation. For contributing to the ElasTest community,
you can use the issue support of GitHub providing full information about your
contribution and its value. In your contributions, you must comply with the
following guidelines

* You must specify the specific contents of your contribution either through a
  detailed bug description, through a pull-request or through a patch.
* You must specify the licensing restrictions of the code you contribute.
* For newly created code to be incorporated in the ElasTest code-base, you
  must accept ElasTest to own the code copyright, so that its open source
  nature is guaranteed.
* You must justify appropriately the need and value of your contribution. The
  ElasTest project has no obligations in relation to accepting contributions
  from third parties.
* The ElasTest project leaders have the right of asking for further
  explanations, tests or validations of any code contributed to the community
  before it being incorporated into the ElasTest code-base. You must be ready
  to addressing all these kind of concerns before having your code approved.

Support
-------

ElasTest project provides community support through the [ElasTest Public
Mailing List], this repo [Issue tracker](https://github.com/elastest/elastest/issues) and through [StackOverflow] using the tag *elastest*.


<p align="center">
  <img src="http://elastest.io/images/logos_elastest/ue_logo-small.png"><br>
  Funded by the European Union
</p>

[Apache 2.0 License]: http://www.apache.org/licenses/LICENSE-2.0
[ElasTest]: http://elastest.io/
[ElasTest Blog]: http://elastest.io/blog/
[ElasTest Doc]: http://elastest.io/docs/
[ElasTest Logo]: http://elastest.io/images/logos_elastest/elastest-logo-gray-small.png
[ElasTest Public Mailing List]: https://groups.google.com/forum/#!forum/elastest-users
[@elastestio]: https://twitter.com/elastestio
[GitHub ElasTest Group]: https://github.com/elastest
[GitHub ElasTest Bugtracker]: https://github.com/elastest/bugtracker
[Repository Doc]: docs/index.md
[StackOverflow]: http://stackoverflow.com/questions/tagged/elastest
[Universidad Rey Juan Carlos]: https://www.urjc.es/en/