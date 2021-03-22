local ScreenGui = Instance.new("ScreenGui")
local frame = Instance.new("Frame")
local Ak = Instance.new("TextButton")
local M9 = Instance.new("TextButton")
local Remigton = Instance.new("TextButton")
local Key = Instance.new("TextButton")
local Btools = Instance.new("TextButton")
local Breakfast = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local frame1 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local Police = Instance.new("TextButton")
local Sewers = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local Speed = Instance.new("TextButton")
local Prisoner = Instance.new("TextButton")
local Police1 = Instance.new("TextButton")
local Car = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

frame.Name = "frame"
frame.Parent = ScreenGui
frame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
frame.Position = UDim2.new(0.669143498, 0, 0.277641207, 0)
frame.Size = UDim2.new(0, 410, 0, 284)

Ak.MouseButton1Down:connect(function()
	local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver["AK-47"].ITEMPICKUP
	local Event = game:GetService("Workspace").Remote.ItemHandler
	Event:InvokeServer(A_1)

	--AK-47 GIVER
end)

Ak.Name = "Ak"
Ak.Parent = frame
Ak.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Ak.Position = UDim2.new(0.0439024419, 0, 0.116197184, 0)
Ak.Size = UDim2.new(0, 105, 0, 28)
Ak.Font = Enum.Font.FredokaOne
Ak.Text = "Get Ak-47"
Ak.TextColor3 = Color3.fromRGB(255, 255, 255)
Ak.TextSize = 14.000

M9.MouseButton1Down:connect(function()

	local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver["M9"].ITEMPICKUP
	local Event = game:GetService("Workspace").Remote.ItemHandler
	Event:InvokeServer(A_1)

	--M9 giver
end)

M9.Name = "M9"
M9.Parent = frame
M9.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
M9.Position = UDim2.new(0.707317114, 0, 0.116197184, 0)
M9.Size = UDim2.new(0, 105, 0, 28)
M9.Font = Enum.Font.FredokaOne
M9.Text = "Get M9"
M9.TextColor3 = Color3.fromRGB(255, 255, 255)
M9.TextSize = 14.000


Remigton.MouseButton1Down:connect(function()

	local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver["Remington 870"].ITEMPICKUP
	local Event = game:GetService("Workspace").Remote.ItemHandler
	Event:InvokeServer(A_1)

	--GET A REMIGTON	
end)

Remigton.Name = "Remigton"
Remigton.Parent = frame
Remigton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Remigton.Position = UDim2.new(0.370731741, 0, 0.116197184, 0)
Remigton.Size = UDim2.new(0, 105, 0, 28)
Remigton.Font = Enum.Font.FredokaOne
Remigton.Text = "Get Remigton"
Remigton.TextColor3 = Color3.fromRGB(255, 255, 255)
Remigton.TextSize = 14.000

Key.MouseButton1Down:connect(function()

	local A_1 = game:GetService("Workspace")["Prison_ITEMS"].single["Key card"].ITEMPICKUP
	local Event = game:GetService("Workspace").Remote.ItemHandler
	Event:InvokeServer(A_1)

	--KEY CARD GIVER
end)

Key.Name = "Key"
Key.Parent = frame
Key.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Key.Position = UDim2.new(0.0439024866, 0, 0.278169036, 0)
Key.Size = UDim2.new(0, 105, 0, 28)
Key.Font = Enum.Font.FredokaOne
Key.Text = "Get Key"
Key.TextColor3 = Color3.fromRGB(255, 255, 255)
Key.TextSize = 14.000

Btools.MouseButton1Down:connect(function()


	local tool1 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	local tool2 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	local tool3 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	local tool4 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	local tool5 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
	tool1.BinType = "Clone"
	tool2.BinType = "GameTool"
	tool3.BinType = "Hammer"
	tool4.BinType = "Script"
	tool5.BinType = "Grab"

	--BTOOLS

end)

Btools.Name = "Btools"
Btools.Parent = frame
Btools.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Btools.Position = UDim2.new(0.370731741, 0, 0.278169036, 0)
Btools.Size = UDim2.new(0, 105, 0, 28)
Btools.Font = Enum.Font.FredokaOne
Btools.Text = "Get Btools"
Btools.TextColor3 = Color3.fromRGB(255, 255, 255)
Btools.TextSize = 14.000

Breakfast.MouseButton1Down:connect(function()

	local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver.Breakfast.ITEMPICKUP
	local Event = game:GetService("Workspace").Remote.ItemHandler
	Event:InvokeServer(A_1)

end)
Breakfast.Name = "Breakfast"
Breakfast.Parent = frame
Breakfast.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Breakfast.Position = UDim2.new(0.707317114, 0, 0.278169036, 0)
Breakfast.Size = UDim2.new(0, 105, 0, 28)
Breakfast.Font = Enum.Font.FredokaOne
Breakfast.Text = "Get Breakfast"
Breakfast.TextColor3 = Color3.fromRGB(255, 255, 255)
Breakfast.TextSize = 14.000

