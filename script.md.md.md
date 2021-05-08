-- Anti-Furry Hub
-- Version: 1.0

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Frame.Position = UDim2.new(0.115060195, 0, 0.2111554, 0)
Frame.Size = UDim2.new(0, 683, 0, 42)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
Frame_2.Position = UDim2.new(0, 0, 0.999999821, 0)
Frame_2.Size = UDim2.new(0, 678, 0, 304)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(-0.0558192208, 0, -0.095238097, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.Gotham
TextLabel.Text = "Anti-Furry Hub"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0131771592, 0, 1.35714269, 0)
TextLabel_2.Size = UDim2.new(0, 660, 0, 50)
TextLabel_2.Font = Enum.Font.Gotham
TextLabel_2.Text = "Anti-Furry Hub"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 20.000

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.0131771592, 0, 1.83333313, 0)
TextLabel_3.Size = UDim2.new(0, 660, 0, 50)
TextLabel_3.Font = Enum.Font.Gotham
TextLabel_3.Text = "Welcome"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 20.000

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0, 0, 3.28571439, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Aimbot"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.Position = UDim2.new(0.3499268, 0, 3.28571439, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Memeus (need r6)"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.Position = UDim2.new(0.686676443, 0, 3.28571439, 0)
TextButton_3.Size = UDim2.new(0, 200, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "tp to baseplate (wip)"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.Position = UDim2.new(0.686676443, 0, 5.35714293, 0)
TextButton_4.Size = UDim2.new(0, 200, 0, 50)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "ESP (IN TESTIN)"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000

TextButton_5.Parent = Frame
TextButton_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.Position = UDim2.new(0.3499268, 0, 5.35714293, 0)
TextButton_5.Size = UDim2.new(0, 200, 0, 50)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "hack game (furry game only and wip)"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000

TextButton_6.Parent = Frame
TextButton_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.Position = UDim2.new(0, 0, 5.16666651, 0)
TextButton_6.Size = UDim2.new(0, 200, 0, 50)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "tp to anti furry game (wip)"
TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.TextSize = 14.000

-- Scripts:

local function BABVLYH_fake_script() -- TextButton.AimbotScript 
	local script = Instance.new('LocalScript', TextButton)

	local button = script.Parent

	local function onButtonActivated()
	--[[
	WARNING!
	This script can lead to a ban if used on more strict games (Phantom Forces, FPS shooters)
	We are not responsible for any consequences on thou.
	
	For the fact of this, this script has been dubbed: "Uncertainary"
	
	To toggle this script, press the LeftShift key, then the Insert key.
--]]

		local PlayerService = game:GetService('Players');
		local player = PlayerService.LocalPlayer;
		local cam = workspace.CurrentCamera;
		local Camera = {};
		local TrackHumanoid = false; -- If set to false, then this will only track players, else we will track NPCs and players.
		local enabled = false;
		local sleight = false;
		local UserInput = game:GetService('UserInputService');
		print("Aimbot ran.")
		if not gui then
			gui = Instance.new('BillboardGui');
			local frame = Instance.new('Frame', gui);

			gui.AlwaysOnTop = true;
			gui.LightInfluence = 0;
			gui.Size = UDim2.new(0, 100, 0, 100);
			frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255);
			frame.BackgroundTransparency = .75;
			frame.Size = UDim2.new(1, 0, 1, 0);
			frame.Rotation = 45;
			frame.BorderSizePixel = 0;
		end;

		function Camera:LockPlayer(p, isNPC)
			if isNPC == true then
				if p and p.Parent:IsA('Model') and p.Parent:FindFirstChild('Torso') then
					local t = p.Parent.Torso.CFrame * Vector3.new(0, -0.25, 0);
					cam.CFrame = CFrame.new(cam.Focus.p, t) * CFrame.new(0, 0, 0.5);
					gui.Parent = p.Parent.Torso;
				end;
			else
				if p and p.Character and p.Character:FindFirstChild('Torso') then
					local t = p.Character.Torso.CFrame * Vector3.new(0, -0.25, 0);
					cam.CFrame = CFrame.new(cam.Focus.p, t) * CFrame.new(0, 0, 0.5);
					gui.Parent = p.Character.Torso;
				end;
			end;
		end;


		game:GetService("RunService").RenderStepped:connect(function()
			if enabled == true then
				for _,v in pairs(PlayerService:GetChildren()) do 
					if v:IsA('Player') and v.Character then
						if v.Character:FindFirstChildOfClass('Humanoid') and v.Character:FindFirstChildOfClass('Humanoid').Health > 0 then
							if v == player then
							else
								Camera:LockPlayer(v);
							end;
						end;
					end;
				end;

				if TrackHumanoid==true then for _,v in pairs(workspace:GetDescendants()) do 
						if v.Parent:IsA('Model') and v.Parent:FindFirstChildOfClass('Humanoid') and v.Parent:FindFirstChildOfClass('Humanoid').Health > 0 then
							if v.Parent.Name == player.Name then
							else
								Camera:LockPlayer(v, true);
							end;
						end;
					end;
				end;
			elseif enabled == false then
				if gui then
					gui.Parent = nil;
				end;
			end;
		end);

		UserInput.InputBegan:connect(function(input)
			if input.KeyCode == Enum.KeyCode.LeftShift then
				sleight = not sleight;
			end;
		end);

		UserInput.InputEnded:connect(function(input)
			if input.KeyCode == Enum.KeyCode.Insert and sleight == true then
				enabled = not enabled;
			end;
		end);

	end

	button.Activated:Connect(onButtonActivated)
	
