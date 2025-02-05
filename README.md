local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("SECRET HUB", "DarkTheme")
 
local Tab = Window:NewTab("Elixir Hub")
 
local Section = Tab:NewSection("First Section")
Section:NewButton("Neva Hub", "Blox Fruits!", function()
 
loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
 
print("Clicked")
end)
