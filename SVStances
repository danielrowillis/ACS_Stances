local TS = game:GetService("TweenService")

local SVStance = {}

local function applyTween(part, tweenInfo, cframe)
	TS:Create(part, tweenInfo, {C1 = cframe}):Play()
end

local function applyTweenC0(part, tweenInfo, cframe)
	TS:Create(part, tweenInfo, {C0 = cframe}):Play()
end


--// SERVER SIDED ANIMATIONS (SERVER SCRIPT)

-- Standing Animations
function SVStance.StandRight(RootJoint, RS, LS, RH, LH)
	-- Apply left standing animation
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(-1, 0, 0) * CFrame.Angles(math.rad(-90), math.rad(-30), math.rad(-180)))
	applyTween(RH, TweenInfo.new(0.3), CFrame.new(0.5, 1, 0) * CFrame.Angles(math.rad(0), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(0.3), CFrame.new(-0.5, 1, 0) * CFrame.Angles(math.rad(0), math.rad(-90), math.rad(0)))
end

function SVStance.StandLeft(RootJoint, RS, LS, RH, LH)
	-- Apply right standing animation
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(1, 0, 0) * CFrame.Angles(math.rad(-90), math.rad(30), math.rad(180)))
	applyTween(RH, TweenInfo.new(0.3), CFrame.new(0.5, 1, 0) * CFrame.Angles(math.rad(0), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(0.3), CFrame.new(-0.5, 1, 0) * CFrame.Angles(math.rad(0), math.rad(-90), math.rad(0)))
end

function SVStance.Stand(RootJoint, RS, LS, RH, LH)
	-- Apply center standing animation (default stance)
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(0, 0, 0) * CFrame.Angles(math.rad(-90), math.rad(0), math.rad(180)))
	applyTween(RH, TweenInfo.new(0.3), CFrame.new(0.5, 1, 0) * CFrame.Angles(math.rad(0), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(0.3), CFrame.new(-0.5, 1, 0) * CFrame.Angles(math.rad(0), math.rad(-90), math.rad(0)))
end

-- Crouching Animations
function SVStance.CrouchRight(RootJoint, RS, LS, RH, LH)
	-- Apply left crouching animation
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(-1, 0.75, 0.25) * CFrame.Angles(math.rad(-80), math.rad(-30), math.rad(-180)))
	applyTween(RH, TweenInfo.new(0.3), CFrame.new(0.5, 0, 0.4) * CFrame.Angles(math.rad(20), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(0.3), CFrame.new(-0.5, 0, 0.4) * CFrame.Angles(math.rad(20), math.rad(-90), math.rad(0)))
end

function SVStance.CrouchLeft(RootJoint, RS, LS, RH, LH)
	-- Apply right crouching animation
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(1, 0.75, 0.25) * CFrame.Angles(math.rad(-80), math.rad(30), math.rad(180)))
	applyTween(RH, TweenInfo.new(0.3), CFrame.new(0.5, 0, 0.4) * CFrame.Angles(math.rad(20), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(0.3), CFrame.new(-0.5, 0, 0.4) * CFrame.Angles(math.rad(20), math.rad(-90), math.rad(0)))
end

function SVStance.Crouch(RootJoint, RS, LS, RH, LH)
	-- Apply center crouching animation
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(0, 1, 0.25) * CFrame.Angles(math.rad(-80), math.rad(0), math.rad(180)))
	applyTween(RH, TweenInfo.new(0.3), CFrame.new(0.5, 0, 0.4) * CFrame.Angles(math.rad(20), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(0.3), CFrame.new(-0.5, 0, 0.4) * CFrame.Angles(math.rad(20), math.rad(-90), math.rad(0)))
end

-- Proning Animations
function SVStance.ProneRight(RootJoint, RS, LS, RH, LH)
	-- Apply left proning animation
	applyTween(RootJoint, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(-2.5, 0.5, 2.45) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(-145)))
	applyTween(RH, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(0.45, 0.8, 0) * CFrame.Angles(math.rad(90), math.rad(60), math.rad(-95)))
	applyTween(RS, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(-0.5, 0.95, 0) * CFrame.Angles(math.rad(-90), math.rad(75), math.rad(-85)))
	applyTween(LH, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(-0.5, 1, 0) * CFrame.Angles(math.rad(-90), math.rad(-70), math.rad(-85)))
	applyTween(LS, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(0.5, 0.95, 0) * CFrame.Angles(math.rad(90), math.rad(-75), math.rad(-95)))
