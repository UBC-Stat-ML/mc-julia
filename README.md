# CANSSI Monte Carlo Workshop: Hands-on introduction to MCMC development in Julia

To render the tutorial files locally, first set the `QUARTO_JULIA` environment variable in your machine to the directory of your julia executive.

In windows

```         
   [Environment]::SetEnvironmentVariable("QUARTO_JULIA", "path\to\julia", "User")
```

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