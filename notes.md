# Coding Café Lab 1

## Questions

1. `pwd` printed `C:\Users\Pratham`, which is my current working directory.

2. `ls -Force` showed hidden items that were not displayed by the normal `ls` command. The `-Force` option makes PowerShell include hidden items in the listing.

3. The `Mode` column shows attributes of the item, including whether it is a directory or file.

4. `coding-cafe\week02` is a relative path because it starts from my current working directory rather than from the root of the drive.

5. The first `mv` moved a file from one directory to another. The second `mv` renamed a file within the same directory.

6. There are 12 folders on my PATH.

7. My Python executable is located at `C:\Users\Pratham\AppData\Local\Programs\Python\Python313\python.exe`.

8. Our Python paths are different because Python may have been installed in different locations on each computer.

9. PowerShell could not find `pyton` because there is no command with that name available through the PATH. The command is a typo, so the shell cannot find a matching executable.

10. `.venv` did not appear in the plain `ls` output because it is treated as a hidden item. The `-Force` option makes PowerShell display hidden items as well.

11. The prompt changed to include `(.venv)` at the beginning. This shows that the Python virtual environment has been activated.

12. The Python path changed from the original Python installation to `C:\Users\Pratham\coding-cafe\.venv\Scripts\python.exe`. This shows that activating the virtual environment changed the PATH so that the virtual environment's Python executable is found first.

13. The second list contains the `requests` package, which was not present in the first list. It also contains packages required by `requests` as dependencies.

14. Python now points back to `C:\Users\Pratham\AppData\Local\Programs\Python\Python313\python.exe`. Deactivating the virtual environment restored the previous PATH configuration.

15. The `-Recurse` option makes the command process the specified directory and its subdirectories recursively. It allows PowerShell to work through the entire folder structure instead of only the current directory.

16. Ctrl+C interrupts the current operation, while Ctrl+Z sends an end-of-input signal in the Windows terminal. In this exercise, Ctrl+C interrupted Python and Ctrl+Z ended the input session.

