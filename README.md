local UserInputService = game:GetService("UserInputService")
local Players = game:GetService("Players")
local StarterGui = game:GetService("StarterGui")
local player = Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

local jumping = false

task.spawn(function()
    local userId = Players:GetUserIdFromNameAsync("EWEX222")
    local thumbType = Enum.ThumbnailType.HeadShot
    local thumbSize = Enum.ThumbnailSize.Size420x420
    local content = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
    StarterGui:SetCore("SendNotification", {
        Title = "EWEX222",
        Text = "Galaxy Hub Hacker Roblox [🔨EWEX222👑] [ภาษาไทย]",
        Icon = content,
        Duration = 15
    })
end)



local colors = {
    SchemeColor = Color3.fromRGB(255, 165, 0),  
    Background = Color3.fromRGB(40, 40, 40),    
    Header = Color3.fromRGB(30, 30, 30),         
    TextColor = Color3.fromRGB(255, 255, 255),
    ElementColor = Color3.fromRGB(50, 50, 50)
}

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/ZeianRussell/Kavo-UI-Library/main/Movable.source.lua"))()
local Window = Library.CreateLib("Galaxy Hub [ภาษาไทย]", colors)
local Tab = Window:NewTab("โซนคีย์บอร์ด:⌨️")
local Section = Tab:NewSection("โซนคีย์บอร์ด:⌨️")

Section:NewButton("คีย์บอร์ด", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Xxtan31/Ata/main/deltakeyboardcrack.txt", true))()
end)



local Tab = Window:NewTab("โซนโปร:👑")
local Section = Tab:NewSection("โซนโปร:👑")

Section:NewTextBox("วิ่งเร็ว", "วิ่งเร็ว", function(txt)
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)

Section:NewTextBox("กระโดดสูง", "กระโดดสูง", function(txt)
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end)

Section:NewButton("กระโดดออโต้", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/eLE97gg9"))()
end)

Section:NewButton("บิน", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/WhEARt7f"))()
end)



local Tab = Window:NewTab("โปรBlox Fruits:🍎")
local Section = Tab:NewSection("โปรBlox Fruits:🍎")
local Section = Tab:NewSection("Script ค่าย [Quantum Onyx Project]")

Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/flazhy/QuantumOnyx/refs/heads/main/QuantumOnyx.lua"))()
end)

local Section = Tab:NewSection("Script ค่าย [Night Hub]")

Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/WhiteX1208/Scripts/refs/heads/main/BF-Beta.lua"))()
end)



local Tab = Window:NewTab("โปรDead Rails:🧟")
local Section = Tab:NewSection("โปรDead Rails:🧟")

Section:NewButton("[โปรเก็บเงินแดง]กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/hungquan99/HungHub/main/loader.lua"))()
end)


local Tab = Window:NewTab("โปรCar Dealership Tycoon:🚗")
local Section = Tab:NewSection("โปรCar Dealership Tycoon:🚗")

Section:NewButton("[เพิ่มความเร็วของรถ]กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/thebestpersol/thebestpersol/refs/heads/main/cdt%20accel%20changer"))()
end)


local Tab = Window:NewTab("โปรEvade:🧑‍💻")
local Section = Tab:NewSection("โปรEvade:🧑‍💻")

Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/d8MpLcjB"))()
end)


local Tab = Window:NewTab("โปร99 Nights in The Forest:🌳")
local Section = Tab:NewSection("โปร99 Nights in The Forest:🌳")

Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/caomod2077/Script/refs/heads/main/FoxnameHub.lua"))()
end)


local Tab = Window:NewTab("โปร[FPS] Flick:🏹")
local Section = Tab:NewSection("โปร[FPS] Flick:🏹")

Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Joshingtonn123/JoshScript/refs/heads/main/SyrexhubSniperOrDie"))()
end)


local Tab = Window:NewTab("โปรBlade Ball:⚔️⚽")
local Section = Tab:NewSection("โปรBlade Ball:⚔️⚽")

Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/NodeX-Enc/NodeX/refs/heads/main/Main.lua"))()
end)


local Tab = Window:NewTab(">")
local Section = Tab:NewSection("โซนรวม Script ของ Map ต่างๆ [ขอโทษด้วยที่ Script ไม่สามารถเลื่อนฝั่งซ้ายได้")
local Section = Tab:NewSection("ก็เลยต้องมารวมอยู่ที่เดียวครับ")


local Section = Tab:NewSection("โปรThe Forge:⛏️")
Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://haze.wtf/api/script"))()
end)


local Section = Tab:NewSection("โปรFisch:🐟")
Section:NewButton("กดใช้งาน Script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/debunked69/Solixreworkkeysystem/refs/heads/main/solix%20new%20keyui.lua"))()
end)
















local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "ScreenGui"
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

local Toggle = Instance.new("TextButton")
local Corner = Instance.new("UICorner")
Corner.CornerRadius = UDim.new(0.5000, 0)  -- Make the button circular
Corner.Parent = Toggle
Toggle.Name = "Toggle"
Toggle.Parent = ScreenGui
Toggle.BackgroundColor3 = Color3.fromRGB(248, 248, 248)
Toggle.Position = UDim2.new(0,40,0,5)
Toggle.Size = UDim2.new(0, 55, 0, 55)
Toggle.Font = Enum.Font.SourceSans
Toggle.Text = "⚡"
Toggle.TextColor3 = Color3.fromRGB(50,150,255)
Toggle.TextSize = 35
Toggle.Draggable = true
Toggle.MouseButton1Click:Connect(function()
    if Toggle.Text == "⚡" then
        Toggle.Text = "⚡"
    else
        Toggle.Text = "⚡"
    end
    Library:ToggleUI()
end)

local Corner = Instance.new("UICorner")
Corner.Name = "Corner"
Corner.Parent = Toggle
