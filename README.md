local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("discord JaJaHub")

local serv = win:Server("JaJa", "")

local btns = serv:Channel("UPDATE 4.2")

btns:Button("FUCKALL", function()
DiscordLib:Notification("Notification", "JaJa เย็ดทุกคนเรียบร้อย!", "Okay!")
end)

btns:Seperator()

btns:Button("Get JaJaMad", function()
DiscordLib:Notification("Notification", "JaJaMad!!", "Okay!")
end)

local tgls = serv:Channel("Auto Farm")

tgls:Toggle("Auto Rage",false, function(bool)
print(bool)
end)

tgls:Toggle("Auto เงี่ยน",false, function(bool)
print(bool)
end)

tgls:Toggle("Auto ทำปาก",false, function(bool)
print(bool)
end)

tgls:Toggle(" Auto ลวนลาม",false, function(bool)
print(bool)
end)

tgls:Toggle(" Auto งอน",false, function(bool)
print(bool)
end)

tgls:Toggle("Auto ด้อย",false, function(bool)
print(bool)
end)


local sldrs = serv:Channel("Stats")

local sldr = sldrs:Slider("JaJa Power!", 0, 1000, 400, function(t)
print(t)
end)

sldrs:Button("Change to 9999999", function()
sldr:Change(9999999)
end)

tgls:Toggle("ฟ้องครู",false, function(bool)
print(bool)
end)

tgls:Toggle("Super Raid",false, function(bool)
print(bool)
end)

tgls:Toggle("บังคับเพื่อน",false, function(bool)
print(bool)
end)

tgls:Toggle("ออกคำสั่ง",false, function(bool)
print(bool)
end)

tgls:Toggle("ร้องไห้",false, function(bool)
print(bool)
end)



local drops = serv:Channel("Dropdowns")


local drop = drops:Dropdown("Pick me!",{"JaJa Friend","JaJa BoyFriend","Justin","Earl","Option 5"}, function(bool)
print(bool)
end)

drops:Button("Clear", function()
drop:Clear()
end)

drops:Button("Add option", function()
drop:Add("Option")
end)

local clrs = serv:Channel("JaJa Color")

clrs:Colorpicker("ESP Color", Color3.fromRGB(255,1,1), function(t)
print(t)
end)

local textbs = serv:Channel("Text To JaJa")

textbs:Textbox("Gun power", "Type here!", true, function(t)
print(t)
end)