end

function SVStance.ProneLeft(RootJoint, RS, LS, RH, LH)
	-- Apply right proning animation
	applyTween(RootJoint, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(2.5, 0.5, 2.45) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(-215)))
	applyTween(RH, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(0.5, 1, 0) * CFrame.Angles(math.rad(-90), math.rad(75), math.rad(85)))
	applyTween(RS, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(-0.5, 0.95, 0) * CFrame.Angles(math.rad(90), math.rad(75), math.rad(94)))
	applyTween(LH, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(-0.45, 0.8, 0) * CFrame.Angles(math.rad(90), math.rad(-60), math.rad(95)))
	applyTween(LS, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(0.5, 0.95, 0) * CFrame.Angles(math.rad(-90), math.rad(-75), math.rad(85)))
end

function SVStance.Prone(RootJoint, RS, LS, RH, LH)
	-- Apply center proning animation
	applyTween(RootJoint, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(0, 1.5, 2.45) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(180)))
	applyTween(RH, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(0.5, 1, 0) * CFrame.Angles(math.rad(-5), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(1.05, Enum.EasingStyle.Quart), CFrame.new(-0.5, 1, 0) * CFrame.Angles(math.rad(-5), math.rad(-90), math.rad(0)))
end

-- Reload Animation Function
function SVStance.ReloadAnimation(Right_Weld, Left_Weld)
	-- Apply first set of movements
	applyTweenC0(Right_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(-0.930, 0.501, -1.235) * CFrame.Angles(math.rad(-90.069), math.rad(-2.017), math.rad(7.990)))
	applyTweenC0(Left_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(1.320, 0.984, -0.861) * CFrame.Angles(math.rad(-72.785), math.rad(20.447), math.rad(-24.384)))
	wait(0.35)

	-- Apply second set of movements
	applyTweenC0(Left_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(1.374, 1.002, -0.988) * CFrame.Angles(math.rad(-72.785), math.rad(20.447), math.rad(-24.384)))
	wait(0.6)

	-- Apply third set of movements
	applyTweenC0(Right_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(-0.930, 0.501, -1.235) * CFrame.Angles(math.rad(-90.069), math.rad(-2.017), math.rad(7.990)))
	applyTweenC0(Left_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(1.195, 1.400, -0.500) * CFrame.Angles(math.rad(0.000), math.rad(25.000), math.rad(0.000)))
	wait(1.4)

	-- Apply fourth set of movements
	applyTweenC0(Left_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(1.374, 1.002, -0.988) * CFrame.Angles(math.rad(-72.785), math.rad(20.447), math.rad(-24.384)))
	wait(0.8)

	-- Apply fifth set of movements
	applyTweenC0(Right_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(-0.930, 0.501, -1.235) * CFrame.Angles(math.rad(-90.069), math.rad(-2.017), math.rad(7.990)))
	applyTweenC0(Left_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(1.320, 0.984, -0.861) * CFrame.Angles(math.rad(-72.785), math.rad(20.447), math.rad(-24.384)))
	wait(0.55)

	-- Apply final movement
	applyTweenC0(Right_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(-0.85, 0.1, -1.2) * CFrame.Angles(math.rad(-90), math.rad(0), math.rad(0)))
	applyTweenC0(Left_Weld, TweenInfo.new(0.5, Enum.EasingStyle.Quart), CFrame.new(1.05, 0.9, -1.4) * CFrame.Angles(math.rad(-100), math.rad(25), math.rad(-20)))
	wait(0.1)
end

--_______________________________________________________________________________________________________________________________________________________________________________________________

function SVStance.Dancing(RootJoint, RS, LS, RH, LH, Head)
	applyTween(RootJoint, TweenInfo.new(0.3), CFrame.new(0, 0, 0) * CFrame.Angles(math.rad(-90), math.rad(0), math.rad(180)))
	applyTween(RH, TweenInfo.new(3), CFrame.new(0.5, 3, 0) * CFrame.Angles(math.rad(0), math.rad(90), math.rad(0)))
	applyTween(LH, TweenInfo.new(3), CFrame.new(-0.5, 3, 0) * CFrame.Angles(math.rad(0), math.rad(-90), math.rad(0)))
end





return SVStance
