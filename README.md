--Bolota na área, faça bom proveito desse script, Deus te abençoe!
local Fluent = loadstring(galocal Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()me:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Universal Bolota Hub" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Gray"
})
?
local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    
    Movement = Window:AddTab({ Title = "Movement"}),
     
 Tabs.Movement:AddButton({ Title = "Voar", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))() end })
 
 Tabs.Main:AddButton({ Title = "Fling", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/LgZwZ7ZB",true))() end })
 
 Tabs.Main:AddButton({ Title = "Infinite Yield", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() end })
 
 Tabs.Main:AddButton({ Title = "", Callback = function() ... end })
 
 Tabs.Main:AddButton({ Title = "Teleport Tool", Callback = function() mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Click Teleport"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack end })

 Tabs.Movement:AddButton({ Title = "Infinite Jump", Callback = function() loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Infinite%20Jump.txt"))() end })
 
 
 
