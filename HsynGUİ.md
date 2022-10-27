-- Gui to Lua
-- Version: 3.2

-- Instances:

local HsynGUI = Instance.new("ScreenGui")
local Gui = Instance.new("Frame")
local GuiName = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Info = Instance.new("TextLabel")
local SelectPlayer = Instance.new("TextButton")
local Player = Instance.new("Frame")
local SpeedHack = Instance.new("TextButton")
local JumpPower = Instance.new("TextButton")
local Anchor = Instance.new("TextButton")
local UnAnchor = Instance.new("TextButton")
local nvisible = Instance.new("TextButton")
local infjp = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local Btools = Instance.new("TextButton")
local Night = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local NoFog = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local morning = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local SpeedFrame = Instance.new("Frame")
local Amount = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local Set = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Reset = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local SelectMain = Instance.new("TextButton")
local Main = Instance.new("Frame")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local JumpFrame = Instance.new("Frame")
local Amount_2 = Instance.new("TextBox")
local UICorner_5 = Instance.new("UICorner")
local JumpPower_2 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local ResetPower = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local UICorner_8 = Instance.new("UICorner")
local Visuals = Instance.new("TextButton")
local Visuals_2 = Instance.new("Frame")
local Esp = Instance.new("TextButton")
local OpenFrame = Instance.new("Frame")
local Open = Instance.new("TextButton")

--Properties:

HsynGUI.Name = "HsynGUI"
HsynGUI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
HsynGUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
HsynGUI.ResetOnSpawn = false

Gui.Name = "Gui"
Gui.Parent = HsynGUI
Gui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Gui.BackgroundTransparency = 0.400
Gui.Position = UDim2.new(0.233597681, 0, 0.271604955, 0)
Gui.Size = UDim2.new(0, 724, 0, 421)

GuiName.Name = "GuiName"
GuiName.Parent = Gui
GuiName.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GuiName.Size = UDim2.new(0, 724, 0, 50)
GuiName.Font = Enum.Font.DenkOne
GuiName.Text = "Hsyn Gui"
GuiName.TextColor3 = Color3.fromRGB(0, 0, 0)
GuiName.TextScaled = true
GuiName.TextSize = 14.000
GuiName.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
GuiName.TextStrokeTransparency = 0.000
GuiName.TextWrapped = true

Close.Name = "Close"
Close.Parent = GuiName
Close.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Close.Position = UDim2.new(1.03038681, 0, 0.879999995, 0)
Close.Size = UDim2.new(0, 63, 0, 56)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

UICorner.Parent = Close

Info.Name = "Info"
Info.Parent = Gui
Info.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Info.BorderColor3 = Color3.fromRGB(0, 0, 0)
Info.Position = UDim2.new(0.0220994484, 0, -0.0593824238, 0)
Info.Size = UDim2.new(0, 163, 0, 25)
Info.Font = Enum.Font.Fantasy
Info.Text = "By Kertenkele_664"
Info.TextColor3 = Color3.fromRGB(255, 255, 255)
Info.TextSize = 14.000
Info.TextWrapped = true

SelectPlayer.Name = "SelectPlayer"
SelectPlayer.Parent = Gui
SelectPlayer.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SelectPlayer.Position = UDim2.new(0, 0, 0.237529695, 0)
SelectPlayer.Size = UDim2.new(0, 134, 0, 50)
SelectPlayer.Font = Enum.Font.FredokaOne
SelectPlayer.Text = "Player"
SelectPlayer.TextColor3 = Color3.fromRGB(0, 0, 0)
SelectPlayer.TextScaled = true
SelectPlayer.TextSize = 14.000
SelectPlayer.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SelectPlayer.TextStrokeTransparency = 0.000
SelectPlayer.TextWrapped = true

Player.Name = "Player"
Player.Parent = Gui
Player.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Player.BackgroundTransparency = 0.300
Player.Position = UDim2.new(0.185082883, 0, 0.118764848, 0)
Player.Size = UDim2.new(0, 590, 0, 371)
Player.Visible = false

