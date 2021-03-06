---
layout: docs
title: Organize Tests
permalink: /documentation/guides/organize-tests.html
---
# Organize Tests

This topic provides information on how to organize your test files.

* [Test Directory](#test-directory)
* [Recorded Tests Files](#recorded-tests-files)
* [Coded Tests Files](#coded-tests-files)

The image below demonstrates the [Explorer](../user-interface/explorer-panel.md) panel that allows you to manage your test files.

![Explorer panel](../../images/guides/explorer-panel.png)

## Test Directory

A test directory is a file system directory used as the root of your test-related workspace. It is used to store files with [recorded](#recorded-tests-files) and [coded](#coded-tests-files) tests.

You can create a test directory anywhere on your computer and then open it in TestCafe Studio in one of the following ways:

* Go to the **File** menu and click **Open Test Directory**.
* On the **Welcome** page, click **Open Folder**.

The **Explorer** panel displays the directory's content.

> TestCafe Studio automatically creates a test directory in the *Users/Username/TestCafeStudio* folder and gives it the tested site's name if you start recording a test from the **Welcome** page. If a directory with the same name already exists, TestCafe Studio opens it and adds a new test to it.

You can also organize test files into *subdirectories*. To create a subdirectory, right-click a test directory in the **Explorer** panel and select **New Directory**. In the **New directory** dialog, enter the directory name and click the **Create** button.

## Recorded Tests Files

**Recorded tests** are tests you record visually or compose from test actions. These tests are stored in `*.testcafe` files. TestCafe Studio automatically creates a new `*.testcafe` file when you [start recording a test](record-tests/README.md#starting-and-stopping-recording) for a new tested page.

The `.testcafe` test file can contain one or more recorded tests. The **Explorer** panel displays these tests as the `.testcafe` file's child items.

![Recorded tests](../../images/guides/recorded-tests.png)

See [Record Tests](record-tests/README.md) for information on how to record tests.

## Coded Tests Files

TestCafe Studio also allows you to write tests in JavaScript or TypeScript. Create a `.js` or `.ts` file in a test directory, open this file in a built-in [Code Editor](../user-interface/code-editor.md) and [write test code](write-test-code.md).

The **Explorer** panel displays tests included to a `.js` or `.ts` file as the file's child items.

![Coded tests](../../images/guides/coded-tests.png)

> TestCafe Studio also allows you to use tests created in an earlier TestCafe version (`.test.js` files). You can add these files to a test directory and view/modify/run the tests from TestCafe Studio.
