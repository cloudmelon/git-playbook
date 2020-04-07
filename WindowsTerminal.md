# How to make my Windows Terminal better

add keybindings in profiles.json

``` shell
  "keybindings": [
        {
            "command" : "copy",
            "keys" :["ctrl+c"]
        },
        {
            "command" : "paste",
            "keys" : ["ctrl+v"]
        },
        {
            "command" : "find",
            "keys":["ctrl+f"]
        },
        {
            "command" : "closeTab",
            "keys" : ["ctrl+w"]
        },
        {
            "command" : "newTab",
            "keys" : ["ctrl+t"]
        },
        {
            "command": {
                "action": "splitPane",
                "split": "auto"
            },
            "keys":["ctrl+shift+t"]
        }
    ]
```

## References:

To know more about, please check at : https://aka.ms/terminal-profiles-schema
