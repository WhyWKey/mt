repeat wait() until game:IsLoaded()
if not IrisNotificationMrJack then
	loadstring(game:HttpGet"https://raw.githubusercontent.com/thedragonslayer2/hey/main/Misc./iris%20notification%20function")()
elseif IrisNotificationUserMrJack then IrisNotificationUserMrJack.ClearAllNotifications() end
IrisNotificationMrJack(1, "Key System", "Executed Please Wait", 9e9)
local KeySystem = loadstring(game:HttpGet"https://raw.githubusercontent.com/thedragonslayer2/hey/main/KeySystem")()
KeySystem"https://raw.githubusercontent.com/thedragonslayer2/hey/main/Detect%20Game"
return true
