local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Tubaro V0.1", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Inicio",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

OrionLib:MakeNotification({
	Name = "Tubaro",
	Content = "Loading Hub",
	Image = "rbxassetid://4483345998",
	Time = 10
})

OrionLib:MakeNotification({
	Name = "Tubaro",
	Content = "Load Complet",
	Image = "rbxassetid://4483345998",
	Time = 10
})

