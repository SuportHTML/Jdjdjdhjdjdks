-- Cria a interface de usuário
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- Cria um botão ESP
local espButton = Instance.new("TextButton")
espButton.Size = UDim2.new(0, 200, 0, 50)
espButton.Position = UDim2.new(0, 0, 0, 100)
espButton.Text = "ESP (Ver Jogadores)"
espButton.Parent = screenGui

espButton.MouseButton1Click:Connect(function()
    -- Código para ativar o ESP (Mostrar jogadores através das paredes)
    -- Esta funcionalidade é contra as regras do Roblox, cuidado
    print("ESP ativado!")
end)

-- Cria um botão AimBot
local aimbotButton = Instance.new("TextButton")
aimbotButton.Size = UDim2.new(0, 200, 0, 50)
aimbotButton.Position = UDim2.new(0, 0, 0, 160)
aimbotButton.Text = "AimBot"
aimbotButton.Parent = screenGui

aimbotButton.MouseButton1Click:Connect(function()
    -- Código para aimbot (mirar no jogador correto)
    print("AimBot ativado!")
end)

-- Cria um botão para desbloquear Gamepasses
local gamePassButton = Instance.new("TextButton")
gamePassButton.Size = UDim2.new(0, 200, 0, 50)
gamePassButton.Position = UDim2.new(0, 0, 0, 220)
gamePassButton.Text = "Premium Brookhaven Grátis"
gamePassButton.Parent = screenGui

gamePassButton.MouseButton1Click:Connect(function()
    -- Código para desbloquear Gamepasses
    print("GamePass desbloqueado!")
end)
