wait(0)

local function callback(Text)
    if Text == "" then
        print("")
    elseif Text == "" then
        print("")
    end
end
------------------------------------------------------------------------------------------------------
local NotificationBindable = Instance.new("BindableFunction")

game.StarterGui:SetCore("SendNotification", {
    Title = "Thank You :D";
    Text = "Thank you for using scripts made by NITRO";
    Icon = "http://www.roblox.com/asset/?id=3264340825";
    Duration = 20;
    Button1 = "Ok";
    Button2 = "";
    Callback = NotificationBindable;
})






-- Gui to Lua
-- Version: 3.2

-- Instances:

local nitrohub = Instance.new("ScreenGui")
local thehub = Instance.new("Frame")
local warningalert = Instance.new("TextLabel")
local GodMode = Instance.new("TextButton")
local jmpower = Instance.new("TextButton")
local allitems = Instance.new("TextButton")
local nitron = Instance.new("TextButton")
local infjump = Instance.new("TextButton")
local acdisable = Instance.new("TextButton")
local tp = Instance.new("TextButton")
local fly = Instance.new("TextButton")
local endtp = Instance.new("TextButton")
local more = Instance.new("TextLabel")
local title = Instance.new("TextLabel")

--Properties:

nitrohub.Name = "nitrohub"
nitrohub.Parent = game.CoreGui
nitrohub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

thehub.Name = "thehub"
thehub.Parent = nitrohub
thehub.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
thehub.Position = UDim2.new(0.0148148276, 0, 0.75429976, 0)
thehub.Size = UDim2.new(0, 383, 0, 182)
thehub.Active = true
thehub.Draggable = true

warningalert.Name = "warning alert"
warningalert.Parent = thehub
warningalert.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
warningalert.BorderColor3 = Color3.fromRGB(35, 35, 35)
warningalert.Position = UDim2.new(0, 0, 0.934065938, 0)
warningalert.Size = UDim2.new(0, 383, 0, 12)
warningalert.Font = Enum.Font.SourceSans
warningalert.Text = "WARNING! THESE SCRIPTS ONLY WORKS ON Tower of Hell!"
warningalert.TextColor3 = Color3.fromRGB(170, 85, 255)
warningalert.TextSize = 14.000

GodMode.Name = "God Mode"
GodMode.Parent = thehub
GodMode.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
GodMode.BorderColor3 = Color3.fromRGB(35, 35, 35)
GodMode.Position = UDim2.new(0.0296735913, 0, 0.203296706, 0)
GodMode.Size = UDim2.new(0, 111, 0, 27)
GodMode.Font = Enum.Font.SourceSansBold
GodMode.Text = "God Mode"
GodMode.TextColor3 = Color3.fromRGB(170, 85, 255)
GodMode.TextSize = 14.000
GodMode.TextWrapped = true
GodMode.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/Q6TvmSva"))() 
end)

jmpower.Name = "jmpower"
jmpower.Parent = thehub
jmpower.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
jmpower.BorderColor3 = Color3.fromRGB(35, 35, 35)
jmpower.Position = UDim2.new(0.028200902, 0, 0.736493289, 0)
jmpower.Size = UDim2.new(0, 111, 0, 27)
jmpower.Font = Enum.Font.SourceSansBold
jmpower.Text = "Set Jump Power"
jmpower.TextColor3 = Color3.fromRGB(170, 85, 255)
jmpower.TextSize = 14.000
jmpower.TextWrapped = true
jmpower.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/zWVTzR5k"))() 
end)

allitems.Name = "allitems"
allitems.Parent = thehub
allitems.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
allitems.BorderColor3 = Color3.fromRGB(35, 35, 35)
allitems.Position = UDim2.new(0.0282008946, 0, 0.423306435, 0)
allitems.Size = UDim2.new(0, 111, 0, 27)
allitems.Font = Enum.Font.SourceSansBold
allitems.Text = "Give All Items"
allitems.TextColor3 = Color3.fromRGB(170, 85, 255)
allitems.TextSize = 14.000
allitems.TextWrapped = true
allitems.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/EDuDZA83"))() 
end)

