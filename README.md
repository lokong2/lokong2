script_key = "" -- premium only, u can leave it blank if ur not
getgenv().Shutdown = false
getgenv().Configs = {
    ["Team"] = "Marines",
    ["Gun Farm"] = false,
    ["FPS Boost"] = {
        ["Enable"] = false,
        ["FPS Cap"] = 30,
    },
    ["Farm Boss Drops"] = {
        ["Enable"] = false,
        ["When x2 Exp Expired"] = false
    },
    ["Auto Evo Race"] = true,
    ["Awaken Fruit"] = true,
    ["Rainbow Haki"] = true,
    ["Hop Player Near"] = true,
    ["Skull Guitar"] = true,
    ["Find Fruit"] = false,
    ["Cursed Dual Katana"] = true,
    ["Switch Melee"] = true,
    ["Eat Fruit"] = "",
    ["Snipe Fruit"] = "",
    ["Lock Fragment"] = 0,
    ["Buy Stuffs"] = true
}
repeat task.wait() pcall(function() loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/refs/heads/main/kaitun.lua"))() end) until getgenv().Check_Execute
