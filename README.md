Android Javafmt Plugin
=========================

A plugin that formats your code using [googe-java-format](https://github.com/google/google-java-format).


Usage
-----

Apply the plugin in your `build.gradle`:

```groovy
buildscript {
  repositories {
    mavenCentral()
  }
  dependencies {
    classpath 'com.f2prateek.javafmt:javafmt:0.1.0'
  }
}

apply plugin: 'com.f2prateek.javafmt'
```


License
--------

    Copyright 2017 Prateek Srivastava

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
