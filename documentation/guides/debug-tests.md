---
layout: docs
title: Debug Tests
permalink: /documentation/guides/debug-tests.html
---
# Debug Tests

This topic provides information about debugging tests and consists of the following sections:

* [Debug Recorded Tests](#debug-recorded-tests)
  * [Debugging Features](#debugging-features)
* [Debug Coded Tests](#debug-coded-tests)

## Debug Recorded Tests

TestCafe Studio's *debug mode* helps you understand what is happening on your web page during testing. In this mode, TestCafe Studio pauses the test and allows you to debug the tested page using the browser's developer tools. You can check the web page's state, DOM elements' location, their CSS styles, etc.

You can activate the debug mode in one of the following ways:

* Add the [Debug](record-tests/test-actions/debug.md#debug) action to a particular position of a test. The test is paused when the test reaches this action.

    ![Debug Action](../../images/guides/debug-action.png)

* Enable the **Debug mode** option for a run configuration in the **Run Configurations** dialog. In this case, the test is paused before the first test action.

    ![Debug Mode Option](../../images/guides/debug-mode-option.png)

* Enable the **Pause the test when it fails** option for a run configuration in the **Run Configurations** dialog. TestCafe Studio automatically enters the debug mode when the test fails.

    ![Pause the Test When it Fails](../../images/guides/pause-test-option.png)

Once the test is paused, you can open browser's developer tools and debug.

During debugging, the browser window displays a footer with the following buttons:

* The **Unlock Page** button unlocks the tested page and allows you to interact with its elements.
* The **Resume** button resumes the test.
* The **Next Action** button allows you to skip to the next test action.

![Browser Footer](../../images/guides/footer.png)

### Debugging Features

TestCafe Studio includes features that help you find the cause of issues in your tests.

#### Screenshots

TestCafe Studio can capture screenshots during a test. You can analyze these screenshots to determine the cause of issues.

There are two ways to take screenshots:

* Use the [Take Screenshot](record-tests/test-actions/browser-actions.md#take-screenshot) action to take a screenshot in a particular place in a test.

    ![Take Screenshot Action](../../images/guides/take-screenshot-action.png)

* Turn on the *Take a screenshot if a test fails* option for a run configuration in the **Run Configurations** dialog to take a screenshot when a test fails.

    ![Take Screenshot Option](../../images/guides/screenshot-option.png)

TestCafe Studio stores the screenshots in the directory specified in the **Run Configurations** dialog and displays them in test reports.

![Screenshots](../../images/guides/screenshots-in-report.png)

#### Test Speed

Tests are executed at full speed with minimum delays between actions. You can adjust the speed in one of the following ways:

* Use the **Set Test Speed** action. The action parameter allows you to specify the test speed from 1 to 0.01.

    ![SEt Test Speed Action](../../images/guides/set-test-speed-action.png)

* Change the **Speed** option's value in the **Run Configurations** dialog's **Advanced Options** section.

    ![Speed Option](../../images/guides/speed-option.png)

## Debug Coded Tests

See [Debugging](https://devexpress.github.io/testcafe/documentation/test-api/debugging.html) in TestCafe documentation for more information about debugging coded tests.
