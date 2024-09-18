-- Start the Orion Library
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({
    Name = "Zenon Universal",
    HidePremium = false,
    SaveConfig = true,
    ConfigFolder = "ZenonUniversal"
})


local Tab = Window:MakeTab({
  Name = "Information",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
})
local Section = Tab:AddSection({
  Name = "Information About Zenon Hub"
})
Tab:AddLabel("Click one of the buttons to copy username/discord.")


Tab:AddButton({
  Name = "Owner - voidyyy0",
  Callback = function()
  setclipboard("voidyyy0")
OrionLib:MakeNotification({
    Name = "Zenon Universal",
    Content = "Successfully copied username.",
    Image = "rbxassetid://4483345998",
    Time = 5
})
    end    
})

Tab:AddButton({
  Name = "Developer - .idontgiveaf",
  Callback = function()
  setclipboard(".idontgiveaf")
OrionLib:MakeNotification({
    Name = "Zenon Universal",
    Content = "Successfully copied username.",
    Image = "rbxassetid://4483345998",
    Time = 5
})
    end    
})

Tab:AddButton({
  Name = "Discord Link - Click to copy",
  Callback = function()
  setclipboard("https://discord.gg/Vmu9rUKn9h")
OrionLib:MakeNotification({
    Name = "Zenon Universal",
    Content = "Successfully copied the discord invite.",
    Image = "rbxassetid://4483345998",
    Time = 5
})
    end    
})

local Tab = Window:MakeTab({
	Name = "Universal",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Universal scripts that may work in all games."
})

Tab:AddButton({
	Name = "UNC Test",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-UNC-Test-13114",true))()
  	end    
})

Tab:AddButton({
	Name = "Infinite Yield",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
  	end    
})

Tab:AddButton({
	Name = "VFly Gui",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/S33dedL0rdz/-Unknown-Roblox-Vfly-Script-.file/main/Rbxscript.c"))()
  	end    
})

Tab:AddButton({
	Name = "Fate's Esp",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/fatesc/fates-esp/main/main.lua'))()

  	end    
})

Tab:AddButton({
	Name = "Fly GUI V3",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fly-Gui-V3-17541",true))()
  	end    
})

Tab:AddButton({
	Name = "Better Roblox V3",
	Callback = function()
loadstring(game:HttpGet('https://astroswrld.club/BetterRoblox/Loader'))()
  	end    
})

Tab:AddButton({
	Name = "Dark Dex",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Babyhamsta/RBLX_Scripts/main/Universal/BypassedDarkDexV3.lua", true))()
  	end    
})

Tab:AddButton({
	Name = "BetterBypasser - Chat Bypasser",
	Callback = function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Synergy-Networks/products/main/BetterBypasser/loader.lua"))()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Strongest Battlegrounds",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Sukuna Moveset - Use Strongest Hero",
	Callback = function()
loadstring(game:HttpGet"https://raw.githubusercortent.com/h8h88/hubfr/main/hubfr")()
  	end    
})

Tab:AddButton({
	Name = "Kazuma Moveset - Use Strongest Hero",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/The-Strongest-Battlegrounds-kazuma-kiryu-moveset-17198",true))()
  	end    
})

Tab:AddButton({
	Name = "Gojo Moveset - Key: Zenon12345",
	Callback = function()
loadstring(game:HttpGet("https://pastefy.app/glr9e0g3/raw"))()
  	end    
})

Tab:AddButton({
	Name = "Phantasm Hub",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/The-Strongest-Battlegrounds-Phantasm-SUPPORTS-SOLARA-18046",true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Doors",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "Blackking Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/DarkDoorsKing/Doors/main/Main"))()
  	end    
})

Tab:AddButton({
	Name = "Curse Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CurseOfDarkness/CurseHubDoors/main/Curse%20Hub%20Doors"))()
  	end    
})


Tab:AddButton({
	Name = "FFJ Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/FFJ1/Roblox-Exploits/main/scripts/Loader.lua"))()
  	end    
})


Tab:AddButton({
	Name = "Floor 1 And 2 Script",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Yumiara/Python/main/Main.lua"))();
  	end    
})

