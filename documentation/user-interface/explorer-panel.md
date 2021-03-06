---
layout: docs
title: Explorer Panel
permalink: /documentation/user-interface/explorer-panel.html
---
# Explorer Panel

The **Explorer** panel allows you to view and manage files in your [test directory](../guides/organize-tests.md#test-directory).

The panel shows the directory's content as a tree of subdirectories, files, and tests. See [Organize Tests](../guides/organize-tests.md) for more information.

![Explorer panel](../../images/guides/explorer-panel.png)

You can manage test directories, files, fixtures, and tests using context menu commands. The available commands depend on the selected item in the panel.

The panel also has buttons for frequently-used actions: **Record a New Test** and **Create a New Fixture**.

## Create a Directory

To create a new directory, invoke the context menu for a directory where you want to create it and select ![New directory icon](../../images/user-interface/context-menu/new-directory.png) **New Directory**. Specify the directory name in the invoked dialog and click **Create**.

![New Directory dialog](../../images/user-interface/dialogs/new-directory-dialog.png)

The new directory appears in the **Explorer** panel.

## Create a Fixture

To create a new [fixture](../guides/record-tests/README.md#create-fixtures), select a directory where you want to create it and click **Create a New Fixture** or select the ![New fixture icon](../../images/user-interface/context-menu/new-fixture.png) **New Fixture** command from the context menu. This invokes the [Fixture Properties](../user-interface/fixture-properties-dialog.md) dialog.

![Create a fixture](../../images/user-interface/dialogs/new-fixture-dialog.png)

Specify the fixture's properties and click **Create**. The new fixture appears in the **Explorer** panel.

## Create a Test

You can create a new test in one of the following ways:

* Record a test - Select the fixture where you want to create a test and click the ![Record button](../../images/getting-started/record-test-icon.png) **Record a New Test** button. This automatically creates a new test, adds it to the fixture and starts [recording](../guides/record-tests/README.md).

* Create an empty test - Select the fixture where you want to create a test and select ![New test icon](../../images/user-interface/context-menu/new-test.png) **New Test** from the context menu to open the **New Test** dialog.

    ![New Test dialog](../../images/user-interface/dialogs/new-test-dialog.png)

    Specify the test name and click **Create**. TestCafe Studio creates an empty test and opens it in the [Test Editor](test-editor.md).

## Create a File

To create a new file,  invoke the context menu in the directory where you want to create a file and select ![New file icon](../../images/user-interface/context-menu/new-file.png) **New File** from the context menu. Specify the file name and extension in the invoked dialog and click **Create**.

![New File dialog](../../images/user-interface/dialogs/new-file-dialog.png)

The created file appears in the **Explorer** panel and opens in the **Code Editor**.

## Run Tests

To run any runnable item (test, fixture or directory), hover the mouse over it and click the ![The Run test button](../../images/user-interface/context-menu/run-tests.png) **Run test** or **Run all tests** button next to this item.

To run several tests from different fixtures and directories, select the tests using Shift-click, Ctrl-click, or Command-click, then click the ![The Run tests button](../../images/user-interface/context-menu/run-tests.png) **Run Tests** button next to any selected item.

![Run multiple items](../../images/user-interface/running-multiple-items.png)

You can also use the context menu's ![Run test icon](../../images/user-interface/context-menu/run-tests.png) **Run Test** command to run tests.

## Modify a Fixture's Properties

To edit a fixture's properties, open its context menu and select ![Edit icon](../../images/user-interface/context-menu/fixture-modify.png) **Edit** to invoke the [Fixture Propeties](../user-interface/fixture-properties-dialog.md) dialog. You can change the fixture name, file name, target webpage and authentication credentials in this dialog. To save the changes, click **OK**.

![Modify Fixture dialog](../../images/user-interface/dialogs/modify-fixture-dialog.png)

## Rename Tests

To rename a test, invoke its context menu and select ![Rename icon](../../images/user-interface/context-menu/rename.png) **Rename**. The **Rename Test** dialog appears. Specify the new test name and click **Rename**.

![Rename Test dialog](../../images/user-interface/dialogs/rename-test-dialog.png)

## Convert Fixtures to JavaScript

To convert a fixture with recorded tests to JavaScript, select the fixture in the **Explorer** panel, open its context menu and select ![Convert icon](../../images/user-interface/context-menu/convert.png) **Convert to JavaScript** to invoke the **Convert to JavaScript** dialog. Specify the test file name and extension, then click **Create**.

![Convert to JavaScript Code Dialog](../../images//user-interface/dialogs/convert-dialog.png)

TestCafe Studio creates the test file in the same test directory and displays it in the **Explorer** panel.

## View Test Code

To view JavaScript and TypeScript files in the [Code Editor](code-editor.md), select a fixture or test in the **Explorer** panel, then select ![Show code icon](../../images/user-interface/context-menu/show-code.png) **Show Code** from the context menu. The fixture code opens in the **Code Editor**.

## Show Files in Windows Explorer/MacOS Finder

To view a fixture or directory in Windows Explorer and macOS Finder, invoke the context menu for the fixture or directory and select ![Show in Explorer icon](../../images/user-interface/context-menu/show-in-explorer.png) **Show in Explorer/Finder**.

## Delete Directories, Fixtures and Tests

To delete a directory, fixture or test, invoke its context menu and select ![Delete icon](../../images/user-interface/context-menu/delete.png) **Delete**. A confirmation dialog appears. Click **Yes** to delete the selected item.

To delete several tests from different fixtures and directories, select the tests with Shift-click, Ctrl-click, or Command-click, then select ![Delete icon](../../images/user-interface/context-menu/delete.png) **Delete** from the context menu.

![Delete multiple items](../../images/user-interface/deleting-multiple-items.png)
