StandardCV
=========================

A **one-page**, **two asymmetric column** resume template in **XeTeX** that caters particularly to  Computer Science students.
Has a bunch of font options as listed in [**Preview**](https://github.com/gautam-jha/standardcv/blob/main/gautam-jha.pdf). 


## Dependencies

1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.


## Install

To install on Debian/Ubuntu, run the following command: ```sudo apt-get install texlive-xetex```

To use it use the following command: ```xelatex StandardCV.tex```

Alternate: [Try this **Not Tested**](https://miktex.org/download)

## TODO

1. Add more font options.
2. Allow for multiple pages and overflow.

## Known Issues:

1. Overflows if vertical limit reached.
2. First bullet point on the second column needs a proper fix.

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
       http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.