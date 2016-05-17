```
# Copyright 2016 Melomap (www.melomap.com)
#
# Licensed under the Apache License, Version 2.0 (the "License"); you may
# not use this file except in compliance with the License. You may obtain
# a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
# WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
# License for the specific language governing permissions and limitations
# under the License.
```

A python module to check valid myanmar mobile numbers, get mobile operator's name, sanitize mobile numbers and get mobile network types.

Will need to update when the new phone numbers came out.

Create issues if you see anything not correct.

Feel free to convert it to other languages and contribute back.

```
##### Usage

from mm_phonenumber import MMPhoneNumber
mm_phonenumber = MMPhoneNumber()
telecom_name = mm_phonenumber.get_telecom_name(phonenumber="")
mm_phonenumber.is_valid_mm_phonenumber(phonenumber="")

```


