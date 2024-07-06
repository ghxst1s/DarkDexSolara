-- Instances:

local Tutorial = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local CloseButton = Instance.new("TextLabel")
local Source = Instance.new("TextBox")
local SourceCorner = Instance.new("UICorner")
local BetaLabel = Instance.new("TextLabel")
local ExecuteButton = Instance.new("TextButton")
local ExecuteCorner = Instance.new("UICorner")
local ClearButton = Instance.new("TextButton")
local ClearCorner = Instance.new("UICorner")
local InjectButton = Instance.new("TextButton")
local InjectCorner = Instance.new("UICorner")
local StatusDot = Instance.new("Frame")
local StatusCorner = Instance.new("UICorner")
local Layout = Instance.new("UIListLayout")
local LibraryButton = Instance.new("TextButton")
local LibraryCorner = Instance.new("UICorner")

local LibraryUI = Instance.new("Frame")
local BackButton = Instance.new("TextButton")
local BackCorner = Instance.new("UICorner")
local InfYieldButton = Instance.new("TextButton")
local InfYieldCorner = Instance.new("UICorner")
local DexExplorerButton = Instance.new("TextButton")
local DexExplorerCorner = Instance.new("UICorner")

-- Properties:

Tutorial.Name = "Tutorial"
Tutorial.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = Tutorial
Main.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Main.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.0538807958, 0, 0.0433307551, 0)
Main.Size = UDim2.new(0, 713, 0, 409)

Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0, 0, 0.0146699268, 0)
Frame.Size = UDim2.new(0, 713, 0, 409)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.00841514766, 0, 0.0146699268, 0)
TextLabel.Size = UDim2.new(0, 57, 0, 40)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Spectra"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 16.000

CloseButton.Name = "CloseButton"
CloseButton.Parent = TextLabel
CloseButton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
CloseButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(1, 0, -0.150000006, 0)
CloseButton.Size = UDim2.new(0, 50, 0, 33)
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Text = "X"
CloseButton.TextColor3 = Color3.fromRGB(170, 0, 0)
CloseButton.TextSize = 16.000

Source.Name = "Source"
Source.Parent = Frame
Source.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Source.BorderColor3 = Color3.fromRGB(0, 0, 0)
Source.BorderSizePixel = 0
Source.Position = UDim2.new(0.0126227206, 0, 0.198044017, 0)
Source.Size = UDim2.new(0, 694, 0, 316)
Source.Font = Enum.Font.SourceSans
Source.MultiLine = true
Source.Text = ""
Source.TextColor3 = Color3.fromRGB(255, 255, 255)
Source.TextSize = 14.000
Source.TextXAlignment = Enum.TextXAlignment.Left
Source.TextYAlignment = Enum.TextYAlignment.Top

SourceCorner.Parent = Source

BetaLabel.Parent = Frame
BetaLabel.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
BetaLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
BetaLabel.BorderSizePixel = 0
BetaLabel.Position = UDim2.new(0.399719507, 0, 0.0317848399, 0)
BetaLabel.Size = UDim2.new(0, 95, 0, 26)
BetaLabel.Font = Enum.Font.SourceSans
BetaLabel.Text = "Beta"
BetaLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
BetaLabel.TextSize = 16.000

InjectButton.Name = "InjectButton"
InjectButton.Parent = Frame
InjectButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
InjectButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
InjectButton.BorderSizePixel = 0
InjectButton.Position = UDim2.new(0.05, 0, 0.0953545198, 0)
InjectButton.Size = UDim2.new(0, 86, 0, 26)
InjectButton.Font = Enum.Font.SourceSans
InjectButton.Text = "Inject"
InjectButton.TextColor3 = Color3.fromRGB(0, 0, 0)
InjectButton.TextSize = 14.000

InjectCorner.Parent = InjectButton

ExecuteButton.Name = "ExecuteButton"
ExecuteButton.Parent = Frame
ExecuteButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ExecuteButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExecuteButton.BorderSizePixel = 0
ExecuteButton.Position = UDim2.new(0.842917264, 0, 0.0953545198, 0)
ExecuteButton.Size = UDim2.new(0, 86, 0, 26)
ExecuteButton.Font = Enum.Font.SourceSans
ExecuteButton.Text = "Execute"
ExecuteButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ExecuteButton.TextSize = 14.000
ExecuteButton.Active = false -- Initially disabled

ExecuteCorner.Parent = ExecuteButton

ClearButton.Name = "ClearButton"
ClearButton.Parent = Frame
ClearButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ClearButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ClearButton.BorderSizePixel = 0
ClearButton.Position = UDim2.new(0.701262295, 0, 0.0953545198, 0)
ClearButton.Size = UDim2.new(0, 86, 0, 26)
ClearButton.Font = Enum.Font.SourceSans
ClearButton.Text = "Clear"
ClearButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ClearButton.TextSize = 14.000

ClearCorner.Parent = ClearButton

StatusDot.Name = "StatusDot"
StatusDot.Parent = Frame
StatusDot.BackgroundColor3 = Color3.fromRGB(255, 0, 0) -- Red initially
StatusDot.BorderColor3 = Color3.fromRGB(0, 0, 0)
StatusDot.BorderSizePixel = 0
StatusDot.Position = UDim2.new(0.95, 0, 0.02, 0) -- Positioned at the top right corner
StatusDot.Size = UDim2.new(0, 20, 0, 20) -- Small dot

