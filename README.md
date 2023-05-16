_G.Key = "sad"
getgenv().Keylink1 = "MrMaxNaJa"
getgenv().Keylink2 = "None"
getgenv().Keylink3 = "None"
getgenv().Keylink4 = "None"
getgenv().Keylink5 = "laerzx-1000-x19zxc-0x4c9"

_G.Key1 = "aaa" 
    -----ที่ล็อกไว้ใช้งานได้แต่กูไม่ชอบ
 --ไม่สามารถใส่คีย์ได้
_G.UIColor = Color3.fromRGB(250,250,250)
local Logo = ("12862171447")
_G.NameHub = "                                           NaJa Hub | Key Vip"
_G.Namelog = "NaJa Hub | Key Vip"
_G.Section = "Login to NaJa Hub"
_G.Title = "Map Blox Fruits"

local Loading = Instance.new("ScreenGui")
local Blur = Instance.new("Frame")
local Main = Instance.new("ImageButton")
local Logo_Image = Instance.new("ImageLabel")
local Logo_Image2 = Instance.new("ImageLabel")
local Bar = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextBox1 = Instance.new("TextBox")
local TextLabel_2 = Instance.new("TextLabel")
local NameHub = Instance.new("TextLabel")
local Start = Instance.new("TextButton")
local GetKey = Instance.new("TextButton")
local X = Instance.new("TextButton")
local M = Instance.new("TextButton")
local M1 = Instance.new("TextButton")
local HowToGetKey = Instance.new("TextButton")
local Youtube = Instance.new("TextButton")
local Corner = Instance.new("UICorner")
local UICorner = Instance.new("UICorner")
local UICorner1 = Instance.new("UICorner")
local UICorner11 = Instance.new("UICorner")
local UICorner2 = Instance.new("UICorner")
local UICorner3 = Instance.new("UICorner")
local UICorner4 = Instance.new("UICorner")
local UICorner5 = Instance.new("UICorner")
local UICorner6 = Instance.new("UICorner")
local UICorner7 = Instance.new("UICorner")
local UICorner31 = Instance.new("UICorner")
local ButtonColor = Instance.new("UIStroke")
local ButtonColor2 = Instance.new("UIStroke")
local ButtonColor3 = Instance.new("UIStroke")
local ButtonColor4 = Instance.new("UIStroke")
local ButtonColor5 = Instance.new("UIStroke")
local ButtonColor6 = Instance.new("UIStroke")
local ButtonColor7 = Instance.new("UIStroke")
local ButtonColor14 = Instance.new("UIStroke")

--Properties:

Loading.Name = "Loading"
Loading.Parent = game.CoreGui
Loading.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Blur.Name = "Blur"
Blur.Parent = Loading
Blur.BackgroundColor3 = Color3.fromRGB(23,23,23)
Blur.BackgroundTransparency = 1
Blur.Size = UDim2.new(1, 0, 1, 0)

Main.Name = "Main"
Main.Parent = Blur
Main.BorderSizePixel = 0
Main.AnchorPoint = Vector2.new(0.5, 0.5)
Main.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
Main.ClipsDescendants = true
Main.Position = UDim2.new(0.5, 0, 0.499241263, 0)
Main.Draggable = true
Main.Size = UDim2.new(0, 500, 0, 200)
Main.Image = "rbxassetid://0"

Corner.Parent = Main

ButtonColor.Thickness = 3.2
ButtonColor.Name = ""
ButtonColor.Parent = Main
ButtonColor.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor.Color = _G.UIColor
ButtonColor.Transparency = 0.10

UICorner5.CornerRadius = UDim.new(0, 10)
UICorner5.Parent = Main

Logo_Image.Name = "Logo_Image"
Logo_Image.Parent = Main
Logo_Image.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo_Image.BackgroundTransparency = 1.000
Logo_Image.ImageTransparency = 1.000
Logo_Image.BorderSizePixel = 0
Logo_Image.Position = UDim2.new(0.01, 0, 0, 2.2)
Logo_Image.Size = UDim2.new(0, 35, 0, 35)
Logo_Image.Image = "rbxassetid://"..(Logo)

