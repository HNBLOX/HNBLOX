local args = {
    [1] = {
        [1] = 100,
        [2] = 180
    }
}

game:GetService("ReplicatedStorage").Events.PlaytimeRedeem:FireServer(unpack(args))