SpeedHack.Name = "SpeedHack"
SpeedHack.Parent = Player
SpeedHack.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
SpeedHack.Position = UDim2.new(0.0262103584, 0, 0.0189767517, 0)
SpeedHack.Size = UDim2.new(0, 86, 0, 77)
SpeedHack.Font = Enum.Font.Arial
SpeedHack.Text = "Speed"
SpeedHack.TextColor3 = Color3.fromRGB(0, 0, 0)
SpeedHack.TextScaled = true
SpeedHack.TextSize = 14.000
SpeedHack.TextWrapped = true

JumpPower.Name = "JumpPower"
JumpPower.Parent = Player
JumpPower.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
JumpPower.Position = UDim2.new(0.227905259, 0, 0.0189767517, 0)
JumpPower.Size = UDim2.new(0, 86, 0, 77)
JumpPower.Font = Enum.Font.Arial
JumpPower.Text = "JumpPower"
JumpPower.TextColor3 = Color3.fromRGB(0, 0, 0)
JumpPower.TextScaled = true
JumpPower.TextSize = 14.000
JumpPower.TextWrapped = true

Anchor.Name = "Anchor"
Anchor.Parent = Player
Anchor.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
Anchor.Position = UDim2.new(0.426210314, 0, 0.0189767517, 0)
Anchor.Size = UDim2.new(0, 86, 0, 77)
Anchor.Font = Enum.Font.Arial
Anchor.Text = "Anchor Player"
Anchor.TextColor3 = Color3.fromRGB(0, 0, 0)
Anchor.TextScaled = true
Anchor.TextSize = 14.000
Anchor.TextWrapped = true

UnAnchor.Name = "UnAnchor"
UnAnchor.Parent = Player
UnAnchor.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
UnAnchor.Position = UDim2.new(0.63468492, 0, 0.018976748, 0)
UnAnchor.Size = UDim2.new(0, 86, 0, 77)
UnAnchor.Font = Enum.Font.Arial
UnAnchor.Text = "UnAnchor"
UnAnchor.TextColor3 = Color3.fromRGB(0, 0, 0)
UnAnchor.TextScaled = true
UnAnchor.TextSize = 14.000
UnAnchor.TextWrapped = true

nvisible.Name = "İnvisible"
nvisible.Parent = Player
nvisible.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
nvisible.Position = UDim2.new(0.853328943, 0, 0.0135859121, 0)
nvisible.Size = UDim2.new(0, 86, 0, 77)
nvisible.Font = Enum.Font.Arial
nvisible.Text = "İnvisible"
nvisible.TextColor3 = Color3.fromRGB(0, 0, 0)
nvisible.TextScaled = true
nvisible.TextSize = 14.000
nvisible.TextWrapped = true

infjp.Name = "infjp"
infjp.Parent = Player
infjp.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
infjp.Position = UDim2.new(0.0262103081, 0, 0.266955197, 0)
infjp.Size = UDim2.new(0, 86, 0, 77)
infjp.Font = Enum.Font.Arial
infjp.Text = "infinite jump"
infjp.TextColor3 = Color3.fromRGB(0, 0, 0)
infjp.TextScaled = true
infjp.TextSize = 14.000
infjp.TextWrapped = true

TextLabel.Parent = infjp
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 0.883116901, 0)
TextLabel.Size = UDim2.new(0, 86, 0, 9)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "(press r)"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

Btools.Name = "Btools"
Btools.Parent = Player
Btools.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
Btools.Position = UDim2.new(0.227905214, 0, 0.266955197, 0)
Btools.Size = UDim2.new(0, 86, 0, 77)
Btools.Font = Enum.Font.Arial
Btools.Text = "Btools"
Btools.TextColor3 = Color3.fromRGB(0, 0, 0)
Btools.TextScaled = true
Btools.TextSize = 14.000
Btools.TextWrapped = true

Night.Name = "Night"
Night.Parent = Player
Night.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
Night.Position = UDim2.new(0.63468492, 0, 0.266955197, 0)
Night.Size = UDim2.new(0, 86, 0, 77)
Night.Font = Enum.Font.Arial
Night.Text = "Night"
Night.TextColor3 = Color3.fromRGB(0, 0, 0)
Night.TextScaled = true
Night.TextSize = 14.000
Night.TextWrapped = true

