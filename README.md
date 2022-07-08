local GUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/aaaa"))() local UI = GUI:CreateWindow("AEGONA HUB I BLOXFRUIT","---------") local win = UI:addPage("Main1",1,true,6) local Home = UI:addPage("Main2",1,true,6) local home1 = UI:addPage("Miss..",1,true,6) local hack = UI:addPage("Hack",1,true,6) local player = game.Players.LocalPlayer.Character local health = player.Humanoid local teleportgame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame local gg1 = UI:addPage("Main3",1,true,6)

players = {}

for i,v in pairs(game:GetService("Players"):GetChildren()) do table.insert(players,v.Name) end

win:addLabel("-- Teleport Main1 --")

win:addButton("Teleport Start",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1106.920654296875, 16.273618698120117, 1445.0765380859375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

win:addButton("Teleport Jungle",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1320.5711669921875, 11.852054595947266, 443.2662048339844) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

win:addButton("Teleport fortree",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4912.26025390625, 20.65204429626465, 4255.9365234375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

win:addButton("Teleport MagMa",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5323.2509765625, 8.59068489074707, 8408.4863281255) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Home:addButton("Teleport Villgie",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1174.0557861328125, 4.752061367034912, 3844.337646484375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Home:addButton("Teleport Colosseum",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1391.7447509765625, 4.8410964012146, -2849.1728515625) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Home:addButton("Teleport ice",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1112.465576171875, 4.9552178382873535, -1193.3912353515625) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Home:addButton("Teleport Kalata",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4080.496337890625, 30.742443084716797, -1816.3831787109375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Home:addButton("Teleport Town",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-649.586181640625, 7.852232456207275, 1584.8131103515625) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

Home:addButton("Teleport Sky1",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4871.09912109375, 717.6699829101562, -2620.962890625) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

gg1:addButton("Teleport Sky2",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7898.86669921875, 5545.49169921875, -407.3098449707031) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

gg1:addButton("Teleport Sand Town",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(896.9306030273438, 27.974153518676758, 4467.33349609375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

gg1:addButton("Teleport Water land",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5185.974609375, 65.51243591308594, 4187.59912109375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

gg1:addButton("Teleport Prison",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4855.091796875, 5.652120113372803, 732.314208984375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

gg1:addButton("Teleport Marines V.Tes",function()

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2606.734619140625, 6.888829708099365, 2056.43115234375) game.Players.LocalPlayer.Character.Humanoid.Health = 0

end)

home1:addToggle("Auto Setspawn",function(value) while wait(.1) do local string_1 = "SetSpawnPoint"; local Target = game:GetService("ReplicatedStorage").Remotes["CommF_"]; Target:InvokeServer(string_1); end end)

hack:addButton("👾ESP Player👾 เปิด",function() _G.ESP = true while wait() do pcall(function() for i,v in pairs(game.Players:GetChildren()) do if not v.Character.Head:FindFirstChild("ESP") then local BillboardGui = Instance.new("BillboardGui") local TextLabel = Instance.new("TextLabel") BillboardGui.Parent = v.Character.Head BillboardGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling BillboardGui.Active = true BillboardGui.Name = "ESP" BillboardGui.AlwaysOnTop = true BillboardGui.LightInfluence = 1.000 BillboardGui.Size = UDim2.new(0, 200, 0, 50) BillboardGui.StudsOffset = Vector3.new(0, 2.5, 0) TextLabel.Parent = BillboardGui TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255) TextLabel.BackgroundTransparency = 1.000 TextLabel.Size = UDim2.new(0, 200, 0, 50) TextLabel.Font = Enum.Font.GothamBold TextLabel.Text = v.Name TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255) TextLabel.TextScaled = true TextLabel.TextSize = 14.000 TextLabel.TextStrokeTransparency = 0.000 TextLabel.TextWrapped = true end end end) end end)

hack:addToggle("grab box Beta ห้ามใช้",function(value) while wait(1) do game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1112.465576171875, 4.9552178382873535, -1193.3912353515625) game.Players.LocalPlayer.Character.Humanoid.Health = 0 wait(6) game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1404.22632, 96.0051575, -1294.61719, -0.996191859, 0, 0.0871884301, 0, 1, 0, -0.0871884301, 0, -0.996191859) end end)