NameHub.Name = "NameHub"
NameHub.Parent = Main
NameHub.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
NameHub.BackgroundTransparency = 1.000
NameHub.Position = UDim2.new(0, 30, 0, -1.5)
NameHub.Size = UDim2.new(0, 200, 0, 50)
NameHub.Font = Enum.Font.Gotham
NameHub.Text = _G.NameHub
NameHub.TextColor3 = _G.UIColor
NameHub.TextSize = 18.000

Logo_Image2.Name = "Logo_Image2"
Logo_Image2.Parent = Main
Logo_Image2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo_Image2.BackgroundTransparency = 1.000
Logo_Image2.BorderSizePixel = 0
Logo_Image2.Position = UDim2.new(0, 7, 0, 52)
Logo_Image2.Size = UDim2.new(0, 123, 0, 140)
Logo_Image2.Image = "rbxassetid://"..(Logo)

ButtonColor6.Thickness = 1.5
ButtonColor6.Name = ""
ButtonColor6.Parent = Logo_Image2
ButtonColor6.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor6.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor6.Color = _G.UIColor
ButtonColor6.Transparency = 0.10

UICorner6.CornerRadius = UDim.new(0, 10)
UICorner6.Parent = Logo_Image2

local NameMap = Instance.new("TextLabel")
NameMap.Name = "NameMap"
NameMap.Parent = Main
NameMap.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NameMap.BackgroundTransparency = 1.000
NameMap.Position = UDim2.new(0, 15, 0, 15)
NameMap.Size = UDim2.new(0, 61, 0, 27)
NameMap.Font = Enum.Font.GothamSemibold
NameMap.Text = _G.Title
NameMap.TextColor3 = Color3.fromRGB(255, 255, 255)
NameMap.TextSize = 11.000

local NameMap1 = Instance.new("TextLabel")
NameMap1.Name = "NameMap1"
NameMap1.Parent = Main
NameMap1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NameMap1.BackgroundTransparency = 1.000
NameMap1.Position = UDim2.new(0, 205, 0, 60)
NameMap1.Size = UDim2.new(0, 61, 0, 27)
NameMap1.Font = Enum.Font.GothamSemibold
NameMap1.Text = _G.Section
NameMap1.TextColor3 = Color3.fromRGB(255, 255, 255)
NameMap1.TextSize = 20.000
    
Start.Name = "Start"
Start.Parent = Main
Start.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
Start.BorderSizePixel = 0
Start.Position = UDim2.new(0, 350, 0, 50)
Start.Size = UDim2.new(0, 145, 0, 45)
Start.Font = Enum.Font.Gotham
Start.Text = "Script No Key"
Start.TextColor3 = Color3.fromRGB(255, 255,255)
Start.TextSize = 14.000
Start.MouseButton1Click:Connect(function()
log("แมพนี้ไม่มีนะจ๊ะ","9649923603",2)
--local SysemKeyyy = game.CoreGui:FindFirstChild("Loading")
--Main:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.4,true)
--wait(0.4)
--SysemKeyyy:Destroy()
--Script()
--loadstring(game:HttpGet("https://raw.githubusercontent.com/xOne2/NaJanew/main/README.md"))()
--loadstring(game:HttpGet("https://raw.githubusercontent.com/NeaPchX2/Playback-X-HUB/main/PlaybackXHub.lua"))()-- You Script' 
--game:GetService("CoreGui").Loading:Destroy()
end)

UICorner2.CornerRadius = UDim.new(0, 10)
UICorner2.Parent = Start

ButtonColor2.Thickness = 3.2
ButtonColor2.Name = ""
ButtonColor2.Parent = Start
ButtonColor2.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor2.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor2.Color = _G.UIColor
ButtonColor2.Transparency = 0.10

GetKey.Name = "GetKey"
GetKey.Parent = Main
GetKey.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
GetKey.BorderSizePixel = 0
GetKey.Position = UDim2.new(0, 350, 0, 105)
GetKey.Size = UDim2.new(0, 145, 0, 45)
GetKey.Font = Enum.Font.Gotham
GetKey.Text = "GetKey"
GetKey.TextColor3 = Color3.fromRGB(255, 255, 255)
GetKey.TextSize = 14.000
GetKey.MouseButton1Click:Connect(function()
setclipboard("https://direct-link.net/436835/mrmaxnaja-key") --YouWap
log("คุณได้คัดลอกลิงค์เป็นที่เรียบร้อยแล้ว","9649923603",2)
end)