TextLabel_2.Parent = Night
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0, 0, 0.883116901, 0)
TextLabel_2.Size = UDim2.new(0, 86, 0, 8)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "(only you)"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

NoFog.Name = "NoFog"
NoFog.Parent = Player
NoFog.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
NoFog.Position = UDim2.new(0.853329003, 0, 0.266955197, 0)
NoFog.Size = UDim2.new(0, 86, 0, 77)
NoFog.Font = Enum.Font.Arial
NoFog.Text = "NoFog"
NoFog.TextColor3 = Color3.fromRGB(0, 0, 0)
NoFog.TextScaled = true
NoFog.TextSize = 14.000
NoFog.TextWrapped = true

TextLabel_3.Parent = NoFog
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(-8.94069672e-08, 0, 0.896103919, 0)
TextLabel_3.Size = UDim2.new(0, 86, 0, 8)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "(only you)"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

morning.Name = "morning"
morning.Parent = Player
morning.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
morning.Position = UDim2.new(0.426210344, 0, 0.266955197, 0)
morning.Size = UDim2.new(0, 86, 0, 77)
morning.Font = Enum.Font.Arial
morning.Text = "morning"
morning.TextColor3 = Color3.fromRGB(0, 0, 0)
morning.TextScaled = true
morning.TextSize = 14.000
morning.TextWrapped = true

TextLabel_4.Parent = morning
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0, 0, 0.883116901, 0)
TextLabel_4.Size = UDim2.new(0, 86, 0, 8)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "(only you)"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

SpeedFrame.Name = "SpeedFrame"
SpeedFrame.Parent = Gui
SpeedFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SpeedFrame.Position = UDim2.new(0.185082868, 0, 0.118764848, 0)
SpeedFrame.Size = UDim2.new(0, 590, 0, 371)
SpeedFrame.Visible = false

Amount.Name = "Amount"
Amount.Parent = SpeedFrame
Amount.BackgroundColor3 = Color3.fromRGB(104, 104, 104)
Amount.Position = UDim2.new(0.330508471, 0, 0.146276593, 0)
Amount.Size = UDim2.new(0, 208, 0, 60)
Amount.Font = Enum.Font.Fantasy
Amount.PlaceholderColor3 = Color3.fromRGB(170, 85, 255)
Amount.Text = "Text here..."
Amount.TextColor3 = Color3.fromRGB(0, 0, 0)
Amount.TextScaled = true
Amount.TextSize = 14.000
Amount.TextWrapped = true

UICorner_2.Parent = Amount

Set.Name = "Set"
Set.Parent = SpeedFrame
Set.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
Set.Position = UDim2.new(0, 15, 0, 144)
Set.Size = UDim2.new(0, 171, 0, 69)
Set.Font = Enum.Font.Fondamento
Set.Text = "SET SPEED"
Set.TextColor3 = Color3.fromRGB(0, 0, 0)
Set.TextScaled = true
Set.TextSize = 14.000
Set.TextWrapped = true

UICorner_3.Parent = Set

Reset.Name = "Reset"
Reset.Parent = SpeedFrame
Reset.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Reset.Position = UDim2.new(0, 383, 0, 144)
Reset.Size = UDim2.new(0, 186, 0, 69)
Reset.Font = Enum.Font.Fondamento
Reset.Text = "RESET SPEED"
Reset.TextColor3 = Color3.fromRGB(0, 0, 0)
Reset.TextScaled = true
Reset.TextSize = 14.000
Reset.TextWrapped = true

UICorner_4.Parent = Reset

SelectMain.Name = "SelectMain"
SelectMain.Parent = Gui
SelectMain.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
SelectMain.Position = UDim2.new(0, 0, 0.118764848, 0)
SelectMain.Size = UDim2.new(0, 134, 0, 50)
SelectMain.Font = Enum.Font.FredokaOne
SelectMain.Text = "Main"
SelectMain.TextColor3 = Color3.fromRGB(0, 0, 0)
SelectMain.TextScaled = true
SelectMain.TextSize = 14.000
SelectMain.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SelectMain.TextStrokeTransparency = 0.000
SelectMain.TextWrapped = true

