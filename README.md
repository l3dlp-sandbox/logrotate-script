# logrotate

## Overview

Perl script to capture input stream (stdin) and write it into log files. A new log file is generated for every day. Every file has date siffix in YYMMDD format.

Example usage:
```
> echo "test" | logrotate
```

## Team

- Anton Tananaev ([anton.tananaev@gmail.com](mailto:anton.tananaev@gmail.com))

## License

    Apache License, Version 2.0

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
