do
	local NM = game:GetService("Workspace").Noclip
	if NM then
		NM:Destroy()
	end
end
local Noclip = Instance.new("Part",Workspace)
	 Noclip.Name = "Noclip"