Main.Name = "Main"
Main.Parent = Gui
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.Position = UDim2.new(0, 134, 0, 50)
Main.Size = UDim2.new(0, 590, 0, 371)
Main.Visible = false

TextLabel_5.Parent = Main
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0, 53, 0, 23)
TextLabel_5.Size = UDim2.new(0, 314, 0, 77)
TextLabel_5.Font = Enum.Font.Bangers
TextLabel_5.Text = "-MADE BY KERTENKELE_664"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

TextLabel_6.Parent = Main
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0, 53, 0, 120)
TextLabel_6.Size = UDim2.new(0, 304, 0, 125)
TextLabel_6.Font = Enum.Font.Bangers
TextLabel_6.Text = "Thanks For Using Hsyn GUI"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 14.000
TextLabel_6.TextWrapped = true

JumpFrame.Name = "JumpFrame"
JumpFrame.Parent = Gui
JumpFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
JumpFrame.Position = UDim2.new(0, 134, 0, 50)
JumpFrame.Size = UDim2.new(0, 590, 0, 371)
JumpFrame.Visible = false

Amount_2.Name = "Amount"
Amount_2.Parent = JumpFrame
Amount_2.BackgroundColor3 = Color3.fromRGB(125, 125, 125)
Amount_2.Position = UDim2.new(0, 166, 0, 50)
Amount_2.Size = UDim2.new(0, 254, 0, 70)
Amount_2.Font = Enum.Font.Fondamento
Amount_2.Text = "Text Here..."
Amount_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Amount_2.TextScaled = true
Amount_2.TextSize = 14.000
Amount_2.TextWrapped = true

UICorner_5.Parent = Amount_2

JumpPower_2.Name = "JumpPower"
JumpPower_2.Parent = JumpFrame
JumpPower_2.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
JumpPower_2.Position = UDim2.new(0, 33, 0, 180)
JumpPower_2.Size = UDim2.new(0, 198, 0, 85)
JumpPower_2.Font = Enum.Font.Fondamento
JumpPower_2.Text = "Set JumpPower"
JumpPower_2.TextColor3 = Color3.fromRGB(0, 0, 0)
JumpPower_2.TextScaled = true
JumpPower_2.TextSize = 14.000
JumpPower_2.TextWrapped = true

UICorner_6.Parent = JumpPower_2

ResetPower.Name = "ResetPower"
ResetPower.Parent = JumpFrame
ResetPower.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
ResetPower.Position = UDim2.new(0, 339, 0, 180)
ResetPower.Size = UDim2.new(0, 198, 0, 85)
ResetPower.Font = Enum.Font.Fondamento
ResetPower.Text = "Reset JumpPower"
ResetPower.TextColor3 = Color3.fromRGB(0, 0, 0)
ResetPower.TextScaled = true
ResetPower.TextSize = 14.000
ResetPower.TextWrapped = true

UICorner_7.Parent = ResetPower

UICorner_8.Parent = Gui

Visuals.Name = "Visuals"
Visuals.Parent = Gui
Visuals.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Visuals.Position = UDim2.new(0, 0, 0.356294543, 0)
Visuals.Size = UDim2.new(0, 134, 0, 50)
Visuals.Font = Enum.Font.FredokaOne
Visuals.Text = "Visuals"
Visuals.TextColor3 = Color3.fromRGB(0, 0, 0)
Visuals.TextScaled = true
Visuals.TextSize = 14.000
Visuals.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Visuals.TextStrokeTransparency = 0.000
Visuals.TextWrapped = true

Visuals_2.Name = "Visuals"
Visuals_2.Parent = Gui
Visuals_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Visuals_2.BackgroundTransparency = 0.300
Visuals_2.Position = UDim2.new(0.185082868, 0, 0.118764848, 0)
Visuals_2.Size = UDim2.new(0, 589, 0, 371)

