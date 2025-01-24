---
hidden: true
noIndex: true
---

# PHP

This is the build/run options settings for a PHP project.

<figure><img src="https://help.goorm.io/~gitbook/image?url=https%3A%2F%2F2181851870-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lq-Q9LciN1X9EABxGkt%252Fuploads%252FTOmoULMCAjWjog9PmptN%252Fimage.png%3Falt%3Dmedia%26token%3D6393e1f1-1675-4481-abf4-5c40a2334885&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=3aad508c&#x26;sv=2" alt=""><figcaption></figcaption></figure>

1. Index file - Set the path and name of the main file to run.
2. Log file path - Set the path to the log file.
3. Web viewer - Set where to show the run results in the browser (tab/new window)

**How can I see the results of running a file other than index.php?**

Since you have a test.php file, you can try one of the two methods below.

1. run the project and access https://\[projectURL]/test.php.
2. go to the top menu \[Project] - \[Build/Run Settings], select the test.php file from the \[Index File] item, and click \[OK] to save it.

Replace the existing execution command with `php -S 0.0.0.0:${current.using.port} -t ${current.project.path}` to `php -S 0.0.0.0:${current.using.port} ${php.set.main}.php`.

Run the project and connect to https://\[projectURL].
