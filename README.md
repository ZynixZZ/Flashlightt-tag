-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_4 = Instance.new("UICorner")
local TextButton1 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton2 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local CloseButton = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local MinusButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton3 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local HealthBox = Instance.new("TextBox")
local UICorner_10 = Instance.new("UICorner")
local TextButton4 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TextButton5 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TextButton6 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local JumpText = Instance.new("TextBox")
local UICorner_14 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0296549238, 0, 0.0550964214, 0)
Frame.Size = UDim2.new(0, 351, 0, 216)
Frame.Active = true
Frame.Draggable = true


TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 351, 0, 32)
TextLabel.Font = Enum.Font.FredokaOne
TextLabel.Text = "Flashlight tag | by ZSploitz"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

UICorner.Parent = TextLabel

UICorner_2.Parent = Frame

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.390313387, 0, 0.185185179, 0)
TextButton.Size = UDim2.new(0, 102, 0, 24)
TextButton.Font = Enum.Font.FredokaOne
TextButton.Text = "WalkSpeed"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

UICorner_3.Parent = TextButton

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.726495743, 0, 0.185185179, 0)
TextBox.Size = UDim2.new(0, 71, 0, 24)
TextBox.Font = Enum.Font.FredokaOne
TextBox.Text = "Speed Here"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 12.000

UICorner_4.Parent = TextBox

TextButton1.Name = "TextButton1"
TextButton1.Parent = Frame
TextButton1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.BorderSizePixel = 0
TextButton1.Position = UDim2.new(0.0626780614, 0, 0.185185179, 0)
TextButton1.Size = UDim2.new(0, 102, 0, 24)
TextButton1.Font = Enum.Font.FredokaOne
TextButton1.Text = "Noclip"
TextButton1.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton1.TextSize = 14.000

UICorner_5.Parent = TextButton1

TextButton2.Name = "TextButton2"
TextButton2.Parent = Frame
TextButton2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton2.BorderSizePixel = 0
TextButton2.Position = UDim2.new(0.678062677, 0, 0.842592597, 0)
TextButton2.Size = UDim2.new(0, 102, 0, 24)
TextButton2.Font = Enum.Font.FredokaOne
TextButton2.Text = "Other Gui"
TextButton2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton2.TextSize = 14.000

UICorner_6.Parent = TextButton2

CloseButton.Name = "CloseButton"
CloseButton.Parent = Frame
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.903134048, 0, 0.0185185187, 0)
CloseButton.Size = UDim2.new(0, 23, 0, 24)
CloseButton.Font = Enum.Font.Creepster
CloseButton.Text = "X"
CloseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.TextSize = 16.000

UICorner_7.Parent = CloseButton

MinusButton.Name = "MinusButton"
MinusButton.Parent = Frame
MinusButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MinusButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
MinusButton.BorderSizePixel = 0
MinusButton.Position = UDim2.new(0.82051301, 0, 0.0185185187, 0)
MinusButton.Size = UDim2.new(0, 23, 0, 24)
MinusButton.Font = Enum.Font.Creepster
MinusButton.Text = "-"
MinusButton.TextColor3 = Color3.fromRGB(0, 0, 0)
MinusButton.TextSize = 20.000

UICorner_8.Parent = MinusButton

TextButton3.Name = "TextButton3"
TextButton3.Parent = Frame
TextButton3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton3.BorderSizePixel = 0
TextButton3.Position = UDim2.new(0.390313387, 0, 0.347222209, 0)
TextButton3.Size = UDim2.new(0, 102, 0, 24)
TextButton3.Font = Enum.Font.FredokaOne
TextButton3.Text = "Health"
TextButton3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton3.TextSize = 14.000

UICorner_9.Parent = TextButton3

HealthBox.Name = "HealthBox"
HealthBox.Parent = Frame
HealthBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HealthBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
HealthBox.BorderSizePixel = 0
HealthBox.Position = UDim2.new(0.726495743, 0, 0.347222209, 0)
HealthBox.Size = UDim2.new(0, 71, 0, 24)
HealthBox.Font = Enum.Font.FredokaOne
HealthBox.Text = "Health here"
HealthBox.TextColor3 = Color3.fromRGB(0, 0, 0)
HealthBox.TextSize = 12.000

UICorner_10.Parent = HealthBox

TextButton4.Name = "TextButton4"
TextButton4.Parent = Frame
TextButton4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton4.BorderSizePixel = 0
TextButton4.Position = UDim2.new(0.0626780614, 0, 0.347222209, 0)
TextButton4.Size = UDim2.new(0, 102, 0, 24)
TextButton4.Font = Enum.Font.FredokaOne
TextButton4.Text = "Walk on Walls"
TextButton4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton4.TextSize = 14.000

UICorner_11.Parent = TextButton4

TextButton5.Name = "TextButton5"
TextButton5.Parent = Frame
TextButton5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton5.BorderSizePixel = 0
TextButton5.Position = UDim2.new(0.0626780614, 0, 0.513888896, 0)
TextButton5.Size = UDim2.new(0, 102, 0, 24)
TextButton5.Font = Enum.Font.FredokaOne
TextButton5.Text = "ESP"
TextButton5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton5.TextSize = 14.000

UICorner_12.Parent = TextButton5

TextButton6.Name = "TextButton6"
TextButton6.Parent = Frame
TextButton6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton6.BorderSizePixel = 0
TextButton6.Position = UDim2.new(0.390313387, 0, 0.513888896, 0)
TextButton6.Size = UDim2.new(0, 102, 0, 24)
TextButton6.Font = Enum.Font.FredokaOne
TextButton6.Text = "Jump Power"
TextButton6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton6.TextSize = 14.000

UICorner_13.Parent = TextButton6

JumpText.Name = "JumpText"
JumpText.Parent = Frame
JumpText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpText.BorderColor3 = Color3.fromRGB(0, 0, 0)
JumpText.BorderSizePixel = 0
JumpText.Position = UDim2.new(0.720797718, 0, 0.513888896, 0)
JumpText.Size = UDim2.new(0, 71, 0, 24)
JumpText.Font = Enum.Font.FredokaOne
JumpText.Text = "Jump P here"
JumpText.TextColor3 = Color3.fromRGB(0, 0, 0)
JumpText.TextSize = 12.000

UICorner_14.Parent = JumpText

-- Scripts:

TextButton.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = TextBox.Text
end)

TextButton1.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ZynixZZ/Nocilp-gui/main/README.md"))()
end)

TextButton3.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.MaxHealth = HealthBox.Text
end)

TextButton2.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/xtrey10x/xtrey10x-hub/main/FlashLight%20Tag"))()
end)

TextButton4.MouseButton1Down:Connect(function()
	loadstring(game:HttpGetAsync("https://pastebin.com/raw/RY9cBbdG"))()
end)

TextButton5.MouseButton1Down:Connect(function()
	loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/ZynixZZ/ESP/main/README.md"))()
end)

TextButton6.MouseButton1Down:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = JumpText.Text
end)
