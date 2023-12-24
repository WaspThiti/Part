--do
	--local NM = game:GetService("Workspace").Noclip
	--if NM then
		--NM:Destroy()
	--end
--end
local Noclip = Instance.new("Part",Workspace)
	 Noclip.Name = "Noclip"
	 Noclip.CanCollide = true
	 Noclip.Anchored = true
	 Noclip.Transparency = 0.5
	 Noclip.Size = Vector3.new(30,-3,30)
	 Noclip.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,6,0)
