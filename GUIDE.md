# UI-LIB GUIDING PAGE

Step 1:
`Install The Core-Module`

```
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/DEV-OceanMan/Library/main/CoreHolderTestVersion", true))()
```

Step 2:
`Load The Core-Module`

```
local Main = Library:CreateMain()
```

Step 3:
`Read the functions manual and we are done!`



# FUNCTIONS

Add Tab(s):

```
local Tab1 = Library:NewTab( <string> )
```

Add Button(s):

```
local Button = Library:NewButton( <string> or <number> , <string>, function(Button)
-- Function
end)
```

Add Toggle(s):

```
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