StatusCorner.Parent = StatusDot
StatusCorner.CornerRadius = UDim.new(0.5, 0) -- Makes the dot round

LibraryButton.Name = "LibraryButton"
LibraryButton.Parent = Frame
LibraryButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
LibraryButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
LibraryButton.BorderSizePixel = 0
LibraryButton.Position = UDim2.new(0.35, 0, 0.0953545198, 0)
LibraryButton.Size = UDim2.new(0, 86, 0, 26)
LibraryButton.Font = Enum.Font.SourceSans
LibraryButton.Text = "Library"
LibraryButton.TextColor3 = Color3.fromRGB(0, 0, 0)
LibraryButton.TextSize = 14.000

LibraryCorner.Parent = LibraryButton

Layout.Parent = Main
Layout.SortOrder = Enum.SortOrder.LayoutOrder

LibraryUI.Name = "LibraryUI"
LibraryUI.Parent = Tutorial
LibraryUI.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
LibraryUI.BorderColor3 = Color3.fromRGB(0, 0, 0)
LibraryUI.BorderSizePixel = 0
LibraryUI.Position = UDim2.new(0.0538807958, 0, 0.0433307551, 0)
LibraryUI.Size = UDim2.new(0, 713, 0, 409)
LibraryUI.Visible = false

BackButton.Name = "BackButton"
BackButton.Parent = LibraryUI
BackButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
BackButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
BackButton.BorderSizePixel = 0
BackButton.Position = UDim2.new(0.05, 0, 0.0953545198, 0)
BackButton.Size = UDim2.new(0, 86, 0, 26)
BackButton.Font = Enum.Font.SourceSans
BackButton.Text = "Back"
BackButton.TextColor3 = Color3.fromRGB(0, 0, 0)
BackButton.TextSize = 14.000

BackCorner.Parent = BackButton

InfYieldButton.Name = "InfYieldButton"
InfYieldButton.Parent = LibraryUI
InfYieldButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
InfYieldButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
InfYieldButton.BorderSizePixel = 0
InfYieldButton.Position = UDim2.new(0.35, 0, 0.0953545198, 0)
InfYieldButton.Size = UDim2.new(0, 86, 0, 26)
InfYieldButton.Font = Enum.Font.SourceSans
InfYieldButton.Text = "Inf Yield"
InfYieldButton.TextColor3 = Color3.fromRGB(0, 0, 0)
InfYieldButton.TextSize = 14.000

InfYieldCorner.Parent = InfYieldButton

DexExplorerButton.Name = "DexExplorerButton"
DexExplorerButton.Parent = LibraryUI
DexExplorerButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
DexExplorerButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
DexExplorerButton.BorderSizePixel = 0
DexExplorerButton.Position = UDim2.new(0.65, 0, 0.0953545198, 0)
DexExplorerButton.Size = UDim2.new(0, 86, 0, 26)
DexExplorerButton.Font = Enum.Font.SourceSans
DexExplorerButton.Text = "Dex Explorer"
DexExplorerButton.TextColor3 = Color3.fromRGB(0, 0, 0)
DexExplorerButton.TextSize = 14.000

DexExplorerCorner.Parent = DexExplorerButton

-- Scripts:

local function makeFrameDraggable(frame)
    local UserInputService = game:GetService("UserInputService")
    local dragging, dragInput, dragStart, startPos

    local function update(input)
        local delta = input.Position - dragStart
        frame.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
    end

    frame.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
            dragging = true
            dragStart = input.Position
            startPos = frame.Position

            input.Changed:Connect(function()
                if input.UserInputState == Enum.UserInputState.End then
                    dragging = false
                end
            end)
        end
    end)

    frame.InputChanged:Connect(function(input)
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

local injected = false

ClearButton.MouseButton1Click:Connect(function()
    Source.Text = "" -- Clear the Source TextBox
end)

ExecuteButton.MouseButton1Click:Connect(function()
    if injected then
        local code = Source.Text
        local success, errorMessage = pcall(function()
            loadstring(code)()
        end)
        if not success then
            warn("Error executing script: " .. errorMessage)
        end
    else
        warn("Script cannot be executed. Please inject first.")
    end
end)

InjectButton.MouseButton1Click:Connect(function()
    InjectButton.Text = "Injecting..."
    StatusDot.BackgroundColor3 = Color3.fromRGB(255, 165, 0) -- Orange while injecting
    wait(2) -- Simulate the delay of injection
    injected = true
    InjectButton.Text = "Inject"
    ExecuteButton.Active = true -- Enable the Execute button
    ExecuteButton.TextColor3 = Color3.fromRGB(255, 255, 255) -- Change text color to indicate activation
    StatusDot.BackgroundColor3 = Color3.fromRGB(0, 255, 0) -- Green once injected
end)

LibraryButton.MouseButton1Click:Connect(function()
    Main.Visible = false
    LibraryUI.Visible = true
end)

BackButton.MouseButton1Click:Connect(function()
    LibraryUI.Visible = false
    Main.Visible = true
end)

InfYieldButton.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

DexExplorerButton.MouseButton1Click:Connect(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/peyton2465/Dex/master/out.lua"))()
end)

makeFrameDraggable(Main)
makeFrameDraggable(LibraryUI)
