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