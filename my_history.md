  107  cd ejercicio_final/
  108  git lol
  109  git lol
  110  git bisect start
  111  giut status
  112  git status
  113  git bisect bad
  114  git lol
  115  git bisect good e1718be
  116  git bisect bad
  117  git bisect good
  118  git lol
  119  git reveret a076d22
  120  git revert a076d22
  121  git status
  122  git revert a076d22
  123  git commit -m "Archivos añadidos"
  124  git lol
  125  git revert a076d22
  126  git lol
  127  git checkout persona_info
  128  git checkout personal_info
  129  git checkout Personal_info
  130  git status
  131  git bisect reset
  132  git lol
  133  git checkout Personal_info
  134  git stash .
  135  git stash
  136  git checkout Personal_info
  137  git lol
  138  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  139  $ git clone https://github.com/angeljimenezs/ejercicio_final.git
  140  Cloning into 'ejercicio_final'...
  141  remote: Enumerating objects: 142, done.
  142  remote: Counting objects: 100% (142/142), done.
  143  remote: Compressing objects: 100% (86/86), done.
  144  remote: Total 142 (delta 26), reused 134 (delta 20), pack-reused 0
  145  Receiving objects: 100% (142/142), 105.93 KiB | 570.00 KiB/s, done.
  146  Resolving deltas: 100% (26/26), done.
  147  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  148  $ history -c
  149  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  150  $ git cd
  151  PiedraPapelTijera/ holamundo.php      prueba2.php
  152  ejercicio_final/   prueba.php         test.php
  153  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  154  $ git cd
  155  PiedraPapelTijera/ holamundo.php      prueba2.php
  156  ejercicio_final/   prueba.php         test.php
  157  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  158  $ git cd ejercicio_final/
  159  git: 'cd' is not a git command. See 'git --help'.
  160  The most similar commands are
  161          ck
  162          cm
  163  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  164  $ history -c
  165  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps
  166  $ cd ejercicio_final/
  167  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  168  $ git lol
  169  * c89a2e5 (HEAD -> master, origin/master, origin/HEAD) Update Readme.md
  170  * f51f6ce fix ins
  171  * 9fac607 instr
  172  * 2b88e49 xml change it
  173  * fb2780a new xml
  174  * a076d22 updating paths
  175  * ad86f59 adding new java file new features added
  176  * 1729ae7 adding android project Addign complete memory game
  177  | * 98d5498 (origin/git_github) fix ins
  178  | * 098d4b5 fix ins
  179  | * 65e6f22 fix ins
  180  |/
  181  | * f86347f (origin/SCRUM) fix ins
  182  | * 17b5dff fix ins
  183  | * cc31d8b fix ins
  184  | * e8a8075 fix ins
  185  |/
  186  | * 201af0f (origin/Personal_info) fix ins
  187  | * 53eda0a fix ins
  188  | * a70de78 fix ins
  189  | * 5a78a7b fix ins
  190  | * e9ee36d instrucciones
  191  |/
  192  | * 8ce89d8 (origin/Android) fix ins
  193  | * 83470f0 fix ins
  194  | * b90f984 fix ins
  195  |/
  196  * e1718be first commit adding new empty file
  197  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  198  $ git bisect start
  199  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master|BISECTING)
  200  $ git branch
  201  * master
  202  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master|BISECTING)
  203  $ git bisect bad
  204  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master|BISECTING)
  205  $ git good e1718be
  206  git: 'good' is not a git command. See 'git --help'.
  207  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master|BISECTING)
  208  $ git bisect good e1718be
  209  Bisecting: 3 revisions left to test after this (roughly 2 steps)
  210  [fb2780a55ee02a1408bca1b3d1b75d96d7618cb2] new xml
  211  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((fb2780a...)|BISECTING)
  212  $ git bisect bad
  213  Bisecting: 1 revision left to test after this (roughly 1 step)
  214  [ad86f596203037156bd84c8e8df4ee4657434a66] adding new java file new features added
  215  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((ad86f59...)|BISECTING)
  216  $ git lol
  217  * c89a2e5 (origin/master, origin/HEAD, master) Update Readme.md
  218  * f51f6ce fix ins
  219  * 9fac607 instr
  220  * 2b88e49 xml change it
  221  * fb2780a (refs/bisect/bad) new xml
  222  * a076d22 updating paths
  223  * ad86f59 (HEAD) adding new java file new features added
  224  * 1729ae7 adding android project Addign complete memory game
  225  | * 98d5498 (origin/git_github) fix ins
  226  | * 098d4b5 fix ins
  227  | * 65e6f22 fix ins
  228  |/
  229  | * f86347f (origin/SCRUM) fix ins
  230  | * 17b5dff fix ins
  231  | * cc31d8b fix ins
  232  | * e8a8075 fix ins
  233  |/
  234  | * 201af0f (origin/Personal_info) fix ins
  235  | * 53eda0a fix ins
  236  | * a70de78 fix ins
  237  | * 5a78a7b fix ins
  238  | * e9ee36d instrucciones
  239  |/
  240  | * 8ce89d8 (origin/Android) fix ins
  241  | * 83470f0 fix ins
  242  | * b90f984 fix ins
  243  |/
  244  * e1718be (refs/bisect/good-e1718be40f3b708ac17954ccb04e7f9d6431d3e5) first commit adding new empty file
  245  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((ad86f59...)|BISECTING)
  246  $ git checkout 83470f0
  247  Previous HEAD position was ad86f59 adding new java file new features added
  248  HEAD is now at 83470f0 fix ins
  249  A       .idea/vcs.xml
  250  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((83470f0...)|BISECTING)
  251  $ git bisect good b90f984
  252  Bisecting: 1 revision left to test after this (roughly 1 step)
  253  [ad86f596203037156bd84c8e8df4ee4657434a66] adding new java file new features added
  254  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((ad86f59...)|BISECTING)
  255  $ git checkout 1729ae7
  256  Previous HEAD position was ad86f59 adding new java file new features added
  257  HEAD is now at 1729ae7 adding android project Addign complete memory game
  258  A       .idea/vcs.xml
  259  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((1729ae7...)|BISECTING)
  260  $ git checkout 2b88e49
  261  Previous HEAD position was 1729ae7 adding android project Addign complete memory game
  262  HEAD is now at 2b88e49 xml change it
  263  A       .idea/vcs.xml
  264  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((2b88e49...)|BISECTING)
  265  $ git checkout HEAD
  266  A       .idea/vcs.xml
  267  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((2b88e49...)|BISECTING)
  268  $ git lol
  269  * c89a2e5 (origin/master, origin/HEAD, master) Update Readme.md
  270  * f51f6ce fix ins
  271  * 9fac607 instr
  272  * 2b88e49 (HEAD) xml change it
  273  * fb2780a (refs/bisect/bad) new xml
  274  * a076d22 updating paths
  275  * ad86f59 adding new java file new features added
  276  * 1729ae7 adding android project Addign complete memory game
  277  | * 98d5498 (origin/git_github) fix ins
  278  | * 098d4b5 fix ins
  279  | * 65e6f22 fix ins
  280  |/
  281  | * f86347f (origin/SCRUM) fix ins
  282  | * 17b5dff fix ins
  283  | * cc31d8b fix ins
  284  | * e8a8075 fix ins
  285  |/
  286  | * 201af0f (origin/Personal_info) fix ins
  287  | * 53eda0a fix ins
  288  | * a70de78 fix ins
  289  | * 5a78a7b fix ins
  290  | * e9ee36d instrucciones
  291  |/
  292  gi
  293  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((2b88e49...)|BISECTING)
  294  $ git bisect reset
  295  Previous HEAD position was 2b88e49 xml change it
  296  Switched to branch 'master'
  297  A       .idea/vcs.xml
  298  Your branch is up to date with 'origin/master'.
  299  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  300  $ git lol
  301  * c89a2e5 (HEAD -> master, origin/master, origin/HEAD) Update Readme.md
  302  * f51f6ce fix ins
  303  * 9fac607 instr
  304  * 2b88e49 xml change it
  305  * fb2780a new xml
  306  * a076d22 updating paths
  307  * ad86f59 adding new java file new features added
  308  * 1729ae7 adding android project Addign complete memory game
  309  | * 98d5498 (origin/git_github) fix ins
  310  | * 098d4b5 fix ins
  311  | * 65e6f22 fix ins
  312  |/
  313  | * f86347f (origin/SCRUM) fix ins
  314  | * 17b5dff fix ins
  315  | * cc31d8b fix ins
  316  | * e8a8075 fix ins
  317  |/
  318  | * 201af0f (origin/Personal_info) fix ins
  319  | * 53eda0a fix ins
  320  | * a70de78 fix ins
  321  | * 5a78a7b fix ins
  322  | * e9ee36d instrucciones
  323  |/
  324  | * 8ce89d8 (origin/Android) fix ins
  325  | * 83470f0 fix ins
  326  | * b90f984 fix ins
  327  |/
  328  * e1718be first commit adding new empty file
  329  gi
  330  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  331  $ git checkout ad86f59
  332  Note: switching to 'ad86f59'.
  333  You are in 'detached HEAD' state. You can look around, make experimental
  334  changes and commit them, and you can discard any commits you make in this
  335  state without impacting any branches by switching back to a branch.
  336  If you want to create a new branch to retain commits you create, you may
  337  do so (now or later) by using -c with the switch command. Example:
  338    git switch -c <new-branch-name>
  339  Or undo this operation with:
  340    git switch -
  341  Turn off this advice by setting config variable advice.detachedHead to false
  342  HEAD is now at ad86f59 adding new java file new features added
  343  A       .idea/vcs.xml
  344  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((ad86f59...))
  345  $ git checkout fb2780a
  346  Previous HEAD position was ad86f59 adding new java file new features added
  347  HEAD is now at fb2780a new xml
  348  A       .idea/vcs.xml
  349  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((fb2780a...))
  350  $ git checkout a076d22
  351  Previous HEAD position was fb2780a new xml
  352  HEAD is now at a076d22 updating paths
  353  A       .idea/vcs.xml
  354  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((a076d22...))
  355  $ git revert a076d22 updating paths
  356  fatal: bad revision 'updating'
  357  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((a076d22...))
  358  $ git status
  359  HEAD detached at a076d22
  360  Changes to be committed:
  361    (use "git restore --staged <file>..." to unstage)
  362          new file:   .idea/vcs.xml
  363  Changes not staged for commit:
  364    (use "git add <file>..." to update what will be committed)
  365    (use "git restore <file>..." to discard changes in working directory)
  366          modified:   .idea/vcs.xml
  367  Untracked files:
  368    (use "git add <file>..." to include in what will be committed)
  369          .idea/.name
  370  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final ((a076d22...))
  371  $ git checkout master
  372  Previous HEAD position was a076d22 updating paths
  373  Switched to branch 'master'
  374  A       .idea/vcs.xml
  375  Your branch is up to date with 'origin/master'.
  376  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  377  $ git lol
  378  * c89a2e5 (HEAD -> master, origin/master, origin/HEAD) Update Readme.md
  379  * f51f6ce fix ins
  380  * 9fac607 instr
  381  * 2b88e49 xml change it
  382  * fb2780a new xml
  383  * a076d22 updating paths
  384  * ad86f59 adding new java file new features added
  385  * 1729ae7 adding android project Addign complete memory game
  386  | * 98d5498 (origin/git_github) fix ins
  387  | * 098d4b5 fix ins
  388  | * 65e6f22 fix ins
  389  |/
  390  | * f86347f (origin/SCRUM) fix ins
  391  | * 17b5dff fix ins
  392  | * cc31d8b fix ins
  393  | * e8a8075 fix ins
  394  |/
  395  | * 201af0f (origin/Personal_info) fix ins
  396  | * 53eda0a fix ins
  397  | * a70de78 fix ins
  398  | * 5a78a7b fix ins
  399  | * e9ee36d instrucciones
  400  |/
  401  | * 8ce89d8 (origin/Android) fix ins
  402  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  403  $ git revert a076d22
  404  error: your local changes would be overwritten by revert.
  405  hint: commit your changes or stash them to proceed.
  406  fatal: revert failed
  407  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  408  $ ls
  409  Readme.md  build.gradle  gradle.properties  gradlew.bat       settings.gradle
  410  app/       gradle/       gradlew*           local.properties
  411  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  412  $ git status
  413  On branch master
  414  Your branch is up to date with 'origin/master'.
  415  Changes to be committed:
  416    (use "git restore --staged <file>..." to unstage)
  417          new file:   .idea/vcs.xml
  418  Changes not staged for commit:
  419    (use "git add <file>..." to update what will be committed)
  420    (use "git restore <file>..." to discard changes in working directory)
  421          modified:   .idea/vcs.xml
  422  Untracked files:
  423    (use "git add <file>..." to include in what will be committed)
  424          .idea/.name
  425  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  426  $ git add .
  427  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  428  $ git status
  429  On branch master
  430  Your branch is up to date with 'origin/master'.
  431  Changes to be committed:
  432    (use "git restore --staged <file>..." to unstage)
  433          new file:   .idea/.name
  434          new file:   .idea/vcs.xml
  435  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  436  $ git revert a076d22
  437  error: your local changes would be overwritten by revert.
  438  hint: commit your changes or stash them to proceed.
  439  fatal: revert failed
  440  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  441  $ git stash
  442  Saved working directory and index state WIP on master: c89a2e5 Update Readme.md
  443  halo_@LAPTOP-806FK5PI MINGW64 ~/Desktop/DevOps/ejercicio_final (master)
  444  $ git lol
  445  *   b4738e2 (refs/stash) WIP on master: c89a2e5 Update Readme.md
  446  || * 7dfc4c9 index on master: c89a2e5 Update Readme.md
  447  |/
  448  * c89a2e5 (HEAD -> master, origin/master, origin/HEAD) Update Readme.md
  449  * f51f6ce fix ins
  450  * 9fac607 instr
  451  * 2b88e49 xml change it
  452  * fb2780a new xml
  453  * a076d22 updating paths
  454  * ad86f59 adding new java file new features added
  455  * 1729ae7 adding android project Addign complete memory game
  456  | * 98d5498 (origin/git_github) fix ins
  457  | * 098d4b5 fix ins
  458  | * 65e6f22 fix ins
  459  |/
  460  | * f86347f (origin/SCRUM) fix ins
  461  | * 17b5dff fix ins
  462  | * cc31d8b fix ins
  463  | * e8a8075 fix ins
  464  |/
  465  | * 201af0f (origin/Personal_info) fix ins
  466  | * 53eda0a fix ins
  467  | * a70de78 fix ins
  468  history
  469  history
  470  git checkout Personal_info
  471  git lol
  472  git rebase SCRUM
  473  git add .
  474  git commit -m "Se contesto parte 4"
  475  git rebase SCRUM
  476  git rebase --skip
  477  git rebase --continue
  478  git status
  479  git rebase --skip
  480  git rebase --continue
  481  git add .
  482  git rebase --continue
  483  git rebase --skip
  484  git lol
  485
  486  git status
  487  git checkout Android
  488  echo Parte5 ******************************************************
  489  git merge git_github
  490  git statu
  491  git status
  492  git add .
  493  git status
  494  git add .
  495  git lol
  496  git checkout master
  497  git commit -m "Se juntan rama git_github con Android"
  498  git lol
  499  git checkout master
  500  history
  501  git merge Android
  502  git add .
  503  git commit -m "Se junto el exodia"
  504  git push -u origin master
  505  git touch my_history.md
  506  touch my_history.md
  507  history