Esp.Name = "Esp"
Esp.Parent = Visuals_2
Esp.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
Esp.Position = UDim2.new(0.0241701156, 0, 0.0189767517, 0)
Esp.Size = UDim2.new(0, 86, 0, 77)
Esp.Font = Enum.Font.Arial
Esp.Text = "Esp"
Esp.TextColor3 = Color3.fromRGB(0, 0, 0)
Esp.TextScaled = true
Esp.TextSize = 14.000
Esp.TextWrapped = true

OpenFrame.Name = "OpenFrame"
OpenFrame.Parent = HsynGUI
OpenFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OpenFrame.Position = UDim2.new(0.00793078542, 0, 0.470370352, 0)
OpenFrame.Size = UDim2.new(0, 201, 0, 48)

Open.Name = "Open"
Open.Parent = OpenFrame
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.BackgroundTransparency = 0.450
Open.Position = UDim2.new(0.00497512426, 0, 0, 0)
Open.Size = UDim2.new(0, 200, 0, 48)
Open.Font = Enum.Font.Cartoon
Open.Text = "Open GUI"
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true

-- Scripts:

local function YFGXA_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.Gui.Visible = false
	end)
end
coroutine.wrap(YFGXA_fake_script)()
local function FQFNJ_fake_script() -- SelectPlayer.LocalScript 
	local script = Instance.new('LocalScript', SelectPlayer)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Player.Visible = true
		script.Parent.Parent.SpeedFrame.Visible = false
		script.Parent.Parent.Main.Visible = false
		script.Parent.Parent.JumpFrame.Visible = false
	end)
end
coroutine.wrap(FQFNJ_fake_script)()
local function YWAY_fake_script() -- SpeedHack.LocalScript 
	local script = Instance.new('LocalScript', SpeedHack)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.SpeedFrame.Visible = true
		script.Parent.Parent.Parent.Main.Visible = false
		script.Parent.Parent.Parent.Player.Visible = false
		script.Parent.Parent.Parent.SpeedFrame.Visible = false
		script.Parent.Parent.Parent.TeleportFrame.Visible = false
	end)
end
coroutine.wrap(YWAY_fake_script)()
local function UIQWUJ_fake_script() -- JumpPower.LocalScript 
	local script = Instance.new('LocalScript', JumpPower)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.JumpFrame.Visible = true
		script.Parent.Parent.Parent.Main.Visible = false
		script.Parent.Parent.Parent.Player.Visible = false
		script.Parent.Parent.Parent.SpeedFrame.Visible = false
		script.Parent.Parent.Parent.TeleportFrame.Visible = false
	end)
end
coroutine.wrap(UIQWUJ_fake_script)()
local function HBSVJB_fake_script() -- Anchor.LocalScript 
	local script = Instance.new('LocalScript', Anchor)

	script.Parent.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character
		local humanoid = character:WaitForChild("Humanoid")
		
		character.HumanoidRootPart.Anchored = true
	end)
end
coroutine.wrap(HBSVJB_fake_script)()
local function JNUHPI_fake_script() -- UnAnchor.LocalScript 
	local script = Instance.new('LocalScript', UnAnchor)

	script.Parent.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character
		local humanoid = character:WaitForChild("Humanoid")
		
		character.HumanoidRootPart.Anchored = false
	end)
end
coroutine.wrap(JNUHPI_fake_script)()
local function JOVJXB_fake_script() -- nvisible.LocalScript 
	local script = Instance.new('LocalScript', nvisible)

	script.Parent.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character
		local humanoid = character:WaitForChild("Humanoid")
		
		character.LeftUpperLeg:Destroy()
		character.LeftFoot:Destroy()
		character.LeftLowerLeg:Destroy()
		character.RightUpperLeg:Destroy()
		character.RightLowerLeg:Destroy()
		character.LeftUpperArm:Destroy()
		character.LeftLowerArm:Destroy()
		character.RightUpperArm:Destroy()
		character.RightLowerArm:Destroy()
		character.Head.face:Destroy()
		character.LeftHand:Destroy()
		character.RightFoot:Destroy()
		character.RightHand:Destroy()
		
	end)
