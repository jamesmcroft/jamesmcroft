# Useful links for UI Testing

## Frameworks

### Selenium

<https://www.seleniumhq.org/>

Selenium is an automation framework for web browsers with support for multiple programming languages including C# and JavaScript.

- [Selenium WebDriver C# cheat sheet - automatetheplanet.com](https://www.automatetheplanet.com/selenium-webdriver-csharp-cheat-sheet/)

### Appium

<https://www.appium.io/>

Appium is an automation framework built on top of Selenium designed for testing native applications for desktop and mobile, including Windows, macOS, iOS, and Android.

### Legerity

<https://made-apps.github.io/legerity/>

Legerity is an automated UI testing framework for building maintainable tests quickly for Windows, Android, iOS, and Web applications with C#/.NET built on top of Selenium and Appium.

- [Writing custom element wrappers for Selenium test with Legerity - jamescroft.co.uk](https://www.jamescroft.co.uk/custom-element-wrappers-for-selenium-tests-with-legerity/)
- [Writing Windows UI tests with Legerity and WinAppDriver - jamescroft.co.uk](https://www.jamescroft.co.uk/windows-ui-testing-with-legerity/)

### Protractor

<https://www.protractortest.org/>

Protractor is a framework for writing UI tests for Angular specific applications and has built in extensions for querying elements in your UI using the Angular syntax you used to build the app.

### Smartbear TestComplete

<https://smartbear.com/product/testcomplete/overview/>

Smartbear TestComplete is a comprehensive automation testing platform for testing both native and web applications with low code.

### Xamarin UITest

<https://docs.microsoft.com/en-us/appcenter/test-cloud/frameworks/uitest/>

Xamarin UITest is a framework for writing UI tests for cross-platform applications built with Xamarin Forms.

## Patterns

### Page Object Pattern

The page object pattern is a UI test design pattern that defines a class for representing a page within an application. The page object encapsulates the web page's functionality and presents it as a set of methods that you can call.

- [Implementing The Page Object Pattern In UI Tests - jamescroft.co.uk](https://www.jamescroft.co.uk/implementing-the-page-object-pattern-in-ui-tests/)
- [Page Object Pattern - webdriver.io](https://webdriver.io/docs/pageobjects)
- [Page Object Pattern in Automated Testing - automatetheplanet.com](https://www.automatetheplanet.com/page-object-pattern/)

## Courses

### Automate The Planet Learning Series (C#, Java, Kotlin, and VB)

<https://github.com/AutomateThePlanet/AutomateThePlanet-Learning-Series/>

Automate The Planet Learning Series is a GitHub repository containing a series of code samples and articles showcasing the use of various automation patterns and techniques for writing maintainable UI tests.

It covers a variety of languages including C#, Java, Kotlin, and VB.

## Demos

### ToDoer Selenium/Legerity UI Test Demo Project

<https://github.com/jamesmcroft/todoer-ui-test-demo/>

This is an example project showcasing how to write maintainable UI tests using the Selenium framework with C#.

The UI test project uses the [Legerity](#legerity) framework to write the maintainable application element wrappers. It is also used to simplify the approach to launching the application in multiple platform scenarios, such as running on Google Chrome and Microsoft Edge.

The demo showcases some best practices in writing UI tests including the [Page Object Pattern](#page-object-pattern), simplifying interactions with components using UI element wrappers with Legerity, and cross-browser test runs.
