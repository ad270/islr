# islr
ISLR Self-study

This repo supports my self-study of "An Introduction to Statisical Learning with Applications in R".

## Helpful Info
R Install - Windows 10, R-3.5.2

RStudio installs packages in a user library directory, which is synched to company file server. R then has issues locating the installed packages. To resolve this issue, move the packages to a local folder on the computer that is not synched:

`C:/My Data/R/win-library/3.5`

For RStudio to automatically recognize this new library, create a new user varaiable using the Control Panel:

`Control Panel > User Accounts`
`Change my environment variables > Add user varable`
`R_LIBS_USER = C:/Program Files/R/win-library/3.5`
