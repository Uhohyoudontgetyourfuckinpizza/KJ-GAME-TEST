local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("|Wave|", "DarkTheme")

local Tab = Window:NewTab("NJAKG")


local Section = Tab:NewSection("kj base (not spammable)")
Section:NewButton("Ravage (auto)", "This isnt spammable", function()
    local args = {
    [1] = "Combat",
    [2] = "Ravage",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Swift Kick", "ButtonInfo", function()
    local args = {
    [1] = "Combat",
    [2] = "Swift Sweep",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Collertal Ruin", "ButtonInfo", function()
local args = {
    [1] = "Combat",
    [2] = "Collateral Ruin",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

Section:NewButton("Signature Kick", "ButtonInfo", function()
    local args = {
    [1] = "Combat",
    [2] = "Signature Kick",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))

end)

local Section = Tab:NewSection("KJ ULT MOVES(SPAMMABLE)")

Section:NewButton("Stoic bomb", "ButtonInfo", function()
    local args = {
    [1] = "Combat",
    [2] = "BOMB",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("Dropkick", "ButtonInfo", function() game:GetService("ReplicatedStorage").KJ.Remote.DropKick:FireServer()
end)

Section:NewButton("Five seasons", "ButtonInfo", function()
    local args = {
    [1] = "Ability",
    [2] = "Season",
    [3] = {
        ["char"] = game:GetService("Players").LocalPlayer.Character,
        ["Player"] = game:GetService("Players").LocalPlayer,
        ["root"] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
        ["player"] = game:GetService("Players").LocalPlayer,
        ["hum"] = game:GetService("Players").LocalPlayer.Character.Humanoid
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("UFW", "ButtonInfo", function()
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

local Section = Tab:NewSection("Gojo (not spammable)")

Section:NewButton("Red", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Red",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("BLUE", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Blue",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("Beatdown", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Beatdown",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("BLACK FLASH", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Black Flash",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end) 

local Section = Tab:NewSection("Gojo's Ult")

Section:NewButton("Maximum Red", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Maximum Output : Red",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("Maximum blue", "ButtonInfo", function()
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

Section:NewButton("purple", "ButtonInfo", function()
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

local Section = Tab:NewSection("Early access char base moves (wip)")

Section:NewButton("Million Slashes", "ButtonInfo", function()
    local args = {
    [1] = "Flashy",
    [2] = "Million Pricks",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

Section:NewButton("Blink", "ButtonInfo", function()
   local args = {
    [1] = "Flashy",
    [2] = "Blink",
    [3] = {
        ["player"] = game:GetService("Players").LocalPlayer,
        ["pllayer"] = game:GetService("Players").LocalPlayer,
        ["Player"] = game:GetService("Players").LocalPlayer
    }
}

game:GetService("ReplicatedStorage").Server:InvokeServer(unpack(args))
end)

local Section = Tab:NewSection("Character switch")

Section:NewButton("KJ", "ButtonInfo", function()
  local args = {
    [1] = "SwitchC",
    [2] = "KJ"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("gojo", "ButtonInfo", function()
    local args = {
    [1] = "SwitchC",
    [2] = "The Honoured One"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)

Section:NewButton("FSM", "ButtonInfo", function()
    local args = {
    [1] = "SwitchC",
    [2] = "Flashiest Swordsman"
}

game:GetService("Players").LocalPlayer.PlayerGui.TopBar.UIScript.RemoteFunction:InvokeServer(unpack(args))

end)


local gui = Instance.new("ScreenGui")
gui.Name = "patrickGui"
gui.Parent = game.CoreGui
--screengui = gui



	local TextButton = Instance.new("TextButton")
-- Text
TextButton.Text = "UI TOGGLE"
TextButton.TextSize = 10
-- Color
TextButton.TextColor3 = Color3.new(1, 1, 1)
TextButton.BackgroundColor3 = Color3.new(0, 1, 1)
TextButton.BorderColor3 = Color3.new(1, 1, 1)
-- thickness
TextButton.BorderSizePixel = 2
-- Text Code
TextButton.Font = Enum.Font.Code
-- Size
TextButton.Size = UDim2.new(0.2, 0, 0.1, 0)
-- Posisition
TextButton.Position = UDim2.new(0, 0, 0.4, 0)
-- Function
TextButton.MouseButton1Click:Connect (function()
Library:ToggleUI()
end)
TextButton.Parent = gui
TextButton.Draggable = true

	local cornerUI = Instance.new("UICorner")
cornerUI.CornerRadius = UDim.new(0, 5)
cornerUI.Parent = TextButton

	local uiStroke = Instance.new("UIStroke")
    uiStroke.Color = Color3.new(0, 0, 0)
    uiStroke.Thickness = 2
    uiStroke.Parent = TextButton
    
