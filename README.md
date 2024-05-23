local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/RedzLibV5/main/Source.Lua"))()

local Window = redzlib:MakeWindow({
  Title = "Kapi Script Hub [Trial]",
  SubTitle = " Trial",
  SaveFolder = "Kapi Script Hub.lua"
})

local Tab = Window:MakeTab({Title = "Blox Fruit", Icon = "Home"})

local Button = Tab:AddButton({"Redz Hub(close Ui)", function()        
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
  -- Button Function
end})

local Button = Tab:AddButton({"Domadic Hub", function()           
loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
  -- Button Function
end})

local Button = Tab:AddButton({"Xero Hub", function()           
loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/main/main.lua"))()
  -- Button Function
end})

local Button = Tab:AddButton({"W-Azure", function()    
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  -- Button Function
end})

local Tab = Window:MakeTab({Title = "Cmds", Icon = ""})

local Button = Tab:AddButton({"Infinity Yield", function()         loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  -- Button Function
end})



local Tab = Window:MakeTab({Title = "Comming Soon", Icon = ""})
