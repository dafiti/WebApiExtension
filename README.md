# WebApiExtension

[![Build Status](https://travis-ci.org/Behat/WebApiExtension.svg?branch=master)](https://travis-ci.org/Behat/WebApiExtension)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/Behat/WebApiExtension/badges/quality-score.png?s=6499e6132229ddab00c3777daf1c74a9f31bee7c)](https://scrutinizer-ci.com/g/Behat/WebApiExtension/)

Provides testing for JSON APIs with Behat 3

## Documentation

[Official documentation](doc/index.rst)

## Steps
```Gherkin
Given /^all requests are in JSON$/
Given /^I am authenticating as "([^\"]*)" with "([^\"]*)" password$/
Given /^I set header "([^\"]*)" with value "([^\"]*)"$/
Given /^the response json should have a "([^\"]*)" key$/
Given /^the response json should have a "([^\"]*)" key with value "([^\"]*)"$/
Given /^the key "([^\"]*)" should have a subkey "([^\"]*)"$/
Given /^the key "([^\"]*)" should have a subkey "([^\"]*)" with value (\d+)$/
Given /^the key "([^\"]*)" should have a subkey "([^\"]*)" with value "([^\"]*)?"$/
Given /^the key "([^\"]*)" should have a subkey "([^\"]*)" in index (\d+)$/
Given /^the response json's "([^\"]*)" key should be of type "([^\"]*)"$/
 Then /^Set PlaceHolder with key '([^\']*)' and values "([^\"]*)"$/
 Then /^Set PlaceHolder with key "([^\"]*)" and values "([^\"]*)"$/
 Then /^Set PlaceHolder with key "([^\"]*)" and value "([^\"]*)"$/
 Then /^Set PlaceHolder with key "([^\"]*)" and dinamic value "([^\"]*)"$/
 Then /^(?:the )?response code should be (\d+)$/
 Then /^(?:the )?response should contain "([^\"]*)"$/
 Then /^(?:the )?response should not contain "([^\"]*)"$/
 Then /^(?:the )?response should contain json:$/
 Then print response
 When /^(?:I )?send a ([A-Z]+) request to "([^\"]+)"$/
 When /^(?:I )?send a ([A-Z]+) request to "([^\"]+)" with values:$/
 When /^(?:I )?send a ([A-Z]+) request to "([^\"]+)" with body:$/
 When /^(?:I )?send a ([A-Z]+) request to "([^\"]+)" with form data:$/
```

## Copyright

Copyright (c) 2014 Konstantin Kudryashov (ever.zet). See LICENSE for details.

## Contributors

* Christophe Coevoet [stof](http://github.com/stof) [lead developer]
* Other [awesome developers](https://github.com/Behat/WebApiExtension/graphs/contributors)
