local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Kapi Hub V0.3", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest", IntroText = "Kapi Script Hub"})

local Tab = Window:MakeTab({
	Name = "Blox Fruit",
	Icon = "",
	PremiumOnly = false
})

OrionLib:MakeNotification({
	Name = "Kapi Script Hub",
	Content = "This are beta version",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
      		print("button pressed")                 loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
  	end    
})

Tab:AddButton({
	Name = "Domadic Hub",
	Callback = function()
      		print("button pressed")                        loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()

  	end    
})

Tab:AddButton({
	Name = "Xero Hub",
	Callback = function()
      		print("button pressed")           loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/main/main.lua"))()
  	end    
})

Tab:AddButton({
	Name = "W-Azure",
	Callback = function()
      		print("button pressed")                  loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "CMDS",
	Icon = "",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Infinity Yield",
	Callback = function()
      		print("button pressed")               loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
})

Tab:AddButton({
	Name = "Simple Spy",
	Callback = function()
      		print("button pressed") loadstring(game:HttpGet("https://raw.githubusercontent.com/78n/SimpleSpy/main/SimpleSpySource.lua"))()
  	end    
})
