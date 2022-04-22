-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local ScriptMain = Instance.new("Frame")
local nft = Instance.new("TextButton")
local Dupe = Instance.new("TextButton")
local owner = Instance.new("TextButton")
local Scripts = Instance.new("TextButton")
local Main = Instance.new("TextButton")
local DupeTab = Instance.new("Frame")
local DupeTHebanana = Instance.new("TextButton")
local MainTab = Instance.new("Frame")
local NftTab = Instance.new("Frame")
local ownerTab = Instance.new("Frame")
local ScriptsTab = Instance.new("Frame")
local nadad = Instance.new("Frame")

--Properties:

ScreenGui.Parent = game.CoreGui

ScriptMain.Name = "ScriptMain"
ScriptMain.Parent = ScreenGui
ScriptMain.Active = true
ScriptMain.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
ScriptMain.BorderColor3 = Color3.fromRGB(27, 42, 53)
ScriptMain.Position = UDim2.new(0.140309125, 0, 0.258064508, 0)
ScriptMain.Size = UDim2.new(0, 605, 0, 358)

nft.Name = "nft"
nft.Parent = ScriptMain
nft.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
nft.Position = UDim2.new(0, 0, 0.163323507, 0)
nft.Size = UDim2.new(0, 114, 0, 50)
nft.Font = Enum.Font.SourceSans
nft.Text = "nft"
nft.TextColor3 = Color3.fromRGB(255, 255, 255)
nft.TextScaled = true
nft.TextSize = 14.000
nft.TextWrapped = true

Dupe.Name = "Dupe"
Dupe.Parent = ScriptMain
Dupe.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
Dupe.Position = UDim2.new(0, 0, 0.400073946, 0)
Dupe.Size = UDim2.new(0, 114, 0, 50)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Dupe"
Dupe.TextColor3 = Color3.fromRGB(255, 255, 255)
Dupe.TextScaled = true
Dupe.TextSize = 14.000
Dupe.TextWrapped = true

owner.Name = "owner"
owner.Parent = ScriptMain
owner.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
owner.Position = UDim2.new(0, 0, 0.623399556, 0)
owner.Size = UDim2.new(0, 114, 0, 50)
owner.Font = Enum.Font.SourceSans
owner.Text = "owner"
owner.TextColor3 = Color3.fromRGB(255, 255, 255)
owner.TextScaled = true
owner.TextSize = 14.000
owner.TextWrapped = true

Scripts.Name = "Scripts"
Scripts.Parent = ScriptMain
Scripts.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
Scripts.Position = UDim2.new(0, 0, 0.809711337, 0)
Scripts.Size = UDim2.new(0, 114, 0, 50)
Scripts.Font = Enum.Font.SourceSans
Scripts.Text = "Scripts"
Scripts.TextColor3 = Color3.fromRGB(255, 255, 255)
Scripts.TextScaled = true
Scripts.TextSize = 14.000
Scripts.TextWrapped = true

Main.Name = "Main"
Main.Parent = ScriptMain
Main.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
Main.Position = UDim2.new(0, 0, -0.00148096681, 0)
Main.Size = UDim2.new(0, 114, 0, 50)
Main.Font = Enum.Font.SourceSans
Main.Text = "Main"
Main.TextColor3 = Color3.fromRGB(255, 255, 255)
Main.TextScaled = true
Main.TextSize = 14.000
Main.TextWrapped = true

DupeTab.Name = "DupeTab"
DupeTab.Parent = ScriptMain
DupeTab.Active = true
DupeTab.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
DupeTab.Position = UDim2.new(0.233057857, 0, 0.00558667723, 0)
DupeTab.Size = UDim2.new(0, 464, 0, 355)
DupeTab.Visible = false

DupeTHebanana.Name = "Dupe THebanana"
DupeTHebanana.Parent = DupeTab
DupeTHebanana.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
DupeTHebanana.Position = UDim2.new(-0.00109961629, 0, 0.133022159, 0)
DupeTHebanana.Size = UDim2.new(0, 114, 0, 50)
DupeTHebanana.Font = Enum.Font.SourceSans
DupeTHebanana.Text = "dupe the banana"
DupeTHebanana.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeTHebanana.TextScaled = true
DupeTHebanana.TextSize = 14.000
DupeTHebanana.TextWrapped = true