local Tab = Window:MakeTab({
	Name = "Ant Life",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "AntHaxx",
	Callback = function()
getgenv().AntHaxxLite = false -- SET THIS TO true IF YOU ARE USING SOLARA
loadstring(game:HttpGet('https://raw.githubusercontent.com/TestAccount69420xd/7632755652/main/943242049'))()
  	end    
})

Tab:AddButton({
	Name = "AntHaxx Solara Version",
	Callback = function()
getgenv().AntHaxxLite = true -- SET THIS TO true IF YOU ARE USING SOLARA
loadstring(game:HttpGet('https://raw.githubusercontent.com/TestAccount69420xd/7632755652/main/943242049'))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Arsenal",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Solaris.lol",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/toasty-dev/pissblox/main/solaris_bootstrapper.lua",true))()
  	end    
})

Tab:AddButton({
	Name = "Thunder Client Solara",
	Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/b95e8fecdf824e41f4a030044b055add.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Thunder Client",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Arsenal-Thunder-Client-V2-12177",true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Baddies",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Syrex Hub",
	Callback = function()
loadstring(game:HttpGet('https://syrexhub.netlify.app/raw/syrexhub'))()
  	end    
})
Tab:AddButton({
	Name = "Money Farm",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Baddiesandx1F525-Money-F1rm-15767",true))()
  	end    
})
Tab:AddButton({
	Name = "Demonic Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Prosexy/Demonic-HUB-V2/main/DemonicHub_V2.lua", true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Break In 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Starry Hub",
	Callback = function()
loadstring(game:HttpGet("https://www.cloudbin.org/love"))()
  	end    
})
Tab:AddButton({
	Name = "Venture Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NoahCodeMaster/VentureHub/main/Main.lua"))()
  	end    
})


local Tab = Window:MakeTab({
	Name = "Rivals",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Silent Rivals - Cracked Key",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cracklua/cracks/m/SilentRivals"))() -- adding later
  	end    
})
Tab:AddButton({
	Name = "God Hub",
	Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/c56622b9897b159614c3e7889571afd5.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Nexam Hub",
	Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/e14fc8a88047414dae10ea96adf47f53.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Breaking Point",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Devils Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/hassanxzayn-lua/devil-sbeakingpointgui/main/main"))();
  	end    
})
Tab:AddButton({
	Name = "Breaking Plus Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NaikoScript/Breaking-Plus/main/Script"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Jailbreak",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Auto Arrest",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SnipeHype200/i-music/main/autoarrest"))();
  	end    
})
Tab:AddButton({
	Name = "iMusic V3 Auto Rob",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SnipeHype200/i-music/main/beta.lua"))()
  	end    
})
Tab:AddButton({
	Name = "iMusic V3 Auto Arrest",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SnipeHype200/i-music/main/autoarrest"))();
  	end    
})

local Tab = Window:MakeTab({
	Name = "Brookhaven",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Ice hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMae17/NewIceHub/main/Brookhaven"))()
  	end    
})
Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/REDzHUB/main/REDzHUB"))()
  	end    
})
Tab:AddButton({
	Name = "R4D Hub",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-R4D-script-no-key-17562"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Bedwars",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Vape V4",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
  	end    
})
Tab:AddButton({
	Name = "Sigma Hub - Key?",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/OofHead-FE/Sigma-Jello/main/RobloxSigma5.lua",true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Blade Ball",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Nexam Hub",
	Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/ad08f0225388445dea30f4b42ea0558e.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Zap Hub",
	Callback = function()
loadstring(game:HttpGet('https://zaphub.xyz/Exec'))()
  	end    
})
Tab:AddButton({
	Name = "Xera Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/luascriptsROBLOX/BladeBallXera/main/XeraUltron"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Meme Sea",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Meme Sea Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Yatsuraa/Matsune/main/memesea.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/MemeSea/main/Source.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Blox Fruits",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Stingray AutoFarm",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/KITSUNE-Blox-Fruits-Stingray-Keyless-Autofarm-9619",true))()
  	end    
})
Tab:AddButton({
	Name = "BT Project Hub",
	Callback = function()
loadstring(game:HttpGetAsync("https://lua-library.btteam.net/script-auth.txt"))() 
  	end    
})
Tab:AddButton({
	Name = "TNG Hub PC",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/tngaming123/TNGHub/main/ForPC.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Eat The World",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "World Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NhatMinhVNQ/w-hub/main/WORLDHUB.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Tbao Hub",
	Callback = function()
loadstring(game:HttpGet"https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubEattheWorld")()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Evade",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Evade Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Babyhamsta/RBLX_Scripts/main/Evade/main.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Ardrak Hub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Hungtu2121/Ardrakhubv7/main/Evade'))()
  	end    
})
Tab:AddButton({
	Name = "Tbao Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubEvade"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Pressure",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "WT Hub",
	Callback = function()
loadstring(game:HttpGet'https://raw.githubusercontent.com/cracklua/cracks/m/WTpressure')()
  	end    
})
Tab:AddButton({
	Name = "Fire Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/InfernusScripts/Fire-Hub/main/Loader"))()
  	end    
})
Tab:AddButton({
	Name = "Caveira Hub - Key",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Powerblack09yt/Scripts/main/caveirahub-pressure.lua"))()
  	end    
})



