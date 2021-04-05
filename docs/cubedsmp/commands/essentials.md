To properly play and utilize the features available on our survival multiplayer server, you should be using the commands we offer you.
We have listed all the commands accessible by any normal user on our survival multiplayer server.
For our staff team, please refer to the handbook for your unique commands list.
## /balance
States the current balance of a player.
### Syntax
```
/balance [player]
```
### Parameters
- **player** - (optional) Check the balance of players other than you.
???+ example
    ```
    /balance Notch
    ```
    
    **Result:**
    
    
    Shows the balance of the player Notch.
## /balancetop
Lists players by top balances.
### Syntax
```
/balancetop [page]
```
### Parameters
- **page** - (optional) Lists top balances by page number.
???+ example
    ```
    /balancetop 1
    ```
    
    **Result:**
    
    Shows the first out of X amount of pages for the balance leaderboards.
## /clearinventory
Clear all items in your inventory.
### Syntax
```
/clearinventory [item:data/*/**] [amount]
```
### Parameters
- **item** - (optional) Define specific items to remove.
- **item:data** - (optional) Give a specific item ID to remove.
- **amount** - (optional) If specific item is specificed, how many of those items should be removed.
???+ example
    ```
    /clearinventory
    ```
    
    **Result:**
    
    Clears your entire inventory.
## /clearinventoryconfirmtoggle
Toggles whether you are prompted to confirm inventory clears.
### Syntax
```
/clearinventoryconfirmtoggle
```
???+ example
    ```
    /clearinventoryconfirmtoggle
    ```
    
    **Result:**
    
    Toggles the requirement for confirmation when running /clearinventory
## /delhome
Removes a home.
### Syntax
```
/delhome <name>
```
### Parameters
- **name** - Define a home name to remove.
???+ example
    ```
    /delhome balcony
    ```
    
    **Result:**
    
    Removes the home named "balcony".
## /disposal
Opens a portable disposal menu.
### Syntax
```
/disposal
```
???+ example
    ```
    /disposal
    ```
    
    **Result:**
    
    Opens the portable disposal menu.
## /exp show
Look at a player's exp.
### Syntax
```
/exp show <playername>
```
### Parameters
- **playername** - Define a player name to inspect.
???+ example
    ```
    /exp show Notch
    ```
    
    **Result:**
    
    Show information regarding Notch's exp.
## /hat
Sets your currently held item as your helmet.
### Syntax
```
/hat [remove]
```
### Parameters
- **remove** - (optional) Add "remove" to remove current hat.
???+ example
    ```
    /hat
    ```
    
    **Result:**
    
    Sets your currently held item as a hat.
## /helpop
Message online staff members.
### Syntax
```
/helpop <message>
```
### Parameters
- **message** - The message you want to send in.
???+ example
    ```
    /helpop I'm stuck in this block.
    ```
    
    **Result:**
    
    Messages all online staff for assistance with the message "I'm stuck in this block."
## /home
Teleport to your home.
### Syntax
```
/home <name>
```
### Parameters
- **name** - Define a home name to remove.
???+ example
    ```
    /home shop
    ```
    
    **Result:**
    
    Teleports you to the home named "shop".
## /list
List all online players.
### Syntax
```
/list
```
???+ example
    ```
    /list
    ```
    
    **Result:**
    
    List all online players.
## /msg
Sends a private message to the specified player.
### Syntax
```
/msg <name> <message>
```
### Parameters
- **name** - Define a player name to contact.
- **message** - Your message you want to send.
???+ example
    ```
    /msg Notch Hey!
    ```
    
    **Result:**
    
    Messages the user "Notch" with the message "Hey!".
## /msgtoggle
Blocks receiving all private messages.
### Syntax
```
/msgtoggle [player] [on/off]
```
### Parameters
- **player** - (optional) Define a player name to block.
- **on/off** - (optional) Specify a specific block status.
???+ example
    ```
    /msgtoggle
    ```
    
    **Result:**
    
    Blocks all incoming private messages.
## /pay
Pays another player from your balance.
### Syntax
```
/pay <player> <amount>
```
### Parameters
- **player** - Define a player name to pay.
- **amount** - Specify a specific money amount to pay.
???+ example
    ```
    /pay Notch 1000
    ```
    
    **Result:**
    
    Pays the user "Notch" $1000 in-game.
## /payconfirmtoggle
Toggles whether you are prompted to confirm payments.
### Syntax
```
/payconfirmtoggle
```
???+ example
    ```
    /payconfirmtoggle
    ```
    
    **Result:**
    
    Toggles the requirement for confirmation when running /pay.
## /paytoggle
Toggles whether you are accepting payments.
### Syntax
```
/paytoggle
```
???+ example
    ```
    /paytoggle
    ```
    
    **Result:**
    
    Toggles whether you can receive payments or not.
## /realname
Displays the username of a user based on nick.
### Syntax
```
/realname <nickname>
```
### Parameters
- **nickname** - The nickname of an online player.
???+ example
    ```
    /nickname Real_Notch
    ```
    
    **Result:**
    
    Shows the real username of the player nicked as "Real_Notch".
## /rules
Views the server rules.
### Syntax
```
/rules [chapter] [page]
```
### Parameters
- **chapter** - (optional) Pick a specific chapter of the server rules.
- **page** - (optional) Pick a specific page of the server rules.
???+ example
    ```
    /rules
    ```
    
    **Result:**
    
    Shows the first page of the server rules.
## /seen
Shows the last logout time of a player.
### Syntax
```
/seen <playername>
```
### Parameters
- **playername** - Define a username for your lookup.
???+ example
    ```
    /seen Notch
    ```
    
    **Result:**
    
    Shows when the user "Notch" was last online.
## /sethome
Set home to your current location.
### Syntax
```
/sethome <name>
```
### Parameters
- **name** - Define a name for your home location.
???+ example
    ```
    /sethome Farm
    ```
    
    **Result:**
    
    Sets your current position to a home called "Farm".
## /tpa
Request to teleport to the specified player.
### Syntax
```
/tpa <player>
```
### Parameters
- **player** - Define a username for your teleport request.
???+ example
    ```
    /tpa Notch
    ```
    
    **Result:**
    
    Sends a teleport request to the player "Notch".
## /tpaall
Requests all players online to teleport to you.
### Syntax
```
/tpaall
```
???+ example
    ```
    /tpaall
    ```
    
    **Result:**
    
    Sends a teleport to your location request to all online players.
## /tpacancel
Cancel all outstanding teleport requests.
### Syntax
```
/tpacancel [player]
```
### Parameters
- **player** - (optional) Define a username to cancel your teleport request to.
???+ example
    ```
    /tpacancel Notch
    ```
    
    **Result:**
    
    Cancels your teleport request to the user "Notch".
## /tpaccept
Accepts a teleport request.
### Syntax
```
/tpaccept [player]
```
### Parameters
- **player** - (optional) Define a username to accept a teleport request from.
???+ example
    ```
    /tpaccept Notch
    ```
    
    **Result:**
    
    Accepts the teleport request from the user "Notch".
## /tpahere
Request that the specified player teleport to you.
### Syntax
```
/tpahere <player>
```
### Parameters
- **name** - Define a username for your teleport request.
???+ example
    ```
    /tpahere Notch
    ```
    
    **Result:**
    
    Sends a teleport to your location request to all online players.
## /whois
Displays player information.
### Syntax
```
/whois <nickname/playername>
```
### Parameters
- **nickname/playername** - Define a username or nickname for your lookup.
???+ example
    ```
    /whois Notch
    ```
    
    **Result:**
    
    Shows player information about the user "Notch".