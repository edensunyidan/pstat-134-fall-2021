# PSTAT 134/234 (Winter 2022)

### Troubleshooting
* If you run into an error, rename "pstat-134-fall-2021" directory to a different name. Then click on this [https://pstat134.lsit.ucsb.edu/](https://pstat134.lsit.ucsb.edu/) again to re-clone a fresh copy of the latest "pstat-134-fall-2021" repository. 

  `$ mv pstat-134-fall-2021 pstat-134-fall-2021-old`

* If you want to delete a directory on JupyterHub permanently, for example, "pstat-134-fall-2021-old", 
  ```
  $ cd pstat-134-fall-2021-old
  $ rm -Rf .git/refs/original
  $ rm -Rf .git/logs/
  $ git gc
  $ git prune --expire 
  $ cd ..
  $ mv -Rf pstat-134-fall-2021-old
  ```
* If you want to reload the template of an assignment without conflict with your current work, you can rename the current file name and click on the [nbgitpuller link](https://pstat134.lsit.ucsb.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fedensunyidan%2Fpstat-134-fall-2021&urlpath=tree%2Fpstat-134-fall-2021%2F&branch=public) to refresh.

### Resources
* Github (course material): [https://github.com/edensunyidan/pstat-134-fall-2021](https://github.com/edensunyidan/pstat-134-fall-2021)
* Jupyter notebook server: [https://pstat134.lsit.ucsb.edu](https://pstat134.lsit.ucsb.edu) ([nbgitpuller link](https://pstat134.lsit.ucsb.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fedensunyidan%2Fpstat-134-fall-2021&urlpath=tree%2Fpstat-134-fall-2021%2F&branch=public))
* Piazza (questions and discussions): [https://piazza.com/ucsb/fall2021/pstat134234](https://piazza.com/ucsb/fall2021/pstat134234)