nitron.Name = "nitron"
nitron.Parent = thehub
nitron.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
nitron.BorderColor3 = Color3.fromRGB(35, 35, 35)
nitron.Position = UDim2.new(0.353210092, 0, 0.736493289, 0)
nitron.Size = UDim2.new(0, 111, 0, 27)
nitron.Font = Enum.Font.SourceSansBold
nitron.Text = "Nitron Admin"
nitron.TextColor3 = Color3.fromRGB(170, 85, 255)
nitron.TextSize = 14.000
nitron.TextWrapped = true
nitron.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/DopeExploits/Nitron/main/README.lua"))() 
end)

infjump.Name = "inf jump"
infjump.Parent = thehub
infjump.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
infjump.BorderColor3 = Color3.fromRGB(35, 35, 35)
infjump.Position = UDim2.new(0.353210092, 0, 0.423306435, 0)
infjump.Size = UDim2.new(0, 111, 0, 27)
infjump.Font = Enum.Font.SourceSansBold
infjump.Text = "Inf Double Jumps"
infjump.TextColor3 = Color3.fromRGB(170, 85, 255)
infjump.TextSize = 14.000
infjump.TextWrapped = true
infjump.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/YxEKjQXe"))() 
end)

acdisable.Name = "acdisable"
acdisable.Parent = thehub
acdisable.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
acdisable.BorderColor3 = Color3.fromRGB(35, 35, 35)
acdisable.Position = UDim2.new(0.352071822, 0, 0.203296706, 0)
acdisable.Size = UDim2.new(0, 111, 0, 27)
acdisable.Font = Enum.Font.SourceSansBold
acdisable.Text = "Disable Anti-Cheat"
acdisable.TextColor3 = Color3.fromRGB(170, 85, 255)
acdisable.TextSize = 14.000
acdisable.TextWrapped = true
acdisable.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/FjgxJNf8"))() 
end)

tp.Name = "tp"
tp.Parent = thehub
tp.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
tp.BorderColor3 = Color3.fromRGB(35, 35, 35)
tp.Position = UDim2.new(0.679302037, 0, 0.736493289, 0)
tp.Size = UDim2.new(0, 111, 0, 27)
tp.Font = Enum.Font.SourceSansBold
tp.Text = "Click TP Tool"
tp.TextColor3 = Color3.fromRGB(170, 85, 255)
tp.TextSize = 14.000
tp.TextWrapped = true
tp.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/gt2i4N3i"))() 
end)

fly.Name = "fly"
fly.Parent = thehub
fly.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
fly.BorderColor3 = Color3.fromRGB(35, 35, 35)
fly.Position = UDim2.new(0.681913018, 0, 0.423306435, 0)
fly.Size = UDim2.new(0, 111, 0, 27)
fly.Font = Enum.Font.SourceSansBold
fly.Text = "Fly (Patched)"
fly.TextColor3 = Color3.fromRGB(170, 85, 255)
fly.TextSize = 14.000
fly.TextWrapped = true
fly.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/63TmQDgR"))() 
end)

endtp.Name = "endtp"
endtp.Parent = thehub
endtp.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
endtp.BorderColor3 = Color3.fromRGB(35, 35, 35)
endtp.Position = UDim2.new(0.680774748, 0, 0.203296706, 0)
endtp.Size = UDim2.new(0, 111, 0, 27)
endtp.Font = Enum.Font.SourceSansBold
endtp.Text = "TP To End"
endtp.TextColor3 = Color3.fromRGB(170, 85, 255)
endtp.TextSize = 14.000
endtp.TextWrapped = true
endtp.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/F6jC1qGz"))() 
end)

more.Name = "more"
more.Parent = thehub
more.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
more.BorderColor3 = Color3.fromRGB(35, 35, 35)
more.Position = UDim2.new(0, 0, 0.626373649, 0)
more.Size = UDim2.new(0, 383, 0, 12)
more.Font = Enum.Font.SourceSansBold
more.Text = "More Scripts // Nitron Admin Works On Almost Every Game!"
more.TextColor3 = Color3.fromRGB(170, 85, 255)
more.TextScaled = true
more.TextSize = 14.000
more.TextWrapped = true

title.Name = "title"
title.Parent = thehub
title.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
title.BorderColor3 = Color3.fromRGB(35, 35, 35)
title.Size = UDim2.new(0, 383, 0, 30)
title.Font = Enum.Font.SourceSansBold
title.Text = "NITRO Hub | Tower of Hell"
title.TextColor3 = Color3.fromRGB(170, 85, 255)
title.TextScaled = true
title.TextSize = 14.000
title.TextWrapped = true
