game.StarterGui:SetCore("SendNotification", {Title = "Bypassing Anti-Cheat", Text = "Status Work", Duration = 5})

local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Kapi V0.2 [Beta]", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest", IntroText = "Kapi Script Hub"})
game.StarterGui:SetCore("SendNotification", {Title = "Kapi Script", Text = "Loading Script", Duration = 5})
wait(4)
game.StarterGui:SetCore("SendNotification", {Title = "Kapi Script", Text = "Load!", Duration = 5})
local Tab = Window:MakeTab({
	Name = "WebSite",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

game.StarterGui:SetCore("SendNotification", {Title = "Welcome!", Text = "Thanks for use my hub", Duration = 5})

Tab:AddButton({
	Name = "Credits",
	Callback = function()
      		print("button pressed")        OrionLib:MakeNotification({
	Name = "Website By",
	Content = "bacon.bloxcodeld,yupoo",
	Image = "rbxassetid://4483345998",
	Time = 20
})

OrionLib:MakeNotification({
	Name = "Creators",
	Content = "bloxcodeld,yupoo,supoiu",
	Image = "rbxassetid://4483345998",
	Time = 20
})

OrionLib:MakeNotification({
	Name = "Beta Testers",
	Content = "supoiu,tubaroscript",
	Image = "rbxassetid://4483345998",
	Time = 20
})

         
        end
})


Tab:AddButton({
	Name = "WebSite OFC",
	Callback = function()
      		print("button pressed")               setclipboard("https://sites.google.com/view/kapiscripthub/início?authuser=0")
  	end    
})

Tab:AddButton({
	Name = "kapiscripthub.workink.me",
	Callback = function()
      		print("button pressed")                setclipboard("https://kapiscripthub.workink.me")
  	end    
})



local Tab = Window:MakeTab({
	Name = "Blox Fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Xero Hub",
	Callback = function()
      		print("button pressed")           
loadstring(game:HttpGet("https://xerohub.click/script/main.lua"))() 
  	end    
})

Tab:AddButton({
	Name = "W-Azure",
	Callback = function()
      		print("button pressed")            loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
      		print("button pressed")           
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
  	end    
})

Tab:AddButton({
	Name = "Matsune V3",
	Callback = function()
      		print("button pressed")           
loadstring(game:HttpGet("https://raw.githubusercontent.com/Yatsuraa/Matsune/main/MatsuneV3.lua"))()
  	end    
})


local Tab = Window:MakeTab({
	Name = "CMDS",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Infinity Yield",
	Callback = function()
      		print("button pressed")                         loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()           

  	end    
})
