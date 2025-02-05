local Mercury = loadstring(game:HttpGet("https://raw.githubusercontent.com/deeeity/mercury-lib/master/src.lua"))()

local GUI = Mercury:Create{
    Name = "Zenith Hub",
    Size = UDim2.fromOffset(600, 400),
    Theme = Mercury.Themes.Dark,
    Link = "https://github.com/deeeity/mercury-lib"
}

local Tab = GUI:Tab{
    Name = "Main",
    Icon = "rbxassetid://8569322835"
}

Tab:Button{
    Name = "Admin",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))()
    end
}

Tab:Button{
    Name = "Infinite Yield",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
    end
}

-- Terms of Service Prompt
GUI:Prompt{
    Followup = false,
    Title = "Agree to Terms of Service",
    Text = [[
    By using this script, you agree to the following terms ]],
    Buttons = {
        agree = function()
            return true
        end,
        decline = function()
            return false
        end
    }
}


Tab:Button{
    Name = "Ghost Hub",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
    end
}


Tab:Button{
    Name = "Dev Products",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-free-gamepass-or-dev-products-12996"))()
    end
}

Tab:Button{
    Name = "Simple Spy",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RealSilentx/SimplySpy/main/.lua"))()
    end
}

Tab:Button{
    Name = "Dex Explorer",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/DEX-Explorer/main/Mobile.lua"))()
    end
}

local Tab = GUI:Tab{
	Name = "Scripts",
	Icon = "rbxassetid://8569322835"
}

Tab:Button{
    Name = "Emotes",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
    end
}

Tab:Button{
    Name = "Drop",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RealSilentx/Test4/refs/heads/main/Droptools"))()
    end
}

Tab:Button{
    Name = "FE Animation",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Animation-Script-17639"))()
    end
}

Tab:Button{
    Name = "Hook",
    Description = nil,
    Callback = function() 
        if hookfunction then
            -- Hook the print function to do nothing
            local old_print = print
            hookfunction(print, function(...)
                -- Do nothing, effectively blocking print statements
            end)

            -- Hook the warn function to do nothing
            local old_warn = warn
            hookfunction(warn, function(...)
                -- Do nothing, blocking warn outputs
            end)

            -- Hook the error function to do nothing
            local old_error = error
            hookfunction(error, function(...)
                -- Do nothing, blocking error outputs
            end)
        else
            -- Notify that the executor doesn't support hookfunction
            old_print("Your executor doesn't support hookfunction.")
        end
    end
}

Tab:Button{
    Name = "Spy Chat",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Chat-spy-3000"))()
    end
}

Tab:Button{
    Name = "Ghost Animation",
    Description = nil,
    Callback = function() 
        loadstring(game:HttpGet('https://pastefy.app/S7xNJSXX/raw'))()execute("Script9")
    end
}

local Tab = GUI:Tab{
	Name = "Hubs",
	Icon = "rbxassetid://8569322835"
}
