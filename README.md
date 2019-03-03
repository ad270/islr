# islr
ISLR Self-study

This repo supports my self-study of *An Introduction to Statisical Learning with Applications in R*.

## Helpful Info
R Install - Windows 10, R-3.5.2

#### Setting libRefs using R_LIBS_USER environment variable
RStudio installs packages in a user library directory, which is synched to company file server. R then has issues locating the installed packages. To resolve this issue, create a local folder on the computer such as `C:/My Data/R/win-library/3.5` and install the packages to new location.

For RStudio to automatically recognize this new library, create a new user varaiable using the Control Panel:

```
Control Panel > User Accounts
Change my environment variables > Add user varable
R_LIBS_USER = C:/My Data/R/win-library/3.5
```
