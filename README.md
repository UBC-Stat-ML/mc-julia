# CANSSI Monte Carlo Workshop: Hands-on introduction to MCMC development in Julia

To render the tutorial files locally, first set the `QUARTO_JULIA` environment variable in your machine to the directory of your julia executable path. Note that you can find this path by running the following command in your julia REPL

```
    Base.julia_cmd()[1]
```

In windows, run the following command

```         
   [Environment]::SetEnvironmentVariable("QUARTO_JULIA", "path\to\julia", "User")
```
here `"path\to\julia"` is the output to the julia code above.

In Mac/Linux, open `.zprofile`

```         
    nano ~/.zprofile
```

or `.bash_profile`

```         
    nano ~/.bash_profile
```

then add the `export` command

```         
    export QUARTO_JULIA = "path\to\julia"
```

then save and exit.

After setting `QUARTO_JULIA`, close and reopen the application you render on (e.g. VSCode or RStudio) for the change to take effect. Now the `qmd` files should render correctly.