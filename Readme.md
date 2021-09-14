## How to use this config. In MacOs

1.) Install nvim.
    `brew install nvim`

2.) Init the nvim config.
    ```
    mkdir -p $HOME/.config/ && cd $HOME/.config/ && git clone git@github.com:MrCoffey/neovim-config.git nvim
    ```

3.) Install the Plugins

    3.1) Open nvim `nvim`
    3.2) Run `:PlugInstall`

**NOTE:** You may have issues running the first time if you don't have python3 intalled.

```
brew install python3
/usr/local/bin/python3 -m venv venv
. venv/bin/activate
pip install pynvim
```

You also need update pynvim module.

```pip3 install --user --upgrade pynvim```
