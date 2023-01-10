local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Title of the library", HidePremium = false,IntroEnabled = false,SaveConfig = true, ConfigFolder = "OrionTest"})
--Tab
local MainTab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
--Section
local Section = MainTab:AddSection({
	Name = "Script Hubs"
})
--Buttons
MainTab:AddButton({
	Name = "Unfair Hub",
	Callback = function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/rblxscriptsnet/unfair/main/rblxhub.lua'),true))()
  	end    
})

MainTab:AddButton({
	Name = "Dark Hub",
	Callback = function()
        loadstring(game:HttpGet("https://darkhub.xyz/remote-script.lua", true))()
  	end    
})

MainTab:AddButton({
	Name = "Universal Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/sinret/rbxscript.com-scripts-reuploads-/main/boronide", true))()
  	end    
})

MainTab:AddButton({
	Name = "Pearl",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RiseValco/keybypasses/main/pearlhub.lua"))()
  	end    
})

MainTab:AddButton({
	Name = "Ez Hub",
	Callback = function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/debug420/Ez-Industries-Launcher-Data/master/Launcher.lua'),true))()
  	end    
})

MainTab:AddButton({
	Name = "UTG Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Blukez/Scripts/main/UTG%20V3%20RAW"))()
  	end    
})

MainTab:AddButton({
	Name = "Equinox Hub",
	Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/wzB1Qh78"))()
  	end    
})

MainTab:AddButton({
	Name = "Nullware Hub",
	Callback = function()
        loadstring(game:HttpGet("https://gist.githubusercontent.com/M6HqVBcddw2qaN4s/37eef2120d509b37b31fa73944ab2361/raw/kT2fVEFnzDfCRXAP"))()
  	end    
})

MainTab:AddButton({
	Name = "Gelatek Hub",
	Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/QSAjtvyW"))()
  	end    
})

MainTab:AddButton({
	Name = "Simplity Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/HeyGyt/simplityv2/main/main"))()
  	end    
})

--Notification
OrionLib:MakeNotification({
	Name = "Welcome!",
	Content = "Made by Roblox_Scripts.",
	Image = "rbxassetid://4483345998",
	Time = 8
})

OrionLib:MakeNotification({
	Name = "NOTE",
	Content = "It Might close the gui when you execute some of the script hubs just execute again when your done.",
	Image = "rbxassetid://4483345998",
	Time = 8
})
