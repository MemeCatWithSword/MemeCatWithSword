-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Name = Instance.new("TextLabel")
local Credits = Instance.new("TextLabel")
local Note = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")
local ACTIVATE = Instance.new("TextButton")
local arrow_forward = Instance.new("ImageButton")
local arrow_back = Instance.new("ImageButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.333580971, 0, 0.183551848, 0)
Frame.Size = UDim2.new(0, 0, 0, 0)

ACTIVATE.Name = "ACTIVATE"
ACTIVATE.Parent = Frame
ACTIVATE.BackgroundColor3 = Color3.fromRGB(40, 255, 16)
ACTIVATE.Position = UDim2.new(0.265625, 0, 0.781544268, 0)
ACTIVATE.Size = UDim2.new(0, 205, 0, 66)
ACTIVATE.Font = Enum.Font.SciFi
ACTIVATE.Text = "ACITVATE UTG"
ACTIVATE.TextColor3 = Color3.fromRGB(0, 0, 0)
ACTIVATE.TextScaled = true
ACTIVATE.TextSize = 14.000
ACTIVATE.TextWrapped = true
ACTIVATE.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character.Humanoid.Health = 0
	loadstring(game:HttpGet("https://pastebin.com/raw/r3Y3PCaz",true))()
end)

