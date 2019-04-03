# pleasant-test
Generic automation framework with object orientation

* Robot framework inspired
* Object oriented, so page object model is natural
* Libraries are global objects
* Functions become part of modules that can be used once a module is imported, as in robot they become accessible without the prefix, but the prefix can be used for dis-ambiguity purposes
DDT with data generation
* Resources can be be defined separately so pages, suites and locators are definied separate
* Locators define variables
* Locators have behaviours, like switch, normal
* Locators have names, like login, so you could do Click login, getText login
* Locators are expandable variables, and they are not expanded until being used by an action
* Pages declare methods, like Select Product(product), Set User Information(firstName, lastName, ...)
* Pages import locators
* Page methods are callable by other methods either in the same page or other pages
* Pages are like classes
* "Variables" live in a page
* Pages when created look for a locator to make sure the page was loaded
* Suites are pages, technically
* Suites define test cases, like buy product
* Suite import pages/suites
* Actions are default behaviors like getText, click
* Actions take a screenshot after each action (UI)
* Take into account DDT with data generation for the future.
* Keywords? For, While, Return
