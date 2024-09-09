# COMP3512-002 Labs

## troubleshooting

- If both ports (80 and 3306) aren't showing, open up a terminal and run these two commands in this order:
    1. **docker compose down**
    2. **docker compose up -d**

- If things are acting wonky, push all work that you don't want to lose, then try the following things - in order from least drastic to most drastic - stopping when things aren't wonky anymore:
    1. `Ctrl+Shift+P` > Reload Window
    2. `Ctrl+Shift+P` > Rebuild Container > Rebuild button (**Not the `Full Rebuild`!**)
    4. Delete the Codespace, then create a new one. (**Don't forget to push beforehand!**)