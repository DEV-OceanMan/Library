# WARNING
`THIS LOGS HWID, IP, AND INFO ABOUT YOUR ROBLOX CHARACTER YOU HAVE BEEN WARNED PROCEED WITH YOUR OWN RISK.`

# UI-LIB GUIDING PAGE

Step 1:
`Install The Core-Module`

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Unknown-publisher/Library/main/CoreHandler", true))()
```

Step 2:
`Load The Core-Module`

```lua
local Main = Library:CreateMain()
```

Step 3:
`Read the functions manual and we are done!`



# FUNCTIONS

Add Tab(s):

```lua
local Tab1 = Library:NewTab( <string> )
```

Add Button(s):

```lua
local Button = Library:NewButton( <string> or <number> , <string>, function(Button)
-- Function
end)
```

Add Toggle(s):

```lua
local Toggle = Library:NewToggle( <string> or <number>, <string>, function(Toggle)
    local toggleFunctions = {
        on = function()
            -- Function 1
        end,
        
        off = function()
            -- Function 2
        end,
    }
    return toggleFunctions
end)
end)
```

# EXAMPLE

End Result:

```lua
pcall(function()
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Unknown-publisher/Library/main/CoreHandler", true))()

local Main = Library:CreateMain()

local Tab1 = Library:NewTab("Title")

local Button = Library:NewButton("Tab1", "Title", function(Button)
print("BABABOE")
end)

local Toggle = Library:NewToggle("Tab1", "Title", function(Toggle)
    local toggleFunctions = {
        on = function()
            print("BABABOE")
        end,
        
        off = function()
            print("BABABRUH")
        end,
    }
    return toggleFunctions
end)
end)
```
