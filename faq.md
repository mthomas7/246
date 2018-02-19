# Some frequent issues, feel free to add

* Typing in username and password every time
  * Open a shell (git menu, more, shell), then type `git config credential.helper store`

* RMarkdown
  - "object 'something' not found."
    - This is probably because the dataset isn't loaded into the RMarkdown document itself. When you import a dataset, you'll see a command run in the console (on the bottom left). Just copy that code into a code block, and it will load it.
  - "qplot not found"
    - If a command is not found, it is likely because the package isn't loaded into the RMarkdown document. Use `library(package)` or `require(package)` in a code block to get it loaded.
