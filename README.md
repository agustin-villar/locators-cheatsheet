# locators-cheatsheet

| Locator          | Description | Syntax (in Java) |
|------------------|-------------|------------------|
| ID               | Figure out the WebElement that uses the ID attribute | driver.findElement(By.id(“element-id”)); |
| Name             | Figure out the WebElement with the Name attribute | driver.findElement(By.name(“element-name”)); |
| ClassName        | Make use of the Class attribute to identify the object | driver.findElement(By.className(“element-class”)); |
| LinkText         | Leverage the text hyperlinks for locating the WebElement | driver.findElement(By.linkText(“click here to read more”)); |
| Partial LinkText | Make use of the text partially in hyperlinks for desired WebElement location | driver.findElement(By.partialLinkText(“to read more”)); |
| TagName          | Make use of the TagName for locating any desired WebElement | driver.findElement(By.tagName(“button”)); |
| CssSelector      | CSS that we use to create different style rules in a web page can be used to locate any needed WebElement | driver.findElement(By.cssSelector(“#buttons .button”)); |
| XPath            | Bring in XPath as a WebElement locator | driver.findElement(By.xpat(“//button[@id='element-id']”)); |