--[[local IMGNAME = Instance.new("ImageLabel")
IMGNAME.Name = "IMGDATA"
IMGNAME.Parent = GetKey
IMGNAME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
IMGNAME.BackgroundTransparency = 1.000
IMGNAME.ImageTransparency = 0.5
IMGNAME.Position = UDim2.new(0, 45, 0, 0)
IMGNAME.Size = UDim2.new(0, 50, 0, 50)
IMGNAME.Image = "rbxassetid://12862797362"
IMGNAME.Rotation = 20]]


ButtonColor3.Thickness = 3.2
ButtonColor3.Name = ""
ButtonColor3.Parent = GetKey
ButtonColor3.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor3.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor3.Color = _G.UIColor
ButtonColor3.Transparency = 0.10

UICorner.CornerRadius = UDim.new(0, 10)
UICorner.Parent = GetKey

HowToGetKey.Name = "HowToGetKey"
HowToGetKey.Parent = Main
HowToGetKey.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
HowToGetKey.BorderSizePixel = 0
HowToGetKey.Position = UDim2.new(0,397,0,160)
HowToGetKey.Size = UDim2.new(0, 98, 0, 35)
HowToGetKey.Font = Enum.Font.Gotham
HowToGetKey.Text = "HowToGetKey"
HowToGetKey.TextColor3 = Color3.fromRGB(255, 255, 255)
HowToGetKey.TextSize = 14.000
HowToGetKey.MouseButton1Click:Connect(function()
setclipboard("https://www.youtube.com/@MrMaxNaJaa/videos") --YouWap
log("คุณได้คัดลอกลิงค์เป็นที่เรียบร้อยแล้ว","9649923603",2)
end)

ButtonColor5.Thickness = 3.2
ButtonColor5.Name = ""
ButtonColor5.Parent = HowToGetKey
ButtonColor5.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor5.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor5.Color = _G.UIColor
ButtonColor5.Transparency = 0.10

UICorner4.CornerRadius = UDim.new(0, 10)
UICorner4.Parent = HowToGetKey

Youtube.Name = "Youtube"
Youtube.Parent = Main
Youtube.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
Youtube.BorderSizePixel = 0
Youtube.Position = UDim2.new(0,350.1,0,160)
Youtube.Size = UDim2.new(0, 35, 0, 35)
Youtube.Font = Enum.Font.Gotham
Youtube.Text = " ▶"
Youtube.TextColor3 = Color3.fromRGB(255, 255, 255)
Youtube.TextSize = 14.000
Youtube.MouseButton1Click:Connect(function()
setclipboard("https://www.youtube.com/@MrMaxNaJaa") --YouWap
wait(.1)
log("คุณได้คัดลอกลิงค์เป็นที่เรียบร้อยแล้ว","9649923603",2)
end)

ButtonColor7.Thickness = 3.2
ButtonColor7.Name = ""
ButtonColor7.Parent = Youtube
ButtonColor7.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor7.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor7.Color = _G.UIColor
ButtonColor7.Transparency = 0.10

UICorner7.CornerRadius = UDim.new(0, 10)
UICorner7.Parent = Youtube

X.Name = "X"
X.Parent = Main
X.BackgroundColor3 = Color3.fromRGB(100,0,0)
X.BorderSizePixel = 0
X.Position = UDim2.new(0.92, 0, 0.008, 2.3)
X.Size = UDim2.new(0, 33, 0, 33)
X.Font = Enum.Font.Gotham
X.Text = "X"
X.TextColor3 = Color3.fromRGB(255, 255, 255)
X.TextSize = 17.00
X.MouseButton1Click:Connect(function()
local SysemKeyyy = game.CoreGui:FindFirstChild("Loading")
Main:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.4,true)
wait(0.4)
SysemKeyyy:Destroy()
game:GetService("CoreGui").Loading:Destroy()
end)

local Corner = Instance.new("UICorner")
Corner.CornerRadius = UDim.new(0, 5)
Corner.Name = "ServerCorner"
Corner.Parent = X

