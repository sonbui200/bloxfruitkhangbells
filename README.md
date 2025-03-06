local Games = loadstring(game:HttpGet("https://raw.githubusercontent.com/sonbui200/bloxfruitkhangbells/refs/heads/main/khangbells"))()

for PlaceID, Execute in pairs(Games) do
    if PlaceID == game.PlaceId then
        loadstring(game:HttpGet(Execute))()
    end
end