MainTab.Name = "MainTab"
MainTab.Parent = ScriptMain
MainTab.Active = true
MainTab.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
MainTab.Position = UDim2.new(0.233057857, 0, 0.00837997347, 0)
MainTab.SelectionImageObject = NftTab
MainTab.Size = UDim2.new(0, 464, 0, 351)
MainTab.Visible = false

NftTab.Name = "NftTab"
NftTab.Parent = ScriptMain
NftTab.Active = true
NftTab.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
NftTab.Position = UDim2.new(0.233057857, 0, -0.00279321079, 0)
NftTab.Size = UDim2.new(0, 464, 0, 358)
NftTab.Visible = false

ownerTab.Name = "ownerTab"
ownerTab.Parent = ScriptMain
ownerTab.Active = true
ownerTab.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
ownerTab.Position = UDim2.new(0.244628102, 0, 0.00837997347, 0)
ownerTab.Size = UDim2.new(0, 457, 0, 354)
ownerTab.Visible = false

ScriptsTab.Name = "ScriptsTab"
ScriptsTab.Parent = ScriptMain
ScriptsTab.Active = true
ScriptsTab.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
ScriptsTab.Position = UDim2.new(0.233057857, 0, 0.0111732697, 0)
ScriptsTab.Size = UDim2.new(0, 464, 0, 353)
ScriptsTab.Visible = false

nadad.Name = "nada d+"
nadad.Parent = ScriptMain
nadad.Active = true
nadad.BackgroundColor3 = Color3.fromRGB(27, 42, 53)
nadad.BorderColor3 = Color3.fromRGB(85, 255, 255)
nadad.Position = UDim2.new(0.218181819, 0, 0, 0)
nadad.Size = UDim2.new(0, 9, 0, 357)

-- Scripts:

local function LPVQ_fake_script() -- nft.LocalScript 
	local script = Instance.new('LocalScript', nft)

	script.Parent.MouseButton1Down:connect(function()
		
		script.Parent.ownerTab.visible = false
		script.Parent.DupeTab.visible = false
		script.Parent.NftTab.visible = true
		script.Parent.ScriptsTab.visible = false
		script.Parent.MainTab.visible = false
	
	end)
end
coroutine.wrap(LPVQ_fake_script)()
local function DKCFZS_fake_script() -- Dupe.LocalScript 
	local script = Instance.new('LocalScript', Dupe)

	script.Parent.MouseButton1Down:connect(function()
		
		script.Parent.ownerTab.visible = false
		script.Parent.DupeTab.visible = true
		script.Parent.nftTab.visible = false
		script.Parent.ScriptsTab.visible = false
		script.Parent.MainTab.visible = false
	
	end)
end
coroutine.wrap(DKCFZS_fake_script)()
local function LLZOUB_fake_script() -- owner.LocalScript 
	local script = Instance.new('LocalScript', owner)

	script.Parent.MouseButton1Down:connect(function()
		
		script.Parent.ownerTab.visible = true
		script.Parent.DupeTab.visible = false
		script.Parent.nftTab.visible = false
		script.Parent.ScriptsTab.visible = false
		script.Parent.MainTab.visible = false
	
	end)
end
coroutine.wrap(LLZOUB_fake_script)()
local function AGHYB_fake_script() -- Scripts.LocalScript 
	local script = Instance.new('LocalScript', Scripts)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.ownerTab.visible = false
		script.Parent.DupeTab.visible = false
		script.Parent.nftTab.visible = false
		script.Parent.ScriptsTab.visible = true
		script.Parent.MainTab.visible = false
	
	end)
end
coroutine.wrap(AGHYB_fake_script)()
local function GOMP_fake_script() -- Main.LocalScript 
	local script = Instance.new('LocalScript', Main)

	script.Parent.MouseButton1Down:connect(function()
		
		script.Parent.ownerTab.visible = false
		script.Parent.DupeTab.visible = false
		script.Parent.nftTab.visible = false
		script.Parent.ScriptsTab.visible = false
		script.Parent.MainTab.visible = true
	
	end)
end
coroutine.wrap(GOMP_fake_script)()