end
coroutine.wrap(JOVJXB_fake_script)()
local function IJEHX_fake_script() -- infjp.LocalScript 
	local script = Instance.new('LocalScript', infjp)

	script.Parent.MouseButton1Click:Connect(function()
		_G.infinjump = true
		local Player = game:GetService("Players").LocalPlayer
		local Mouse = Player:GetMouse()
		Mouse.KeyDown:connect(function(k)
			if _G.infinjump then
				if k:byte() == 32 then
					local Humanoid = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
					Humanoid:ChangeState("Jumping")
					wait(0.1)
					Humanoid:ChangeState("Seated")
				end
			end
		end)
	
		local Player = game:GetService("Players").LocalPlayer
		local Mouse = Player:GetMouse()
		Mouse.KeyDown:connect(function(k)
			k = k:lower()
			if k == "r" then
				if _G.infinjump == true then
					_G.infinjump = false
				else
					_G.infinjump = true
				end
			end
		end)
	end)
end
coroutine.wrap(IJEHX_fake_script)()
local function AUFZO_fake_script() -- Btools.LocalScript 
	local script = Instance.new('LocalScript', Btools)

	btools = script.Parent
	
	btools.MouseButton1Click:Connect(function()
		game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Backpack, true)
		for index, child in pairs(game:GetService("Workspace"):GetChildren()) do
			if child.ClassName == "Part" then
				child.Locked = false
			end
			if child.ClassName == "MeshPart" then
				child.Locked = false
			end
			if child.ClassName == "UnionOperation" then
				child.Locked = false
			end
			if child.ClassName == "Model" then
				for index, chil in pairs(child:GetChildren()) do
					if chil.ClassName == "Part" then
						chil.Locked = false
					end
					if chil.ClassName == "MeshPart" then
						chil.Locked = false
					end
					if chil.ClassName == "UnionOperation" then
						chil.Locked = false
					end
					if chil.ClassName == "Model" then
						for index, childe in pairs(chil:GetChildren()) do
							if childe.ClassName == "Part" then
								childe.Locked = false
							end
							if childe.ClassName == "MeshPart" then
								childe.Locked = false
							end
							if childe.ClassName == "UnionOperation" then
								childe.Locked = false
							end
							if childe.ClassName == "Model" then
								for index, childeo in pairs(childe:GetChildren()) do
									if childeo.ClassName == "Part" then
										childeo.Locked = false
									end
									if childeo.ClassName == "MeshPart" then
										childeo.Locked = false
									end
									if childeo.ClassName == "UnionOperation" then
										childeo.Locked = false
									end
									if childeo.ClassName == "Model" then
									end
								end
							end
						end
					end
				end
			end
		end
		local c = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
		c.BinType = Enum.BinType.Hammer
		c = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
		c.BinType = Enum.BinType.Clone
		c = Instance.new("HopperBin", game:GetService("Players").LocalPlayer.Backpack)
		c.BinType = Enum.BinType.Grab
	end)
end
coroutine.wrap(AUFZO_fake_script)()
local function ETQED_fake_script() -- Night.LocalScript 
	local script = Instance.new('LocalScript', Night)

	script.Parent.MouseButton1Click:Connect(function()
		game.Lighting.TimeOfDay = "00:00:00"
		
	end)
end
coroutine.wrap(ETQED_fake_script)()
local function KCBDO_fake_script() -- NoFog.LocalScript 
	local script = Instance.new('LocalScript', NoFog)

	script.Parent.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character
		local HumanoidRootPart = character.HumanoidRootPart
		
		game.Lighting.FogEnd = 1000000000000000
	end)
end
coroutine.wrap(KCBDO_fake_script)()
local function WFAJ_fake_script() -- morning.LocalScript 
	local script = Instance.new('LocalScript', morning)

	script.Parent.MouseButton1Click:Connect(function()
		game.Lighting.TimeOfDay = "14:00:00"
		
	end)
end
coroutine.wrap(WFAJ_fake_script)()
local function YEVNM_fake_script() -- Set.LocalScript 
	local script = Instance.new('LocalScript', Set)

	script.Parent.MouseButton1Click:Connect(function()
		local character = game.Players.LocalPlayer.Character
		local humanoid = character:WaitForChild("Humanoid")
		
		humanoid.WalkSpeed = (script.Parent.Parent.Amount.Text)
	end)
