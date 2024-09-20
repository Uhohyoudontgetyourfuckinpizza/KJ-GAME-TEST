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

