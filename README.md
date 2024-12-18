local a=Instance.new("ScreenGui")local b=Instance.new("Frame")local c=Instance.new("UIListLayout")a.Parent=game:FindFirstChild('CoreGui')or game.Players.LocalPlayer:WaitForChild("PlayerGui")a.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;a.IgnoreGuiInset=true;a.ResetOnSpawn=false;b.Parent=a;b.Active=true;b.AnchorPoint=Vector2.new(0.5,0.5)b.BackgroundColor3=Color3.fromRGB(255,255,255)b.BackgroundTransparency=1.000;b.BorderColor3=Color3.fromRGB(0,0,0)b.BorderSizePixel=0;b.Position=UDim2.new(0.5,0,0.5,0)b.Size=UDim2.new(0.0500000007,500,0,225)c.Parent=b;c.FillDirection=Enum.FillDirection.Horizontal;c.HorizontalAlignment=Enum.HorizontalAlignment.Center;c.SortOrder=Enum.SortOrder.LayoutOrder;c.VerticalAlignment=Enum.VerticalAlignment.Center;local d=function()local e=Instance.new("TextLabel")local f=Instance.new("UIGradient")e.Parent=b;e.BackgroundColor3=Color3.fromRGB(255,255,255)e.BackgroundTransparency=1.000;e.BorderColor3=Color3.fromRGB(0,0,0)e.BorderSizePixel=0;e.Size=UDim2.new(0,0,0,0)e.Font=Enum.Font.GothamBold;e.Text="N"e.TextColor3=Color3.fromRGB(255,255,255)e.TextSize=0;e.TextStrokeTransparency=1;e.TextWrapped=true;e.TextTransparency=1;f.Color=ColorSequence.new{ColorSequenceKeypoint.new(0.00,Color3.fromRGB(255,255,255)),ColorSequenceKeypoint.new(1.00,Color3.fromRGB(111,111,111))}f.Rotation=48;f.Parent=e;return e end;local g={'N','E','U','R','O','N'}for h,i in ipairs(g)do task.wait(0.1)local j=d()j.Text=i;game:GetService('TweenService'):Create(j,TweenInfo.new(1,Enum.EasingStyle.Back),{Size=UDim2.new(0.125,0,1,0),TextStrokeTransparency=0.6,TextTransparency=0,TextSize=90}):Play()end;task.wait(1.25)local k={'X'}for h,i in ipairs(k)do task.wait(0.1)local j=d()j.Text=i;j.TextColor3=Color3.new(1,0.635294,0)game:GetService('TweenService'):Create(j,TweenInfo.new(1.5,Enum.EasingStyle.Back),{Size=UDim2.new(0.09,0,1,0),TextStrokeTransparency=0.6,TextTransparency=0,TextSize=65}):Play()end;task.wait(3)for h,i in ipairs(b:GetChildren())do task.wait(0.1)if i:IsA('TextLabel')then game:GetService('TweenService'):Create(i,TweenInfo.new(1.5,Enum.EasingStyle.Back,Enum.EasingDirection.In),{Size=UDim2.new(0,0,0,0),TextStrokeTransparency=1,TextTransparency=1,TextSize=0}):Play()end end;task.wait(1.7)a:Destroy()
if game:GetService("CoreGui"):WaitForChild("RobloxGui"):FindFirstChild("Dashboard") then
	game:GetService("CoreGui"):WaitForChild("RobloxGui"):FindFirstChild("Dashboard"):Destroy(true);
end;

if game:GetService("CoreGui"):WaitForChild("RobloxGui"):FindFirstChild("Dashboard") then
	game:GetService("CoreGui"):WaitForChild("RobloxGui"):FindFirstChild("Dashboard"):Destroy(true);
end;

local G2L = {};

-- StarterGui.Neu.Dashboard
G2L["1"] = Instance.new("ScreenGui", game:GetService("CoreGui"):WaitForChild("RobloxGui"));
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["Name"] = [[Dashboard]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.Neu.Dashboard.M
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["Size"] = UDim2.new(0.5, 0, 0.3, 0);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[M]];


-- StarterGui.Neu.Dashboard.M.UICorner
G2L["3"] = Instance.new("UICorner", G2L["2"]);



