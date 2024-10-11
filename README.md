local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))() local Window = Library.CreateLib("V4LK HUB", "DarkTheme")

local Tab = Window:NewTab("Not just a kj game")

local Section = Tab:NewSection("kj base moves")

Section:NewButton("Ravage", "ButtonInfo", function() local args = { [1] = "Combat", [2] = "Ravage", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Swift kick", "ButtonInfo", function() local args = { [1] = "Combat", [2] = "Swift Sweep", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Collertal Ruin", "ButtonInfo", function() local args = { [1] = "Combat", [2] = "Collateral Ruin", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Signature Kicl", "ButtonInfo", function() local args = { [1] = "Combat", [2] = "Signature Kick", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewLabel("kj ult moves SPAMMABLE")

Section:NewButton("Stoic bomb", "ButtonInfo", function() local args = { [1] = "Combat", [2] = "BOMB", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Dropkick", "ButtonInfo", function() game:GetService("ReplicatedStorage").KJ.Remote.DropKick:FireServer()

end)

Section:NewButton("Five seasons", "ButtonInfo", function() local args = { [1] = "Ability", [2] = "Season", [3] = { ["char"] = game:GetService("Players").LocalPlayer.Character, ["Player"] = game:GetService("Players").LocalPlayer, ["root"] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, ["player"] = game:GetService("Players").LocalPlayer, ["hum"] = game:GetService("Players").LocalPlayer.Character.Humanoid } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Flex works", "ButtonInfo", function()
local args = {
    [1] = "Combat",
    [2] = "FLEX",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewLabel("The honored one BASE")

Section:NewButton("red", "ButtonInfo", function() local args = { [1] = "Flashy", [2] = "Red", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Blue", "ButtonInfo", function() local args = { [1] = "Flashy", [2] = "Blue", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Beatdown", "ButtonInfo", function() local args = { [1] = "Flashy", [2] = "Beatdown", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Black flash", "ButtonInfo", function() local args = { [1] = "Flashy", [2] = "Black Flash", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args)) end)

Section:NewLabel("Honored one ULT moves")

Section:NewButton("Maximum Red", "ButtonInfo", function() local args = { [1] = "Flashy", [2] = "Maximum Output : Red", [3] = { ["player"] = game:GetService("Players").LocalPlayer, ["pllayer"] = game:GetService("Players").LocalPlayer, ["Player"] = game:GetService("Players").LocalPlayer } }

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Maximum Blue", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Amplification : Blue",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Metal Beatdown", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Metal Beatdown",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Imaginary technique", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Imaginary Technique",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

local Section = Tab:NewSection("Rlly?")

Section:NewButton("KJ", "ButtonInfo", function() local args = { [1] = "SwitchC", [2] = "KJ" }

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("HONORED ONE", "ButtonInfo", function() local args = { [1] = "SwitchC", [2] = "The Honoured One" }

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("Flashiest Swordsmen", "ButtonInfo", function() local args = { [1] = "SwitchC", [2] = "Flashiest Swordsman" }

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

local Section = Tab:NewSection("PS+ CMDS")

Section:NewButton("Give awk", "ButtonInfo", function()
    local args = {
    [1] = "Grant",
    [2] = "GiveAwakening"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("No cd", "ButtonInfo", function()
    local args = {
    [1] = "SwitchServer",
    [2] = "No Cooldown"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("No Dash cd", "ButtonInfo", function()
    local args = {
    [1] = "SwitchServer",
    [2] = "No Dash Cooldown"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)


Section:NewButton("Dual Movesets", "ButtonInfo", function()
   local args = {
    [1] = "SwitchServer",
    [2] = "Dual Moveset"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)


Section:NewButton("Instant awk", "ButtonInfo", function()
   local args = {
    [1] = "SwitchServer",
    [2] = "Instant Awakening"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("Inf awk", "ButtonInfo", function()
    local args = {
    [1] = "SwitchServer",
    [2] = "Infinite Awakening"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("No speed debuff", "ButtonInfo", function()
local args = {
    [1] = "SwitchServer",
    [2] = "No Speed Debuff"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

local Tab = Window:NewTab("KJ REMASTERED GAME")

local Section = Tab:NewSection("Character Selection")

Section:NewButton("Admin char", "ButtonInfo", function()
    local args = {
    [1] = "Character",
    [2] = "Kagenou",
    [3] = "Select"
}

game:GetService("ReplicatedStorage").Attribute:FireServer(unpack(args))

end)

Section:NewButton("Suiryu (early access)", "ButtonInfo", function()
    local args = {
    [1] = "Character",
    [2] = "EarlyAccess",
    [3] = "Select"
}

game:GetService("ReplicatedStorage").Attribute:FireServer(unpack(args))

end)

Section:NewButton("KJ", "ButtonInfo", function()
    local args = {
    [1] = "Character",
    [2] = "KJ",
    [3] = "Select"
}

game:GetService("ReplicatedStorage").Attribute:FireServer(unpack(args))

end)

Section:NewButton("Gojo spawn thingy", "ButtonInfo", function()
    game:GetService("ReplicatedStorage").Spawns.Gojo:FireServer()

end)

Section:NewButton("Sukuna", "ButtonInfo", function()
    local args = {
    [1] = "Character",
    [2] = "Sukuna",
    [3] = "Select"
}

game:GetService("ReplicatedStorage").Attribute:FireServer(unpack(args))

end)

local Section = Tab:NewSection("Ult Anims + Moves") 

Section:NewButton("Suiryu (ult not finished)", "ButtonInfo", function()
    local args = {
    [1] = "Suiryu"
}

game:GetService("ReplicatedStorage").UltimateUsed:FireServer(unpack(args))

end)

Section:NewButton("Kj", "ButtonInfo", function()
    local args = {
    [1] = "Serious"
}

game:GetService("ReplicatedStorage").UltimateUsed:FireServer(unpack(args))

end)

Section:NewButton("Gojo", "ButtonInfo", function()
   local args = {
    [1] = "Gojo"
}

game:GetService("ReplicatedStorage").UltimateUsed:FireServer(unpack(args))

end)

Section:NewButton("Sukuna", "ButtonInfo", function()
    local args = {
    [1] = "Sukuna"
}

game:GetService("ReplicatedStorage").UltimateUsed:FireServer(unpack(args))

end)

local Section = Tab:NewSection("acceries+")

Section:NewButton("Saitama Gloves", "ButtonInfo", function()
    game:GetService("ReplicatedStorage").AccessoryRemotes.Glove:FireServer()

end)

Section:NewButton("KJ Aura", "ButtonInfo", function()
    game:GetService("ReplicatedStorage").AccessoryRemotes.KJAura:FireServer()

end)

Section:NewButton("Light yagami's dark aura.", "ButtonInfo", function()
    game:GetService("ReplicatedStorage").AccessoryRemotes.DarkAura:FireServer()

end)

local Tab = Window:NewTab("Battlegrounds Mania")

local Section = Tab:NewSection("YOU NEED EARLY ACCESS AND KJ ACCESS")

Section:NewButton("KJ", "ButtonInfo", function()
    local args = {
    [1] = {
        [1] = "KJ",
        [2] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").ChangeCharacter:FireServer(unpack(args))

end)

Section:NewButton("JUN", "ButtonInfo", function()
    local args = {
    [1] = {
        [1] = "Jun",
        [2] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").ChangeCharacter:FireServer(unpack(args))

end)

Section:NewButton("MINOS PRIME", "ButtonInfo", function()
    local args = {
    [1] = {
        [1] = "Minos",
        [2] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").ChangeCharacter:FireServer(unpack(args))

end)


local Tab = Window:NewTab("TSB")

local Section = Tab:NewSection("Custom Movesets")

Section:NewButton("KJ", "ButtonInfo", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Gokou300/Gokou300/main/kJ%20Moveset%20V2%20by%20camerawoman"))()
end)

Section:NewButton("Toji (need atomic)", "ButtonInfo", function() loadstring(game:HttpGet('https://pastebin.com/raw/VQnyWP5D'))()
end)

Section:NewButton("Saitama To Suiryu", "ButtonInfo", function()
    --Move & Ultimate Names

local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("1").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Vanishing Normal Kick"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Consective Kicks"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("3").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Spin (troll move)"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("4").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Stomp"


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local playerGui = player:WaitForChild("PlayerGui")


local function findGuiAndSetText()

    local screenGui = playerGui:FindFirstChild("ScreenGui")

    if screenGui then

        local magicHealthFrame = screenGui:FindFirstChild("MagicHealth")

        if magicHealthFrame then

            local textLabel = magicHealthFrame:FindFirstChild("TextLabel")

            if textLabel then

                textLabel.Text = "WarmUp (WIP)"

            end

        end

    end

end


playerGui.DescendantAdded:Connect(findGuiAndSetText)

findGuiAndSetText()

--[[Animations]]

--[[Move 1]]

local animationId = 10468665991


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18897120868"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0.1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.9)


    end

end

--[[END OF MOVE 1 ANIM]]

--[[Move 2]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10466974800


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18181589384"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF MOVE 2 ANIM]]

--[[Move 3]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10471336737


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18896121004"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

--[[END OF MOVE 3 ANIM]]

--[[Move 4]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 12510170988


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18897119503"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF MOVE 4 ANIM]]

--[[Wall combo]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 15955393872


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18716197426"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.05


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF WALL COMBO ANIM]]

--[[Ult Activation]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 12447707844


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://17292505729 "

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)

    end

end
--[[END OF ULT ACTIVATION ANIM]]

--[[Dash]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10479335397


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://13294790250"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1.3)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

--[[END OF DASH ANIM]]

--[[Uppercut]]
humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10503381238


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14900168720"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 1.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.7)


    end

end

--[[END OF UPPERCUT ANIM]]

--[[Downslam]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10470104242


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12447247483"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


wait(0.2)

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(6)


    end

end

--[[END OF DOWNSLAM ANIM]]

--[[Punch anims]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local animationIdsToStop = {

    [17859015788] = true, --punch idk

    [10469493270] = true, --punch1

    [10469630950] = true, --punch2

    [10469639222] = true, --punch3

    [10469643643] = true, --punch4

}


local replacementAnimations = {

    ["10469630950"] = "rbxassetid://18716133404", --punch1

    ["10469630950"] = "rbxassetid://18716143973", --punch2

    ["10469639222"] = "rbxassetid://17889471098", --punch3

    ["10469643643"] = "rbxassetid://17889290569", --punch4

    ["17859015788"] = "rbxassetid://12684185971", --punch idk

    ["11365563255"] = "rbxassetid://14516273501" --punch idk

}


local queue = {}

local isAnimating = false


local function playReplacementAnimation(animationId)

    if isAnimating then

        table.insert(queue, animationId)

        return

    end

   

    isAnimating = true

    local replacementAnimationId = replacementAnimations[tostring(animationId)]

    if replacementAnimationId then

        local AnimAnim = Instance.new("Animation")

        AnimAnim.AnimationId = replacementAnimationId

        local Anim = humanoid:LoadAnimation(AnimAnim)

        Anim:Play()

       

        Anim.Stopped:Connect(function()

            isAnimating = false

            if #queue > 0 then

                local nextAnimationId = table.remove(queue, 1)

                playReplacementAnimation(nextAnimationId)

            end

        end)

    else

        isAnimating = false

    end

end


local function stopSpecificAnimations()

    for _, track in ipairs(humanoid:GetPlayingAnimationTracks()) do

        local animationId = tonumber(track.Animation.AnimationId:match("%d+"))

        if animationIdsToStop[animationId] then

            track:Stop()

        end

    end

end


local function onAnimationPlayed(animationTrack)

    local animationId = tonumber(animationTrack.Animation.AnimationId:match("%d+"))

    if animationIdsToStop[animationId] then

        stopSpecificAnimations()

        animationTrack:Stop()

       

        local replacementAnimationId = replacementAnimations[tostring(animationId)]

        if replacementAnimationId then

            playReplacementAnimation(animationId)

        end

    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoidRootPart = character:WaitForChild("HumanoidRootPart")


local function onBodyVelocityAdded(bodyVelocity)

    if bodyVelocity:IsA("BodyVelocity") then

        bodyVelocity.Velocity = Vector3.new(bodyVelocity.Velocity.X, 0, bodyVelocity.Velocity.Z)

    end

end


character.DescendantAdded:Connect(onBodyVelocityAdded)


for _, descendant in pairs(character:GetDescendants()) do

    onBodyVelocityAdded(descendant)

end


player.CharacterAdded:Connect(function(newCharacter)

    character = newCharacter

    humanoidRootPart = character:WaitForChild("HumanoidRootPart")

    character.DescendantAdded:Connect(onBodyVelocityAdded)

   

    for _, descendant in pairs(character:GetDescendants()) do

        onBodyVelocityAdded(descendant)

    end

end) 
end)

Section:NewButton("Sorcerer That everyone knows", "ButtonInfo", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Uhohyoudontgetyourfuckinpizza/REWORK-FREE-VIP-RELEASE/refs/heads/main/README.md",true))();
end)

Section:NewButton("Sukuna Recreation", "ButtonInfo", function()
    --Move & Ultimate Names

local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("1").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Ki"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Consective Beatdowns"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("3").Base

local ToolName = baseButton.ToolName


ToolName.Text = ":S"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("4").Base

local ToolName = baseButton.ToolName


ToolName.Text = "FAKE SUMMONING"


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local playerGui = player:WaitForChild("PlayerGui")


local function findGuiAndSetText()

    local screenGui = playerGui:FindFirstChild("ScreenGui")

    if screenGui then

        local magicHealthFrame = screenGui:FindFirstChild("MagicHealth")

        if magicHealthFrame then

            local textLabel = magicHealthFrame:FindFirstChild("TextLabel")

            if textLabel then

                textLabel.Text = "UltimateName"

            end

        end

    end

end


playerGui.DescendantAdded:Connect(findGuiAndSetText)

findGuiAndSetText()

--[[Animations]]

--[[Move 1]]

local animationId = 10468665991


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://16598695404"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0.1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.9)


    end

end

--[[END OF MOVE 1 ANIM]]

--[[Move 2]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10466974800


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18440389930"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(1)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF MOVE 2 ANIM]]

--[[Move 3]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10471336737


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://17838006839"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

--[[END OF MOVE 3 ANIM]]

--[[Move 4]]


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 12510170988


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://17862993552"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF MOVE 4 ANIM]]

--[[Wall combo]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 15955393872


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://18716750744"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.05


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)


    end

end

--[[END OF WALL COMBO ANIM]]

--[[Ult Activation]]
local args = {
    [1] = "I MAY BE a SORCERER",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 12447707844


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://16002726844 "

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1)

    end

end
--[[END OF ULT ACTIVATION ANIM]]

--[[Dash]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10479335397


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://13294790250"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(1.3)


delay(1.8, function()

    Anim:Stop()

end)


    end

end

--[[END OF DASH ANIM]]

--[[Uppercut]]
humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10503381238


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://14900168720"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 1.3


Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.7)


    end

end

--[[END OF UPPERCUT ANIM]]

--[[Downslam]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10470104242


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://12447247483"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0


wait(0.2)

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(6)


    end

end

--[[END OF DOWNSLAM ANIM]]

--[[Punch anims]]

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local animationIdsToStop = {

    [17859015788] = true, --punch idk

    [10469493270] = true, --punch1

    [10469630950] = true, --punch2

    [10469639222] = true, --punch3

    [10469643643] = true, --punch4

}


local replacementAnimations = {

    ["10469493270"] = "rbxassetid://17889458563", --punch1

    ["10469630950"] = "rbxassetid://17889461810", --punch2

    ["10469639222"] = "rbxassetid://17889471098", --punch3

    ["10469643643"] = "rbxassetid://17889290569", --punch4

    ["17859015788"] = "rbxassetid://12684185971", --punch idk

    ["11365563255"] = "rbxassetid://14516273501" --punch idk

}


local queue = {}

local isAnimating = false


local function playReplacementAnimation(animationId)

    if isAnimating then

        table.insert(queue, animationId)

        return

    end

   

    isAnimating = true

    local replacementAnimationId = replacementAnimations[tostring(animationId)]

    if replacementAnimationId then

        local AnimAnim = Instance.new("Animation")

        AnimAnim.AnimationId = replacementAnimationId

        local Anim = humanoid:LoadAnimation(AnimAnim)

        Anim:Play()

       

        Anim.Stopped:Connect(function()

            isAnimating = false

            if #queue > 0 then

                local nextAnimationId = table.remove(queue, 1)

                playReplacementAnimation(nextAnimationId)

            end

        end)

    else

        isAnimating = false

    end

end


local function stopSpecificAnimations()

    for _, track in ipairs(humanoid:GetPlayingAnimationTracks()) do

        local animationId = tonumber(track.Animation.AnimationId:match("%d+"))

        if animationIdsToStop[animationId] then

            track:Stop()

        end

    end

end


local function onAnimationPlayed(animationTrack)

    local animationId = tonumber(animationTrack.Animation.AnimationId:match("%d+"))

    if animationIdsToStop[animationId] then

        stopSpecificAnimations()

        animationTrack:Stop()

       

        local replacementAnimationId = replacementAnimations[tostring(animationId)]

        if replacementAnimationId then

            playReplacementAnimation(animationId)

        end

    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoidRootPart = character:WaitForChild("HumanoidRootPart")


local function onBodyVelocityAdded(bodyVelocity)

    if bodyVelocity:IsA("BodyVelocity") then

        bodyVelocity.Velocity = Vector3.new(bodyVelocity.Velocity.X, 0, bodyVelocity.Velocity.Z)

    end

end


character.DescendantAdded:Connect(onBodyVelocityAdded)


for _, descendant in pairs(character:GetDescendants()) do

    onBodyVelocityAdded(descendant)

end


player.CharacterAdded:Connect(function(newCharacter)

    character = newCharacter

    humanoidRootPart = character:WaitForChild("HumanoidRootPart")

    character.DescendantAdded:Connect(onBodyVelocityAdded)

   

    for _, descendant in pairs(character:GetDescendants()) do

        onBodyVelocityAdded(descendant)

    end

end) 
end)

local Tab = Window:NewTab("The Kj battlegrounds")

local Section = Tab:NewSection("character selection")

Section:NewButton("KJ", "ButtonInfo", function()
    local args = {
    [1] = "KJ"
}

game:GetService("ReplicatedStorage").Remotes.Charchange:FireServer(unpack(args))

end)

Section:NewButton("STEALTH (need ea)", "ButtonInfo", function()
    local args = {
    [1] = "Stealth"
}

game:GetService("ReplicatedStorage").Remotes.Charchange:FireServer(unpack(args))

end)

local Section = Tab:NewSection("KJ Base moves (cooldowns)")

Section:NewButton("Ravage (with quote)", "ButtonInfo", function()
    local args = {
    [1] = "KJ",
    [2] = "Ravage",
    [3] = "Ravage"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

local player = game.Players.LocalPlayer
repeat wait() until player.Character
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

local messages = {"Dang", "Isnt iT.", "KILL KJ DAY", "WEAK"}

local function sendMessage(text)
    ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(text, "All")
end

for _, message in ipairs(messages) do
    sendMessage(message)
    wait(1.7) 
end

end)

Section:NewButton("Swift Kick", "ButtonInfo", function()
    local args = {
    [1] = "KJ",
    [2] = "SwiftSweep",
    [3] = "Swift Sweep"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("Collertal (with quote)", "ButtonInfo", function()
    local args = {
    [1] = "KJ",
    [2] = "CollateralRuin",
    [3] = "Collateral Ruin"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

local player = game.Players.LocalPlayer
repeat wait() until player.Character
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

local messages = {"HMPH"}

local function sendMessage(text)
    ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(text, "All")
end

for _, message in ipairs(messages) do
    sendMessage(message)
    wait(1.7) -- Wait time
end

end)

local Section = Tab:NewSection("KJ ULT")

Section:NewButton("activate ult (NEED ULT)", "ButtonInfo", function()
    local args = {
    [1] = game:GetService("Players").LocalPlayer
}

game:GetService("ReplicatedStorage").Remotes.Ultimate:FireServer(unpack(args))

local player = game.Players.LocalPlayer
repeat wait() until player.Character
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

-- messages u wanna send
local messages = {"COME AS CLOSE AS YOU WANT", "HOWEVER", "THIS IS THE LAST TIME"}

-- the function to send the messages
local function sendMessage(text)
    ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(text, "All")
end

for _, message in ipairs(messages) do
    sendMessage(message)
    wait(1.7) -- Wait time
end

end)

Section:NewButton("kj slap", "ButtonInfo", function()
    local args = {
    [1] = "KJ",
    [2] = "MightySlap",
    [3] = "Mighty Slap"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("Five seasons", "ButtonInfo", function()
    local args = {
    [1] = "KJ",
    [2] = "FiveSeasons",
    [3] = "Five Seasons"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

local player = game.Players.LocalPlayer
repeat wait() until player.Character
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

-- messages u wanna send
local messages = {"kj 20 series.", "five", "seasons", "Die."}

-- the function to send the messages
local function sendMessage(text)
    ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(text, "All")
end

for _, message in ipairs(messages) do
    sendMessage(message)
    wait(1.7) -- Wait time
end

end)


Section:NewButton("Stoic bomb", "ButtonInfo", function()
    local args = {
    [1] = "KJ",
    [2] = "StoicBomb",
    [3] = "Stoic Bomb"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

local player = game.Players.LocalPlayer
repeat wait() until player.Character
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

-- messages u wanna send
local messages = {"KJ 20 SERIES", "STOIC", "BOMB", "..."}

-- the function to send the messages
local function sendMessage(text)
    ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(text, "All")
end

for _, message in ipairs(messages) do
    sendMessage(message)
    wait(1.7) -- Wait time
end

end)

Section:NewButton("DROPKICK", "ButtonInfo", function()
   local args = {
    [1] = "KJ",
    [2] = "Dropkick",
    [3] = "20-20-20 Dropkick"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

local Section = Tab:NewSection("stealth base + ult")

Section:NewButton("Flash barrage", "ButtonInfo", function()
    local args = {
    [1] = "Stealth",
    [2] = "FlashBarrage",
    [3] = "Flash Barrage"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("Thunderclap", "ButtonInfo", function()
    local args = {
    [1] = "Stealth",
    [2] = "ThunderClap",
    [3] = "Thunder Clap"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("Flashkick", "ButtonInfo", function()
    local args = {
    [1] = "Stealth",
    [2] = "FlashKick",
    [3] = "Flash Kick"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("WhirlWind", "ButtonInfo", function()
    local args = {
    [1] = "Stealth",
    [2] = "WhirlingCrush",
    [3] = "Whirling Crush"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("Ionse", "ButtonInfo", function()
    local args = {
    [1] = "Stealth",
    [2] = "Ionise",
    [3] = "Ionise"
}

game:GetService("ReplicatedStorage").Remotes.Move:FireServer(unpack(args))

end)

Section:NewButton("ult (wont work)", "ButtonInfo", function()
    local args = {
    [1] = game:GetService("Players").LocalPlayer
}

game:GetService("ReplicatedStorage").Remotes.Ultimate:FireServer(unpack(args))

end)

local Section = Tab:NewSection("Gamepass")

Section:NewButton("Kill sounds", "ButtonInfo", function()
    local args = {
    [1] = "8788677208"
}

game:GetService("ReplicatedStorage").Remotes.Killsound:FireServer(unpack(args))

end)