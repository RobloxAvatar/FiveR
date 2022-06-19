local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/RobloxAvatar/uiLibary/main/Uilib.lua')))()

local w = library:CreateWindow("FiveR - Hulpdiensten")
local MainTab = w:CreateFolder("Main")
local teleports = {"Bomb Shop", "Spawn", "Wit-Was", "ANWB(ATM)", "Car-Dealer(ATM)", "AH(Albert Heijn)", "Black Market"}

MainTab:Dropdown("Teleport Place", teleports, true, function(place)
    if place == "Bomb Shop" then
        local tween = game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(6570.66943, 13.1463814, 512.772339, -0.53114599, -8.380038e-08, -0.847280324, 2.0013637e-08, 1, -1.11451364e-07, 0.847280324, -7.61541017e-08, -0.53114599) + Vector3.new(0,350,0)}):Play()
        wait(7.5)
        game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2.25), {CFrame = CFrame.new(6659.91748, 5.0260067, 466.374237, 0.535636246, -4.93030825e-08, -0.844448805, 5.47191341e-08, 1, -2.36764262e-08, 0.844448805, -3.35255557e-08, 0.535636246)}):Play()
    else
        if place == "Spawn" then
            game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(-99.960907, 3.59226179, 868.699463, 0.0766810179, 2.81778281e-08, -0.99705565, 8.07136757e-09, 1, 2.88817859e-08, 0.99705565, -1.02622879e-08, 0.0766810179) + Vector3.new(0,350,0)}):Play()
            wait(7.5)
            game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(0.5), {CFrame = CFrame.new(-45.4451294, 3.55185246, 725.09436, 0.00712037366, -1.18080308e-07, 0.999974668, 1.47211532e-08, 1, 1.1797848e-07, -0.999974668, 1.38807295e-08, 0.00712037366) + Vector3.new(0,2,0)}):Play()
        else
            if place == "ANWB(ATM)" then
                game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(1374.52917, 3.55583858, -1127.95459, 0.992869735, -1.29419373e-08, -0.11920435, 1.92864853e-08, 1, 5.20704937e-08, 0.11920435, -5.39982494e-08, 0.992869735) + Vector3.new(0,350,0)}):Play()
                wait(7.5)
                game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3), {CFrame = CFrame.new(1389.00439, 3.60583806, -1255.39771, 0.0131397368, 9.81259873e-08, -0.999913692, 1.99115235e-09, 1, 9.81606263e-08, 0.999913692, -3.2807852e-09, 0.0131397368) + Vector3.new(0,1,0)}):Play()
            else
                if place == "Car-Dealer(ATM)" then
                    game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(-662.457153, 3.59897304, 1791.79468, -0.0687660649, 8.39341183e-08, 0.997632802, 3.06760768e-08, 1, -8.20187935e-08, -0.997632802, 2.49633523e-08, -0.0687660649) + Vector3.new(0,350,0)}):Play()
                    wait(7.5)
                    game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3), {CFrame = CFrame.new(-720.082092, 3.59897304, 1811.17883, -0.999140263, 2.69025318e-08, -0.0414581262, 3.08138262e-08, 1, -9.37042302e-08, 0.0414581262, -9.49011536e-08, -0.999140263) + Vector3.new(0,1,0)}):Play()
                else
                    if place == "Wit-Was" then
                        game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(2575.72852, -220.261322, -44.92202, -0.999404371, 9.88895899e-09, 0.0345098786, 1.17069234e-08, 1, 5.24774926e-08, -0.0345098786, 5.28502397e-08, -0.999404371)}):Play()
                    else
                        if place == "AH(Albert Heijn)" then
                            game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(2369.15063, 3.55583763, -1977.66003, -0.010134412, -1.06304334e-07, -0.999948621, 2.46698857e-08, 1, -1.06559824e-07, 0.999948621, -2.57485411e-08, -0.010134412) + Vector3.new(0,350,0)}):Play()
                            wait(7.5)
                            game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3), {CFrame = CFrame.new(2219.08179, 3.57427263, -1996.64355, -0.0336495116, -6.72787337e-08, 0.999433696, 6.37408348e-08, 1, 6.94629207e-08, -0.999433696, 6.60421335e-08, -0.0336495116) + Vector3.new(0,1,0)}):Play()
                        else
                            if place == "Black Market" then
                                game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(7.5), {CFrame = CFrame.new(6983.87061, 47.13937, 152.880493, 0.617196798, -7.57511671e-08, 0.786808789, 1.19501323e-07, 1, 2.53597965e-09, -0.786808789, 9.24595014e-08, 0.617196798) + Vector3.new(0,350,0)}):Play()
                                wait(7.5)
                                game:GetService("TweenService"):Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3), {CFrame = CFrame.new(6756.93457, 5.00387716, 280.771057, 0.124544218, -2.66058304e-08, -0.992214084, -4.21433777e-10, 1, -2.68675056e-08, 0.992214084, 3.76434484e-09, 0.124544218) + Vector3.new(0,1,0)}):Play()
                            end
                        end
                    end
                end
            end
        end
    end
end)
