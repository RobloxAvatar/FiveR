local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/RobloxAvatar/uiLibary/main/Uilib.lua')))()

local w = library:CreateWindow("FiveR - Hulpdiensten")
local MainTab = w:CreateFolder("Main")
local teleports = {"Bomb Shop", "Spawn"}

MainTab:Dropdown("Teleport Place", teleports, true, function(place)
    if place == "Bomb Shop" then
        local tween = game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(6570.66943, 13.1463814, 512.772339, -0.53114599, -8.380038e-08, -0.847280324, 2.0013637e-08, 1, -1.11451364e-07, 0.847280324, -7.61541017e-08, -0.53114599) + Vector3.new(0,350,0)}):Play()
        wait(7.5)
        game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2.25), {CFrame = CFrame.new(6659.91748, 5.0260067, 466.374237, 0.535636246, -4.93030825e-08, -0.844448805, 5.47191341e-08, 1, -2.36764262e-08, 0.844448805, -3.35255557e-08, 0.535636246)}):Play()
    else
        if place == "Spawn" then
            game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(-99.960907, 3.59226179, 868.699463, 0.0766810179, 2.81778281e-08, -0.99705565, 8.07136757e-09, 1, 2.88817859e-08, 0.99705565, -1.02622879e-08, 0.0766810179) + Vector3.new(0,350,0)}):Play()
            wait(7.5)
            game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(0.2), {CFrame = CFrame.new(-45.4451294, 3.55185246, 725.09436, 0.00712037366, -1.18080308e-07, 0.999974668, 1.47211532e-08, 1, 1.1797848e-07, -0.999974668, 1.38807295e-08, 0.00712037366) + Vector3.new(0,2,0)}):Play()
        end
    end
end)
