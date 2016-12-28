# Age Calculator

It's a amazing java library that simplifies the calculation of the age from birthday.

How
---
* Default constructor gets current time as reference date
```java
AgeCalculator ageCalculator = new AgeCalculator();
String myAge = ageCalculator.calculateAge("1974-11-20")
```

* Custom constructor accept as reference date 3 variable types: String, Date and LocalDate
```java
AgeCalculator ageCalculator = new AgeCalculator("2016-12-28");
String myAge = ageCalculator.calculateAge("1974-11-20")
```
```java
LocalDate referenceDate = LocalDate.parse("2016-12-28");
AgeCalculator ageCalculator = new AgeCalculator(referenceDate);
String myAge = ageCalculator.calculateAge("1974-11-20")
```

#Download

* Get <a href="https://github.com/juanet3/age-calculator/releases/download/1.0.0/age-calculator-1.0.0.jar">the latest .jar</a>

* Grab via Gradle:
```groovy
repositories { jcenter() }
    
compile 'com.ullahbluh.tools:age-calculator:1.0.0'
```

* Grab via Maven:
```xml
<repository>
  <id>jcenter</id>
  <url>http://jcenter.bintray.com</url>
</repository>

<dependency>
  <groupId>com.ullahbluh.tools</groupId>
  <artifactId>age-calculator</artifactId>
	<version>1.0.0</version>
</dependency>

```


## LICENSE ##

The MIT License (MIT)

Copyright (c) 2015 Fewlaps

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
