_G.UI_Name = "Discord"

local CoreGui = game:GetService("CoreGui")

if CoreGui:FindFirstChild(_G.UI_Name) then
    
    CoreGui:FindFirstChild(_G.UI_Name):Destroy() 
    
end

local DiscordLib =
    loadstring(game:HttpGet "https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/discord")()

local win = DiscordLib:Window("Script Fruit Warrior by.TanHub")

local serv = win:Server("[MOBILE] Fruit Warrior", "")


local btns = serv:Channel("Teleports")


btns:Button(
    "Rookie Town",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-365.293915, 216.513016, 370.433624, -0.943796039, -5.47732455e-08, 0.330528349, -7.73711903e-08, 1, -5.52127553e-08, -0.330528349, -7.76829552e-08, -0.943796039)
    end
)

btns:Seperator()

btns:Button(
    "Orange Town",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-322.802765, 210.497192, -1356.58606, -0.870313168, 5.69270178e-08, -0.492498696, 5.78326009e-08, 1, 1.33899718e-08, 0.492498696, -1.68290111e-08, -0.870313168)
    end
)

btns:Seperator()

btns:Button(
    "Desert Dungoen",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2979.74878, 202.302307, -4792.76074, -0.869051516, -4.65984762e-08, -0.494721591, -9.9380264e-09, 1, -7.67337056e-08, 0.494721591, -6.17689864e-08, -0.869051516)
    end
)

btns:Seperator()

btns:Button(
    "Snow Island",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2239.90503, 533.599731, 2462.49512, -0.701303601, 2.71321596e-08, 0.71286273, -1.22532109e-10, 1, -3.8181394e-08, -0.71286273, -2.68640967e-08, -0.701303601)
    end
)

btns:Seperator()

btns:Button(
    "Arena Island",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1576, 206.129105, 1055, 1, 5.29863229e-08, -2.19965376e-14, -5.29863229e-08, 1, -9.78804451e-08, 1.68102125e-14, 9.78804451e-08, 1)
    end
)

btns:Seperator()

btns:Button(
    "South Hil",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1105.95471, 393.949921, 1140.0719, 0.976835668, 1.01113375e-08, 0.213990778, -2.2462153e-08, 1, 5.52850707e-08, -0.213990778, -5.88111213e-08, 0.976835668)
    end
)

btns:Seperator()

btns:Button(
    "East Hill",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(654.424377, 396.699921, -538.694702, -0.983435631, -7.15427007e-08, -0.181257784, -6.44050289e-08, 1, -4.52642546e-08, 0.181257784, -3.28405676e-08, -0.983435631)
    end
)

btns:Seperator()

btns:Button(
    "North Hill",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1983, 632.199829, -422, 1, -1.82775981e-08, 2.09899948e-14, 1.82775981e-08, 1, -1.62648135e-08, -2.06927134e-14, 1.62648135e-08, 1)
    end
)

btns:Seperator()

btns:Button(
    "Jungle Island",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(162.381592, 221.998795, 2151.99438, 0.488149375, -4.18663753e-08, 0.872760117, 2.16360139e-08, 1, 3.58686982e-08, -0.872760117, 1.37376732e-09, 0.488149375)
    end
)

btns:Seperator()

btns:Button(
    "Sky Island",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2997, 1824.70398, -5161, 1, -1.14508369e-09, 8.05737692e-18, 1.14508369e-09, 1, -6.58881422e-11, -7.98192978e-18, 6.58881422e-11, 1)
    end
)

btns:Seperator()

btns:Button(
    "WaterFallen Island",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2441.56714, 225.629349, -2821.84131, -0.97957921, -1.66912972e-08, 0.201058492, 1.00574915e-09, 1, 8.79172433e-08, -0.201058492, 8.63241141e-08, -0.97957921)
    end
)

btns:Seperator()

btns:Button(
    "Sky Runic",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4226.08301, 2572.99683, -5523.66309, -0.148562178, 6.1275351e-08, 0.988903046, -3.21604077e-08, 1, -6.67943851e-08, -0.988903046, -4.1726647e-08, -0.148562178)
    end
)

btns:Seperator()

btns:Button(
    "EastHil Runic",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(599, 657.752319, -617, 1, -8.47427284e-09, 8.4323641e-14, 8.47427284e-09, 1, -6.24992751e-08, -8.37940015e-14, 6.24992751e-08, 1)
    end
)

btns:Seperator()

btns:Button(
    "NorthHill Ialand",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2022, 657.797974, -446, 1, 5.3683884e-08, 9.5834236e-14, -5.3683884e-08, 1, 2.22333494e-08, -9.46406649e-14, -2.22333494e-08, 1)
    end
)

btns:Seperator()

btns:Button(
    "Desert Runic",
    function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2824.64868, 202.052368, -4420.31641, 0.99999994, 8.27996838e-11, 0.000351778028, -1.02504595e-10, 1, 5.60151605e-08, -0.000351778028, -5.6015196e-08, 0.99999994)
    end
)

win:Server("Main", "http://www.roblox.com/asset/?id=6031075938")

local tgls = serv:Channel("Auto Farm All")

tgls:Toggle(
    "Auto-FarmDefense",false,function(bool)
        while bool do
    wait(4)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3308.13037, 1888.37122, -5220.68115, -0.852645338, 0.118890397, -0.508783877, -0.094260633, 0.922788322, 0.373599708, 0.513917267, 0.366506338, -0.775604427)
end
end
)