M.Name = "M"
M.Parent = Main
M.BackgroundColor3 = Color3.fromRGB(0,0,100)
M.BorderSizePixel = 0
M.Position = UDim2.new(0.85, -2, 0.008, 2.3)
M.Size = UDim2.new(0, 33, 0, 33)
M.Font = Enum.Font.Gotham
M.Text = "-"
M.TextColor3 = Color3.fromRGB(255, 255, 255)
M.TextSize = 17.00
M.MouseButton1Click:Connect(function()
Main:TweenSize(UDim2.new(0,500,0,50),"Out","Quad",0.4,true)
M.Position = UDim2.new(0.85, 9999, 0.008, 2.3)
M1.Position = UDim2.new(0.85, -2, 0.008, 2.3)
end)

local UICorner1 = Instance.new("UICorner")
UICorner1.CornerRadius = UDim.new(0, 5)
UICorner1.Name = "ServerCorner"
UICorner1.Parent = M

M1.Name = "M1"
M1.Parent = Main
M1.BackgroundColor3 = Color3.fromRGB(0,0,100)
M1.BorderSizePixel = 0
M1.Position = UDim2.new(0.85, 9999, 0.008, 2.3)
M1.Size = UDim2.new(0, 33, 0, 33)
M1.Font = Enum.Font.Gotham
M1.Text = "-"
M1.TextColor3 = Color3.fromRGB(255, 255, 255)
M1.TextSize = 17.00
M1.MouseButton1Click:Connect(function()
Main:TweenSize(UDim2.new(0,500,0,200),"Out","Quad",0.4,true)
M1.Position = UDim2.new(0.85, 99999, 0.008, 2.3)
M.Position = UDim2.new(0.85, -2, 0.008, 2.3)
end)

local UICorner11 = Instance.new("UICorner")
UICorner11.CornerRadius = UDim.new(0, 5)
UICorner11.Name = "ServerCorner"
UICorner11.Parent = M1

Bar.Name = "Bar"
Bar.Parent = Main
Bar.BorderSizePixel = 0
Bar.BackgroundColor3 = _G.UIColor
Bar.Position = UDim2.new(0, 0, 0, 40)
Bar.Size = UDim2.new(0, 525, 0, 1)

TextBox.Parent = Main
TextBox.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
TextBox.BorderSizePixel = 0
TextBox.ClipsDescendants = true
TextBox.Position = UDim2.new(0, 140, 0, 155)
TextBox.Size = UDim2.new(0, 200, 0, 35)
TextBox.ZIndex = 99
TextBox.ClearTextOnFocus = false
TextBox.Font = Enum.Font.Gotham
TextBox.PlaceholderColor3 = Color3.fromRGB(20, 21, 22)
TextBox.PlaceholderText = "Type here!"
TextBox.Text = "Login with Premium Key"
TextBox.TextColor3 = Color3.fromRGB(255,255,255)
TextBox.TextSize = 17.00

-----ที่ล็อกไว้ใช้งานได้แต่กูไม่ชอบ
--[[local IMGNAME1 = Instance.new("ImageLabel")
IMGNAME1.Name = "IMGDATA"
IMGNAME1.Parent = TextBox
IMGNAME1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
IMGNAME1.BackgroundTransparency = 1.000
IMGNAME1.ImageTransparency = 0.5
IMGNAME1.Position = UDim2.new(0, 45, 0, 0)
IMGNAME1.Size = UDim2.new(0, 50, 0, 50)
IMGNAME1.Image = "rbxassetid://12862797362"
IMGNAME1.Rotation = 20

local IMGNAME2 = Instance.new("ImageLabel")
IMGNAME2.Name = "IMGDATA"
IMGNAME2.Parent = TextBox1
IMGNAME2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
IMGNAME2.BackgroundTransparency = 1.000
IMGNAME2.ImageTransparency = 0.5
IMGNAME2.Position = UDim2.new(0, 45, 0, 0)
IMGNAME2.Size = UDim2.new(0, 50, 0, 50)
IMGNAME2.Image = "rbxassetid://12862797362"
IMGNAME2.Rotation = 20]]

ButtonColor4.Thickness = 3.2
ButtonColor4.Name = ""
ButtonColor4.Parent = TextBox
ButtonColor4.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor4.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor4.Color = _G.UIColor
ButtonColor4.Transparency = 0.10

