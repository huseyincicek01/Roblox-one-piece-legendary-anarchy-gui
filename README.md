local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cat Hub V 0.0.0 | This Gui Made By Cat#2728", "Synapse")

local Main = Window:NewTab("Npc")
local MainSection = Main:NewSection("NpcStuff")
--script
MainSection:NewButton("Santa", "Gives Santa Present", function()
    workspace.Merchants.SantaMerchant.Clickable.Retum:FireServer()
end)

local Main = Window:NewTab("Teleport")
local MainSection = Main:NewSection("Teleport")
--script
MainSection:NewButton("Sam", "Teleports you to sam", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1302, 218, -1353)
end)

MainSection:NewButton("Drink", "Teleports you to Drink Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1282, 218, -1367)
end)

MainSection:NewButton("Better Drink", "Teleports you to Better Drink Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1493, 260, 2171)
end)

Section:NewButton("Flail", "Teleports you to flail sword seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1110, 217, 3366)
end)

Section:NewButton("Rod Quest", "Teleports you to fish quest", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1699, 216, -326)
end)

Section:NewButton("Krizma Seller", "Teleports you to krizma seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1074, 361, 1670)
end)

Section:NewButton("Sword Seller", "Teleports you to sword seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1007, 224, -3338)
end)

Section:NewButton("Gun Seller", "Teleports you to gun seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1843, 222, 3408)
end)

local Main = Window:NewTab("Island")
local MainSection = Main:NewSection("Island")
--script
