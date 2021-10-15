---MENU---

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("oMonterX_THo HUB V.1.0.0", "Sentinel")

local Tab = Window:NewTab("Main MENU")
local Section = Tab:NewSection("MENU AUTOFarm")

Section:NewButton("Auto Farm#1", "Farm Server VIP", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/GFf5MZ7R", true))()
end)

Section:NewButton("Auto Farm#2", "Farm Server VIP", function()
    getgenv().speed = 100
local function getCar()
    for index, value in next, game:GetService("Workspace")["$cars"]:GetChildren()  do 
        if value.State.Owner.Value == game.Players.LocalPlayer then 
            return value 
        end
    end
end

local car = getCar()


while true do 
    local i = 0 
    car.RootPart.CFrame = CFrame.new(500,1000,500)
    repeat 
        car.RootPart.Anchored = false
        game:GetService("RunService").Heartbeat:wait()
        car.RootPart.Velocity = Vector3.new(math.random(speed/1.1,speed),-100,math.random(0,speed/10))
        i = i + 1 
    until i >= 400 
    car.RootPart.Velocity = Vector3.new(0,0,0)
    car.RootPart.Anchored = true 
end
end)

Section:NewButton("NIF Nitro Boost", "Nitro Boost NIF", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/kvMMHyH3", true))()
end)

Section:NewButton("Anti AFK", "Anti Kicked ", function()
    wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,304,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk Kick Script"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,304,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,304,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by oMonterX_THo"
_b.TextColor3=Color3.new(1,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377379,0)
ab.Size=UDim2.new(0,304,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Script Started"
ab.TextColor3=Color3.new(1,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="You went idle and ROBLOX tried to kick you but we reflected it!"wait(2)ab.Text="Script Re-Enabled"end)
end)

---TELEPORT---

local Tab = Window:NewTab("TELEPORT")
local Section = Tab:NewSection("TELEPORT")

Section:NewButton("Downtown Race", "TELEPORT to Downtown Race", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2913.61548, 8.08807182, -4986.99121, 0.719358087, 0, 0.694639385, 0, 1, 0, -0.694639385, 0, 0.719358087)
end)

Section:NewButton("City Mania", "TELEPORT to City Mania", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2617.62524, 7.81079102, -3591.23828, -1, 0, 0, 0, 1, 0, 0, 0, -1)
end)

Section:NewButton("City Roundabout", "TELEPORT to City Roundabout", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1017.57776, 22.8223152, -2922.66187, 0, 0, -1, 0, 1, 0, 1, 0, 0)
end)

Section:NewButton("Trespasser,s Dash", "TELEPORT to Trespasser,s Dash", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(274.568359, 290.913879, 1744.06665, 0.984812498, -0, -0.173621148, 0, 1, -0, 0.173621148, 0, 0.984812498)
end)

Section:NewButton("Area 52 Quarter Mile", "TELEPORT to Area 52 Quarter Mile", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-825.577515, 365.171509, 520.331116, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

Section:NewButton("Wall of Death", "TELEPORT to Wall of Death", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1978.56897, 20.347044, -1372.7218, 0.500045776, 0, -0.865998983, 0, -1, -0, -0.865998983, 0, -0.500045776)
end)

Section:NewButton("Frenzy Race", "TELEPORT to Frenzy Race", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(908.387878, 12.0350342, -1141.89612, -0.866007447, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, -0.866007447)
end)

Section:NewButton("Midtown Race", "TELEPORT to Midtown Race", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3829.12598, 10.84065247, -2574.33203, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

Section:NewButton("The Grand Race", "TELEPORT to The Grand Race", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1415.6582, 20.399902, -2509.6521, 0, 0, 1, 0, 1, -0, -1, 0, 0)
end)

Section:NewButton("Main Street Drag", "TELEPORT to Main Street Drag", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(935.620361, 40.8095703, -3635.74438, -0.0340052843, -0.126973003, -0.991323352, -0.965938926, 0.258770704, -1.01923943e-05, 0.256526858, 0.957557261, -0.131447792)
end)

Section:NewButton("Arund the world", "TELEPORT to Arund the world", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-891.571228, 100.784027, -940.737976, 0.997859299, 0, 0.0653970614, 0, 1, 0, -0.0653970614, 0, 0.997859299)
end)

Section:NewButton("Madness City Race", "TELEPORT to Madness City Race", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-332.932587, 42.6305962, -3498.77905, 0.382687271, 0.923877954, 0, 0.923877954, -0.38268733, 0, 0, 0, -1)
end)

---Unlocklocation---

local Tab = Window:NewTab("Unlocklocation")
local Section = Tab:NewSection("Unlocklocation")

Section:NewButton("Unlocklocation", "Unlocklocation", function()
    for _,v in pairs(game:GetService("ReplicatedStorage").assets.DiscoverableAreas:GetChildren()) do
        game:GetService("ReplicatedStorage").remotes.AreaDiscovered:FireServer(v.Name)
    end
end)

---Gamepass---

local Tab = Window:NewTab("Gamepasses")
local Section = Tab:NewSection("Gamepasses [Wait for update]")

Section:NewButton("Unlockall Gamepasses", "Wait for update", function()
    print("Clicked")
end)

---Update---

local Tab = Window:NewTab("Update")
local Section = Tab:NewSection("Update")

Section:NewButton("Fixbug", "Fixbug", function()
    print("Clicked")
end)

local Tab = Window:NewTab("Update")
local Section = Tab:NewSection("Update")

Section:NewButton("NEW MENU", "NEW MENU", function()
    print("Clicked")
end)

---Settings---

local Tab = Window:NewTab("Settings")
local Section = Tab:NewSection("Settings")

Section:NewKeybind("CloseGUI", "CloseGUI", Enum.KeyCode.RightControl, function()
	Library:ToggleUI()
end)