end
coroutine.wrap(BABVLYH_fake_script)()
local function OTDNDKO_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local UserInputService = game:GetService("UserInputService")

	local gui = script.Parent

	local dragging
	local dragInput
	local dragStart
	local startPos

	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end

	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position

			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)

	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)

	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
	
end
coroutine.wrap(OTDNDKO_fake_script)()
local function EGRF_fake_script() -- TextButton_4.EspScript 
	local script = Instance.new('LocalScript', TextButton_4)

	local button = script.Parent

	local function onButtonActivated()

		-- WRITTEN BY LOUKA @ V3RMILLION
		-- Re-Edited/Configed: V3M1 @V3RMILLION 

		local UNIVERSALESP = {}
		UNIVERSALESP.Version = "1"
		UNIVERSALESP.Modules = {}
		UNIVERSALESP.ModuleCount = 0
		UNIVERSALESP.ModuleSelection = 1
		FreeForAll = true -- Adds esp to teammates

		UNIVERSALESP.Stealth = true -- this will just remove print messages
		UNIVERSALESP.Debug = true
		UNIVERSALESP.FreeForAll = True
		UNIVERSALESP.Studio = false

		function UNIVERSALESP:RegisterModule(name, onrender, norender)
			if UNIVERSALESP.Modules[name] then
				return error("Module \""..name.."\" already registered!")
			else
				UNIVERSALESP:FLog("Registering module \"%s\"", name)
				UNIVERSALESP.Modules[name] = {OnRender = onrender, NoRender = norender, Scratchpad = {}, Enabled = false, Order = UNIVERSALESP.ModuleCount}
				UNIVERSALESP.ModuleCount = UNIVERSALESP.ModuleCount + 1
			end
		end

		function UNIVERSALESP:Log(...)
			if UNIVERSALESP.Stealth then return end
			return print("[- UNIVERSALESP -] ", ...)
		end

		function UNIVERSALESP:FLog(o, ...)
			return UNIVERSALESP:Log(o:format(...))
		end

		local getrawmetatable = getrawmetatable

		---------------------------------------------------------------

		UNIVERSALESP:Log("Loading core utilities...")

		UNIVERSALESP.HookManager = {IdxHooks = {}, NIdxHooks = {}}
		UNIVERSALESP.Utilities = {}
		UNIVERSALESP.Services = {
			Players = game:GetService("Players"),
			Lighting = game:GetService("Lighting"),
			RunService = game:GetService("RunService"),
			UserInputService = game:GetService("UserInputService")
		}
		UNIVERSALESP.Instances = {
			LocalPlayer = UNIVERSALESP.Services.Players.LocalPlayer,
			LocalCharacter = UNIVERSALESP.Services.Players.LocalPlayer.Character,
			LocalCamera = workspace.CurrentCamera,
			LocalMouse = UNIVERSALESP.Services.Players.LocalPlayer:GetMouse()
		}

		function UNIVERSALESP.HookManager:Init()
			if getrawmetatable then
				local ObjectMt = getrawmetatable(game)
				UNIVERSALESP.OriginalIndex = ObjectMt.__index
				UNIVERSALESP.OriginalNewIndex = ObjectMt.__newindex

				ObjectMt.__index = function(self, key)
					local Hook = UNIVERSALESP.HookManager:LookupIndexHook(self, key)
					if Hook then
						return Hook(self)
					else
						return UNIVERSALESP.OriginalIndex(self, key)
					end
				end

				ObjectMt.__newindex = function(self, key, value)
					local Hook = UNIVERSALESP.HookManager:LookupNewIndexHook(self, key)
					if Hook then
						return Hook(self, value)
					else
						return UNIVERSALESP.OriginalNewIndex(self, key, value)
					end
				end

				return true
			end
		end

		function UNIVERSALESP.HookManager:LookupIndexHook(inst, key)
			for _, Hook in next, UNIVERSALESP.HookManager.IdxHooks do
				if UNIVERSALESP.OriginalIndex(inst, "IsA")(inst, Hook.AffectedClass) and Hook.Property == key then
					return Hook.HookFunction
				end
			end
		end

		function UNIVERSALESP.HookManager:LookupNewIndexHook(inst, key)
			for _, Hook in next, UNIVERSALESP.HookManager.NIdxHooks do
				if UNIVERSALESP.OriginalIndex(inst, "IsA")(inst, Hook.AffectedClass) and Hook.Property == key then
					return Hook.HookFunction
				end
			end
		end

		function UNIVERSALESP.HookManager:HookIndex(class, prop, f)
			return table.insert(UNIVERSALESP.HookManager.IdxHooks, {AffectedClass = class, Property = prop, HookFunction = f})
		end

		function UNIVERSALESP.HookManager:HookNewIndex(class, prop, f)
			return table.insert(UNIVERSALESP.HookManager.NIdxHooks, {AffectedClass = class, Property = prop, HookFunction = f})
		end

		function UNIVERSALESP.Utilities:WorldToScreenPoint(...)
			return UNIVERSALESP.Instances.LocalCamera:WorldToScreenPoint(...)
		end

		function UNIVERSALESP.Utilities:PathObstructed(p1, p2, ...)
			local ray = Ray.new(p1, (p2 - p1).unit * 500)
			local haspart, hitpos = workspace:FindPartOnRayWithIgnoreList(ray, {...})
			if haspart then return true, hitpos else return false end
		end

		function UNIVERSALESP.Utilities:GetReplicator()
			return game:FindFirstChild("ClientReplicator", true)
		end

		function UNIVERSALESP.Utilities:GetSize(i)
			if i:IsA("BasePart") then
				return i.Size
			elseif i:IsA("Model") then
				return i:GetExtentsSize()
			end
		end

		function UNIVERSALESP.Utilities:GetPlayers(mode)
			local Result = {}
			for _,player in next, UNIVERSALESP.Services.Players:GetPlayers() do
				if mode == 0 then -- exclude players in current team
					if (player ~= UNIVERSALESP.Instances.LocalPlayer and (UNIVERSALESP.Instances.LocalPlayer.TeamColor ~= player.TeamColor or (FreeForAll or DEBUG))) then
						table.insert(Result, player)
					end
				else -- include everyone
					table.insert(Result, player)
				end
			end
			return Result
		end

		function UNIVERSALESP.Utilities:GetNearestPlayer()
			if not UNIVERSALESP.Instances.LocalPlayer.Character then return end
			local Players = UNIVERSALESP.Utilities:GetPlayers(0)
			local SelectedPlayer, SelectedPlayerPrevDistance = nil, 25000
			for i,v in next, Players do
				if v.Character and v.Character:FindFirstChild("HumanoidRootPart") then
					local Distance = UNIVERSALESP.Utilities:GetDistance(UNIVERSALESP.Instances.LocalPlayer.Character.HumanoidRootPart.Position, v.Character.HumanoidRootPart.Position)
					if Distance < SelectedPlayerPrevDistance then
						SelectedPlayer = v
						SelectedPlayerPrevDistance = Distance
					end
				end
			end
			return SelectedPlayer
		end

		function UNIVERSALESP.Utilities:GetDistance(v1, v2)
			return (v1 - v2).magnitude
		end

		function UNIVERSALESP.Utilities:GetCanvas()
			if not UNIVERSALESP.Canvas then
				if getrawmetatable then
					UNIVERSALESP.Canvas = Instance.new("ScreenGui", game:GetService("CoreGui"))
				else
					UNIVERSALESP.Canvas = Instance.new("ScreenGui", UNIVERSALESP.Services.Players.LocalPlayer.PlayerGui)
				end
			end
			return UNIVERSALESP.Canvas
		end

		UNIVERSALESP.EmptyVector3 = Vector3.new()
		UNIVERSALESP.EmptyCFrame = CFrame.new()

		---------------------------------------------------------------

		--> ESP
		UNIVERSALESP:RegisterModule("ESP", function(Storage)
			local Canvas = UNIVERSALESP.Utilities:GetCanvas()
			local Root = Canvas:FindFirstChild("ESP")
			if not Root then
				Root = Instance.new("Frame")
				Root.Name = "ESP"
				Root.Size = UDim2.new(1, 0, 1, 0)
				Root.BackgroundTransparency = 1
			end

			Root:ClearAllChildren()
			for _, Player in next, UNIVERSALESP.Utilities:GetPlayers(0) do
				if Player.Character and Player.Character:FindFirstChild("Torso") then
					local Locator = Instance.new("Frame")
					Locator.BackgroundColor = Player.TeamColor
					Locator.BackgroundTransparency = .5
					local VPos, VVis =  UNIVERSALESP.Utilities:WorldToScreenPoint(Player.Character.Torso.Position)
					if VVis then
						Locator.Size = UDim2.new(0, -2800 / VPos.z, 0, -4300 / VPos.z)
						Locator.Position = UDim2.new(0, VPos.x - Locator.Size.X.Offset / 2, 0, VPos.y - Locator.Size.Y.Offset / 2)
						Locator.Parent = Root
					else
						Locator:Destroy()
					end
				end
			end

			if not Root.Parent then
				Root.Parent = Canvas
			end
		end)

		---------------------------------------------------------------

		UNIVERSALESP:Log("Loading UI...")

		function UNIVERSALESP:CreateWindow(name, size, timed_close, tween)
			local TopBar = Instance.new("TextLabel")
			TopBar.Name = "NO_CLEAR"
			TopBar.Size = UDim2.new(size.X.Scale, size.X.Offset, 0, 20)
			TopBar.BorderSizePixel = 0
			TopBar.BackgroundColor3 = Color3.new(1, 1, 1)
			TopBar.Text = "UNIVERSAL ESP (1.1)"
			TopBar.TextXAlignment = Enum.TextXAlignment.Left
			TopBar.TextScaled = true
			TopBar.Font = Enum.Font.Code
			TopBar.TextColor3 = Color3.new(0, 0, 0)
			TopBar.Position = UDim2.new(.5, -(size.X.Offset/2), .5, -(size.Y.Offset/2))
			TopBar.Draggable = true
			TopBar.Active = true

			local Window = Instance.new("Frame")
			Window.Name = "Content"
			Window.Size = size
			Window.BackgroundColor3 = Color3.new(0, 1, 0)
			Window.Position = UDim2.new(0, 0, 0, 20)
			Window.BackgroundTransparency = .3
			Window.BorderSizePixel = 0

			if not timed_close then
				local CloseBtn = Instance.new("TextButton", TopBar)
				CloseBtn.Position = UDim2.new(1, -20, 0, 0)
				CloseBtn.Size = UDim2.new(0, 20, 1, 0)
				CloseBtn.BorderSizePixel = 0
				CloseBtn.Name = "CloseBtn"
				CloseBtn.BackgroundColor3 = Color3.new(0,0,0)
				CloseBtn.TextColor3 = Color3.new(1, 0, 0)
				CloseBtn.Text = "X"
				CloseBtn.MouseButton1Click:connect(function()
					TopBar:Destroy()
				end)
			else
				local Countdown = Instance.new("TextLabel", TopBar)
				Countdown.Position = UDim2.new(1, -20, 0, 0)
				Countdown.Size = UDim2.new(0, 20, 1, 0)
				Countdown.BackgroundTransparency = 1
				Countdown.TextColor3 = Color3.new(0, 0, 0)
				Countdown.Text = tostring(timed_close)
				local BackPos
				if tween then
					BackPos = TopBar.Position
					TopBar.Position = UDim2.new(.5, -(size.X.Offset/2), 1, 0)
				end
				spawn(function()
					if tween then
						TopBar:TweenPosition(BackPos, "Out", "Quad", .3, true)
					end
					for i = timed_close-1, 0, -1 do
						wait(1)
						Countdown.Text = tostring(i)
					end
					if not tween then
						TopBar:Destroy()
					else
						TopBar:TweenPosition(UDim2.new(.5, -(size.X.Offset/2), 1, 0), "Out", "Sine", .3, true)
						wait(.3)
						TopBar:Destroy()
					end
				end)
			end

			Window.Parent = TopBar
			TopBar.Parent = UNIVERSALESP.Utilities:GetCanvas()
			return TopBar
		end


		---------------------------------------------------------------

		if not script then script = Instance.new("LocalScript") end
		UNIVERSALESP.UpvalScript = script

		UNIVERSALESP:Log("Hooking functions...")
		UNIVERSALESP.HookManager:Init()
		UNIVERSALESP.HookManager:HookIndex("Player", "Kick", error)
		UNIVERSALESP.HookManager:HookIndex("BasePart", "Size", function(Part)
			local caller_env = getfenv(1)
			if caller_env.script ~= UNIVERSALESP.UpvalScript and caller_env.script.ClassName ~= "CoreScript" then
				if Part.Name == "Head" then
					return UNIVERSALESP.EmptyVector3
				end
			end
			return UNIVERSALESP.OriginalIndex(Part, "Size")
		end)

		UNIVERSALESP.HookManager:HookIndex("BasePart", "CFrame", function(Part)
			local caller_env = getfenv(1)
			if caller_env.script ~= UNIVERSALESP.UpvalScript and caller_env.script.ClassName ~= "CoreScript" then
				if Part.Name == "Head" then
					return UNIVERSALESP.EmptyCFrame
				end
			end
			return UNIVERSALESP.OriginalIndex(Part, "CFrame")
		end)

		UNIVERSALESP.HookManager:HookIndex("BasePart", "Transparency", function(Part)
			local caller_env = getfenv(1)
			if caller_env.script ~= UNIVERSALESP.UpvalScript and caller_env.script.ClassName ~= "CoreScript" then
				if Part.Name == "Head" then
					return 0
				end
			end
			return UNIVERSALESP.OriginalIndex(Part, "Transparency")
		end)

		UNIVERSALESP:Log("Creating menu...")
		UNIVERSALESP.SelectionMenu = UNIVERSALESP:CreateWindow("UNIVERSALESP v"..UNIVERSALESP.Version, UDim2.new(0, 250, 0, 20 * UNIVERSALESP.ModuleCount))
		UNIVERSALESP.SelectionMenu.Position = UDim2.new(0, 10, 0, 10)
		UNIVERSALESP.SelectionMenu.CloseBtn:Destroy()

		for ModuleName, Module in next, UNIVERSALESP.Modules do
			local Entry = Instance.new("TextLabel")
			Entry.BackgroundTransparency = 1
			Entry.BackgroundColor3 = Color3.new(1,1,1)
			Entry.TextColor3 = Color3.new(1, 0, 0)
			Entry.TextScaled = true
			Entry.Font = "Code"
			Entry.TextXAlignment = "Left"
			Entry.Text = ModuleName
			Entry.Position = UDim2.new(0, 0, 0, 20 * Module.Order)
			Entry.Size = UDim2.new(1, 0, 0, 20)
			Entry.Name = tostring(Module.Order)
			Entry.Parent = UNIVERSALESP.SelectionMenu.Content
			Entry.BorderSizePixel = 0

			local Status = Instance.new("Frame")
			Status.BorderSizePixel = 0
			Status.BackgroundColor3 = Color3.new(1, 0, 0)
			Status.Size = UDim2.new(0, 5, 0, 5)
			Status.Position = UDim2.new(1, -10, 0, 8)
			Status.Name = "Status"
			Status.Parent = Entry
		end

		UNIVERSALESP:Log("Connecting UI renderer...")
		UNIVERSALESP.Services.RunService:BindToRenderStep("UNIVERSALESP", Enum.RenderPriority.Last.Value + 1, function()
			for _, Object in next, UNIVERSALESP.Utilities:GetCanvas():GetChildren() do
				if not Object.Name:find("NO_CLEAR") then
					Object:Destroy()
				end
			end

			for i, Module in next, UNIVERSALESP.Modules do
				if Module.Enabled and Module.OnRender then
					local Success, ErrMsg = pcall(Module.OnRender, Module.Scratchpad)
					if not Success then
						UNIVERSALESP:FLog("Panic during execution of \"%s\"::OnRender: %s", i, ErrMsg)
					end
				elseif not Module.Enabled and Module.NoRender then
					local Success, ErrMsg = pcall(Module.NoRender, Module.Scratchpad)
					if not Success then
						UNIVERSALESP:FLog("Panic during execution of \"%s\"::NoRender: %s", i, ErrMsg)
					end
				end
			end
		end)

		UNIVERSALESP:Log("Attaching controls...")
		UNIVERSALESP.Services.UserInputService.InputBegan:connect(function(InputObject)
			local PreviousSelection = UNIVERSALESP.SelectionMenu.Content:FindFirstChild(tostring(UNIVERSALESP.ModuleSelection))
			if PreviousSelection then
				PreviousSelection.BackgroundTransparency = 1
				PreviousSelection.TextColor3 = Color3.new(1, 0, 0)
			end
			if InputObject.KeyCode.Name == "I" then
				UNIVERSALESP.ModuleSelection = UNIVERSALESP.ModuleSelection - 1
				if UNIVERSALESP.ModuleSelection < 0 then
					UNIVERSALESP.ModuleSelection = UNIVERSALESP.ModuleCount - 1
				end
			elseif InputObject.KeyCode.Name == "J" then
				UNIVERSALESP.ModuleSelection = UNIVERSALESP.ModuleSelection + 1
				if UNIVERSALESP.ModuleSelection > UNIVERSALESP.ModuleCount-1 then
					UNIVERSALESP.ModuleSelection = 0
				end
			elseif InputObject.KeyCode.Name == "K" then
				local EntryLabel = UNIVERSALESP.SelectionMenu.Content:FindFirstChild(tostring(UNIVERSALESP.ModuleSelection))
				if EntryLabel then
					local ModuleEntry = UNIVERSALESP.Modules[EntryLabel.Text]
					if ModuleEntry then
						ModuleEntry.Enabled = not ModuleEntry.Enabled
						if ModuleEntry.Enabled then
							EntryLabel.Status.BackgroundColor3 = Color3.new(0, 1, 0)
						else
							EntryLabel.Status.BackgroundColor3 = Color3.new(1, 0, 0)
						end
					end
				end
			elseif InputObject.KeyCode.Name == "p" then 
				UNIVERSALESP.SelectionMenu.Position = UDim2.new(1, -270, 0, 10)
			end
			local EntryLabel = UNIVERSALESP.SelectionMenu.Content:FindFirstChild(tostring(UNIVERSALESP.ModuleSelection))
			if EntryLabel then
				EntryLabel.BackgroundTransparency = .3
				EntryLabel.TextColor3 = Color3.new(0, 0, 0)
			end
		end)

		UNIVERSALESP:Log("Finishing up...")
		local IntroWindow = UNIVERSALESP:CreateWindow("UNIVERSALESP", UDim2.new(0, 350, 0, 200), 7, true)
		local IntroLabel = Instance.new("TextLabel")
		IntroLabel.Font = "Code"
		IntroLabel.TextWrapped = true
		IntroLabel.FontSize = "Size14"
		IntroLabel.TextColor3 = Color3.new(1, 0, 0)
		IntroLabel.BackgroundTransparency = 1
		IntroLabel.Text = "-Universal ESP- Source Code by: LOUKA @ V3RMILLION  Re-Edited/Configed: V3M1 @V3RMILLION                                       ||J = ENABLE MENU||K = TOGGLE ESP||"
		IntroLabel.Parent = IntroWindow.Content
		IntroLabel.Size = UDim2.new(1, 0, 1, 0)

		UNIVERSALESP:Log("Initialization complete!")
		-- Perform expected button action(s) here

	end

	button.Activated:Connect(onButtonActivated)
	
end
coroutine.wrap(EGRF_fake_script)()
