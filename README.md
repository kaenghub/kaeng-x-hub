local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("kaeng x hub", "Midnight")
local Tab = Window:NewTab("main menu")
local Section = Tab:NewSection("bloxfruit")
Section:NewButton("บอกฟุต", "สคริปบอกฟุต", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Omgshit/Scripts/main/MainLoader.lua"))()
end)
---------------------------------------------------------------------------------------------------

local Tab = Window:NewTab("admin")
local adminSection = Tab:NewadminSection("admin")
Section:NewButton("admin", "พลังเเอดมิน", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
------------------------------------------------------------------------------------------------
local Tab = Window:NewTab("blade  ball")
local Section = Tab:Newblade ballSection("blade ball")
Section:NewButton("blade ball", "blade ball", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Rylvns/EnvisionExploits/master/game-scripts/Blade%20Ball/source.lua"))();
end)
