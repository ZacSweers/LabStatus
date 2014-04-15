LabStatus
=========

A very minimal REST API for the UTCS labs using cgi scripts, used in the UTCS mobile apps.

Special thanks to [Craig Yeh](https://www.github.com/yeh) for his early work in parsing lab map and helping me out with getting cgi-bin to work.

#### cgi-bin
To use the scripts there, do the following:

* Copy the cgi-bin folder to the `public_html` directory (make sure it's readable)

* Make the scripts executable (`chmod +x *.scgi`)

Then the scripts will be accessible at `http://www.cs.utexas.edu/~<user>/cgi-bin/<script>.scgi`

#### License

     Copyright 2014 Henri Sweers

     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.