-- StarterGui.Neu.Dashboard.M.UIGradient
G2L["4"] = Instance.new("UIGradient", G2L["2"]);
G2L["4"]["Rotation"] = -86;
G2L["4"]["Offset"] = Vector2.new(2, 0.12);
G2L["4"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(0.492, Color3.fromRGB(0, 5, 122)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.Neu.Dashboard.M.DropShadowHolder
G2L["5"] = Instance.new("Frame", G2L["2"]);
G2L["5"]["ZIndex"] = 0;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["5"]["Name"] = [[DropShadowHolder]];
G2L["5"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.DropShadowHolder.DropShadow
G2L["6"] = Instance.new("ImageLabel", G2L["5"]);
G2L["6"]["ZIndex"] = 0;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["6"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["6"]["ImageTransparency"] = 0.5;
G2L["6"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6"]["Image"] = [[rbxassetid://6015897843]];
G2L["6"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Name"] = [[DropShadow]];
G2L["6"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame
G2L["7"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["7"]["Active"] = true;
G2L["7"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["CanvasSize"] = UDim2.new(0, 0, 0.5, 0);
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["ScrollBarImageTransparency"] = 1;
G2L["7"]["BorderMode"] = Enum.BorderMode.Inset;
G2L["7"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["7"]["Size"] = UDim2.new(0.9, 0, 0.3, 0);
G2L["7"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Position"] = UDim2.new(0.5, 0, 0.67822, 0);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.UIListLayout
G2L["8"] = Instance.new("UIListLayout", G2L["7"]);
G2L["8"]["HorizontalFlex"] = Enum.UIFlexAlignment.SpaceEvenly;
G2L["8"]["Wraps"] = true;
G2L["8"]["VerticalFlex"] = Enum.UIFlexAlignment.SpaceAround;
G2L["8"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["8"]["ItemLineAlignment"] = Enum.ItemLineAlignment.Center;
G2L["8"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable
G2L["9"] = Instance.new("Frame", G2L["7"]);
G2L["9"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["9"]["ZIndex"] = 0;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(86, 86, 128);
G2L["9"]["Size"] = UDim2.new(0.3, 0, 0.15, 0);
G2L["9"]["Position"] = UDim2.new(0.35, 0, 0.06099, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["Name"] = [[Stackable]];
G2L["9"]["BackgroundTransparency"] = 0.75;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);



-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable.UIStroke
G2L["b"] = Instance.new("UIStroke", G2L["9"]);
G2L["b"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable.TextButton
G2L["c"] = Instance.new("TextButton", G2L["9"]);
G2L["c"]["TextWrapped"] = true;
G2L["c"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["TextScaled"] = true;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c"]["ZIndex"] = 2;
G2L["c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["c"]["Size"] = UDim2.new(1, 0, 0.2, 0);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[Stackable]];
G2L["c"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable.DropShadowHolder
G2L["d"] = Instance.new("Frame", G2L["9"]);
G2L["d"]["ZIndex"] = 0;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["d"]["Name"] = [[DropShadowHolder]];
G2L["d"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable.DropShadowHolder.DropShadow
G2L["e"] = Instance.new("ImageLabel", G2L["d"]);
G2L["e"]["ZIndex"] = 0;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["e"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["e"]["ImageTransparency"] = 0.5;
G2L["e"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["e"]["Image"] = [[rbxassetid://6014261993]];
G2L["e"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["Name"] = [[DropShadow]];
G2L["e"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Stackable.TextLabel
G2L["f"] = Instance.new("TextLabel", G2L["9"]);
G2L["f"]["TextWrapped"] = true;
G2L["f"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextScaled"] = true;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["TextSize"] = 14;
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["f"]["Size"] = UDim2.new(0.8, 0, 0.17, 0);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[Check for stack error if the script support stack functions]];
G2L["f"]["Position"] = UDim2.new(0.5, 0, 0.7, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request
G2L["10"] = Instance.new("Frame", G2L["7"]);
G2L["10"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["10"]["ZIndex"] = 0;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(86, 86, 128);
G2L["10"]["Size"] = UDim2.new(0.3, 0, 0.15, 0);
G2L["10"]["Position"] = UDim2.new(0.35, 0, 0.06099, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["Name"] = [[Request]];
G2L["10"]["BackgroundTransparency"] = 0.75;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);



-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request.UIStroke
G2L["12"] = Instance.new("UIStroke", G2L["10"]);
G2L["12"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request.TextButton
G2L["13"] = Instance.new("TextButton", G2L["10"]);
G2L["13"]["TextWrapped"] = true;
G2L["13"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["TextScaled"] = true;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["13"]["ZIndex"] = 2;
G2L["13"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["13"]["Size"] = UDim2.new(1, 0, 0.2, 0);
G2L["13"]["BackgroundTransparency"] = 1;
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Text"] = [[Request]];
G2L["13"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request.DropShadowHolder
G2L["14"] = Instance.new("Frame", G2L["10"]);
G2L["14"]["ZIndex"] = 0;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["14"]["Name"] = [[DropShadowHolder]];
G2L["14"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request.DropShadowHolder.DropShadow
G2L["15"] = Instance.new("ImageLabel", G2L["14"]);
G2L["15"]["ZIndex"] = 0;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["15"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["15"]["ImageTransparency"] = 0.5;
G2L["15"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["15"]["Image"] = [[rbxassetid://6014261993]];
G2L["15"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["15"]["BackgroundTransparency"] = 1;
G2L["15"]["Name"] = [[DropShadow]];
G2L["15"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Request.TextLabel
G2L["16"] = Instance.new("TextLabel", G2L["10"]);
G2L["16"]["TextWrapped"] = true;
G2L["16"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextScaled"] = true;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["TextSize"] = 14;
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["BackgroundTransparency"] = 1;
G2L["16"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["16"]["Size"] = UDim2.new(0.8, 0, 0.17, 0);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[Output of function you requested]];
G2L["16"]["Position"] = UDim2.new(0.5, 0, 0.7, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console
G2L["17"] = Instance.new("Frame", G2L["7"]);
G2L["17"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["17"]["ZIndex"] = 0;
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(86, 86, 128);
G2L["17"]["Size"] = UDim2.new(0.3, 0, 0.15, 0);
G2L["17"]["Position"] = UDim2.new(0.35, 0, 0.06099, 0);
G2L["17"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["Name"] = [[Console]];
G2L["17"]["BackgroundTransparency"] = 0.75;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console.UICorner
G2L["18"] = Instance.new("UICorner", G2L["17"]);



-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console.UIStroke
G2L["19"] = Instance.new("UIStroke", G2L["17"]);
G2L["19"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console.TextButton
G2L["1a"] = Instance.new("TextButton", G2L["17"]);
G2L["1a"]["TextWrapped"] = true;
G2L["1a"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 14;
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["1a"]["TextScaled"] = true;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1a"]["ZIndex"] = 2;
G2L["1a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1a"]["Size"] = UDim2.new(1, 0, 0.2, 0);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[Console]];
G2L["1a"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console.DropShadowHolder
G2L["1b"] = Instance.new("Frame", G2L["17"]);
G2L["1b"]["ZIndex"] = 0;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["1b"]["Name"] = [[DropShadowHolder]];
G2L["1b"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console.DropShadowHolder.DropShadow
G2L["1c"] = Instance.new("ImageLabel", G2L["1b"]);
G2L["1c"]["ZIndex"] = 0;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["1c"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["1c"]["ImageTransparency"] = 0.5;
G2L["1c"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1c"]["Image"] = [[rbxassetid://6014261993]];
G2L["1c"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Name"] = [[DropShadow]];
G2L["1c"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Console.TextLabel
G2L["1d"] = Instance.new("TextLabel", G2L["17"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundTransparency"] = 1;
G2L["1d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1d"]["Size"] = UDim2.new(0.8, 0, 0.17, 0);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[You can copy errors for reporting bug in here]];
G2L["1d"]["Position"] = UDim2.new(0.5, 0, 0.7, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands
G2L["1e"] = Instance.new("Frame", G2L["7"]);
G2L["1e"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["1e"]["ZIndex"] = 0;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(86, 86, 128);
G2L["1e"]["Size"] = UDim2.new(0.3, 0, 0.15, 0);
G2L["1e"]["Position"] = UDim2.new(0.35, 0, 0.06099, 0);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["Name"] = [[Commands]];
G2L["1e"]["BackgroundTransparency"] = 0.75;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);



-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands.UIStroke
G2L["20"] = Instance.new("UIStroke", G2L["1e"]);
G2L["20"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands.TextButton
G2L["21"] = Instance.new("TextButton", G2L["1e"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextSize"] = 14;
G2L["21"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["21"]["TextScaled"] = true;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["ZIndex"] = 2;
G2L["21"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["21"]["Size"] = UDim2.new(1, 0, 0.2, 0);
G2L["21"]["BackgroundTransparency"] = 1;
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[Commands]];
G2L["21"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands.DropShadowHolder
G2L["22"] = Instance.new("Frame", G2L["1e"]);
G2L["22"]["ZIndex"] = 0;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["22"]["Name"] = [[DropShadowHolder]];
G2L["22"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands.DropShadowHolder.DropShadow
G2L["23"] = Instance.new("ImageLabel", G2L["22"]);
G2L["23"]["ZIndex"] = 0;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["23"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["23"]["ImageTransparency"] = 0.5;
G2L["23"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["23"]["Image"] = [[rbxassetid://6014261993]];
G2L["23"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["23"]["BackgroundTransparency"] = 1;
G2L["23"]["Name"] = [[DropShadow]];
G2L["23"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Commands.TextLabel
G2L["24"] = Instance.new("TextLabel", G2L["1e"]);
G2L["24"]["TextWrapped"] = true;
G2L["24"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["TextScaled"] = true;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["TextSize"] = 14;
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["24"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["24"]["BackgroundTransparency"] = 1;
G2L["24"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["24"]["Size"] = UDim2.new(0.8, 0, 0.17, 0);
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Text"] = [[You can check for chat commands]];
G2L["24"]["Position"] = UDim2.new(0.5, 0, 0.7, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links
G2L["25"] = Instance.new("Frame", G2L["7"]);
G2L["25"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["25"]["ZIndex"] = 0;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(86, 86, 128);
G2L["25"]["Size"] = UDim2.new(0.3, 0, 0.15, 0);
G2L["25"]["Position"] = UDim2.new(0.35, 0, 0.06099, 0);
G2L["25"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["Name"] = [[Client Links]];
G2L["25"]["BackgroundTransparency"] = 0.75;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links.UICorner
G2L["26"] = Instance.new("UICorner", G2L["25"]);



-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links.UIStroke
G2L["27"] = Instance.new("UIStroke", G2L["25"]);
G2L["27"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links.TextButton
G2L["28"] = Instance.new("TextButton", G2L["25"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["28"]["TextScaled"] = true;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["ZIndex"] = 2;
G2L["28"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["28"]["Size"] = UDim2.new(1, 0, 0.2, 0);
G2L["28"]["BackgroundTransparency"] = 1;
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Client Links]];
G2L["28"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links.DropShadowHolder
G2L["29"] = Instance.new("Frame", G2L["25"]);
G2L["29"]["ZIndex"] = 0;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["29"]["Name"] = [[DropShadowHolder]];
G2L["29"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links.DropShadowHolder.DropShadow
G2L["2a"] = Instance.new("ImageLabel", G2L["29"]);
G2L["2a"]["ZIndex"] = 0;
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["2a"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["2a"]["ImageTransparency"] = 0.5;
G2L["2a"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2a"]["Image"] = [[rbxassetid://6014261993]];
G2L["2a"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["2a"]["BackgroundTransparency"] = 1;
G2L["2a"]["Name"] = [[DropShadow]];
G2L["2a"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Client Links.TextLabel
G2L["2b"] = Instance.new("TextLabel", G2L["25"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["BackgroundTransparency"] = 1;
G2L["2b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2b"]["Size"] = UDim2.new(0.8, 0, 0.17, 0);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[Client Links is In development]];
G2L["2b"]["Position"] = UDim2.new(0.5, 0, 0.7, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun
G2L["2c"] = Instance.new("Frame", G2L["7"]);
G2L["2c"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["2c"]["ZIndex"] = 0;
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(86, 86, 128);
G2L["2c"]["Size"] = UDim2.new(0.3, 0, 0.15, 0);
G2L["2c"]["Position"] = UDim2.new(0.35, 0, 0.06099, 0);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["Name"] = [[Fun]];
G2L["2c"]["BackgroundTransparency"] = 0.75;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun.UICorner
G2L["2d"] = Instance.new("UICorner", G2L["2c"]);



-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun.UIStroke
G2L["2e"] = Instance.new("UIStroke", G2L["2c"]);
G2L["2e"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun.TextButton
G2L["2f"] = Instance.new("TextButton", G2L["2c"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["ZIndex"] = 2;
G2L["2f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2f"]["Size"] = UDim2.new(1, 0, 0.2, 0);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[Fun]];
G2L["2f"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun.DropShadowHolder
G2L["30"] = Instance.new("Frame", G2L["2c"]);
G2L["30"]["ZIndex"] = 0;
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["30"]["Name"] = [[DropShadowHolder]];
G2L["30"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun.DropShadowHolder.DropShadow
G2L["31"] = Instance.new("ImageLabel", G2L["30"]);
G2L["31"]["ZIndex"] = 0;
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["31"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["31"]["ImageTransparency"] = 0.5;
G2L["31"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["31"]["Image"] = [[rbxassetid://6014261993]];
G2L["31"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["31"]["BackgroundTransparency"] = 1;
G2L["31"]["Name"] = [[DropShadow]];
G2L["31"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.ScrollingFrame.Fun.TextLabel
G2L["32"] = Instance.new("TextLabel", G2L["2c"]);
G2L["32"]["TextWrapped"] = true;
G2L["32"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["32"]["BorderSizePixel"] = 0;
G2L["32"]["TextScaled"] = true;
G2L["32"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["TextSize"] = 14;
G2L["32"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["32"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["32"]["BackgroundTransparency"] = 1;
G2L["32"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["32"]["Size"] = UDim2.new(0.8, 0, 0.17, 0);
G2L["32"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["32"]["Text"] = [[to be honest.. I dont know]];
G2L["32"]["Position"] = UDim2.new(0.5, 0, 0.7, 0);


-- StarterGui.Neu.Dashboard.M.TopBarPlus
G2L["33"] = Instance.new("Frame", G2L["2"]);
G2L["33"]["SizeConstraint"] = Enum.SizeConstraint.RelativeYY;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["33"]["Size"] = UDim2.new(0.4, 0, 0.05, 0);
G2L["33"]["Position"] = UDim2.new(0.19211, 0, 0.09148, 0);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Name"] = [[TopBarPlus]];
G2L["33"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame
G2L["34"] = Instance.new("Frame", G2L["33"]);
G2L["34"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["34"]["BorderSizePixel"] = 0;
G2L["34"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["34"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["34"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["34"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame.TextButton
G2L["35"] = Instance.new("TextButton", G2L["34"]);
G2L["35"]["TextWrapped"] = true;
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["TextSize"] = 14;
G2L["35"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["TextScaled"] = true;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["35"]["BackgroundTransparency"] = 1;
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Text"] = [[B]];


-- StarterGui.Neu.Dashboard.M.TopBarPlus.UIListLayout
G2L["36"] = Instance.new("UIListLayout", G2L["33"]);
G2L["36"]["Padding"] = UDim.new(0.05, 0);
G2L["36"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["36"]["FillDirection"] = Enum.FillDirection.Horizontal;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame
G2L["37"] = Instance.new("Frame", G2L["33"]);
G2L["37"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["37"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["37"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame.TextButton
G2L["38"] = Instance.new("TextButton", G2L["37"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["TextScaled"] = true;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["38"]["BackgroundTransparency"] = 1;
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[S]];


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame
G2L["39"] = Instance.new("Frame", G2L["33"]);
G2L["39"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["39"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["39"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame.TextButton
G2L["3a"] = Instance.new("TextButton", G2L["39"]);
G2L["3a"]["TextWrapped"] = true;
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextSize"] = 14;
G2L["3a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["TextScaled"] = true;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3a"]["BackgroundTransparency"] = 1;
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[D]];


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame
G2L["3b"] = Instance.new("Frame", G2L["33"]);
G2L["3b"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["3b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3b"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame.TextButton
G2L["3c"] = Instance.new("TextButton", G2L["3b"]);
G2L["3c"]["TextWrapped"] = true;
G2L["3c"]["BorderSizePixel"] = 0;
G2L["3c"]["TextSize"] = 14;
G2L["3c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["TextScaled"] = true;
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3c"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3c"]["BackgroundTransparency"] = 1;
G2L["3c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["Text"] = [[Y]];


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame
G2L["3d"] = Instance.new("Frame", G2L["33"]);
G2L["3d"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.TopBarPlus.Frame.TextButton
G2L["3e"] = Instance.new("TextButton", G2L["3d"]);
G2L["3e"]["TextWrapped"] = true;
G2L["3e"]["BorderSizePixel"] = 0;
G2L["3e"]["TextSize"] = 14;
G2L["3e"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
G2L["3e"]["TextScaled"] = true;
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["3e"]["BackgroundTransparency"] = 1;
G2L["3e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["Text"] = [[?]];
G2L["3e"]["Position"] = UDim2.new(28.5873, 0, 0, 0);


-- StarterGui.Neu.Dashboard.M.Each
G2L["3f"] = Instance.new("Folder", G2L["2"]);
G2L["3f"]["Name"] = [[Each]];


-- StarterGui.Neu.Dashboard.M.Each.Stackable
G2L["40"] = Instance.new("Frame", G2L["3f"]);
G2L["40"]["Visible"] = false;
G2L["40"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["40"]["ZIndex"] = 4;
G2L["40"]["BorderSizePixel"] = 0;
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["40"]["Size"] = UDim2.new(0.8, 0, 0.5, 0);
G2L["40"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["Name"] = [[Stackable]];


-- StarterGui.Neu.Dashboard.M.Each.Stackable.
G2L["41"] = Instance.new("UIGradient", G2L["40"]);
G2L["41"]["Rotation"] = -93;
G2L["41"]["Name"] = [[]];
G2L["41"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 51))};


-- StarterGui.Neu.Dashboard.M.Each.Stackable.
G2L["42"] = Instance.new("Frame", G2L["40"]);
G2L["42"]["ZIndex"] = 0;
G2L["42"]["BorderSizePixel"] = 0;
G2L["42"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["42"]["Name"] = [[]];
G2L["42"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Stackable..
G2L["43"] = Instance.new("ImageLabel", G2L["42"]);
G2L["43"]["ZIndex"] = 0;
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["43"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["43"]["ImageTransparency"] = 0.5;
G2L["43"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["43"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["43"]["Image"] = [[rbxassetid://6015897843]];
G2L["43"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["43"]["BackgroundTransparency"] = 1;
G2L["43"]["Name"] = [[]];
G2L["43"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.Each.Stackable.
G2L["44"] = Instance.new("UICorner", G2L["40"]);
G2L["44"]["Name"] = [[]];


-- StarterGui.Neu.Dashboard.M.Each.Stackable.
G2L["45"] = Instance.new("UIStroke", G2L["40"]);
G2L["45"]["Name"] = [[]];
G2L["45"]["Color"] = Color3.fromRGB(0, 111, 255);


-- StarterGui.Neu.Dashboard.M.Each.Stackable.
G2L["46"] = Instance.new("TextLabel", G2L["40"]);
G2L["46"]["TextWrapped"] = true;
G2L["46"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["TextScaled"] = true;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["TextSize"] = 14;
G2L["46"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["46"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["BackgroundTransparency"] = 1;
G2L["46"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["46"]["Size"] = UDim2.new(0.4, 0, 0.1, 0);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Text"] = [[Stackable]];
G2L["46"]["Name"] = [[]];
G2L["46"]["Position"] = UDim2.new(0.5, 0, 0.1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Stackable.List
G2L["47"] = Instance.new("ScrollingFrame", G2L["40"]);
G2L["47"]["Active"] = true;
G2L["47"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["47"]["BorderSizePixel"] = 0;
G2L["47"]["CanvasSize"] = UDim2.new(0, 0, 1, 0);
G2L["47"]["ElasticBehavior"] = Enum.ElasticBehavior.Always;
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["47"]["ClipsDescendants"] = true;
G2L["47"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["47"]["Size"] = UDim2.new(0.9, 0, 0.4, 0);
G2L["47"]["Position"] = UDim2.new(0.5, 0, 0.6, 0);
G2L["47"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["47"]["ScrollBarThickness"] = 5;
G2L["47"]["Name"] = [[List]];
G2L["47"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Stackable.List.
G2L["48"] = Instance.new("UIListLayout", G2L["47"]);
G2L["48"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["48"]["Padding"] = UDim.new(0.1, 0);
G2L["48"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["48"]["Name"] = [[]];


-- StarterGui.Neu.Dashboard.M.Each.Stackable.List.NPF
G2L["49"] = Instance.new("Frame", G2L["47"]);
G2L["49"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["49"]["Size"] = UDim2.new(0.9, 0, 0.1, 0);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Name"] = [[NPF]];
G2L["49"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Stackable.List.NPF.
G2L["4a"] = Instance.new("UICorner", G2L["49"]);
G2L["4a"]["Name"] = [[]];
G2L["4a"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Stackable.List.NPF.
G2L["4b"] = Instance.new("UIStroke", G2L["49"]);
G2L["4b"]["Name"] = [[]];
G2L["4b"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.Each.Stackable.List.NPF.T
G2L["4c"] = Instance.new("TextLabel", G2L["49"]);
G2L["4c"]["TextWrapped"] = true;
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["TextScaled"] = true;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["TextSize"] = 14;
G2L["4c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.ExtraLight, Enum.FontStyle.Normal);
G2L["4c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["BackgroundTransparency"] = 1;
G2L["4c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4c"]["Size"] = UDim2.new(0.8, 0, 1, 0);
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["Text"] = [[No problem found]];
G2L["4c"]["Name"] = [[T]];
G2L["4c"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.Each.Stackable.TextButton
G2L["4d"] = Instance.new("TextButton", G2L["40"]);
G2L["4d"]["TextWrapped"] = true;
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextSize"] = 14;
G2L["4d"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["4d"]["TextScaled"] = true;
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4d"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["4d"]["BackgroundTransparency"] = 1;
G2L["4d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Text"] = [[Close]];
G2L["4d"]["Position"] = UDim2.new(0.4985, 0, 0.94877, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request
G2L["4e"] = Instance.new("Frame", G2L["3f"]);
G2L["4e"]["Visible"] = false;
G2L["4e"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["4e"]["ZIndex"] = 4;
G2L["4e"]["BorderSizePixel"] = 0;
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["4e"]["Size"] = UDim2.new(0.8, 0, 0.5, 0);
G2L["4e"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["Name"] = [[Request]];


-- StarterGui.Neu.Dashboard.M.Each.Request.
G2L["4f"] = Instance.new("UIGradient", G2L["4e"]);
G2L["4f"]["Rotation"] = -93;
G2L["4f"]["Name"] = [[]];
G2L["4f"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 51))};


-- StarterGui.Neu.Dashboard.M.Each.Request.
G2L["50"] = Instance.new("Frame", G2L["4e"]);
G2L["50"]["ZIndex"] = 0;
G2L["50"]["BorderSizePixel"] = 0;
G2L["50"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["50"]["Name"] = [[]];
G2L["50"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Request..
G2L["51"] = Instance.new("ImageLabel", G2L["50"]);
G2L["51"]["ZIndex"] = 0;
G2L["51"]["BorderSizePixel"] = 0;
G2L["51"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["51"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["51"]["ImageTransparency"] = 0.5;
G2L["51"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["51"]["Image"] = [[rbxassetid://6015897843]];
G2L["51"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["51"]["BackgroundTransparency"] = 1;
G2L["51"]["Name"] = [[]];
G2L["51"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request.
G2L["52"] = Instance.new("UICorner", G2L["4e"]);
G2L["52"]["Name"] = [[]];


-- StarterGui.Neu.Dashboard.M.Each.Request.
G2L["53"] = Instance.new("UIStroke", G2L["4e"]);
G2L["53"]["Name"] = [[]];
G2L["53"]["Color"] = Color3.fromRGB(0, 111, 255);


-- StarterGui.Neu.Dashboard.M.Each.Request.
G2L["54"] = Instance.new("TextLabel", G2L["4e"]);
G2L["54"]["TextWrapped"] = true;
G2L["54"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["TextScaled"] = true;
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["TextSize"] = 14;
G2L["54"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["54"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["BackgroundTransparency"] = 1;
G2L["54"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["54"]["Size"] = UDim2.new(0.4, 0, 0.1, 0);
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Text"] = [[Request Output]];
G2L["54"]["Name"] = [[]];
G2L["54"]["Position"] = UDim2.new(0.5, 0, 0.1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request.Out
G2L["55"] = Instance.new("Frame", G2L["4e"]);
G2L["55"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["55"]["ClipsDescendants"] = true;
G2L["55"]["Size"] = UDim2.new(0.9, 0, 0.4, 0);
G2L["55"]["Position"] = UDim2.new(0.5, 0, 0.6, 0);
G2L["55"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Name"] = [[Out]];
G2L["55"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Request.Out.TextBox
G2L["56"] = Instance.new("TextBox", G2L["55"]);
G2L["56"]["CursorPosition"] = -1;
G2L["56"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["BorderSizePixel"] = 0;
G2L["56"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["56"]["TextSize"] = 14;
G2L["56"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["56"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["56"]["PlaceholderText"] = [[Nothing has been request yet]];
G2L["56"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["56"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["Text"] = [[]];
G2L["56"]["BackgroundTransparency"] = 0.9;


-- StarterGui.Neu.Dashboard.M.Each.Request.Out.TextBox.UICorner
G2L["57"] = Instance.new("UICorner", G2L["56"]);



-- StarterGui.Neu.Dashboard.M.Each.Request.Close
G2L["58"] = Instance.new("TextButton", G2L["4e"]);
G2L["58"]["TextWrapped"] = true;
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["TextSize"] = 14;
G2L["58"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["58"]["TextScaled"] = true;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["58"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["58"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["58"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["58"]["BackgroundTransparency"] = 1;
G2L["58"]["Name"] = [[Close]];
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Text"] = [[Close]];
G2L["58"]["Position"] = UDim2.new(0.4985, 0, 0.94877, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request.Copy
G2L["59"] = Instance.new("TextButton", G2L["4e"]);
G2L["59"]["TextWrapped"] = true;
G2L["59"]["BorderSizePixel"] = 0;
G2L["59"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["59"]["TextSize"] = 14;
G2L["59"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["TextScaled"] = true;
G2L["59"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["59"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["59"]["Size"] = UDim2.new(0.1, 0, 0.03739, 0);
G2L["59"]["BackgroundTransparency"] = 1;
G2L["59"]["Name"] = [[Copy]];
G2L["59"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["59"]["Text"] = [[Copy]];
G2L["59"]["Position"] = UDim2.new(0.10481, 0, 0.21949, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request.workspace
G2L["5a"] = Instance.new("TextButton", G2L["4e"]);
G2L["5a"]["TextWrapped"] = true;
G2L["5a"]["BorderSizePixel"] = 0;
G2L["5a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5a"]["TextSize"] = 14;
G2L["5a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["TextScaled"] = true;
G2L["5a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5a"]["Size"] = UDim2.new(0.1, 0, 0.03739, 0);
G2L["5a"]["BackgroundTransparency"] = 1;
G2L["5a"]["Name"] = [[workspace]];
G2L["5a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5a"]["Text"] = [[workspace]];
G2L["5a"]["Position"] = UDim2.new(0.19465, 0, 0.21949, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request.print
G2L["5b"] = Instance.new("TextButton", G2L["4e"]);
G2L["5b"]["TextWrapped"] = true;
G2L["5b"]["BorderSizePixel"] = 0;
G2L["5b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5b"]["TextSize"] = 14;
G2L["5b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5b"]["TextScaled"] = true;
G2L["5b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5b"]["Size"] = UDim2.new(0.1, 0, 0.03739, 0);
G2L["5b"]["BackgroundTransparency"] = 1;
G2L["5b"]["Name"] = [[print]];
G2L["5b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5b"]["Text"] = [[print]];
G2L["5b"]["Position"] = UDim2.new(0.3139, 0, 0.21949, 0);


-- StarterGui.Neu.Dashboard.M.Each.Request.warn
G2L["5c"] = Instance.new("TextButton", G2L["4e"]);
G2L["5c"]["TextWrapped"] = true;
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5c"]["TextSize"] = 14;
G2L["5c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["TextScaled"] = true;
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5c"]["Size"] = UDim2.new(0.1, 0, 0.03739, 0);
G2L["5c"]["BackgroundTransparency"] = 1;
G2L["5c"]["Name"] = [[warn]];
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["Text"] = [[Warn]];
G2L["5c"]["Position"] = UDim2.new(0.38088, 0, 0.21949, 0);


-- StarterGui.Neu.Dashboard.M.Each.Console
G2L["5d"] = Instance.new("Frame", G2L["3f"]);
G2L["5d"]["Visible"] = false;
G2L["5d"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["5d"]["ZIndex"] = 4;
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5d"]["Size"] = UDim2.new(0.8, 0, 0.5, 0);
G2L["5d"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["Name"] = [[Console]];


-- StarterGui.Neu.Dashboard.M.Each.Console.
G2L["5e"] = Instance.new("UIGradient", G2L["5d"]);
G2L["5e"]["Rotation"] = -93;
G2L["5e"]["Name"] = [[]];
G2L["5e"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 51))};


-- StarterGui.Neu.Dashboard.M.Each.Console.
G2L["5f"] = Instance.new("Frame", G2L["5d"]);
G2L["5f"]["ZIndex"] = 0;
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["5f"]["Name"] = [[]];
G2L["5f"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Console..
G2L["60"] = Instance.new("ImageLabel", G2L["5f"]);
G2L["60"]["ZIndex"] = 0;
G2L["60"]["BorderSizePixel"] = 0;
G2L["60"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["60"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["60"]["ImageTransparency"] = 0.5;
G2L["60"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["60"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["60"]["Image"] = [[rbxassetid://6015897843]];
G2L["60"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["60"]["BackgroundTransparency"] = 1;
G2L["60"]["Name"] = [[]];
G2L["60"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.Each.Console.
G2L["61"] = Instance.new("UICorner", G2L["5d"]);
G2L["61"]["Name"] = [[]];


-- StarterGui.Neu.Dashboard.M.Each.Console.
G2L["62"] = Instance.new("UIStroke", G2L["5d"]);
G2L["62"]["Name"] = [[]];
G2L["62"]["Color"] = Color3.fromRGB(0, 111, 255);


-- StarterGui.Neu.Dashboard.M.Each.Console.
G2L["63"] = Instance.new("TextLabel", G2L["5d"]);
G2L["63"]["TextWrapped"] = true;
G2L["63"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextScaled"] = true;
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["TextSize"] = 14;
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["63"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["BackgroundTransparency"] = 1;
G2L["63"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["63"]["Size"] = UDim2.new(0.4, 0, 0.1, 0);
G2L["63"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["63"]["Text"] = [[Console]];
G2L["63"]["Name"] = [[]];
G2L["63"]["Position"] = UDim2.new(0.5, 0, 0.1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Console.List
G2L["64"] = Instance.new("ScrollingFrame", G2L["5d"]);
G2L["64"]["Active"] = true;
G2L["64"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["CanvasSize"] = UDim2.new(0, 0, 1, 0);
G2L["64"]["ElasticBehavior"] = Enum.ElasticBehavior.Always;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["64"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["64"]["ClipsDescendants"] = true;
G2L["64"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["64"]["Size"] = UDim2.new(0.9, 0, 0.4, 0);
G2L["64"]["Position"] = UDim2.new(0.5, 0, 0.6, 0);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["ScrollBarThickness"] = 5;
G2L["64"]["Name"] = [[List]];
G2L["64"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Console.List.
G2L["65"] = Instance.new("UIListLayout", G2L["64"]);
G2L["65"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["65"]["Padding"] = UDim.new(0.1, 0);
G2L["65"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["65"]["Name"] = [[]];


-- StarterGui.Neu.Dashboard.M.Each.Console.List.NPF
G2L["66"] = Instance.new("Frame", G2L["64"]);
G2L["66"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["66"]["BorderSizePixel"] = 0;
G2L["66"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["66"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["66"]["Size"] = UDim2.new(0.9, 0, 0.1, 0);
G2L["66"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["66"]["Name"] = [[NPF]];
G2L["66"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Console.List.NPF.
G2L["67"] = Instance.new("UICorner", G2L["66"]);
G2L["67"]["Name"] = [[]];
G2L["67"]["CornerRadius"] = UDim.new(1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Console.List.NPF.
G2L["68"] = Instance.new("UIStroke", G2L["66"]);
G2L["68"]["Name"] = [[]];
G2L["68"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.Each.Console.List.NPF.E
G2L["69"] = Instance.new("TextButton", G2L["66"]);
G2L["69"]["TextWrapped"] = true;
G2L["69"]["BorderSizePixel"] = 0;
G2L["69"]["TextSize"] = 14;
G2L["69"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["69"]["TextScaled"] = true;
G2L["69"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["69"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.ExtraLight, Enum.FontStyle.Normal);
G2L["69"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["69"]["Size"] = UDim2.new(0.8, 0, 1, 0);
G2L["69"]["BackgroundTransparency"] = 1;
G2L["69"]["Name"] = [[E]];
G2L["69"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["69"]["Text"] = [[No problem found]];
G2L["69"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.Each.Console.TextButton
G2L["6a"] = Instance.new("TextButton", G2L["5d"]);
G2L["6a"]["TextWrapped"] = true;
G2L["6a"]["BorderSizePixel"] = 0;
G2L["6a"]["TextSize"] = 14;
G2L["6a"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["6a"]["TextScaled"] = true;
G2L["6a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6a"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["6a"]["BackgroundTransparency"] = 1;
G2L["6a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6a"]["Text"] = [[Close]];
G2L["6a"]["Position"] = UDim2.new(0.4985, 0, 0.94877, 0);


-- StarterGui.Neu.Dashboard.M.Each.Console.Copy
G2L["6b"] = Instance.new("TextButton", G2L["5d"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6b"]["TextSize"] = 14;
G2L["6b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6b"]["Size"] = UDim2.new(0.1, 0, 0.03739, 0);
G2L["6b"]["BackgroundTransparency"] = 1;
G2L["6b"]["Name"] = [[Copy]];
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[Copy]];
G2L["6b"]["Position"] = UDim2.new(0.10481, 0, 0.21949, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands
G2L["6c"] = Instance.new("Frame", G2L["3f"]);
G2L["6c"]["Visible"] = false;
G2L["6c"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["6c"]["ZIndex"] = 4;
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6c"]["Size"] = UDim2.new(0.8, 0, 0.5, 0);
G2L["6c"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Name"] = [[Commands]];


-- StarterGui.Neu.Dashboard.M.Each.Commands.
G2L["6d"] = Instance.new("UIGradient", G2L["6c"]);
G2L["6d"]["Rotation"] = -93;
G2L["6d"]["Name"] = [[]];
G2L["6d"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 51))};


-- StarterGui.Neu.Dashboard.M.Each.Commands.
G2L["6e"] = Instance.new("Frame", G2L["6c"]);
G2L["6e"]["ZIndex"] = 0;
G2L["6e"]["BorderSizePixel"] = 0;
G2L["6e"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["6e"]["Name"] = [[]];
G2L["6e"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Commands..
G2L["6f"] = Instance.new("ImageLabel", G2L["6e"]);
G2L["6f"]["ZIndex"] = 0;
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["6f"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["6f"]["ImageTransparency"] = 0.5;
G2L["6f"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6f"]["Image"] = [[rbxassetid://6015897843]];
G2L["6f"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["6f"]["BackgroundTransparency"] = 1;
G2L["6f"]["Name"] = [[]];
G2L["6f"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.
G2L["70"] = Instance.new("UICorner", G2L["6c"]);
G2L["70"]["Name"] = [[]];


-- StarterGui.Neu.Dashboard.M.Each.Commands.
G2L["71"] = Instance.new("UIStroke", G2L["6c"]);
G2L["71"]["Name"] = [[]];
G2L["71"]["Color"] = Color3.fromRGB(0, 111, 255);


-- StarterGui.Neu.Dashboard.M.Each.Commands.
G2L["72"] = Instance.new("TextLabel", G2L["6c"]);
G2L["72"]["TextWrapped"] = true;
G2L["72"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["72"]["BorderSizePixel"] = 0;
G2L["72"]["TextScaled"] = true;
G2L["72"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["TextSize"] = 14;
G2L["72"]["FontFace"] = Font.new([[rbxasset://fonts/families/Nunito.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["72"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["BackgroundTransparency"] = 1;
G2L["72"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["72"]["Size"] = UDim2.new(0.4, 0, 0.1, 0);
G2L["72"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["72"]["Text"] = [[Commands]];
G2L["72"]["Name"] = [[]];
G2L["72"]["Position"] = UDim2.new(0.5, 0, 0.1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.TextButton
G2L["73"] = Instance.new("TextButton", G2L["6c"]);
G2L["73"]["TextWrapped"] = true;
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["TextSize"] = 14;
G2L["73"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["73"]["TextScaled"] = true;
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["73"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["73"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["73"]["Size"] = UDim2.new(0.1, 0, 0.1, 0);
G2L["73"]["BackgroundTransparency"] = 1;
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Text"] = [[Close]];
G2L["73"]["Position"] = UDim2.new(0.4985, 0, 0.94877, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame
G2L["74"] = Instance.new("ScrollingFrame", G2L["6c"]);
G2L["74"]["Active"] = true;
G2L["74"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["CanvasSize"] = UDim2.new(0, 0, 1, 0);
G2L["74"]["ElasticBehavior"] = Enum.ElasticBehavior.Always;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["74"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["74"]["AutomaticCanvasSize"] = Enum.AutomaticSize.XY;
G2L["74"]["Size"] = UDim2.new(0.9, 0, 0.4, 0);
G2L["74"]["Position"] = UDim2.new(0.5, 0, 0.6, 0);
G2L["74"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["ScrollBarThickness"] = 5;
G2L["74"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.UIListLayout
G2L["75"] = Instance.new("UIListLayout", G2L["74"]);
G2L["75"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["75"]["Padding"] = UDim.new(0.1, 0);
G2L["75"]["SortOrder"] = Enum.SortOrder.LayoutOrder;
G2L["75"]["ItemLineAlignment"] = Enum.ItemLineAlignment.Center;


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop
G2L["76"] = Instance.new("Frame", G2L["74"]);
G2L["76"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["76"]["ZIndex"] = 0;
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["76"]["Size"] = UDim2.new(0.9, 0, 0.2, 0);
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Name"] = [[ExampleCommandOnTop]];
G2L["76"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.
G2L["77"] = Instance.new("UICorner", G2L["76"]);
G2L["77"]["Name"] = [[]];
G2L["77"]["CornerRadius"] = UDim.new(0.1, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.
G2L["78"] = Instance.new("UIStroke", G2L["76"]);
G2L["78"]["Name"] = [[]];
G2L["78"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.E
G2L["79"] = Instance.new("TextButton", G2L["76"]);
G2L["79"]["TextWrapped"] = true;
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["TextSize"] = 14;
G2L["79"]["TextColor3"] = Color3.fromRGB(0, 255, 0);
G2L["79"]["TextScaled"] = true;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.SemiBold, Enum.FontStyle.Normal);
G2L["79"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["79"]["Size"] = UDim2.new(1, 0, 0.304, 0);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Name"] = [[E]];
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["Text"] = [[Example Commands (Notify Player name)]];
G2L["79"]["Position"] = UDim2.new(0.50258, 0, 0.15181, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.
G2L["7a"] = Instance.new("TextButton", G2L["76"]);
G2L["7a"]["TextWrapped"] = true;
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7a"]["TextSize"] = 14;
G2L["7a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["TextScaled"] = true;
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.SemiBold, Enum.FontStyle.Normal);
G2L["7a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7a"]["Size"] = UDim2.new(0.23535, 0, 0.2174, 0);
G2L["7a"]["BackgroundTransparency"] = 1;
G2L["7a"]["Name"] = [[]];
G2L["7a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["Text"] = [[Arguments]];
G2L["7a"]["Position"] = UDim2.new(0.15919, 0, 0.48079, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.Arg
G2L["7b"] = Instance.new("TextButton", G2L["76"]);
G2L["7b"]["TextWrapped"] = true;
G2L["7b"]["BorderSizePixel"] = 0;
G2L["7b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7b"]["TextSize"] = 14;
G2L["7b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7b"]["TextScaled"] = true;
G2L["7b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.SemiBold, Enum.FontStyle.Normal);
G2L["7b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7b"]["Size"] = UDim2.new(0.3949, 0, 0.2174, 0);
G2L["7b"]["BackgroundTransparency"] = 1;
G2L["7b"]["Name"] = [[Arg]];
G2L["7b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7b"]["Text"] = [[!example <player name>]];
G2L["7b"]["Position"] = UDim2.new(0.23897, 0, 0.6986, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.
G2L["7c"] = Instance.new("TextButton", G2L["76"]);
G2L["7c"]["TextWrapped"] = true;
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextSize"] = 14;
G2L["7c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["TextScaled"] = true;
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.SemiBold, Enum.FontStyle.Normal);
G2L["7c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7c"]["Size"] = UDim2.new(0.23535, 0, 0.2174, 0);
G2L["7c"]["BackgroundTransparency"] = 1;
G2L["7c"]["Name"] = [[]];
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[Example Usage]];
G2L["7c"]["Position"] = UDim2.new(0.859, 0, 0.48079, 0);


-- StarterGui.Neu.Dashboard.M.Each.Commands.ScrollingFrame.ExampleCommandOnTop.Usage
G2L["7d"] = Instance.new("TextButton", G2L["76"]);
G2L["7d"]["TextWrapped"] = true;
G2L["7d"]["BorderSizePixel"] = 0;
G2L["7d"]["TextXAlignment"] = Enum.TextXAlignment.Right;
G2L["7d"]["TextSize"] = 14;
G2L["7d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7d"]["TextScaled"] = true;
G2L["7d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.SemiBold, Enum.FontStyle.Normal);
G2L["7d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7d"]["Size"] = UDim2.new(0.3949, 0, 0.2174, 0);
G2L["7d"]["BackgroundTransparency"] = 1;
G2L["7d"]["Name"] = [[Usage]];
G2L["7d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7d"]["Text"] = [[!example realplay002]];
G2L["7d"]["Position"] = UDim2.new(0.77744, 0, 0.6986, 0);


-- StarterGui.Neu.Dashboard.M.TextButton
G2L["7e"] = Instance.new("TextButton", G2L["2"]);
G2L["7e"]["TextWrapped"] = true;
G2L["7e"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["7e"]["BorderSizePixel"] = 0;
G2L["7e"]["TextSize"] = 14;
G2L["7e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7e"]["TextScaled"] = true;
G2L["7e"]["Visible"] = false;
G2L["7e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7e"]["FontFace"] = Font.new([[rbxasset://fonts/families/Zekton.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["7e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7e"]["Size"] = UDim2.new(0.3, 0, 0.1, 0);
G2L["7e"]["BackgroundTransparency"] = 1;
G2L["7e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7e"]["Text"] = [[Drk Hub]];
G2L["7e"]["Position"] = UDim2.new(0.5, 0, 0.2, 0);
G2L["7e"]["Visible"] = true;


-- StarterGui.Neu.Dashboard.M.P1
G2L["7f"] = Instance.new("Path2D", G2L["2"]);
G2L["7f"]["Visible"] = false;
G2L["7f"]["Name"] = [[P1]];


-- StarterGui.Neu.Dashboard.M.P2
G2L["80"] = Instance.new("Path2D", G2L["2"]);
G2L["80"]["Visible"] = false;
G2L["80"]["Name"] = [[P2]];


-- StarterGui.Neu.Dashboard.M.P3
G2L["81"] = Instance.new("Path2D", G2L["2"]);
G2L["81"]["Visible"] = false;
G2L["81"]["Name"] = [[P3]];


-- StarterGui.Neu.Dashboard.M.P4
G2L["82"] = Instance.new("Path2D", G2L["2"]);
G2L["82"]["Visible"] = false;
G2L["82"]["Name"] = [[P4]];


-- StarterGui.Neu.Dashboard.M.P5
G2L["83"] = Instance.new("Path2D", G2L["2"]);
G2L["83"]["Visible"] = false;
G2L["83"]["Name"] = [[P5]];


-- StarterGui.Neu.Dashboard.M.P6
G2L["84"] = Instance.new("Path2D", G2L["2"]);
G2L["84"]["Visible"] = false;
G2L["84"]["Name"] = [[P6]];


-- StarterGui.Neu.Dashboard.B
G2L["85"] = Instance.new("Frame", G2L["1"]);
G2L["85"]["SizeConstraint"] = Enum.SizeConstraint.RelativeXX;
G2L["85"]["ZIndex"] = 0;
G2L["85"]["BorderSizePixel"] = 0;
G2L["85"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["85"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["85"]["Size"] = UDim2.new(0.5, 0, 0.3, 0);
G2L["85"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["85"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["85"]["Name"] = [[B]];
G2L["85"]["Visible"] = false;


-- StarterGui.Neu.Dashboard.B.UICorner
G2L["86"] = Instance.new("UICorner", G2L["85"]);



-- StarterGui.Neu.Dashboard.B.UIGradient
G2L["87"] = Instance.new("UIGradient", G2L["85"]);
G2L["87"]["Rotation"] = -86;
G2L["87"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0.1),NumberSequenceKeypoint.new(1.000, 0.1)};
G2L["87"]["Offset"] = Vector2.new(2, 0.12);
G2L["87"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(0, 0, 0)),ColorSequenceKeypoint.new(0.492, Color3.fromRGB(0, 2, 80)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.Neu.Dashboard.B.DropShadowHolder
G2L["88"] = Instance.new("Frame", G2L["85"]);
G2L["88"]["ZIndex"] = 0;
G2L["88"]["BorderSizePixel"] = 0;
G2L["88"]["Size"] = UDim2.new(1, 0, 1, 0);
G2L["88"]["Name"] = [[DropShadowHolder]];
G2L["88"]["BackgroundTransparency"] = 1;


-- StarterGui.Neu.Dashboard.B.DropShadowHolder.DropShadow
G2L["89"] = Instance.new("ImageLabel", G2L["88"]);
G2L["89"]["ZIndex"] = 0;
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["SliceCenter"] = Rect.new(49, 49, 450, 450);
G2L["89"]["ScaleType"] = Enum.ScaleType.Slice;
G2L["89"]["ImageTransparency"] = 0.5;
G2L["89"]["ImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["89"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["89"]["Image"] = [[rbxassetid://6014261993]];
G2L["89"]["Size"] = UDim2.new(1, 47, 1, 47);
G2L["89"]["BackgroundTransparency"] = 1;
G2L["89"]["Name"] = [[DropShadow]];
G2L["89"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);

local Lib = {};
local UiParentalControl = game:GetService("CoreGui");
local TweenS = game:GetService("TweenService");

local ClonerCon = G2L["66"]:Clone();
ClonerCon.Parent = nil;

local Template = {
	["CMD"] = G2L["76"]:Clone();
	["Stack"] = G2L["49"]:Clone();
	["Console"] = ClonerCon;
};

function Lib:AddCmd(Command, Arguments, Usage, Color)
	local a = Template["CMD"]:Clone();
	a.E.Text = Command;
	a.E.TextColor3 = Color;
	a.Arg.Text = Arguments;
	a.Usage.Text = Usage;
	a.Parent = G2L["74"];
end;

function Lib:StackError(value, destroy)
	if G2L["47"]:FindFirstChild("NPF") then
		G2L["47"]:FindFirstChild("NPF"):Destroy(true);
	end;
	if G2L["47"]:FindFirstChild(value) and not destroy then return end;
	if not G2L["47"]:FindFirstChild(value) and not destroy then
		local a = Template["Stack"]:Clone();
		a.T.Text = value;
		a.T.TextColor3 = Color3.fromRGB(255, 0, 0);
		a.Parent = G2L["47"];
		a.Name = value;
	elseif destroy then
		if G2L["47"]:FindFirstChild(value) then
			G2L["47"]:FindFirstChild(value):Destroy(true);
		end;
		if #G2L["47"]:GetChildren() == 1 then
			local a = Template["Stack"]:Clone();
			a.Parent = G2L["47"]
		end;
	end;
end;

function Lib:SendConsole(value, Color)
	local ConsoleChild = G2L["64"]:GetChildren();
	if #ConsoleChild >= 50 then
		for i, v in pairs(ConsoleChild) do
			if not v:IsA("UIListLayout") then
				v:Destroy();
			end;
		end;
	end;
	local a = Template["Console"]:Clone();
	local EFa = a:WaitForChild("E");
	EFa.Text = value;
	EFa.TextColor3 = Color;
	EFa.Parent = G2L["64"];
	EFa.MouseButton1Click:Connect(function()
		POPCD.TargetConsoleOut = EFa.Text;
	end);
end;

function Lib:SendRequest(value)
	G2L["56"].Text = value;
end;

local POPCD = {
	["InCDG2L40"] = false;
	["InCDG2L4e"] = false;
	["InCDG2L5d"] = false;
	["InCDG2L6c"] = false;
	["TargetConsoleOut"] = "No problem found";
};

G2L["40"].Position = UDim2.new(0.5, 0, 1, 0);
G2L["40"].Size = UDim2.new(0, 0, 0, 0);

G2L["c"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L40 then return end;
	if G2L["40"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
		POPCD.InCDG2L40 = true;
		G2L["40"].Visible = true; task.wait();
		TweenS:Create(G2L["40"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 0.5, 0)
		}):Play();
		TweenS:Create(G2L["40"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0.8, 0, 0.5, 0)
		}):Play();
		POPCD.InCDG2L40 = false;
	else
		POPCD.InCDG2L40 = true;
		TweenS:Create(G2L["40"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 1, 0)
		}):Play();
		TweenS:Create(G2L["40"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0, 0, 0, 0)
		}):Play();
		task.wait(0.4);
		G2L["40"].Visible = false;
		POPCD.InCDG2L40 = false;
	end;
end);

G2L["4d"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L40 then return end;
	POPCD.InCDG2L40 = true;
	TweenS:Create(G2L["40"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Position = UDim2.new(0.5, 0, 1, 0)
	}):Play();
	TweenS:Create(G2L["40"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Size = UDim2.new(0, 0, 0, 0)
	}):Play();
	task.wait(0.4);
	G2L["40"].Visible = false;
	POPCD.InCDG2L40 = false;
end);

G2L["4e"].Position = UDim2.new(0.5, 0, 1, 0);
G2L["4e"].Size = UDim2.new(0, 0, 0, 0);

G2L["13"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L4e then return end;
	if G2L["4e"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
		POPCD.InCDG2L4e = true;
		G2L["4e"].Visible = true; task.wait();
		TweenS:Create(G2L["4e"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 0.5, 0)
		}):Play();
		TweenS:Create(G2L["4e"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0.8, 0, 0.5, 0)
		}):Play();
		POPCD.InCDG2L4e = false;
	else
		POPCD.InCDG2L4e = true;
		TweenS:Create(G2L["4e"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 1, 0)
		}):Play();
		TweenS:Create(G2L["4e"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0, 0, 0, 0)
		}):Play();
		task.wait(0.4);
		G2L["4e"].Visible = false;
		POPCD.InCDG2L4e = false;
	end;
end);

G2L["58"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L4e then return end;
	POPCD.InCDG2L4e = true;
	TweenS:Create(G2L["4e"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Position = UDim2.new(0.5, 0, 1, 0)
	}):Play();
	TweenS:Create(G2L["4e"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Size = UDim2.new(0, 0, 0, 0)
	}):Play();
	task.wait(0.4);
	G2L["4e"].Visible = false;
	POPCD.InCDG2L4e = false;
end);

G2L["5d"].Position = UDim2.new(0.5, 0, 1, 0);
G2L["5d"].Size = UDim2.new(0, 0, 0, 0);

G2L["1a"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L5d then return end;
	if G2L["5d"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
		POPCD.InCDG2L5d = true;
		G2L["5d"].Visible = true; task.wait();
		TweenS:Create(G2L["5d"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 0.5, 0)
		}):Play();
		TweenS:Create(G2L["5d"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0.8, 0, 0.5, 0)
		}):Play();
		POPCD.InCDG2L5d = false;
	else
		POPCD.InCDG2L5d = true;
		TweenS:Create(G2L["5d"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 1, 0)
		}):Play();
		TweenS:Create(G2L["5d"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0, 0, 0, 0)
		}):Play();
		task.wait(0.4);
		G2L["5d"].Visible = false;
		POPCD.InCDG2L5d = false;
	end;
end);

G2L["6a"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L5d then return end;
	POPCD.InCDG2L5d = true;
	TweenS:Create(G2L["5d"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Position = UDim2.new(0.5, 0, 1, 0)
	}):Play();
	TweenS:Create(G2L["5d"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Size = UDim2.new(0, 0, 0, 0)
	}):Play();
	task.wait(0.4);
	G2L["5d"].Visible = false;
	POPCD.InCDG2L5d = false;
end);

G2L["6c"].Position = UDim2.new(0.5, 0, 1, 0);
G2L["6c"].Size = UDim2.new(0, 0, 0, 0);

G2L["21"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L6c then return end;
	if G2L["6c"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
		POPCD.InCDG2L6c = true;
		G2L["6c"].Visible = true; task.wait();
		TweenS:Create(G2L["6c"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 0.5, 0)
		}):Play();
		TweenS:Create(G2L["6c"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0.8, 0, 0.5, 0)
		}):Play();
		POPCD.InCDG2L6c = false;
	else
		POPCD.InCDG2L6c = true;
		TweenS:Create(G2L["6c"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 1, 0)
		}):Play();
		TweenS:Create(G2L["6c"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0, 0, 0, 0)
		}):Play();
		task.wait(0.4);
		G2L["6c"].Visible = false;
		POPCD.InCDG2L6c = false;
	end;
end);

G2L["73"].MouseButton1Click:Connect(function()
	if POPCD.InCDG2L6c then return end;
	POPCD.InCDG2L6c = true;
	TweenS:Create(G2L["6c"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Position = UDim2.new(0.5, 0, 1, 0)
	}):Play();
	TweenS:Create(G2L["6c"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
		Size = UDim2.new(0, 0, 0, 0)
	}):Play();
	task.wait(0.4);
	G2L["6c"].Visible = false;
	POPCD.InCDG2L6c = false;
end);

G2L["59"].MouseButton1Click:Connect(function()
	Clipboard = setclipboard or toclipboard
	Clipboard(G2L["56"].Text);
end);

G2L["5a"].MouseButton1Click:Connect(function()
	writefile("Request.txt", G2L["56"].Text);
end);

G2L["5b"].MouseButton1Click:Connect(function()
	print(G2L["56"].Text);
end);

G2L["5c"].MouseButton1Click:Connect(function()
	warn(G2L["56"].Text);
end);

G2L["6b"].MouseButton1Click:Connect(function()
	Clipboard = setclipboard or toclipboard
	Clipboard(POPCD.TargetConsoleOut);
end);

local clickCount = 0
local doubleClickTime = 0.5
local lastClick = 0

G2L["2"].Position = UDim2.new(0.5, 0, 1, 0);
G2L["2"].Size = UDim2.new(0, 0, 0, 0);
G2L["85"].Position = UDim2.new(0.5, 0, 1, 0);
G2L["85"].Size = UDim2.new(0, 0, 0, 0);

G2L["7e"].MouseButton1Click:Connect(function()
	local currentTime = tick();
    if currentTime - lastClick <= doubleClickTime then
        clickCount = clickCount + 1;
    else
        clickCount = 1;
    end;
    lastClick = currentTime;
    if clickCount == 2 then
        clickCount = 0;
		if G2L["2"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
			G2L["85"].Visible = true;
			G2L["2"].Visible = true; task.wait()
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 0.5, 0)
			}):Play();
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0.5, 0, 0.3, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 0.5, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0.5, 0, 0.3, 0)
			}):Play();
		else
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 1, 0)
			}):Play();
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0, 0, 0, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 1, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0, 0, 0, 0)
			}):Play();
			task.wait(0.4);
			G2L["2"].Visible = false;
			G2L["85"].Visible = false;
		end;
    end;
end);

G2L["3e"].MouseButton1Click:Connect(function()
	G2L["7e"].Text = "Double click me to close"; task.wait(2);
	G2L["7e"].Text = "Drk Hub"
end);

G2L["3c"].MouseButton1Click:Connect(function()
	Clipboard = setclipboard or toclipboard;
	Clipboard("soon")
	G2L["7e"].Text = "Youtube link has been copy to your clipboard"; task.wait(2);
	G2L["7e"].Text = "Drk Hub"
end);

G2L["3a"].MouseButton1Click:Connect(function()
	Clipboard = setclipboard or toclipboard;
	Clipboard("https://discord.gg/5ZH4v44r")
	G2L["7e"].Text = "Discord link has been copy to your clipboard"; task.wait(2);
	G2L["7e"].Text = "Drk Hub"
end);

getgenv().NeuDa = function()
	if G2L["2"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
		G2L["85"].Visible = true;
		G2L["2"].Visible = true; task.wait()
		TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 0.5, 0)
		}):Play();
		TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0.5, 0, 0.3, 0)
		}):Play();
		TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 0.5, 0)
		}):Play();
		TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0.5, 0, 0.3, 0)
		}):Play();
	else
		TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 1, 0)
		}):Play();
		TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0, 0, 0, 0)
		}):Play();
		TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Position = UDim2.new(0.5, 0, 1, 0)
		}):Play();
		TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
			Size = UDim2.new(0, 0, 0, 0)
		}):Play();
		task.wait(0.4);
		G2L["2"].Visible = false;
		G2L["85"].Visible = false;
	end;
end;

local UserInputService = game:GetService("UserInputService")

UserInputService.InputBegan:Connect(function(input)
    if input.KeyCode == Enum.KeyCode.BackSlash then
		if G2L["2"].Position ~= UDim2.new(0.5, 0, 0.5, 0) then
			G2L["85"].Visible = true;
			G2L["2"].Visible = true; task.wait()
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 0.5, 0)
			}):Play();
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0.5, 0, 0.3, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 0.5, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0.5, 0, 0.3, 0)
			}):Play();
		else
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 1, 0)
			}):Play();
			TweenS:Create(G2L["2"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0, 0, 0, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Position = UDim2.new(0.5, 0, 1, 0)
			}):Play();
			TweenS:Create(G2L["85"], TweenInfo.new(0.2, Enum.EasingStyle.Linear), {
				Size = UDim2.new(0, 0, 0, 0)
			}):Play();
			task.wait(0.4);
			G2L["2"].Visible = false;
			G2L["85"].Visible = false;
		end;
    end;
end);

task.wait(0.3);

getgenv().NeuDa();

return Lib;