local Tab = Window:MakeTab({
	Name = "Pillar Chase 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Ritual Hub Cracked - Click Login",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cracklua/cracks/m/ritual"))()
-- just click login, dont change the text
  	end    
})
Tab:AddButton({
	Name = "felssj Hub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/dqvh/dqvh/main/pillar%20chase%202.lua'))()
  	end    
})


local Tab = Window:MakeTab({
	Name = "Slap Battles",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Get All Gloves - Check Inventory",
	Callback = function()
for l, j in pairs(game.workspace.Lobby.GloveStands:GetChildren()) do
for i, v in pairs (game.ReplicatedStorage._NETWORK:GetChildren()) do if v.ClassName == "RemoteEvent" then
v:FireServer(j.Name)
end
end
end
	end
})

Tab:AddButton({
	Name = "Giang Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Giangplay/Slap_Battles/main/Slap_Battles.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Forge Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Skzuppy/forge-hub/main/loader.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Jujutsu Shenanigans",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Auto Block and More",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Synarcy/JJS-GUI/main/JJSAutoBlock.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Eternity Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/EternityDarkness/EternityHubJJS/main/Jujutsu%20Shenanigans"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Murder Mystery 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "God Hub",
	Callback = function()
loadstring(game:HttpGet("https://cdn.luarmor.net/verified/godhubloader.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Starry Hub",
	Callback = function()
loadstring(game:HttpGet("https://www.cloudbin.org/love"))()
  	end    
})
Tab:AddButton({
	Name = "Byte Hub",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Murder-Mystery-2-ByteHub-10357",true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "A Dusty Trip",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Nurk Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AbdouGG/dustytripv1/main/beta"))()
  	end    
})
Tab:AddButton({
	Name = "Erudite Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ThacG/EruditeHub/main/A%20Dusty%20Trip/V3"))()
  	end    
})


local Tab = Window:MakeTab({
	Name = "Combat Warriors",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "OP Hub",
	Callback = function()
loadstring(game:HttpGet("https://pastefy.app/50B4Z9UK/raw"))()
  	end    
})
Tab:AddButton({
	Name = "Infinite Stamina",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Combat-Warriors-Infinite-Stamina-7424",true))()
  	end    
})
Tab:AddButton({
	Name = "Max Hub",
	Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/1d4db6a1b04aaeccf046f7c63fbad31a.lua"))()
  	end    
})



local Tab = Window:MakeTab({
	Name = "Tower Of Hell",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Starry Hub",
	Callback = function()
loadstring(game:HttpGet("https://www.cloudbin.org/love"))()
  	end    
})
Tab:AddButton({
	Name = "Unnamed Hub",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/laeraz/scripts/main/Scripts%20that%20i%20made%20out%20of%20boredom/toh.lua'))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "3008",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Chiezzy Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/chiepz/aslbnmnkhby7e/main/crqhryvjahdjwysrnegsf%5Csgd"))()

  	end    
})
Tab:AddButton({
	Name = "Tbao Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHub3008"))()
  	end    
})


