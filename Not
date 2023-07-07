

--source
local cloneref = cloneref or function(ref) 
    return ref
end

local TweenService = cloneref(game:GetService("TweenService"))
local CoreGui

if gethui and identifyexecutor and identifyexecutor() == "ScriptWare" then
    CoreGui = cloneref(gethui())
elseif gethiddengui then
    CoreGui = cloneref(gethiddengui())
else
    CoreGui = cloneref(game:GetService("CoreGui"))
end

local Debris = cloneref(game:GetService("Debris"))




return function(Arguments)
    coroutine.resume(coroutine.create(function()

        local Text = Arguments.Text or "lorem ipsum"
        local Duration = Arguments.Duration or 5

        local ScreenGui
        if CoreGui:FindFirstChild("Error") then
            ScreenGui = CoreGui:FindFirstChild("Error")
        elseif syn and syn.protect_gui then
            ScreenGui = Instance.new("ScreenGui")
            syn.protect_gui(ScreenGui)
            ScreenGui.Parent = CoreGui
        else
            ScreenGui = Instance.new("ScreenGui",CoreGui)
        end


local ErrorMessage = cloneref(Instance.new("Frame"))
local SideT = cloneref(Instance.new("Frame"))
local UICorner = cloneref(Instance.new("UICorner"))
local ErrorText = cloneref(Instance.new("TextLabel"))
local Togg = cloneref(Instance.new("TextLabel"))
local UICorner_2 = cloneref(Instance.new("UICorner"))
local Circol = cloneref(Instance.new("Frame"))
local UICorner_3 = cloneref(Instance.new("UICorner"))
local ErrorIcon = cloneref(Instance.new("ImageLabel"))
local AsspectRatioConstraint_2 = cloneref(Instance.new("UIAspectRatioConstraint"))
local TextSizeConstraint = cloneref(Instance.new("UISizeConstraint"))

--Properties:

local Children = ScreenGui:GetChildren()
for i,v in pairs(Children) do
    local Tween = TweenService:Create(v,TweenInfo.new(0.5,Enum.EasingStyle.Quad,Enum.EasingDirection.Out),{Position = UDim2.new(ErrorMessage.Position.X.Scale, 0, .1, (i*v.AbsoluteSize.Y*1.2))})
    Tween:Play()
end

ScreenGui.Parent = CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.Name = "Error"



ErrorMessage.Name = "ErrorMessage"
ErrorMessage.Parent = ScreenGui
ErrorMessage.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ErrorMessage.BackgroundTransparency = 0.190
ErrorMessage.BorderColor3 = Color3.fromRGB(0, 0, 0)
ErrorMessage.BorderSizePixel = 0
ErrorMessage.Position = UDim2.new(-1, 0, 0.100000001, 0)
ErrorMessage.Size = UDim2.new(0, 278, 0, 61)

SideT.Name = "SideT"
SideT.Parent = ErrorMessage
SideT.BackgroundColor3 = getgenv().HUDColor
SideT.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideT.BorderSizePixel = 0
SideT.Position = UDim2.new(0.980000019, 3, -0.00100000005, 0)
SideT.Size = UDim2.new(0, 4, 0, 61)

UICorner.CornerRadius = UDim.new(0, 9)
UICorner.Parent = SideT

ErrorText.Name = "ErrorText"
ErrorText.Parent = ErrorMessage
ErrorText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ErrorText.BackgroundTransparency = 9.000
ErrorText.BorderColor3 = Color3.fromRGB(0, 0, 0)
ErrorText.BorderSizePixel = 0
ErrorText.Position = UDim2.new(0.197841823, 0, 0.426229507, 0)
ErrorText.Size = UDim2.new(0, 265, 0, 34)
ErrorText.Font = Enum.Font.Arial
ErrorText.Text = Text
ErrorText.TextColor3 = Color3.fromRGB(255, 255, 255)
ErrorText.TextSize = 17.000
ErrorText.TextWrapped = true
ErrorText.TextXAlignment = Enum.TextXAlignment.Left

Togg.Name = "Togg"
Togg.Parent = ErrorMessage
Togg.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Togg.BackgroundTransparency = 9.000
Togg.BorderColor3 = Color3.fromRGB(0, 0, 0)
Togg.BorderSizePixel = 0
Togg.Position = UDim2.new(0.197841853, 0, 2.98023224e-08, 0)
Togg.Size = UDim2.new(0, 206, 0, 26)
Togg.Font = Enum.Font.ArialBold
Togg.Text = "Toggle"
Togg.TextColor3 = getgenv().HUDColor
Togg.TextSize = 18.000
Togg.TextWrapped = true
Togg.TextXAlignment = Enum.TextXAlignment.Left

UICorner_2.CornerRadius = UDim.new(0, 9)
UICorner_2.Parent = ErrorMessage

Circol.Name = "Circol"
Circol.Parent = ErrorMessage
Circol.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Circol.BorderColor3 = Color3.fromRGB(0, 0, 0)
Circol.BorderSizePixel = 0
Circol.Position = UDim2.new(0.0223741066, 0, 0.14654091, 0)
Circol.Size = UDim2.new(0, 41, 0, 42)

UICorner_3.CornerRadius = UDim.new(0, 9)
UICorner_3.Parent = Circol

ErrorIcon.Name = "ErrorIcon"
ErrorIcon.Parent = ErrorMessage
ErrorIcon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ErrorIcon.BackgroundTransparency = 9.000
ErrorIcon.BorderColor3 = Color3.fromRGB(0, 0, 0)
ErrorIcon.BorderSizePixel = 0
ErrorIcon.Position = UDim2.new(0.809352517, 0, 0.16393441, 0)
ErrorIcon.Rotation = 180.000
ErrorIcon.Size = UDim2.new(0.200000003, -20, 1, -20)
ErrorIcon.Image = "rbxasset://textures/ui/Emotes/ErrorIcon.png"
ErrorIcon.ImageColor3 = getgenv().HUDColor
ErrorIcon.ScaleType = Enum.ScaleType.Fit

AsspectRatioConstraint_2.Name = "AsspectRatioConstraint_2"
AsspectRatioConstraint_2.Parent = ErrorIcon

TextSizeConstraint.Name = "TextSizeConstraint"
TextSizeConstraint.Parent = ErrorMessage
TextSizeConstraint.MinSize = Vector2.new(336, 56)




Debris:AddItem(ErrorMessage, Duration)
local Tween = TweenService:Create(ErrorMessage,TweenInfo.new(1,Enum.EasingStyle.Quad,Enum.EasingDirection.Out),{Position = UDim2.new(0, 0, 0, ErrorMessage.AbsolutePosition.Y)})
Tween:Play()
task.wait(0.6)
local IconTween = TweenService:Create(ErrorIcon,TweenInfo.new(1,Enum.EasingStyle.Quad,Enum.EasingDirection.Out),{Rotation = 0})
IconTween:Play()
wait(Duration)
Tweenn = TweenService:Create(ErrorMessage,TweenInfo.new(1,Enum.EasingStyle.Quad,Enum.EasingDirection.In),{Position = UDim2.new(-1, 0, 0, ErrorMessage.AbsolutePosition.Y)})
Tweenn:Play()
    end))
end
