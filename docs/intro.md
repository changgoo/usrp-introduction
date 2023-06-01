# Introduction

```{tableofcontents}
```

## How to add your page

Now, its your turn to add your page.

* Clone the repository and change the directory.

    ```sh
    $ git clone git@github.com:changgoo/usrp2023.git
    $ cd usrp2023
    ```

* Create a branch for your changes.

    ```sh
    $ git checkout -b _your_branch_name_
    ```

* Navigate to the `docs/students` folder.

    ```sh
    $ cd usrp2023/docs/students
    ```

* Copy the `template.md` file to `your_name.md`.

    ```sh
    $ cp ../template.md your_name.md
    ```

* Edit `your_name.md` using your favorite editor. You can use `nano`, `vim`, `emacs`, or something else.

* Commit your changes.

    ```sh
    $ git add your_name.md
    $ git commit -m "commit message"
    ```

* Push the committed changes.

    If you do this for the first time in your branch, you need to do this:

    ```sh
    $ git push --set-upstream origin _your_branch_name_
    ```

    otherwise, you can simply do this.

    ```sh
    $ git push
    ```

* Create a pull request for review and merging.