local Tab = Window:MakeTab({
	Name = "Ability Wars",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Nut Hub",
	Callback = function()
loadstring(game:HttpGet("https://pastefy.app/Kzc4felK/raw",true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Blade Ball",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Plutonium Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/PawsThePaw/Plutonium.AA/main/Plutonium.Loader.lua", true))()
  	end    
})
Tab:AddButton({
	Name = "Chaotic Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Mc4121ban/trashscript/main/chaotic.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Da Hood",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Nuker Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Allvideo1/Nukermode/main/Nukerscript"))()
  	end    
})
Tab:AddButton({
	Name = "SwagMode",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002'))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "CHAOS",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "FE Kill Aura",
	Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/VyCMCYG5"))()
  	end    
})
Tab:AddButton({
	Name = "Dash And Gamepass Script",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ApollyxnHashed/Chaos-Mobile-Scripts-Kit/main/Chaos%20KIT"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Realm Rampage",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "NBLM Hub",
	Callback = function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Emplic/NOBULEM/main/loader.lua"))()
	end
})

Tab:AddButton({
	Name = "Demonic Hub V2",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Prosexy/Demonic-HUB-V2/main/DemonicHub_V2.lua", true))()
	end
})

local Tab = Window:MakeTab({
	Name = "Dress To Impress",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Syrex Hub",
	Callback = function()
loadstring(game:HttpGet('https://syrexhub.netlify.app/raw/syrexhub'))()
	end
})

Tab:AddButton({
	Name = "ECCS Searcher V25",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ECCSco/ECCS-V3/main/ECCS%20Searcher%20V2.5"))("Copyright ERROR_CODE ECCS Co")
	end
})

local Tab = Window:MakeTab({
	Name = "Murder Mystery 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Starry Hub",
	Callback = function()
loadstring(game:HttpGet("https://www.cloudbin.org/love"))()
	end
})

Tab:AddButton({
	Name = "Byte Hub",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Murder-Mystery-2-ByteHub-10357",true))()
	end
})

local Tab = Window:MakeTab({
	Name = "Funky Friday",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Auto Player",
	Callback = function()
loadstring(game:HttpGet('https://pastebin.com/raw/dcyuEgyK'))()
	end
})

Tab:AddButton({
	Name = "Auto Player 2",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadir3709/RandomScript/main/FunkyFridayMobile"))()
	end
})
local Tab = Window:MakeTab({
	Name = "Untitled Tag Game",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Rinns Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SkibidiCen/MainMenu/main/Code"))()
	end
})

Tab:AddButton({
	Name = "UTG Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/nAlwspa/Into/main/hhh"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Bee Swarm Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "beacon hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/BaconBossScript/BeeSwarmSim/main/BeeSwarmSim"))()
	end
})

Tab:AddButton({
	Name = "Atlas Sticker Steal Script",
	Callback = function()
_G.antilag = true
_G.serverhop = true
loadstring(game:HttpGet("https://raw.githubusercontent.com/Chris8889/atlasbss/main/sticker.lua"))()
	end
})

Tab:AddButton({
	Name = "Kocmoc V3",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NukeVsCity/Scripts2024/main/KocmocV3"))()
	end
})


local Tab = Window:MakeTab({
	Name = "Anime Vanguards",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Speed Hub X",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Script-Games/main/Anime%20Vanguards.lua"))()
	end
})

Tab:AddButton({
	Name = "OP New Script",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CurseOfDarkness/CurseHubAnimeVanguards/main/Anime%20Vanguard%20OP"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Heroes battlegrounds",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Infernokarl Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/InfernoKarl/infernokarl/main/loadstring.lua", true))()
	end
})

Tab:AddButton({
	Name = "Demonic Hub V2",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Prosexy/Demonic-HUB-V2/main/DemonicHub_V2.lua", true))()
	end
})

local Tab = Window:MakeTab({
	Name = "Project Smash",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Auto Farm",
	Callback = function()
loadstring(Game:HttpGet("https://raw.githubusercontent.com/SumitScripts/Lil/main/Source"))()
	end
})

Tab:AddButton({
	Name = "Project Smash Script",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Riosetro/LERAZZHUB/main/HUB"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Item Asylum",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Hub",
	Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/TwXsMX4S",true))()
	end
})

Tab:AddButton({
	Name = "Hub 2",
	Callback = function()
loadstring(game:HttpGet(('https://pastebin.com/raw/Z4qVL5tM'),true))()
	end
})

Tab:AddButton({
	Name = "Hitbox Expander",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Vcsk/RobloxScripts/main/HitboxExpander.lua"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Greenville",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "YTTA Hub",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-its-op-YTTA-15154",true))()
	end
})

