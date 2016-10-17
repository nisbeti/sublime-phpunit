# Sublime PHPUnit

Convenient Sublime Text commands for running your PHPUnit tests. Scans up the directory tree to find the closest phpunit.xml file and runs phpunit from there. If it can't find one, it just runs phpunit from `/`.

It can also open a matching PHPUnit test. For example, if the file you're testing is `Invoice.php`, it will search your tests folder for a file with a name of either `InvoiceTest.php` or `Invoice.php`.

Just `git clone` this repo into your `~/Library/Application Support/Sublime Text 3/Packages` directory and you're good to go.

You can find the commands in the command palette under "Sublime PHPUnit", or map any of these commands to whatever shortcuts you want:

```
run_phpunit_test
run_phpunit_tests_in_dir
run_single_phpunit_test
run_all_phpunit_tests
open_matching_test
```

By default, this package uses macOS's built-in Terminal.app. If you want to use iTerm, you can do so by setting `"phpunit-sublime-terminal": "iTerm"` in your settings.
