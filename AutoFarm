
local v_2400 = game:GetService("Players")
local v_6116 = game:GetService("RunService")
local v_536176 = game:GetService("UserInputService")
local v_956923 = game:GetService("VirtualUser")
local v_428177 = v_2400.v_428177
local v_129823 = Instance.new("ScreenGui")
v_129823.Name = "VenomHubScreenGui"
v_129823.ResetOnSpawn = false
v_129823.Parent = v_428177:WaitForChild("PlayerGui")
local v_395979 = Instance.new("Frame")
v_395979.Name = "VenomHubMainFrame"
v_395979.Size = UDim2.new(0, 320, 0, 390)
v_395979.Position = UDim2.new(0.05, 0, 0.1, 0)
v_395979.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
v_395979.BorderSizePixel = 2
v_395979.Visible = false
v_395979.Active = true
v_395979.Selectable = true
v_395979.Parent = v_129823
local v_515303 = Instance.new("TextLabel")
v_515303.Name = "TitleBar"
v_515303.Size = UDim2.new(1, 0, 0, 30)
v_515303.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
v_515303.TextColor3 = Color3.fromRGB(255, 255, 255)
v_515303.Font = Enum.Font.SourceSansBold
v_515303.TextSize = 18
v_515303.Text = "Чёрно хаб (Drag / Press K to show/hide)"
v_515303.Parent = v_395979
local v_366336 = Instance.new("TextLabel")
v_366336.Size = UDim2.new(1, 0, 0, 20)
v_366336.Position = UDim2.new(0, 0, 1, -20)
v_366336.BackgroundTransparency = 1
v_366336.TextColor3 = Color3.fromRGB(255, 255, 255)
v_366336.Font = Enum.Font.SourceSansSemibold
v_366336.TextSize = 16
v_366336.Text = "By bestik_"
v_366336.Parent = v_395979
local v_987896 = Instance.new("ScrollingFrame")
v_987896.Name = "ContentFrame"
v_987896.Size = UDim2.new(1, -10, 1, -60)
v_987896.Position = UDim2.new(0, 5, 0, 35)
v_987896.BackgroundTransparency = 1
v_987896.BorderSizePixel = 0
v_987896.ScrollingDirection = Enum.ScrollingDirection.Y
v_987896.ScrollBarThickness = 4
v_987896.Parent = v_395979
local v_276892 = Instance.new("UIListLayout")
v_276892.Padding = UDim.new(0,5)
v_276892.Parent = v_987896
do
local v_405021 = false
local v_640294 = Vector2.new()
v_395979.InputBegan:Connect(v_663625(v_746085)
if v_746085.UserInputType == Enum.UserInputType.MouseButton1 then
v_405021 = true
v_640294 = v_746085.Position - v_395979.AbsolutePosition
end
end)
v_395979.InputEnded:Connect(v_663625(v_746085)
if v_746085.UserInputType == Enum.UserInputType.MouseButton1 then
v_405021 = false
end
end)
v_536176.InputChanged:Connect(v_663625(v_746085)
if v_405021 and v_746085.UserInputType == Enum.UserInputType.MouseMovement then
local v_920838 = v_746085.Position - v_640294
v_395979.Position = UDim2.fromOffset(v_920838.X, v_920838.Y)
end
end)
end
v_536176.InputBegan:Connect(v_663625(v_746085, gp)
if not gp and v_746085.KeyCode == Enum.KeyCode.K then
v_395979.Visible = not v_395979.Visible
end
end)
local v_115650 = false
local v_914296 = nil
local v_583360
local v_792195 = 50
local v_663625 Fly_Enable()
if v_115650 then return end
v_115650 = true
v_583360 = v_6116.RenderStepped:Connect(v_663625(dt)
if not v_115650 then return end
local v_539682 = v_428177.Character
local v_19210 = v_539682 and v_539682:FindFirstChild("HumanoidRootPart")
if v_19210 then
local v_199216 = workspace.CurrentCamera
local v_37411 = Vector3.new()
if v_536176:IsKeyDown(Enum.KeyCode.W) then
v_37411 += v_199216.CFrame.LookVector
end
if v_536176:IsKeyDown(Enum.KeyCode.S) then
v_37411 -= v_199216.CFrame.LookVector
end
if v_536176:IsKeyDown(Enum.KeyCode.A) then
v_37411 -= v_199216.CFrame.RightVector
end
if v_536176:IsKeyDown(Enum.KeyCode.D) then
v_37411 += v_199216.CFrame.RightVector
end
if v_536176:IsKeyDown(Enum.KeyCode.Space) then
v_37411 += Vector3.new(0,1,0)
end
if v_536176:IsKeyDown(Enum.KeyCode.LeftControl) then
v_37411 -= Vector3.new(0,1,0)
end
if v_37411.Magnitude > 0 then
v_19210.CFrame = v_19210.CFrame + (v_37411.Unit * v_792195 * dt)
end
end
end)
end
local v_663625 Fly_Disable()
if not v_115650 then return end
v_115650 = false
if v_583360 then
v_583360:Disconnect()
v_583360 = nil
end
end
local v_814077 = false
local v_469424
local v_836160
local v_59591 = {
["tabootvcat"] = true,
["Revenantic"] = true,
["Saabor"] = true,
["MoIitor"] = true,
["IAmUnderAMask"] = true,
["SheriffGorji"] = true,
["xXFireyScorpionXx"] = true,
["LoChips"] = true,
["DeliverCreations"] = true,
["TDXiswinning"] = true,
["TZZV"] = true,
["FelixVenue"] = true,
["SIEGFRlED"] = true,
["ARRYvvv"] = true,
["z_papermoon"] = true,
["Malpheasance"] = true,
["ModHandIer"] = true,
["valphex"] = true,
["J_anday"] = true,
["tvdisko"] = true,
["yIlehs"] = true,
["COLOSSUSBUILTOFSTEEL"] = true,
["SeizedHolder"] = true,
["r3shape"] = true,
["RVVZ"] = true,
["adurize"] = true,
["codedcosmetics"] = true,
["QuantumCaterpillar"] = true,
["FractalHarmonics"] = true,
["GalacticSculptor"] = true,
["oTheSilver"] = true,
["Kretacaous"] = true,
["icarus_xs1goliath"] = true,
["GlamorousDradon"] = true,
["rainjeremy"] = true,
["parachuter2000"] = true,
["faintermercury"] = true,
["harht"] = true,
["Sansek1252"] = true,
["Snorpuwu"] = true,
["BenAzoten"] = true,
["Cand1ebox"] = true,
["KeenlyAware"] = true,
["mrzued"] = true,
["BruhmanVIII"] = true,
["Nystesia"] = true,
["fausties"] = true,
["zateopp"] = true,
["Iordnabi"] = true,
["ReviveTheDevil"] = true,
["jake_jpeg"] = true,
["UncrossedMeat3888"] = true,
["realpenyy"] = true,
["karateeeh"] = true,
["JayyMlg"] = true,
["Lo_Chips"] = true,
["Avelosky"] = true,
["king_ab09"] = true,
["TigerLe123"] = true,
["Dalvanuis"] = true,
["iSonMillions"] = true,
["DieYouOder"] = true,
["whosframed"] = true
}
local v_663625 CheckAdmins()
for _, plr in ipairs(v_2400:GetPlayers()) do
if v_59591[plr.Name] then
v_428177:Kick("Admin")
task.wait(2)
game:Shutdown()
return
end
end
end
local v_663625 AdminCheck_Enable()
if v_814077 then return end
v_814077 = true
CheckAdmins()
v_469424 = v_2400.PlayerAdded:Connect(v_663625(plr)
if not v_814077 then return end
if v_59591[plr.Name] then
v_428177:Kick("Detected Nigger")
task.wait(2)
game:Shutdown()
end
end)
v_836160 = coroutine.create(v_663625()
while v_814077 do
CheckAdmins()
task.wait(4)
end
end)
coroutine.resume(v_836160)
end
local v_663625 AdminCheck_Disable()
if not v_814077 then return end
v_814077 = false
if v_469424 then
v_469424:Disconnect()
v_469424 = nil
end
v_836160 = nil
end
local v_774744 = false
local v_663625 DeletedMob_RunOnce()
if v_774744 then return end
v_774744 = true
local v_684754, err = pcall(v_663625()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Mick-gordon/Hyper-Escape/main/DeleteMobV2.lua", true))()
end)
if not v_684754 then
warn("[Deleted Mob<3] Ошибка: ", err)
end
end
local v_18787 = false
local v_711894
local v_364328
local v_663625 AntiAFK_DoAction()
pcall(v_663625()
v_956923:CaptureController()
v_956923:SetKeyDown('0x20')
task.wait(0.1)
v_956923:SetKeyUp('0x20')
end)
pcall(v_663625()
local v_378171 = workspace.CurrentCamera
v_378171.CFrame = v_378171.CFrame * CFrame.Angles(math.rad(0.5), 0, 0)
task.wait(0.1)
v_378171.CFrame = v_378171.CFrame * CFrame.Angles(math.rad(-0.5), 0, 0)
end)
end
local v_663625 AntiAFK_Enable()
if v_18787 then return end
v_18787 = true
local v_366231 = v_428177
v_711894 = v_366231.Idled:Connect(v_663625()
if v_18787 then
AntiAFK_DoAction()
end
end)
v_364328 = coroutine.create(v_663625()
while v_18787 do
AntiAFK_DoAction()
task.wait(30)
end
end)
coroutine.resume(v_364328)
end
local v_663625 AntiAFK_Disable()
if not v_18787 then return end
v_18787 = false
if v_711894 then
v_711894:Disconnect()
v_711894 = nil
end
v_364328 = nil
end
local v_488626 = false
local v_373951
local v_861674 do
local v_705288 = game:GetService("Players")
local v_750458 = v_705288.v_428177
local v_249609 = game:GetService("RunService")
local v_230563 = game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("XMHH.2")
local v_488629 = game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("XMHH2.2")
local v_789904 = 20
local v_663625 Attack(target)
if not (target and target:FindFirstChild("Head")) then return end
local v_575143 = {
[1] = "🍞",
[2] = tick(),
[3] = v_750458.Character and v_750458.Character:FindFirstChildOfClass("Tool"),
[4] = "43TRFWX",
[5] = "Normal",
[6] = tick(),
[7] = true
}
local v_543376 = v_230563:InvokeServer(unpack(v_575143))
task.wait(0.5)
local v_708250 = v_750458.Character and v_750458.Character:FindFirstChildOfClass("Tool")
if v_708250 then
local v_138645 = v_708250:FindFirstChild("WeaponHandle") or v_708250:FindFirstChild("Handle")
or v_750458.Character:FindFirstChild("Right Arm")
if v_138645 and target:FindFirstChild("Head") then
local v_442209 = {
[1] = "🍞",
[2] = tick(),
[3] = v_708250,
[4] = "2389ZFX34",
[5] = v_543376,
[6] = false,
[7] = v_138645,
[8] = target:FindFirstChild("Head"),
[9] = target,
[10] = v_750458.Character:FindFirstChild("HumanoidRootPart").Position,
[11] = target:FindFirstChild("Head").Position
}
v_488629:FireServer(unpack(v_442209))
end
end
end
v_861674 = v_663625()
return v_249609.RenderStepped:Connect(v_663625()
if not v_488626 then return end
local v_539682 = v_750458.Character
local v_19210 = v_539682 and v_539682:FindFirstChild("HumanoidRootPart")
if v_19210 then
for _, plr in ipairs(v_705288:GetPlayers()) do
if plr ~= v_750458 then
local v_373440 = plr.Character
local v_89732 = v_373440 and v_373440:FindFirstChild("HumanoidRootPart")
local v_892265 = v_373440 and v_373440:FindFirstChildOfClass("Humanoid")
if v_89732 and v_892265 then
local v_309205 = (v_19210.Position - v_89732.Position).Magnitude
if v_309205 < v_789904 and v_892265.Health > 15 and not v_373440:FindFirstChildOfClass("ForceField") then
Attack(v_373440)
end
end
end
end
end
end)
end
end
local v_663625 MeleeAura_Enable()
if v_488626 then return end
v_488626 = true
v_373951 = v_861674()
end
local v_663625 MeleeAura_Disable()
if not v_488626 then return end
v_488626 = false
if v_373951 then
v_373951:Disconnect()
v_373951 = nil
end
end
local v_441479 = false
local v_490978 = "h4rtbrkrW"
local v_532773 = nil
local v_851068 = nil
local v_400426 = nil
local v_675137 = game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("DeathRespawn")
local v_663625 TPFarm_OnCharacterAdded(v_539682)
if v_532773 then
v_532773:Disconnect()
v_532773 = nil
end
task.wait(0.4)
local v_19210 = v_539682:FindFirstChild("HumanoidRootPart")
local v_892265 = v_539682:FindFirstChildOfClass("Humanoid")
if not (v_19210 and v_892265) then return end
v_532773 = v_6116.Stepped:Connect(v_663625()
if not v_441479 then return end
local v_502695 = v_2400:FindFirstChild(v_490978)
local v_417655 = v_502695 and v_502695.Character
local v_111316 = v_417655 and v_417655:FindFirstChild("HumanoidRootPart")
if v_111316 then
v_19210.CFrame = v_111316.CFrame + (v_111316.CFrame.LookVector * 3)
v_892265:GetPropertyChangedSignal("Health"):Connect(v_663625()
v_892265.Health = 0
end)
end
end)
end
local v_663625 TPFarm_Enable()
if v_441479 then return end
v_441479 = true
local v_750458 = v_428177
if v_750458.Character then
TPFarm_OnCharacterAdded(v_750458.Character)
end
v_400426 = v_750458.CharacterAdded:Connect(v_663625(newChar)
if not v_441479 then return end
TPFarm_OnCharacterAdded(newChar)
local v_708250 = v_750458.Backpack:FindFirstChildOfClass("Tool")
if v_708250 and newChar then
v_708250.Parent = newChar
end
end)
v_851068 = v_6116.RenderStepped:Connect(v_663625()
if not v_441479 then return end
local v_539682 = v_750458.Character
if v_539682 then
local v_730301 = v_539682:FindFirstChildOfClass("Humanoid")
if v_730301 and v_730301.Health <= 0 then
v_675137:InvokeServer("KMG4R904")
end
end
end)
end
local v_663625 TPFarm_Disable()
if not v_441479 then return end
v_441479 = false
if v_532773 then
v_532773:Disconnect()
v_532773 = nil
end
if v_851068 then
v_851068:Disconnect()
v_851068 = nil
end
if v_400426 then
v_400426:Disconnect()
v_400426 = nil
end
end
local v_615273 = v_675137
local v_790592 = false
local v_60686
local v_61157 = Vector3.new(-4184.4, 102.7, 276.9)
local v_663625 SaveCube_Enable()
if v_790592 then return end
v_790592 = true
v_60686 = v_6116.RenderStepped:Connect(v_663625()
if not v_790592 then return end
local v_539682 = v_428177.Character
if v_539682 then
local v_19210 = v_539682:FindFirstChild("HumanoidRootPart")
local v_892265 = v_539682:FindFirstChildOfClass("Humanoid")
if v_19210 then
v_19210.CFrame = CFrame.new(v_61157)
end
if v_892265 and v_892265.Health <= 0 then
v_615273:InvokeServer("KMG4R904")
end
end
end)
end
local v_663625 SaveCube_Disable()
if not v_790592 then return end
v_790592 = false
if v_60686 then
v_60686:Disconnect()
v_60686 = nil
end
end
local v_634129 = false
local v_910539
local v_803669 = Vector3.new(-4857.5, -161.5, -918.3)
local v_663625 SaveVibe_Enable()
if v_634129 then return end
v_634129 = true
v_910539 = v_6116.RenderStepped:Connect(v_663625()
if not v_634129 then return end
local v_539682 = v_428177.Character
if v_539682 then
local v_19210 = v_539682:FindFirstChild("HumanoidRootPart")
local v_892265 = v_539682:FindFirstChildOfClass("Humanoid")
if v_19210 then
v_19210.CFrame = CFrame.new(v_803669)
end
if v_892265 and v_892265.Health <= 0 then
v_615273:InvokeServer("KMG4R904")
end
end
end)
end
local v_663625 SaveVibe_Disable()
if not v_634129 then return end
v_634129 = false
if v_910539 then
v_910539:Disconnect()
v_910539 = nil
end
end
local v_260839 = false
local v_736820
local v_457236 = Vector3.new(-5169.8, 102.6, -515.5)
local v_663625 SaveMount_Enable()
if v_260839 then return end
v_260839 = true
v_736820 = v_6116.RenderStepped:Connect(v_663625()
if not v_260839 then return end
local v_539682 = v_428177.Character
if v_539682 then
local v_19210 = v_539682:FindFirstChild("HumanoidRootPart")
local v_892265 = v_539682:FindFirstChildOfClass("Humanoid")
if v_19210 then
v_19210.CFrame = CFrame.new(v_457236)
end
if v_892265 and v_892265.Health <= 0 then
v_615273:InvokeServer("KMG4R904")
end
end
end)
end
local v_663625 SaveMount_Disable()
if not v_260839 then return end
v_260839 = false
if v_736820 then
v_736820:Disconnect()
v_736820 = nil
end
end
local v_663625 createToggleRow(parent, scriptName, canToggle, isEnabledFn, onEnable, onDisable, getKeyBindFn, setKeyBindFn)
local v_560760 = Instance.new("Frame")
v_560760.Size = UDim2.new(1, 0, 0, 30)
v_560760.BackgroundTransparency = 1
v_560760.Parent = parent
local v_393716 = Instance.new("TextLabel")
v_393716.Size = UDim2.new(0.4, 0, 1, 0)
v_393716.BackgroundTransparency = 1
v_393716.Text = scriptName
v_393716.TextColor3 = Color3.new(1, 1, 1)
v_393716.Font = Enum.Font.SourceSansSemibold
v_393716.TextSize = 16
v_393716.TextXAlignment = Enum.TextXAlignment.Left
v_393716.Parent = v_560760
local v_363626 = Instance.new("TextButton")
v_363626.Size = UDim2.new(0.2, 0, 1, 0)
v_363626.Position = UDim2.new(0.4, 5, 0, 0)
v_363626.Font = Enum.Font.SourceSans
v_363626.TextSize = 16
v_363626.Parent = v_560760
local v_716272 = Instance.new("TextButton")
v_716272.Size = UDim2.new(0.2, 0, 1, 0)
v_716272.Position = UDim2.new(0.6, 10, 0, 0)
v_716272.Font = Enum.Font.SourceSans
v_716272.TextSize = 16
v_716272.Text = "Bind"
v_716272.TextColor3 = Color3.fromRGB(255, 255, 255)
v_716272.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
v_716272.Parent = v_560760
local v_663625 updateToggleButton()
if not canToggle then
v_363626.Text = "Run"
v_363626.BackgroundColor3 = Color3.fromRGB(150, 150, 150)
return
end
if isEnabledFn() then
v_363626.Text = "ON"
v_363626.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
else
v_363626.Text = "OFF"
v_363626.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
end
end
updateToggleButton()
v_363626.MouseButton1Click:Connect(v_663625()
if not canToggle then
onEnable()
v_363626.Text = "DONE"
v_363626.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
v_363626.Active = false
v_716272.Active = false
return
end
if isEnabledFn() then
onDisable()
else
onEnable()
end
updateToggleButton()
end)
if getKeyBindFn and setKeyBindFn then
local v_113781 = false
local v_663625 updateBindButtonText()
local v_80153 = getKeyBindFn()
if v_80153 then
v_716272.Text = "[".. v_80153.Name .."]"
else
v_716272.Text = "Bind"
end
end
updateBindButtonText()
v_716272.MouseButton1Click:Connect(v_663625()
if v_113781 then
v_113781 = false
v_716272.Text = "Bind"
else
v_113781 = true
v_716272.Text = "Press Key..."
end
end)
v_536176.InputBegan:Connect(v_663625(v_746085, gp)
if gp then return end
if v_113781 then
if v_746085.KeyCode ~= Enum.KeyCode.Unknown then
setKeyBindFn(v_746085.KeyCode)
v_113781 = false
updateBindButtonText()
end
else
local v_80153 = getKeyBindFn()
if v_80153 and v_746085.KeyCode == v_80153 then
if canToggle then
if isEnabledFn() then
onDisable()
else
onEnable()
end
updateToggleButton()
else
if not v_774744 then
onEnable()
v_363626.Text = "DONE"
v_363626.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
v_363626.Active = false
v_716272.Active = false
end
end
end
end
end)
else
v_716272.Visible = false
end
return v_560760
end
local v_663625 createTPFarmTargetRow(parent)
local v_730106 = Instance.new("Frame")
v_730106.Size = UDim2.new(1, 0, 0, 30)
v_730106.BackgroundTransparency = 1
v_730106.Parent = parent
local v_393716 = Instance.new("TextLabel")
v_393716.Size = UDim2.new(0.4, 0, 1, 0)
v_393716.BackgroundTransparency = 1
v_393716.Text = "TP Target:"
v_393716.TextColor3 = Color3.new(1,1,1)
v_393716.Font = Enum.Font.SourceSansSemibold
v_393716.TextSize = 16
v_393716.TextXAlignment = Enum.TextXAlignment.Left
v_393716.Parent = v_730106
local v_746085 = Instance.new("TextBox")
v_746085.Size = UDim2.new(0.5, 0, 1, 0)
v_746085.Position = UDim2.new(0.4, 5, 0, 0)
v_746085.BackgroundColor3 = Color3.fromRGB(80,80,80)
v_746085.TextColor3 = Color3.new(1,1,1)
v_746085.Font = Enum.Font.SourceSans
v_746085.TextSize = 16
v_746085.Text = v_490978
v_746085.ClearTextOnFocus = false
v_746085.Parent = v_730106
v_746085.FocusLost:Connect(v_663625()
v_490978 = v_746085.Text
end)
end
createToggleRow(
v_987896,
"Fly",
true,
v_663625() return v_115650 end,
Fly_Enable,
Fly_Disable,
v_663625() return v_914296 end,
v_663625(k) v_914296 = k end
)
do
local v_516979 = nil
createToggleRow(
v_987896,
"Admin Check",
true,
v_663625() return v_814077 end,
AdminCheck_Enable,
AdminCheck_Disable,
v_663625() return v_516979 end,
v_663625(k) v_516979 = k end
)
end
createToggleRow(
v_987896,
"Deleted Mob<3",
false,
v_663625() return v_774744 end,
DeletedMob_RunOnce,
v_663625() end,
(v_663625()
local v_647035 = nil
return v_663625() return v_647035 end,
v_663625(k) v_647035 = k end
end)()
)
do
local v_524878 = nil
createToggleRow(
v_987896,
"Anti AFK",
true,
v_663625() return v_18787 end,
AntiAFK_Enable,
AntiAFK_Disable,
v_663625() return v_524878 end,
v_663625(k) v_524878 = k end
)
end
do
local v_560890 = nil
createToggleRow(
v_987896,
"Melee Aura 4 Alt MAX!",
true,
v_663625() return v_488626 end,
MeleeAura_Enable,
MeleeAura_Disable,
v_663625() return v_560890 end,
v_663625(k) v_560890 = k end
)
end
do
local v_857519 = nil
createToggleRow(
v_987896,
"Teleport Farm",
true,
v_663625() return v_441479 end,
TPFarm_Enable,
TPFarm_Disable,
v_663625() return v_857519 end,
v_663625(k) v_857519 = k end
)
createTPFarmTargetRow(v_987896)
end
do
local v_681624 = nil
createToggleRow(
v_987896,
"Save Cube",
true,
v_663625() return v_790592 end,
SaveCube_Enable,
SaveCube_Disable,
v_663625() return v_681624 end,
v_663625(k) v_681624 = k end
)
end
do
local v_302753 = nil
createToggleRow(
v_987896,
"Save Vibecheck",
true,
v_663625() return v_634129 end,
SaveVibe_Enable,
SaveVibe_Disable,
v_663625() return v_302753 end,
v_663625(k) v_302753 = k end
)
end
do
local v_678358 = nil
createToggleRow(
v_987896,
"Save Mountain",
true,
v_663625() return v_260839 end,
SaveMount_Enable,
SaveMount_Disable,
v_663625() return v_678358 end,
v_663625(k) v_678358 = k end
)
end