Tab:AddButton({
	Name = "Hub",
	Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/bZFnsBZv"))();
	end
})

local Tab = Window:MakeTab({
	Name = "Unnamed Shooter",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Aimbot & Esp",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/glenn4you/Script/main/Aimbot"))()
	end
})

Tab:AddButton({
	Name = "CanCantHUB US",
	Callback = function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/AmertaNestapa/CanCantHUB/main/games/Unnamed%20Shooter"))()
	end
})

Tab:AddButton({
	Name = "Rinns Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SkibidiCen/MainMenu/main/Code"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Survival Odyssey",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "CosmicHub",
	Callback = function()
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/59f093f67078d77846105beada5053cd.lua"))()
	end
})

Tab:AddButton({
	Name = "Unnamed Hub",
	Callback = function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/sigmarizzler11aa/survival-goonesy/main/obfuscated.lua"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Granny",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Zephyr Gr4nny Pr0m1dius G4mes",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Unknownlodfc/Zephyr/main/Zephyr%20%7C%20Granny"))()
	end
})

Tab:AddButton({
	Name = "Ski hub",
	Callback = function()
loadstring(game:HttpGet(("https://pastebin.com/raw/mT10xnt7"), true))()
	end
})

local Tab = Window:MakeTab({
	Name = "Prison Life",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Impact Hub (Solara Works)",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NoobExploits/Impact/main/main.lua"))()
	end
})

Tab:AddButton({
	Name = "X Rawnder V14",
	Callback = function()
loadstring(game:HttpGet("https://bit.ly/x-Rawnder"))();
	end
})

local Tab = Window:MakeTab({
	Name = "Fight In A School",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Dope Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/JayXSama/Fight-in-a-school/main/Solara"))()
	end
})

Tab:AddButton({
	Name = "Roxide Hub - PC Only",
	Callback = function()
-- FOR COMPUTER FOR COMPUTER FOR COMPUTER
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/2d566786c4bcee0a23e4543e0d3bd8b0.lua"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Curse Battlegrounds",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Blackking Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/BlackKing"))()
	end
})

local Tab = Window:MakeTab({
	Name = "DayBreak 2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Ritual Hub - Click Login",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cracklua/cracks/m/ritual"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Dandy's World",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab:AddButton({
	Name = "Ritual Hub - Click Login",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cracklua/cracks/m/ritual"))()
	end
})

Tab:AddButton({
	Name = "Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Bac0nHck/Scripts/main/Dandy's%20World"))("t.me/arceusxscripts")
	end
})

local Tab = Window:MakeTab({
	Name = "Ro-ghoul",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Ritual Hub - Click Login",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cracklua/cracks/m/ritual"))()
-- just click login, dont change the text
	end
})

Tab:AddButton({
	Name = "Script Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CurseOfDarkness/CurseHubRoGhoul/main/Curse%20Hub%20Ro%20Ghoul"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Jujutsu Piece",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Auto Farm And More",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/OhhMyGehlee/Mob/main/JJP"))()
	end
})

Tab:AddButton({
	Name = "Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/AnchorHub/Script/main/Universal"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Bronx PVP",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Infinite Money",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/FREE-DRACO-BRONX-PVP-Inf-money-18361",true))()
	end
})

Tab:AddButton({
	Name = "Steal Other Peoples Money",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cnzins1/scripts/main/steal%20others%20money%20and%20set%20negative"))()
	end
})

local Tab = Window:MakeTab({
	Name = "Monkey Raft",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Auto Collect Golden Bananas",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/TIGER-SHARK-monkey-raft-Auto-Collect-Golden-Bananas-15432",true))()
	end
})

Tab:AddButton({
	Name = "Auto Collect Golden Bananas",
	Callback = function()
loadstring(game:HttpGet("https://rawscripts.net/raw/TIGER-SHARK-monkey-raft-Collect-Items-15424",true))()
	end
})

local Tab = Window:MakeTab({
	Name = "Blank Tab",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Tab = Window:MakeTab({
	Name = "Blank Tab",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Tab = Window:MakeTab({
	Name = "Blank Tab",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


-- Orion Library Handler
OrionLib:Init()
