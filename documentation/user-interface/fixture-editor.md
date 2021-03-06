---
layout: docs
title: Fixture Editor
permalink: /documentation/user-interface/fixture-editor.html
---
# Fixture Editor

The **Fixture Editor** allows you to view and modify a fixture. To open the editor, double-click the fixture in the [Explorer](explorer-panel.md) panel.

The editor consists of the following parts:

* The toolbar - Provides information about the fixture (the name and tested webpage's URL) and buttons to perform [common tasks](#common-tasks).

    You can click the webpage's URL to open the webpage in the browser.

* The test list - Displays tests included in the fixture. You can click a test's row to open the test in the [Test Editor](test-editor.md).

![Fixture editor](../../images/user-interface/fixture-editor.png)

## Common Tasks

You can perform the following tasks in the editor:

* [Record New Tests](#record-new-tests)
* [Run the Fixture or Single Test](#run-the-fixture-or-single-test)
* [Convert the Fixture to JavaScript](#convert-the-fixture-to-javascript)
* [Modify the Fixture's Properties](#modify-the-fixtures-properties)
* [Delete Tests](#delete-tests)

### Record New Tests

Click ![Record button](../../images/guides/record-test-icon.png) **Record a new test** on the editor's toolbar to start recording a new test and add it to the fixture.

### Run the Fixture or Single Test

Click the ![Run tests button](../../images/guides/action-run-icon.png) **Run all tests** button on the editor's toolbar to run the entire fixture.

To run a single test, hover the mouse cursor over the test's row and click ![Run test button](../../images/guides/action-run-icon.png) **Run test** displayed to the right of it.

### Convert the Fixture to JavaScript

Click ![Convert icon](../../images/user-interface/js-icon.svg) **Convert to JavaScript** on the editor's toolbar to convert the fixture to a .js file. This invokes the **Convert to JavaScript** dialog that allows you to specify the file's name.

![Convert to JavaScript Code Dialog](../../images//user-interface/dialogs/convert-dialog.png)

TestCafe Studio creates the test file in the same test directory and displays it in the **Explorer** panel.

## Modify the Fixture's Properties

Click ![Settings button](../../images/guides/settings-icon.png) on the editor's toolbar to modify the fixture's properties. This invokes the [Fixture Properties](../user-interface/fixture-properties-dialog.md) dialog where you can change the fixture name, file name, target webpage, and authentication credentials. To save the changes, click **OK**.

![Fixture Properties dialog](../../images/user-interface/dialogs/modify-fixture-dialog.png)

### Delete Tests

Click ![Remove all tests icon](../../images/user-interface/remove-all-icon.svg) **Remove all tests** on the editor's toolbar to delete all the fixture's tests.

To delete a single test from the fixture, hover the mouse cursor over the test's row and click the row's ![Remove icon](../../images/user-interface/remove-big-icon.svg) **Remove test** button.
