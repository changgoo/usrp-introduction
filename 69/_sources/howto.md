# How to add your page

Now, its your turn to add your page.

* Fork the repository (click the fork button in the top-right corner from [the main repository](https://github.com/changgoo/usrp-introduction))

    ![fork](./fork.jpg)

* Clone the repository and change the directory.

    ```sh
    git clone git@github.com:_your_GitHub_id_/usrp-introduction.git
    cd usrp-introduction
    ```

* Create a branch for your changes.

    ```sh
    git checkout -b _your_branch_name_
    ```

* Navigate to the `docs/students` folder.

    ```sh
    cd docs/students
    ```

* Copy the `_template.md` file to `your_name.md`.

    ```sh
    cp _template.md your_name.md
    ```

* Edit `your_name.md` using your favorite editor. You can use `nano`, `vim`, `emacs`, or something else.

* Commit your changes.

    ```sh
    git add your_name.md
    git commit -m "commit message"
    ```

* Push the committed changes.

    If you do this for the first time in your branch, you need to do this:

    ```sh
    git push --set-upstream origin _your_branch_name_
    ```

    otherwise, you can simply do this.

    ```sh
    git push
    ```

* Create a pull request to `changgoo/usrp-introduction:master` for review and merging.
