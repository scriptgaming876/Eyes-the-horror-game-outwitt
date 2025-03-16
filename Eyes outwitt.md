local Rayfield = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Rayfield/main/source'))()
 
 local Window = Rayfield:CreateWindow({
 	Name = "Outwitt ",
 	LoadingTitle = "Rayfield Interface Suite",
 	LoadingSubtitle = "by Outwitt",
 	ConfigurationSaving = {
 		Enabled = true,
 		FolderName = "Rayfield Interface Suite",
 		FileName = "Big Hub"
 	},
 	KeySystem = false, -- Set this to true to use their key system
 	KeySettings = {
 		Title = "Outwitt Hub",
 		Subtitle = "Key System",
 		Note = "Tokens In Enter",
 		SaveKey = true,
 		Key = "78"
 	}
 })
 
 Rayfield:Notify("Welcome", "Welcome To Outwitt", 4483362458) -- Notfication -- Title, Content, Image
 
 local Tab = Window:CreateTab("Player", 4483362458) -- Title, Image
 
 local Section = Tab:CreateSection("Local Player")
 
 local Toggle = Tab:CreateToggle({
 	Name = "GOD MODE",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Toggle = Tab:CreateToggle({
 	Name = "FLY",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Toggle = Tab:CreateToggle({
 	Name = "NOCLIP",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Toggle = Tab:CreateToggle({
 	Name = "INF WIN",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Toggle = Tab:CreateToggle({
 	Name = "UNLIMITED WIN",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Toggle = Tab:CreateToggle({
 	Name = "FULLBRIGHT",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Tab = Window:CreateTab("VISUAL", 4483362458) -- Title, Image
 
 local Section = Tab:CreateSection("Section Example")
 
 local Toggle = Tab:CreateToggle({
 	Name = "ESP KRASUE",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
 
 local Toggle = Tab:CreateToggle({
 	Name = "ESP BAGS",
 	CurrentValue = false,
 	Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
 	Callback = function(Value)
 		-- The function that takes place when the toggle is pressed
     		-- The variable (Value) is a boolean on whether the toggle is true or false
 	end,
 })
