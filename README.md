## RStudio Connect Jumpstart Examples

This repository contains **a copy** of the JumpStart Examples in RStudio Connect.

The examples were run with a CRAN snapshot June 28, 2020 using **R 4.0.2** and **Python 3.7.3**.

Each example includes a manifest file, to deploy the examples to RStudio Connect:

**Your RStudio Connect server will need the correct versions of R and Python available**

1. On the Connect homepage, click the *Publish* dropdown and select *Import from Git*

2. Enter the repository URL: `https://github.com/rstudio/connect-examples`

3. Select *main* from the branch drop down

4. Pick the corresponding folder for the example you want to deploy and enter a name

Note that the `pins-tutorial` and `stock-import` examples will require setting an API key before the reports will render correctly. All other content should deploy and render or run automatically.