UICorner3.CornerRadius = UDim.new(0, 5)
UICorner3.Parent = TextBox

TextBox1.Parent = Main
TextBox1.BackgroundColor3 = Color3.fromRGB(20, 21, 22)
TextBox1.BorderSizePixel = 0
TextBox1.ClipsDescendants = true
TextBox1.Position = UDim2.new(0, 140, 0, 110)
TextBox1.Size = UDim2.new(0, 200, 0, 35)
TextBox1.ZIndex = 99
TextBox1.ClearTextOnFocus = false
TextBox1.Font = Enum.Font.Gotham
TextBox1.PlaceholderColor3 = Color3.fromRGB(20, 21, 22)
TextBox1.PlaceholderText = "Type here!"
TextBox1.Text = "Login with key"
TextBox1.TextColor3 = Color3.fromRGB(255,255,255)
TextBox1.TextSize = 17.00

ButtonColor14.Thickness = 3.2
ButtonColor14.Name = ""
ButtonColor14.Parent = TextBox1
ButtonColor14.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
ButtonColor14.LineJoinMode = Enum.LineJoinMode.Round
ButtonColor14.Color = _G.UIColor
ButtonColor14.Transparency = 0.10

UICorner31.CornerRadius = UDim.new(0, 5)
UICorner31.Parent = TextBox1

function log(Text,picture,time)
	local LogLoading = Instance.new("ScreenGui")
	local ToggleFrameUi = Instance.new("Frame")
	local UICorner = Instance.new("UICorner")
	local ToggleImgUi = Instance.new("ImageLabel")
	local Uitoggle = Instance.new("TextLabel")
	local Yedhee = Instance.new("TextLabel")
	local SearchStroke = Instance.new("UIStroke")
	local labell = {}
	
	LogLoading.Name = "LogLoading"
	LogLoading.Parent = game.CoreGui
	LogLoading.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
	ToggleFrameUi.Name = "ToggleFrameUi"
	ToggleFrameUi.Parent = LogLoading
	ToggleFrameUi.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
	ToggleFrameUi.Position = UDim2.new(0.01, 0, 0, 170)
	ToggleFrameUi.Size = UDim2.new(0, 198, 0, 48)
	
	ToggleFrameUi:TweenPosition(UDim2.new(0, 0, 0, 170),"In","Quad",0.4,true)
	ToggleFrameUi:TweenPosition(UDim2.new(0.01, 0, 0, 170),"In","Quad",0.4,true)
	ToggleFrameUi:TweenSize(UDim2.new(0, 0, 0, 48),"In","Quad",0.4,true)
	ToggleFrameUi:TweenSize(UDim2.new(0, 198, 0, 48),"In","Quad",0.4,true)
	
	SearchStroke.Thickness = 3.2
	SearchStroke.Name = ""
	SearchStroke.Parent = ToggleFrameUi
	SearchStroke.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
	SearchStroke.LineJoinMode = Enum.LineJoinMode.Round
	SearchStroke.Color = _G.UIColor
	SearchStroke.Transparency = 0.10
	
	UICorner.CornerRadius = UDim.new(0, 4)
	UICorner.Parent = ToggleFrameUi
	
	ToggleImgUi.Name = "ToggleImgUi"
	ToggleImgUi.Parent = ToggleFrameUi
	ToggleImgUi.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	ToggleImgUi.BackgroundTransparency = 1.000
	ToggleImgUi.Position = UDim2.new(0.0454545468, 0, 0.125000313, 0)
	ToggleImgUi.Size = UDim2.new(0, 35, 0, 35)
	ToggleImgUi.Image = "rbxassetid://"..(picture)
	
	Uitoggle.Name = "Uitoggle"
	Uitoggle.Parent = ToggleFrameUi
	Uitoggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Uitoggle.BackgroundTransparency = 1.000
	Uitoggle.Position = UDim2.new(0.25757575, 0, 0, 0)
	Uitoggle.Size = UDim2.new(0, 137, 0, 25)
	Uitoggle.Font = Enum.Font.GothamSemibold
	Uitoggle.Text = _G.Namelog
	Uitoggle.TextColor3 = Color3.fromRGB(255, 255, 255)
	Uitoggle.TextSize = 12.000
	
	Yedhee.Name = "Yedhee"
	Yedhee.Parent = ToggleFrameUi
	Yedhee.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Yedhee.BackgroundTransparency = 1.000
	Yedhee.Position = UDim2.new(0.25757575, 0, 0.479166657, 0)
	Yedhee.Size = UDim2.new(0, 137, 0, 25)
	Yedhee.Font = Enum.Font.GothamSemibold
	Yedhee.Text = Text
	Yedhee.TextColor3 = Color3.fromRGB(255, 255, 255)
	Yedhee.TextSize = 12.000
	
	function labell:Set(newtext)
		Yedhee.Text = newtext
	end
	wait(time)
	ToggleFrameUi:TweenPosition(UDim2.new(0.01, 0, 0, 170),"In","Quad",0.4,true)
	ToggleFrameUi:TweenPosition(UDim2.new(0, 0, 0, 170),"In","Quad",0.4,true)
	ToggleFrameUi:TweenSize(UDim2.new(0, 198, 0, 48),"In","Quad",0.4,true)
	ToggleFrameUi:TweenSize(UDim2.new(0, 0, 0, 48),"In","Quad",0.4,true)
	local Log = game.CoreGui:FindFirstChild("LogLoading")
	Log:Destroy()
	return labell
