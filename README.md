-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local icon = Instance.new("Frame")
local AutoFram = Instance.new("Frame")
local AutoFram_2 = Instance.new("TextButton")
local p = Instance.new("TextLabel")
local Pvp = Instance.new("Frame")
local Island = Instance.new("Frame")
local Setting = Instance.new("Frame")
local Misc = Instance.new("Frame")
local AutoFram_3 = Instance.new("TextButton")
local p_2 = Instance.new("TextLabel")
local Pvp_2 = Instance.new("TextButton")
local p_3 = Instance.new("TextLabel")
local Island_2 = Instance.new("TextButton")
local p_4 = Instance.new("TextLabel")
local Misc_2 = Instance.new("TextButton")
local p_5 = Instance.new("TextLabel")
local Setting_2 = Instance.new("TextButton")
local p_6 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 2
Frame.Position = UDim2.new(0.0509478226, 0, 0.0819398016, 0)
Frame.Size = UDim2.new(0.436019003, 0, 0.725752532, 0)

icon.Name = "icon"
icon.Parent = Frame
icon.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
icon.BorderSizePixel = 2
icon.Position = UDim2.new(0.0302013475, 0, 0.0889423043, 0)
icon.Size = UDim2.new(0.936241686, 0, 0.877403855, 0)

AutoFram.Name = "AutoFram"
AutoFram.Parent = icon
AutoFram.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoFram.BackgroundTransparency = 1.000
AutoFram.Size = UDim2.new(1, 0, 1, 0)

AutoFram_2.Name = "AutoFram"
AutoFram_2.Parent = AutoFram
AutoFram_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoFram_2.BorderSizePixel = 0
AutoFram_2.Position = UDim2.new(0.0182815231, 0, 0.0250741821, 0)
AutoFram_2.Size = UDim2.new(0.0539875627, 0, 0.0533637293, 0)
AutoFram_2.Font = Enum.Font.RobotoMono
AutoFram_2.Text = ""
AutoFram_2.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoFram_2.TextScaled = true
AutoFram_2.TextSize = 14.000
AutoFram_2.TextWrapped = true

p.Name = "p"
p.Parent = AutoFram_2
p.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
p.BackgroundTransparency = 1.000
p.BorderSizePixel = 0
p.Position = UDim2.new(1.29027331, 0, -0.0612722933, 0)
p.Size = UDim2.new(4.05882072, 0, 1.04300153, 0)
p.Font = Enum.Font.SourceSans
p.Text = "AutoFram"
p.TextColor3 = Color3.fromRGB(255, 255, 255)
p.TextSize = 14.000
p.TextXAlignment = Enum.TextXAlignment.Left

Pvp.Name = "Pvp"
Pvp.Parent = icon
Pvp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pvp.BackgroundTransparency = 1.000
Pvp.Size = UDim2.new(1, 0, 1, 0)

Island.Name = "Island"
Island.Parent = icon
Island.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Island.BackgroundTransparency = 1.000
Island.Size = UDim2.new(1, 0, 1, 0)

Setting.Name = "Setting"
Setting.Parent = icon
Setting.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Setting.BackgroundTransparency = 1.000
Setting.Size = UDim2.new(1, 0, 1, 0)

Misc.Name = "Misc"
Misc.Parent = icon
Misc.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Misc.BackgroundTransparency = 1.000
Misc.Size = UDim2.new(1, 0, 1, 0)

AutoFram_3.Name = "AutoFram"
AutoFram_3.Parent = Frame
AutoFram_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoFram_3.BackgroundTransparency = 1.000
AutoFram_3.Position = UDim2.new(0.0298912805, 0, 0.0460829511, 0)
AutoFram_3.Size = UDim2.new(0.187500104, 0, 0.0428593382, 0)
AutoFram_3.Font = Enum.Font.RobotoMono
AutoFram_3.Text = "AutoFram"
AutoFram_3.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoFram_3.TextScaled = true
AutoFram_3.TextSize = 14.000
AutoFram_3.TextWrapped = true

