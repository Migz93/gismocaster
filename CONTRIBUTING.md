You are welcome to do PR to enhance GismoCaster. In general PR's should be targeted at the development or a feature branch.

Branch structure
---------------
```
master ---v1.1.0---------------------------|--v1.1.1--|--v1.2.0------->
              \        \----- hotfix -----/           /\
development ---\--v1.2.0--------------------|--------/  \-v1.3.0------>
                       \----- feature -----/
```

Branch names
-----------------
* `hotfix/<issue>`        In commit mention github issue number (eg #123)
* `feature/<enhancement>` In commit mention github issue number (eg #123)

Version numbers
-----------------
```
 +---------- Major: Can break compatibility
 | +-------- Minor: Enhancement of master, must be compatible 
 | |                with other versions within major version
 | | +------ Fix:   Bugfix on master branch
 | | |
v1.2.1
```

Code quality
-----------------
#TODO: describe
- flake8
- black
- mypi