end

local UKey = {
    getgenv().Keylink1,
    getgenv().Keylink2,
    getgenv().Keylink3,
    getgenv().Keylink4,
    getgenv().Keylink5,
}

local SysemKey = {
    "123",
    "NoKey",
    "ADMIN",
    "Sub MrMaxNaJa",
}

TextBox1.FocusLost:Connect(function()
LoadingScript1(TextBox1.Text)
end)

function LoadingScript1(Text)
register_key1 = Text
	for i,v in pairs(UKey) do	
		if v == register_key1 then
       	TextBox1.Text = "คีย์ถูกต้อง"
      	 wait(.5)
      	 TextBox1.TextColor3 = Color3.fromRGB(0,255,0)
      	 wait(1)
			local SysemKeyyy = game.CoreGui:FindFirstChild("Loading")
			Main:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.4,true)
			wait(0.4)
			SysemKeyyy:Destroy()
			
			Script()
     elseif TextBox1.Text == "Login with key" or TextBox1.Text == "" then
        	TextBox1.TextColor3 = Color3.fromRGB(255,255,255)
        	TextBox1.Text = "Login with key"
        	TextBox1.TextSize = 12.00
	  else
		   TextBox1.TextColor3 = Color3.fromRGB(255,0,0)
           TextBox1.Text = "คีย์ไม่ถูกต้อง"
           wait(1)
           TextBox1.TextColor3 = Color3.fromRGB(255,255,255)
     	  TextBox1.Text = "Login with key"
		end
	end
end

TextBox.FocusLost:Connect(function()
LoadingScript(TextBox.Text)
end)
function LoadingScript(Text)
register_key = Text
	for i,v in pairs(SysemKey) do	
		if v == register_key then
       	TextBox.Text = "คีย์ถูกต้อง"
      	 wait(.5)
      	 TextBox.TextColor3 = Color3.fromRGB(0,255,0)
      	 wait(1)
			local SysemKeyyy = game.CoreGui:FindFirstChild("Loading")
			Main:TweenSize(UDim2.new(0,0,0,0),"Out","Quad",0.4,true)
			wait(0.4)
			SysemKeyyy:Destroy()
			Script()
			game:GetService("CoreGui").Loading:Destroy()
     elseif TextBox.Text == "Login with Premium Key" or TextBox.Text == "" then
        	TextBox.TextColor3 = Color3.fromRGB(255,255,255)
        	TextBox.Text = "Login with Premium Key"
        	TextBox.TextSize = 12.00
	  else
		   TextBox.TextColor3 = Color3.fromRGB(255,0,0)
           TextBox.Text = "คีย์ไม่ถูกต้อง"
           wait(1)
           TextBox.TextColor3 = Color3.fromRGB(255,255,255)
     	   TextBox.Text = "Login with Premium Key"
		end
	end
end

function Script()
--Src
print("Hummmmmmmmm")


end

LoadingScript(_G.Key)--อย่าลบนะไอ้โง้
LoadingScript1(_G.Key1)--อย่าลบนะไอ้โง้