p_2.Name = "p"
p_2.Parent = AutoFram_3
p_2.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
p_2.BorderSizePixel = 0
p_2.Position = UDim2.new(1.10570859e-07, 0, 1, 0)
p_2.Size = UDim2.new(1, 0, 0.100000001, 0)
p_2.Font = Enum.Font.SourceSans
p_2.Text = ""
p_2.TextColor3 = Color3.fromRGB(0, 0, 0)
p_2.TextSize = 14.000

Pvp_2.Name = "Pvp"
Pvp_2.Parent = Frame
Pvp_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pvp_2.BackgroundTransparency = 1.000
Pvp_2.Position = UDim2.new(0.217391267, 0, 0.0460829511, 0)
Pvp_2.Size = UDim2.new(0.187500104, 0, 0.0428593382, 0)
Pvp_2.Font = Enum.Font.RobotoMono
Pvp_2.Text = "Pvp"
Pvp_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Pvp_2.TextScaled = true
Pvp_2.TextSize = 14.000
Pvp_2.TextWrapped = true

p_3.Name = "p"
p_3.Parent = Pvp_2
p_3.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
p_3.BorderSizePixel = 0
p_3.Position = UDim2.new(-1.10570859e-07, 0, 1, 0)
p_3.Size = UDim2.new(1, 0, 0.100000001, 0)
p_3.Visible = false
p_3.Font = Enum.Font.SourceSans
p_3.Text = ""
p_3.TextColor3 = Color3.fromRGB(0, 0, 0)
p_3.TextSize = 14.000

Island_2.Name = "Island"
Island_2.Parent = Frame
Island_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Island_2.BackgroundTransparency = 1.000
Island_2.Position = UDim2.new(0.404891253, 0, 0.0460829511, 0)
Island_2.Size = UDim2.new(0.187500104, 0, 0.0428593382, 0)
Island_2.Font = Enum.Font.RobotoMono
Island_2.Text = "Island"
Island_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Island_2.TextScaled = true
Island_2.TextSize = 14.000
Island_2.TextWrapped = true

p_4.Name = "p"
p_4.Parent = Island_2
p_4.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
p_4.BorderSizePixel = 0
p_4.Position = UDim2.new(0, 0, 1, 0)
p_4.Size = UDim2.new(1, 0, 0.100000001, 0)
p_4.Visible = false
p_4.Font = Enum.Font.SourceSans
p_4.Text = ""
p_4.TextColor3 = Color3.fromRGB(0, 0, 0)
p_4.TextSize = 14.000

Misc_2.Name = "Misc"
Misc_2.Parent = Frame
Misc_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Misc_2.BackgroundTransparency = 1.000
Misc_2.Position = UDim2.new(0.592391253, 0, 0.0460829511, 0)
Misc_2.Size = UDim2.new(0.187500104, 0, 0.0428593382, 0)
Misc_2.Font = Enum.Font.RobotoMono
Misc_2.Text = "Misc"
Misc_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Misc_2.TextScaled = true
Misc_2.TextSize = 14.000
Misc_2.TextWrapped = true

p_5.Name = "p"
p_5.Parent = Misc_2
p_5.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
p_5.BorderSizePixel = 0
p_5.Position = UDim2.new(0, 0, 1, 0)
p_5.Size = UDim2.new(1, 0, 0.100000001, 0)
p_5.Visible = false
p_5.Font = Enum.Font.SourceSans
p_5.Text = ""
p_5.TextColor3 = Color3.fromRGB(0, 0, 0)
p_5.TextSize = 14.000

Setting_2.Name = "Setting"
Setting_2.Parent = Frame
Setting_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Setting_2.BackgroundTransparency = 1.000
Setting_2.Position = UDim2.new(0.779891253, 0, 0.0460829511, 0)
Setting_2.Size = UDim2.new(0.187500104, 0, 0.0428593382, 0)
Setting_2.Font = Enum.Font.RobotoMono
Setting_2.Text = "Setting"
Setting_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Setting_2.TextScaled = true
Setting_2.TextSize = 14.000
Setting_2.TextWrapped = true

