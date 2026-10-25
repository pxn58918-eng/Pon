-- ดึงข้อมูลผู้เล่นปัจจุบันที่กำลังเล่นอยู่
local player = game.Players.LocalPlayer

-- สร้าง ScreenGui สำหรับแสดงผลบนหน้าจอ
local screenGui = Instance.new("ScreenGui")
screenGui.Name = "PlayerInfoGui"
screenGui.Parent = player:WaitForChild("PlayerGui")

-- สร้าง TextLabel เพื่อแสดงข้อความ
local textLabel = Instance.new("TextLabel")
textLabel.Size = UDim2.new(0, 350, 0, 100)
textLabel.Position = UDim2.new(0.5, -175, 0.1, 0) -- แสดงไว้ที่กลางจอส่วนบน
textLabel.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
textLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
textLabel.TextScaled = true
textLabel.Font = Enum.Font.GothamBold
textLabel.Parent = screenGui

-- ดึงชื่อและ UserId มาแสดงผล
textLabel.Text = "ชื่อผู้เล่น: " .. player.Name .. "\nUserId: " .. player.UserId
