# Clink and oh-my-posh Config

> My terminal configuration files

This is my Windows terminal config. I am looking to add my Linux config in time.

# Install

-   Clink: https://github.com/clink-dev/clink/releases
-   oh-my-posh: https://ohmyposh.dev

# Clink Configuration

-   Navigate to `C:\Program Files (x86)\clink`
    -   Clink might be in a different dir for you.
    -   Use `clink info` and navigate to the directory linked to `binaries`.
-   In the "clink" folder, create file `oh-my-posh.lua`
-   Open `oh-my-posh.lua` and add the following:

```shell
load(io.popen('oh-my-posh init cmd --config C:/Users/<user>/AppData/Local/Programs/oh-my-posh/themes/catppuccin_frappe.omp.json'):read("*a"))()
```

-   Replace \<user\> with your username.

# oh-my-posh Configuration

-   Copy the `catppuccin_frappe.omp.json` file to `C:/Users/<user>/AppData/Local/Programs/oh-my-posh/themes/` (replacing \<user\> with your username)