TextLabel.Parent = frame
TextLabel.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
TextLabel.Position = UDim2.new(0, 0, 0.411971837, 0)
TextLabel.Size = UDim2.new(0, 410, 0, 26)
TextLabel.Text = "Teleports"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 17.000

frame1.Name = "frame1"
frame1.Parent = frame
frame1.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
frame1.Position = UDim2.new(0, 0, -0.142571151, 0)
frame1.Size = UDim2.new(0, 410, 0, 48)

TextLabel_2.Parent = frame1
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.204878062, 0, -0.208333343, 0)
TextLabel_2.Size = UDim2.new(0, 242, 0, 50)
TextLabel_2.Font = Enum.Font.FredokaOne
TextLabel_2.Text = "Made By Skrillex#7985 and pigeon#2500"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 20.000

TextLabel_3.Parent = frame1
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.256097555, 0, 0.208333313, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 50)
TextLabel_3.Font = Enum.Font.FredokaOne
TextLabel_3.Text = "Prison Gui"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 31.000

Police.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(811.166504, 99.9900055, 2278.73193)

	--police station tp
end)

Police.Name = "Police"
Police.Parent = frame
Police.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Police.Position = UDim2.new(0.0439024866, 0, 0.549295783, 0)
Police.Size = UDim2.new(0, 105, 0, 28)
Police.Font = Enum.Font.FredokaOne
Police.Text = "Police Station"
Police.TextColor3 = Color3.fromRGB(255, 255, 255)
Police.TextSize = 14.000

Sewers.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(913.732605, 78.7050629, 2104.45483)

	--Sewers tp	
end)

Sewers.Name = "Sewers"
Sewers.Parent = frame
Sewers.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Sewers.Position = UDim2.new(0.707317114, 0, 0.549295783, 0)
Sewers.Size = UDim2.new(0, 105, 0, 28)
Sewers.Font = Enum.Font.FredokaOne
Sewers.Text = "Sewers"
Sewers.TextColor3 = Color3.fromRGB(255, 255, 255)
Sewers.TextSize = 14.000

TextLabel_4.Parent = frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(27, 27, 27)
TextLabel_4.Position = UDim2.new(-0.00243902439, 0, 0.67957747, 0)
TextLabel_4.Size = UDim2.new(0, 410, 0, 26)
TextLabel_4.Text = "Misc"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 17.000

Speed.MouseButton1Down:connect(function()

	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50

	--speed 50	
end)	



Speed.Name = "Speed"
Speed.Parent = frame
Speed.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Speed.Position = UDim2.new(0.0439024866, 0, 0.813380301, 0)
Speed.Size = UDim2.new(0, 105, 0, 28)
Speed.Font = Enum.Font.FredokaOne
Speed.Text = "Speed"
Speed.TextColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextSize = 14.000

Prisoner.MouseButton1Down:connect(function()

	local A_1 = "Bright orange"
	local Event = game:GetService("Workspace").Remote.TeamEvent
	Event:FireServer(A_1)

	--BECOME A PRISONER
end)

Prisoner.Name = "Prisoner"
Prisoner.Parent = frame
Prisoner.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Prisoner.Position = UDim2.new(0.707317114, 0, 0.813380301, 0)
Prisoner.Size = UDim2.new(0, 105, 0, 28)
Prisoner.Font = Enum.Font.FredokaOne
Prisoner.Text = "Become Prisoner"
Prisoner.TextColor3 = Color3.fromRGB(255, 255, 255)
Prisoner.TextSize = 14.000

Police1.MouseButton1Down:connect(function()
	
	local A_1 = "Bright blue"
	local Event = game:GetService("Workspace").Remote.TeamEvent
	Event:FireServer(A_1)
	
	--become a police man
end)

Police1.Name = "Police1"
Police1.Parent = frame
Police1.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Police1.Position = UDim2.new(0.370731741, 0, 0.813380301, 0)
Police1.Size = UDim2.new(0, 105, 0, 28)
Police1.Font = Enum.Font.FredokaOne
Police1.Text = "Become Police"
Police1.TextColor3 = Color3.fromRGB(255, 255, 255)
Police1.TextSize = 14.000

Car.MouseButton1Down:connect(function()
	
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(620.666626, 98.1842728, 2502.59131)
	
	--car teleport
end)

Car.Name = "Car"
Car.Parent = frame
Car.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Car.Position = UDim2.new(0.370731741, 0, 0.549295783, 0)
Car.Size = UDim2.new(0, 105, 0, 28)
Car.Font = Enum.Font.FredokaOne
Car.Text = "Car Spawner"
Car.TextColor3 = Color3.fromRGB(255, 255, 255)
Car.TextSize = 14.000

-- Scripts:

local function WWYOZ_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	frame = script.Parent.frame
	
	frame.Draggable = true
	
	frame.Active = true
	
	frame.Selectable = true
end
coroutine.wrap(WWYOZ_fake_script)()