p_6.Name = "p"
p_6.Parent = Setting_2
p_6.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
p_6.BorderSizePixel = 0
p_6.Position = UDim2.new(0, 0, 1, 0)
p_6.Size = UDim2.new(1, 0, 0.100000001, 0)
p_6.Visible = false
p_6.Font = Enum.Font.SourceSans
p_6.Text = ""
p_6.TextColor3 = Color3.fromRGB(0, 0, 0)
p_6.TextSize = 14.000

-- Scripts:

local function CMIQTQ_fake_script() -- AutoFram.LocalScript 
	local script = Instance.new('LocalScript', AutoFram)

	local AutoFram = script.Parent.AutoFram
	local AF = script.Parent.AF
	AutoFram.MouseButton1Click:Connect(function()
		if AF == false then
			AutoFram.BackgroundColor3 = Color3.new(0, 0.768627, 1)
			AF = true
		elseif AF == true then
			AutoFram.BackgroundColor3 = Color3.new(0, 0, 0)
			AF = false
			end
		
	end)
	
end
coroutine.wrap(CMIQTQ_fake_script)()
local function GXCK_fake_script() -- AutoFram.Auto 
	local script = Instance.new('LocalScript', AutoFram)

	local AF = script.Parent.AF
	
	spawn(function()
		game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if AF.Value == true then
					local Combat = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
					local Cemara = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker)
					Cemara.CameraShakeInstance.CameraShakeState = {FadingIn = 3, FadingOut = 2, Sustained = 0, Inactive = 1}
					Combat.activeController.timeToNextAttack = 0
					Combat.activeController.hitboxMagnitude = 120
					Combat.activeController.increment = 3
				end
			end)
		end) 
	end)
	
	
	spawn(function()
		game:GetService("RunService").RenderStepped:Connect(function()
			pcall(function()
				if AF.Value == true then
					game:GetService'VirtualUser':CaptureController()
					game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
				end
			end)
		end) 
	end)
end
coroutine.wrap(GXCK_fake_script)()
local function EUIP_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local icon = script.Parent.icon
	local a = script.Parent.AutoFram
	local pv = script.Parent.Pvp
	local i = script.Parent.Island
	local m = script.Parent.Misc
	local s = script.Parent.Setting
	
	a.MouseButton1Click:Connect(function()
		
		icon.AutoFram.Visible = true
		icon.Pvp.Visible = false
		icon.Island.Visible = false
		icon.Misc.Visible = false
		icon.Setting.Visible = false
		
		a.p.Visible = true
		pv.p.Visible = false
		i.p.Visible = false
		m.p.Visible = false
		s.p.Visible = false
		
	end)
	
	pv.MouseButton1Click:Connect(function()
	
		icon.AutoFram.Visible = false
		icon.Pvp.Visible = true
		icon.Island.Visible = false
		icon.Misc.Visible = false
		icon.Setting.Visible = false
	
		a.p.Visible = false
		pv.p.Visible = true
		i.p.Visible = false
		m.p.Visible = false
		s.p.Visible = false
	
	end)
	
	i.MouseButton1Click:Connect(function()
	
		icon.AutoFram.Visible = false
		icon.Pvp.Visible = false
		icon.Island.Visible = true
		icon.Misc.Visible = false
		icon.Setting.Visible = false
	
		a.p.Visible = false
		pv.p.Visible = false
		i.p.Visible = true
		m.p.Visible = false
		s.p.Visible = false
	
	end)
	
	m.MouseButton1Click:Connect(function()
	
		icon.AutoFram.Visible = false
		icon.Pvp.Visible = false
		icon.Island.Visible = false
		icon.Misc.Visible = true
		icon.Setting.Visible = false
	
		a.p.Visible = false
		pv.p.Visible = false
		i.p.Visible = false
		m.p.Visible = true
		s.p.Visible = false
	
	end)
	
	s.MouseButton1Click:Connect(function()
	
		icon.AutoFram.Visible = false
		icon.Pvp.Visible = false
		icon.Island.Visible = false
		icon.Misc.Visible = false
		icon.Setting.Visible = true
	
		a.p.Visible = false
		pv.p.Visible = false
		i.p.Visible = false
		m.p.Visible = false
		s.p.Visible = true
	
	end)
end
coroutine.wrap(EUIP_fake_script)()
