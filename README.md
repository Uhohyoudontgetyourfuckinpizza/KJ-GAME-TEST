local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))() local Window = Library.CreateLib("Wave Hub", "DarkTheme")

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