end
coroutine.wrap(YEVNM_fake_script)()
local function STEH_fake_script() -- Reset.LocalScript 
	local script = Instance.new('LocalScript', Reset)

	script.Parent.MouseButton1Click:Connect(function()
		local character = game.Players.LocalPlayer.Character
		local humanoid = character:WaitForChild("Humanoid")
	
		humanoid.WalkSpeed = 16
		
	end)
end
coroutine.wrap(STEH_fake_script)()
local function FFSY_fake_script() -- SelectMain.LocalScript 
	local script = Instance.new('LocalScript', SelectMain)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Player.Visible = false
		script.Parent.Parent.Main.Visible = true
		script.Parent.Parent.SpeedFrame.Visible = false
		script.Parent.Parent.TeleportFrame.Visible = false
	end)
end
coroutine.wrap(FFSY_fake_script)()
local function QFFLJ_fake_script() -- JumpPower_2.LocalScript 
	local script = Instance.new('LocalScript', JumpPower_2)

	script.Parent.MouseButton1Click:Connect(function()
		local character = game.Players.LocalPlayer.Character
		local humanoid = character:WaitForChild("Humanoid")
	
		humanoid.JumpPower = (script.Parent.Parent.Amount.Text)
		
	end)
end
coroutine.wrap(QFFLJ_fake_script)()
local function ASAIFYJ_fake_script() -- ResetPower.LocalScript 
	local script = Instance.new('LocalScript', ResetPower)

	script.Parent.MouseButton1Click:Connect(function()
		local character = game.Players.LocalPlayer.Character
		local humanoid = character:WaitForChild("Humanoid")
	
		humanoid.JumpPower = 50
		
	end)
end
coroutine.wrap(ASAIFYJ_fake_script)()
local function HLSP_fake_script() -- Visuals.LocalScript 
	local script = Instance.new('LocalScript', Visuals)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Player.Visible = true
		script.Parent.Parent.SpeedFrame.Visible = false
		script.Parent.Parent.Main.Visible = false
		script.Parent.Parent.JumpFrame.Visible = false
	end)
end
coroutine.wrap(HLSP_fake_script)()
local function ITKBKU_fake_script() -- Esp.LocalScript 
	local script = Instance.new('LocalScript', Esp)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players"):GetChildren()
		local RunService = game:GetService("RunService")
		local Highlight = Instance.new("Highlight")
		Highlight.Name = "HighLight"
	
		for i, v in pairs(Players) do
		repeat wait() until v.Character
		if not v.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("HighLight") then
			local HighLightClone = Highlight:Clone()
			HighLightClone.Adornee = v.Character
			HighLightClone.Parent = v.Character:FindFirstChild("HumanoidRootPart")
			HighLightClone.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
			HighLightClone.Name = "HighLight"
		end
		
	
		game.Players.PlayerAdded:Connect(function(player)
		repeat wait() until player.Character
		if not player.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("HighLight") then
		local HighLightClone = Highlight:Clone()
		HighLightClone.Adornee = player.Character
		HighLightClone.Parent = player.Character.FindFirstChild("HumanoidRootPart")
		HighLightClone.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
		end
		end)
	
		game.Players.PlayerRemoving:Connect(function(playerRemoved)
		playerRemoved.Character:FindFirstChild("HumanoidRootPart").HighLight:Destroy()
		end)
	
	
		RunService.HeartBeat:Connect(function()
		for i, v in pairs(Players) do
			repeat wait() until v.Character
			if not v.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("HighLight") then
				local HighLightClone = Highlight:Clone()
				HighLightClone.Adornee = v.Character
				HighLightClone.Parent = v.Character:FindFirstChild("HumanoidRootPart")
				HighLightClone.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
				HighLightClone.Name "HighLight"
				task.wait()
				end
			end
	end)
	end)
	
end
coroutine.wrap(ITKBKU_fake_script)()
local function SQWVUVI_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Gui.Visible = true
	end)
end
coroutine.wrap(SQWVUVI_fake_script)()
