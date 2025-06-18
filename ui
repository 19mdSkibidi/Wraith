local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Eazvy/UILibs/main/Librarys/Elerium/Example.lua"))()

loadstring(game:HttpGet("https://raw.githubusercontent.com/19mdSkibidi/Wraith.lol/main/Wraith"))()

local win = lib:Window("Wraith Triggerbot")
local legitTab = win:Tab("Legit")

legitTab:Toggle("Triggerbot", function(bool)
    getgenv().Wraith.Legit.triggerbot.Enabled = bool
end, true)

legitTab:Toggle("Knife Check", function(bool)
    getgenv().Wraith.Legit.triggerbot.KnifeCheck = bool
end, true)

legitTab:Slider("X Prediction", 0, 1, 0.13, function(val)
    getgenv().Wraith.Legit.triggerbot.XPred = val
end)

legitTab:Slider("Y Prediction", 0, 1, 0.03, function(val)
    getgenv().Wraith.Legit.triggerbot.YPred = val
end)

legitTab:Slider("Click Radius", 0, 10, 3, function(val)
    getgenv().Wraith.Legit.triggerbot.Radius = val
end)
