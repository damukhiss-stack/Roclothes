--[[	

	/ ＲＯＣＬＯＴＨＥＳ
	Version - 0.7.7:lerp()
	Link - discord.gg/HBzvWE6Rp3
	
	| This script requires a LOCAL folder "RClothesContent" to be added in ROBLOX's content folder, or it'll self-destruct itself
	
	| RoClothes is a Client-Sided Exploiting Script, that allows the player to have nude BodyParts/Clothes
	Can be used on any executor
	
	| This script WILL cause FPS drops, because of BodyParts/Clothes meshes inside the Player model
	
	| 𝐔𝐒𝐄 𝐀𝐓 𝐘𝐎𝐔𝐑 𝐎𝐖𝐍 𝐑𝐈𝐒𝐊
	| 𝐖𝐎𝐑𝐊 𝐈𝐍 𝐏𝐑𝐎𝐆𝐑𝐄𝐒𝐒
	
	The original developer of RoClothes is no longer working on this script.
	This is a MODDED version of this script that might or might not be updated.
	If you know who the creator of this mod is, feel free to make requests or suggest some things.
	
	
	
	original version 0.7
	local version 0.7.7:lerp()
		














	
	














]]



























local RS = game:GetService("RunService")

function RoClothes(Player)
	warn("RoClothes Connected")

	--[[
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------

                                      ██╗░░░░░░█████╗░░█████╗░░█████╗░██╗░░░░░
                                      ██║░░░░░██╔══██╗██╔══██╗██╔══██╗██║░░░░░
                                      ██║░░░░░██║░░██║██║░░╚═╝███████║██║░░░░░
                                      ██║░░░░░██║░░██║██║░░██╗██╔══██║██║░░░░░
                                      ███████╗╚█████╔╝╚█████╔╝██║░░██║███████╗
                                      ╚══════╝░╚════╝░░╚════╝░╚═╝░░╚═╝╚══════╝
                                  
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	]]

	local GUIObject = {}

	GUIObject.Screen = Instance.new("ScreenGui")
	GUIObject.MainFrame = Instance.new("TextButton")
	GUIObject.Dragger = Instance.new("UIDragDetector")
	GUIObject.PageFrame = Instance.new("Frame")
	GUIObject.UIGradient = Instance.new("UIGradient")
	GUIObject.UICorner = Instance.new("UICorner")
	GUIObject.Clothes_3 = Instance.new("Frame")
	GUIObject.ClothesSearch = Instance.new("TextBox")
	GUIObject.UIGradient_34 = Instance.new("UIGradient")
	GUIObject.UICorner_35 = Instance.new("UICorner")
	GUIObject.ClothesButtonFrame = Instance.new("ScrollingFrame")
	GUIObject.UIGridLayout = Instance.new("UIGridLayout")
	GUIObject.Menu = Instance.new("Frame")
	GUIObject.DestroyFrame = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UIGradient_3 = Instance.new("UIGradient")
	GUIObject.UICorner_3 = Instance.new("UICorner")
	GUIObject.DestroyButton = Instance.new("TextButton")
	GUIObject.PlayerFrame = Instance.new("Frame")
	GUIObject.UIGradient_4 = Instance.new("UIGradient")
	GUIObject.UICorner_4 = Instance.new("UICorner")
	GUIObject.PlayerExecute = Instance.new("TextBox")
	GUIObject.BreastsTypeFrame = Instance.new("Frame")
	GUIObject.UIGradient_5 = Instance.new("UIGradient")
	GUIObject.UICorner_5 = Instance.new("UICorner")
	GUIObject.BreastsTypeButton = Instance.new("TextButton")
	GUIObject.BundleFrame = Instance.new("Frame")
	GUIObject.UIGradient_6 = Instance.new("UIGradient")
	GUIObject.UICorner_6 = Instance.new("UICorner")
	GUIObject.BundleText = Instance.new("TextLabel")
	GUIObject.BundleSearch = Instance.new("TextBox")
	GUIObject.UIGradient_A17 = Instance.new("UIGradient")
	GUIObject.UICorner_A17 = Instance.new("UICorner")
	GUIObject.DelayFrame = Instance.new("Frame")
	GUIObject.UIGradient_7 = Instance.new("UIGradient")
	GUIObject.UICorner_7 = Instance.new("UICorner")
	GUIObject.DelayTimeText = Instance.new("TextBox")
	GUIObject.AutoExecuteFrame = Instance.new("Frame")
	GUIObject.UICorner_8 = Instance.new("UICorner")
	GUIObject.UIGradient_8 = Instance.new("UIGradient")
	GUIObject.AutoExecuteButton = Instance.new("TextButton")
	GUIObject.BundleBodyColorFrame = Instance.new("Frame")
	GUIObject.UIGradient_15 = Instance.new("UIGradient")
	GUIObject.UICorner_15 = Instance.new("UICorner")
	GUIObject.BundleBodyColorButton = Instance.new("TextButton")
	GUIObject.ResetFrame = Instance.new("Frame")
	GUIObject.UICorner_9 = Instance.new("UICorner")
	GUIObject.UIGradient_9 = Instance.new("UIGradient")
	GUIObject.ResetButton = Instance.new("TextButton")
	GUIObject.ExecuteFrame = Instance.new("Frame")
	GUIObject.UICorner_10 = Instance.new("UICorner")
	GUIObject.UIGradient_10 = Instance.new("UIGradient")
	GUIObject.ExecuteButton = Instance.new("TextButton")
	GUIObject.ToneFrame = Instance.new("Frame")
	GUIObject.UIGradient_11 = Instance.new("UIGradient")
	GUIObject.UICorner_11 = Instance.new("UICorner")
	GUIObject.ToneButton = Instance.new("TextButton")
	GUIObject.Bundles = Instance.new("Frame")
	GUIObject.BundlesButtonFrame = Instance.new("ScrollingFrame")
	GUIObject.UIGridLayout_2 = Instance.new("UIGridLayout")
	GUIObject.ButtonFrame = Instance.new("Frame")
	GUIObject.UIListLayout = Instance.new("UIListLayout")
	GUIObject.FaceFrame = Instance.new("Frame")
	GUIObject.UIGradient_17 = Instance.new("UIGradient")
	GUIObject.UICorner_17 = Instance.new("UICorner")
	GUIObject.FaceButton = Instance.new("TextButton")
	GUIObject.Menu_2 = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_12 = Instance.new("UICorner")
	GUIObject.MenuButton = Instance.new("TextButton")
	GUIObject.UIGradient_12 = Instance.new("UIGradient")
	GUIObject.Clothes_2 = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_13 = Instance.new("UICorner")
	GUIObject.ClothesButton = Instance.new("TextButton")
	GUIObject.UIGradient_13 = Instance.new("UIGradient")
	GUIObject.Bundles_2 = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_14 = Instance.new("UICorner")
	GUIObject.BundlesButton = Instance.new("TextButton")
	GUIObject.UIGradient_14 = Instance.new("UIGradient")
	GUIObject.NameFrame = Instance.new("Frame")
	GUIObject.NameText = Instance.new("TextLabel")
	GUIObject.VersionText = Instance.new("TextLabel")
	GUIObject.KeybindFrame = Instance.new("Frame")
	GUIObject.UIGradient_16 = Instance.new("UIGradient")
	GUIObject.UICorner_16 = Instance.new("UICorner")
	GUIObject.KeybindButton = Instance.new("TextButton")
	GUIObject.RoClothes = Instance.new("ScreenGui")
	GUIObject.Menu2 = Instance.new("Frame")
	GUIObject.LocalTransparencyFrame = Instance.new("Frame")
	GUIObject.UIGradient_18 = Instance.new("UIGradient")
	GUIObject.UICorner_18 = Instance.new("UICorner")
	GUIObject.LocalTransparencyButton = Instance.new("TextBox")
	GUIObject.CharacterFrame = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
	GUIObject.LeftArmButton = Instance.new("ImageButton")
	GUIObject.TorsoButton = Instance.new("ImageButton")
	GUIObject.RightArmButton = Instance.new("ImageButton")
	GUIObject.RightLegButton = Instance.new("ImageButton")
	GUIObject.LeftLegButton = Instance.new("ImageButton")
	GUIObject.HeadButton = Instance.new("ImageButton")
	GUIObject.UICorner_19 = Instance.new("UICorner")
	GUIObject.Menu2_2 = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_20 = Instance.new("UICorner")
	GUIObject.Menu2Button = Instance.new("TextButton")
	GUIObject.UIGradient_19 = Instance.new("UIGradient")
	GUIObject.MeshSizeLockFrame = Instance.new("Frame")
	GUIObject.UIGradient_20 = Instance.new("UIGradient")
	GUIObject.UICorner_21 = Instance.new("UICorner")
	GUIObject.MeshSizeLockButton = Instance.new("TextButton")
	GUIObject.AccessorySizeLockFrame = Instance.new("Frame")
	GUIObject.UIGradient_21 = Instance.new("UIGradient")
	GUIObject.UICorner_22 = Instance.new("UICorner")
	GUIObject.AccessorySizeLockButton = Instance.new("TextButton")
	GUIObject.MeshBasePartInvisibleFrame = Instance.new("Frame")
	GUIObject.UIGradient_22 = Instance.new("UIGradient")
	GUIObject.UICorner_23 = Instance.new("UICorner")
	GUIObject.MeshBasePartInvisibleButton = Instance.new("TextButton")
	GUIObject.BodyPartPhysicsFrame = Instance.new("Frame")
	GUIObject.UIGradient_23 = Instance.new("UIGradient")
	GUIObject.UICorner_24 = Instance.new("UICorner")
	GUIObject.BodyPartPhysicsButton = Instance.new("TextButton")
	GUIObject.MethodFrame = Instance.new("Frame")
	GUIObject.UIGradient_24 = Instance.new("UIGradient")
	GUIObject.UICorner_25 = Instance.new("UICorner")
	GUIObject.MethodButton = Instance.new("TextButton")
	GUIObject.Edit_2 = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_33 = Instance.new("UICorner")
	GUIObject.EditButton = Instance.new("TextButton")
	GUIObject.UIGradient_32 = Instance.new("UIGradient")
	GUIObject.Catalog_2 = Instance.new("Frame")
	GUIObject.UIAspectRatioConstraint_8 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_34 = Instance.new("UICorner")
	GUIObject.CatalogButton = Instance.new("TextButton")
	GUIObject.UIGradient_33 = Instance.new("UIGradient")
	GUIObject.Catalog_3 = Instance.new("Frame")
	GUIObject.UsernameFrame = Instance.new("Frame")
	GUIObject.UICorner_27 = Instance.new("UICorner")
	GUIObject.UsernameTextbox = Instance.new("TextBox")
	GUIObject.UIGradient_26 = Instance.new("UIGradient")
	GUIObject.AccessoryFrame = Instance.new("Frame")
	GUIObject.UICorner_28 = Instance.new("UICorner")
	GUIObject.AccessoryTextbox = Instance.new("TextBox")
	GUIObject.UIGradient_27 = Instance.new("UIGradient")
	GUIObject.ShirtFrame = Instance.new("Frame")
	GUIObject.UICorner_29 = Instance.new("UICorner")
	GUIObject.ShirtTextbox = Instance.new("TextBox")
	GUIObject.UIGradient_28 = Instance.new("UIGradient")
	GUIObject.PantsFrame = Instance.new("Frame")
	GUIObject.UICorner_30 = Instance.new("UICorner")
	GUIObject.PantsTextbox = Instance.new("TextBox")
	GUIObject.UIGradient_29 = Instance.new("UIGradient")
	GUIObject.ShirtGraphicFrame = Instance.new("Frame")
	GUIObject.UICorner_31 = Instance.new("UICorner")
	GUIObject.ShirtGraphicTextbox = Instance.new("TextBox")
	GUIObject.UIGradient_30 = Instance.new("UIGradient")
	GUIObject.Edit = Instance.new("Frame")
	GUIObject.MeshNameFrame = Instance.new("Frame")
	GUIObject.UICorner_32 = Instance.new("UICorner")
	GUIObject.MeshNameTextbox = Instance.new("TextBox")
	GUIObject.UIGradient_31 = Instance.new("UIGradient")
	GUIObject.PropertyListFrame = Instance.new("ScrollingFrame")
	GUIObject.UIGridLayout_4 = Instance.new("UIGridLayout")
	GUIObject.EditNote = Instance.new("TextLabel")
	GUIObject.CharacterPreviewFrame = Instance.new("Frame")
	GUIObject.ViewportFrame = Instance.new("ViewportFrame")
	GUIObject.ViewportCamera = Instance.new("Camera")
	GUIObject.PreviewUIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
	GUIObject.PreviewButton = Instance.new("TextButton")
	GUIObject.ClickExecuteFrame = Instance.new("Frame")
	GUIObject.UIGradientCE = Instance.new("UIGradient")
	GUIObject.UICornerCE = Instance.new("UICorner")
	GUIObject.ClickExecuteButton = Instance.new("TextButton")
	GUIObject.PositionPhysicsMultiplyFrame = Instance.new("Frame")
	GUIObject.UICornerPPM = Instance.new("UICorner")
	GUIObject.PositionPhysicsMultiplyText = Instance.new("TextBox")
	GUIObject.UIGradientPPM = Instance.new("UIGradient")
	GUIObject.RotationPhysicsMultiplyFrame = Instance.new("Frame")
	GUIObject.UICornerRPM = Instance.new("UICorner")
	GUIObject.RotationPhysicsMultiplyText = Instance.new("TextBox")
	GUIObject.UIGradientRPM = Instance.new("UIGradient")
	GUIObject.MobileCloseButtonScreen = Instance.new("ScreenGui")
	GUIObject.MobileCloseButton = Instance.new("ImageButton")
	GUIObject.MCBUIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
	GUIObject.SkinToneFrame = Instance.new("Frame")
	GUIObject.STUICorner = Instance.new("UICorner")
	GUIObject.SkinToneText = Instance.new("TextBox")
	GUIObject.STUIGradient = Instance.new("UIGradient")
	GUIObject.NippleColorFrame = Instance.new("Frame")
	GUIObject.NTUICorner = Instance.new("UICorner")
	GUIObject.NippleColorText = Instance.new("TextBox")
	GUIObject.NTUIGradient = Instance.new("UIGradient")

	GUIObject.Menu3_3 = Instance.new("Frame")
	GUIObject.M3UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
	GUIObject.M3UICorner = Instance.new("UICorner")
	GUIObject.M3UIGradient = Instance.new("UIGradient")
	GUIObject.Menu3Button = Instance.new("TextButton")

	GUIObject.Menu3 = Instance.new("Frame")
	GUIObject.BreastsScaleFrame = Instance.new("Frame")
	GUIObject.BS1UICorner = Instance.new("UICorner")
	GUIObject.BreastsScaleText = Instance.new("TextBox")
	GUIObject.BS1UIGradient = Instance.new("UIGradient")
	GUIObject.ButtsScaleFrame = Instance.new("Frame")
	GUIObject.BS2UICorner = Instance.new("UICorner")
	GUIObject.BS2UIGradient = Instance.new("UIGradient")
	GUIObject.ButtsScaleText = Instance.new("TextBox")
	GUIObject.LegsScaleFrame = Instance.new("Frame")
	GUIObject.BS3UICorner = Instance.new("UICorner")
	GUIObject.BS3UIGradient = Instance.new("UIGradient")
	GUIObject.LegsScaleText = Instance.new("TextBox")

	GUIObject.OutfitIdFrame = Instance.new("Frame")
	GUIObject.UICornerUI = Instance.new("UICorner")
	GUIObject.OutfitIdTextbox = Instance.new("TextBox")
	GUIObject.UIGradientUI = Instance.new("UIGradient")

	GUIObject.TorsoTypeFrame = Instance.new("Frame")
	GUIObject.UIGradient_A1 = Instance.new("UIGradient")
	GUIObject.UICorner_A1 = Instance.new("UICorner")
	GUIObject.TorsoTypeButton = Instance.new("TextButton")
	GUIObject.ArmTypeFrame = Instance.new("Frame")
	GUIObject.UIGradient_A11 = Instance.new("UIGradient")
	GUIObject.UICorner_A11 = Instance.new("UICorner")
	GUIObject.ArmTypeButton = Instance.new("TextButton")
	GUIObject.LegsTypeFrame = Instance.new("Frame")
	GUIObject.UIGradient_A2 = Instance.new("UIGradient")
	GUIObject.UICorner_A2 = Instance.new("UICorner")
	GUIObject.LegsTypeButton = Instance.new("TextButton")
	GUIObject.ButtTypeFrame = Instance.new("Frame")
	GUIObject.UIGradient_A16 = Instance.new("UIGradient")
	GUIObject.UICorner_A16 = Instance.new("UICorner")
	GUIObject.ButtTypeButton = Instance.new("TextButton")

	GUIObject.HP = Instance.new("Frame")
	GUIObject.HPButton = Instance.new("TextButton")
	GUIObject.UIGradient_A3 = Instance.new("UIGradient")
	GUIObject.UIAspectRatioConstraint_A1 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_A3 = Instance.new("UICorner")
	GUIObject.HPFrame = Instance.new("Frame")

	GUIObject.FPFrame = Instance.new("Frame")
	GUIObject.UIGradient_A4 = Instance.new("UIGradient")
	GUIObject.UICorner_A4 = Instance.new("UICorner")
	GUIObject.FPExecute = Instance.new("TextButton")

	GUIObject.TopHPFrame = Instance.new("Frame")
	GUIObject.UIGradient_A5 = Instance.new("UIGradient")
	GUIObject.UICorner_A5 = Instance.new("UICorner")
	GUIObject.TopHPText = Instance.new("TextBox")

	GUIObject.BottomHPFrame = Instance.new("Frame")
	GUIObject.UIGradient_A6 = Instance.new("UIGradient")
	GUIObject.UICorner_A6 = Instance.new("UICorner")
	GUIObject.BottomHPText = Instance.new("TextBox")

	GUIObject.TopClothesFrame = Instance.new("Frame")
	GUIObject.UIGradient_A7 = Instance.new("UIGradient")
	GUIObject.UICorner_A7 = Instance.new("UICorner")
	GUIObject.TopClothesText = Instance.new("TextBox")

	GUIObject.BottomClothesFrame = Instance.new("Frame")
	GUIObject.UIGradient_A8 = Instance.new("UIGradient")
	GUIObject.UICorner_A8 = Instance.new("UICorner")
	GUIObject.BottomClothesText = Instance.new("TextBox")

	GUIObject.DamageFrame = Instance.new("Frame")
	GUIObject.UIGradient_A9 = Instance.new("UIGradient")
	GUIObject.UICorner_A9 = Instance.new("UICorner")
	GUIObject.DamageSFX = Instance.new("TextBox")

	GUIObject.VolumeFrame = Instance.new("Frame")
	GUIObject.UIGradient_A10 = Instance.new("UIGradient")
	GUIObject.UICorner_A10 = Instance.new("UICorner")
	GUIObject.VolumeText = Instance.new("TextBox")

	GUIObject.TPFrame = Instance.new("Frame")
	GUIObject.UIGradient_A12 = Instance.new("UIGradient")
	GUIObject.UICorner_A12 = Instance.new("UICorner")
	GUIObject.TPToggle = Instance.new("TextButton")
	GUIObject.PHFrame = Instance.new("Frame")
	GUIObject.UIGradient_A13 = Instance.new("UIGradient")
	GUIObject.UICorner_A13 = Instance.new("UICorner")
	GUIObject.PHToggle = Instance.new("TextButton")

	GUIObject.Recolor = Instance.new("Frame")
	GUIObject.RecolorButton = Instance.new("TextButton")
	GUIObject.UIGradient_A14 = Instance.new("UIGradient")
	GUIObject.UIAspectRatioConstraint_A2 = Instance.new("UIAspectRatioConstraint")
	GUIObject.UICorner_A14 = Instance.new("UICorner")
	GUIObject.RecolorFrame = Instance.new("Frame")
	GUIObject.RecolorListFrame = Instance.new("ScrollingFrame")
	GUIObject.UIGridLayout_A1 = Instance.new("UIGridLayout")

	GUIObject.GravityFrame = Instance.new("Frame")
	GUIObject.UIGradient_A15 = Instance.new("UIGradient")
	GUIObject.UICorner_A15 = Instance.new("UICorner")
	GUIObject.GravityButton = Instance.new("TextButton")

	GUIObject.BodyTransparencyFrame = Instance.new("Frame")
	GUIObject.UIGradient_A18 = Instance.new("UIGradient")
	GUIObject.UICorner_A18 = Instance.new("UICorner")
	GUIObject.BodyTransparencyButton = Instance.new("TextButton")

	GUIObject.HardcoreFrame = Instance.new("Frame")
	GUIObject.UIGradient_A19 = Instance.new("UIGradient")
	GUIObject.UICorner_A19 = Instance.new("UICorner")
	GUIObject.HardcoreToggle = Instance.new("TextButton")

	GUIObject.HatButton = Instance.new("ImageButton")

	-- variables --
	local Mouse = Player:GetMouse()

	local Method2CharacterFolder = game.Workspace:FindFirstChild("Method2CharacterFolder")

	if not Method2CharacterFolder then
		Method2CharacterFolder = Instance.new("Folder", game.Workspace)
		Method2CharacterFolder.Name = "Method2CharacterFolder"
	end

	local IS = game:GetService("InsertService")
	local UIS = game:GetService("UserInputService")
	local TS = game:GetService("TweenService")
	local MPS = game:GetService("MarketplaceService")

	local CVersion = "0.7.7:lerp()"

	local Method = 2
	local MaxMethod = 3

	local MaxBreastsType = 4
	local MaxTorsoType = 8
	local MaxArmType = 4
	local MaxLegsType = 5
	local MaxButtType = 3

	local KEYBIND = Enum.KeyCode.Insert
	local KeybindDetect = false

	local hpKEYBIND = Enum.KeyCode.Equals
	local hpKeybindDetect = false

	local ClickExecute = false

	local IsEnterFrame = false
	local IsMouseDown = false

	local GuiPositionStart = nil
	local MouseDownStart = nil

	local AllConnect = {}
	local MeshEditConnect = {}
	local Debug = false

	local SelectPlayer = Player.Name

	local DarkerColorPercentage = 17.75
	local Darker2ColorPercentage = 32.75

	local Circle = 2*math.pi
	local PreviewRotate = 0
	local PreviewRadius = 5
	local PreviewRotateSpeed = 200
	local CharacterPreviewLoading = false

	local NPCs = {}

	local PositionPhysicsMultiply = 1
	local RotationPhysicsMultiply = 4

	local Function = {Spring = {}}

	function Function.PlayerDataDefault()
		return {
			Character = nil,

			CurrentClothes = {},
			ClothesRecolor = {},
			CurrentBundle = "nil",
			AutoExecute = true,
			DelayTime = 1,
			Tone = "Base",
			BundleBodyColor = true,
			Face = true,
			MeshSizeLock = false,
			AccessorySizeLock = false,
			MeshBasePartInvisible = false,
			BodyPartPhysics = false,
			PhysicsObeyGravity = true,
			CatalogUsername = "",
			CatalogOutfitId = "",
			CatalogClothes = {
				Shirt = "",
				Pants = "",
				ShirtGraphic = "",
			},
			OldestClothings = {
				Shirt = nil,
				Pants = nil,
				ShirtGraphic = nil,
			},
			CatalogAccessory = {},
			CatalogRemove = {},
			SkinTone = nil,
			NippleColor = nil,
			CockScale = 1,
			BreastsScale = 1,
			ButtsScale = 1,
			LegsScale = 1,
			BreastsType = 1,
			TorsoType = 1,
			ArmType = 1,
			LegsType = 1,
			ButtType = 1,
			ToggleBBC = false,
			Cooldown = false,
			updateCooldown = false,
			FPsnap = false,
			FPerson = false,
			RealtimeBodyTransparency = true,
			OldTransparency = {},

			TopRipped = false,
			BottomRipped = false,
			SavedPreviousHP = 0,
			SavedTopHP = 0,
			SavedBottomHP = 0,
			Healing = false,
			HealProgress = 0,
			HardcoreHP = false,
			TopHP = "",
			BottomHP = "",
			HPClothes = {
				Shirt = "",
				Pants = ""
			},
			DamageSFX = "",
			Volume = 1,
			TearParticles = true,
			HealParticles = true,

			PartList = Function.PartListDefault(),

			LocalTransparency = {
				["Head"] = false,
				["Right Arm"] = false,
				["Left Arm"] = false,
				["Torso"] = false,
				["Right Leg"] = false,
				["Left Leg"] = false,
				["Hat"] = true
			},

			CurrentPartList = {
				Organ = {},
				Clothes = {},
				Accessory = {},
				TransparencyLink = {},
				ParentTransparency = {},
				RealtimeUpdateList = {
					["Mesh"] = {},
					["Accessory"] = {},
					["Special"] = {}
				},
				PartParent = {},
				BodyPartPhysics = {},
				AreolaDecal = {},
			},
			ConvertedPart = {}
		}
	end

	local R15Size = {
		["UpperTorso"] = Vector3.new(2, 1.6, 1),
		["UpperTorsoFemale"] = Vector3.new(2.043, 1.796, 1.01),
		["RightLowerArm"] = Vector3.new(1, 1.052, 1),
		["LeftLowerArm"] = Vector3.new(1, 1.052, 1),
		["RightLowerLeg"] = Vector3.new(1, 1.193, 1),
		["LeftLowerLeg"] = Vector3.new(1, 1.193, 1),
	}

	local R15Transparency = {
		"UpperTorso",
		"LowerTorso",
		"RightUpperArm",
		"RightLowerArm",
		"RightHand",
		"LeftUpperArm",
		"LeftLowerArm",
		"LeftHand",
		"RightUpperLeg",
		"RightLowerLeg",
		"RightFoot",
		"LeftUpperLeg",
		"LeftLowerLeg",
		"LeftFoot",
	}

	local R6Size = {
		["Head"] = Vector3.new(2, 1, 1),
		["Torso"] = Vector3.new(2, 2, 1),
		["Left Arm"] = Vector3.new(1, 2, 1),
		["Left Leg"] = Vector3.new(1, 2, 1),
		["Right Arm"] = Vector3.new(1, 2, 1),
		["Right Leg"] = Vector3.new(1, 2, 1),
	}

	local WeldCFrame = {
		["Torso"] = CFrame.new(0, -0.2, 0),
		["Right Arm"] = CFrame.new(0, 0.2, 0),
		["Left Arm"] = CFrame.new(0, 0.2, 0),
		["Right Leg"] = CFrame.new(0, 0.2, 0),
		["Left Leg"] = CFrame.new(0, 0.2, 0)
	}

	local ConvertPart = {
		["Torso"] = "UpperTorso",
		["Right Arm"] = "RightLowerArm",
		["Left Arm"] = "LeftLowerArm",
		["Right Leg"] = "RightLowerLeg",
		["Left Leg"] = "LeftLowerLeg"
	}

	local R6Mesh = {
		["TorsoMale"] = "rbxassetid://456901040",
		["TorsoFemale"] = "rbxassetid://9747912904",
		["Right Arm"] = "rbxassetid://5062992824",
		["Left Arm"] = "rbxassetid://5062992824",
		["Right Leg"] = "rbxassetid://5062992824",
		["Left Leg"] = "rbxassetid://5062992824"
	}

	--[[
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------

                                      ████████╗░█████╗░██████╗░██╗░░░░░███████╗
                                      ╚══██╔══╝██╔══██╗██╔══██╗██║░░░░░██╔════╝
                                      ░░░██║░░░███████║██████╦╝██║░░░░░█████╗░░
                                      ░░░██║░░░██╔══██║██╔══██╗██║░░░░░██╔══╝░░
                                      ░░░██║░░░██║░░██║██████╦╝███████╗███████╗
                                      ░░░╚═╝░░░╚═╝░░╚═╝╚═════╝░╚══════╝╚══════╝
                                  
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	]]

	function Function.PartListDefault()
		return {
			-- BODY PARTS
			["Torso"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["MeshId"] = "rbxasset://RClothesContent/13181228593.mesh",
				["Size"] = Vector3.new(2.04, 2.06, 1.06),
				["CFrame"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Left Leg"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Mesh",
				["MeshId"] = "rbxasset://RClothesContent/7332360863.mesh",
				["Size"] = Vector3.new(1.213, 2.18, 1.201),
				["CFrame"] = CFrame.new(-0.0359992981, 0.0627000332, 0.0440006256, -4.37113883e-08, 0, -1, 0, 0.999999881, 0, 1, 0, -4.37113883e-08),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Right Leg"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Mesh",
				["MeshId"] = "rbxasset://RClothesContent/7332415457.mesh",
				["Size"] = Vector3.new(1.213, 2.18, 1.201),
				["CFrame"] = CFrame.new(0.0359992981, 0.0627000332, 0.0440006256, -4.37113883e-08, 0, -1, 0, 0.999999881, 0, 1, 0, -4.37113883e-08),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Left Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Mesh",
				["MeshId"] = "rbxasset://RClothesContent/11617989163.mesh",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0.0349998474, 0, 0, -1, 0, -8.74227766e-08, 0, 0.999999881, 0, 8.74227766e-08, 0, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			},
			["Right Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Mesh",
				["MeshId"] = "rbxasset://RClothesContent/11617988681.mesh",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(-0.0349998474, 0, 0, -1, 0, -8.74227766e-08, 0, 0.999999881, 0, 8.74227766e-08, 0, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			},
			["Left Butt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt",
				["MeshId"] = "rbxasset://RClothesContent/13181475662.mesh",
				["Size"] = Vector3.new(1.252, 1.239, 1.263),
				["CFrame"] = CFrame.new(-0.532000542, -0.961999893, 0.328999966, -1, 3.52998995e-06, -5.08968776e-07, 3.69696932e-06, 1, -1.92065613e-06, 5.08962978e-07, -1.92066227e-06, -1),
				["CFrame1"] = CFrame.new(-0.0004, 0, 0.001),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "PantsTexture",
				["Scale"] = "ButtsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=800}
			},
			["Right Butt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt",
				["MeshId"] = "rbxasset://RClothesContent/13181475663.mesh",
				["Size"] = Vector3.new(1.252, 1.239, 1.263),
				["CFrame"] = CFrame.new(0.532000542, -0.961999893, 0.328999966, -1, 3.52998995e-06, -6.08968776e-07, 3.69696932e-06, 1, -1.92065613e-06, 6.08962978e-07, -1.92066227e-06, -1),
				["CFrame1"] = CFrame.new(0.0004, 0, 0.001),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "PantsTexture",
				["Scale"] = "ButtsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=800}
			},
			["Left Breast"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Breast",
				["MeshId"] = "rbxasset://RClothesContent/17645666081.mesh",
				["Size"] = Vector3.new(1.15, 1.403, 0.98),
				["CFrame"] = CFrame.new(-0.24647522, 0.635471106, -0.450698853, 0.320868134, 0.223423854, -0.920394123, -0.184720367, 0.967879057, 0.170553446, 0.928935945, 0.115290381, 0.351832479),
				["CFrame1"] = CFrame.new(0.200012207, 0.400005341, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "AreolaDecalCreate",
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			},
			["Right Breast"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Breast",
				["MeshId"] = "rbxasset://RClothesContent/17645666081.mesh",
				["Size"] = Vector3.new(1.15, 1.403, 0.98),
				["CFrame"] = CFrame.new(0.24647522, 0.635471106, -0.450698853, -0.320868134, -0.223423854, -0.920394123, -0.184720367, 0.967879057, -0.170553446, 0.928935945, 0.115290381, -0.351832479),
				["CFrame1"] = CFrame.new(0.200012207, 0.400005341, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "AreolaDecalCreate",
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			},
			["Left Nipple"] = {
				["Instance"] = "Mesh",
				["Name"] = "Nipple",
				["MeshId"] = "rbxasset://RClothesContent/17645756055.mesh",
				["Size"] = Vector3.new(0.129, 0.067, 0.129),
				["CFrame"] = CFrame.new(-0.572320938, -0.203234434, 0.00150489807, 0.000296547514, 0.999854326, -0.0170696471, -0.982211947, 0.0029140336, -0.18775323, -0.187775597, 0.0168216899, 0.982067883),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
				},
				["Function"] = "DarkPart",
				["Scale"] = "BreastsScale"
			},
			["Right Nipple"] = {
				["Instance"] = "Mesh",
				["Name"] = "Nipple",
				["MeshId"] = "rbxasset://RClothesContent/17645756055.mesh",
				["Size"] = Vector3.new(0.129, 0.067, 0.129),
				["CFrame"] = CFrame.new(-0.572320938, -0.203234434, 0.00150489807, -0.000296547514, 0.999854326, -0.0170696471, -0.982211947, 0.0029140336, 0.18775323, 0.187775597, 0.0168216899, 0.982067883),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
				},
				["Function"] = "DarkPart",
				["Scale"] = "BreastsScale"
			},
			["BBC Rod"] = {
				["Instance"] = "Mesh",
				["Name"] = "BBC Rod",
				["MeshId"] = "rbxassetid://14437003062",
				["Size"] = Vector3.new(0.565, 0.802, 1.98),
				["CFrame"] = CFrame.new(-0.077, -0.982, -0.233, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["CFrame1"] = CFrame.new(0, -0.2, 0.9, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "BBCRodPhysics",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame1"}

			},
			["BBC Tip"] = {
				["Instance"] = "Mesh",
				["Name"] = "BBC Tip",
				["MeshId"] = "rbxassetid://14437018423",
				["Size"] = Vector3.new(0.444, 0.313, 0.481),
				["CFrame"] = CFrame.new(0.017, 0.283, -0.838, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "BBC Rod",

				},
				["Function"] = "DarkPart",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame"}
			},
			["BBC Balls"] = {
				["Instance"] = "Mesh",
				["Name"] = "BBC Balls",
				["MeshId"] = "rbxassetid://14436718311",
				["Size"] = Vector3.new(1.036, 0.976, 0.592),
				["CFrame"] = CFrame.new(0.002, -0.441, 0.652, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "BBC Rod",

				},
				["Function"] = "BBCBallPhysics",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame"}
			},
			["EasterSack"] = {
				["Instance"] = "Mesh",
				["Name"] = "BBC Balls",
				["MeshId"] = "rbxasset://RClothesContent/74969809748782.mesh",
				["Size"] = Vector3.new(1.036, 0.976, 0.592),
				["CFrame"] = CFrame.new(0.002, -0.441, 0.652, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["TextureId"] = "rbxasset://RClothesContent/easter_balls_better.png",
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "BBC Rod",

				},
				["Function"] = "BBCBallPhysics",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame"}
			},
			["Cock"] = {
				["Instance"] = "Mesh",
				["Name"] = "Rod",
				["Size"] = Vector3.new(1.2970000505447388, 0.46000000834465027, 0.47099998593330383),
				["CFrame"] = CFrame.new(-0.0308074951, -0.971994877, -0.571624756, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),
				["CFrame1"] = CFrame.new(0.5, -0, 0.0379999988, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/RoCat Cock.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "BBCRodPhysics",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Balls"] = {
				["Instance"] = "Mesh",
				["Name"] = "Balls",
				["Size"] = Vector3.new(0.4475859999656677, 0.8527889847755432, 0.7235980033874512),
				["CFrame"] = CFrame.new(-0.0351104736, -0.967835665, -0.569778442, -6.90403394e-05, 1.09312105e-05, -1, 0.156382754, 0.987696528, 0, 0.987696528, -0.156382754, -6.99003576e-05),
				["CFrame1"] = CFrame.new(-1.52587927e-05, 0.299999237, 0.0345458984, 1.00000429, 1.04308157e-07, 4.76063741e-13, 3.27825546e-07, 1.00000226, 1.43209888e-11, -6.2847505e-12, -1.91024085e-10, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/RoCat Balls.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "BBCBallPhysics",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			},
			["Tip"] = {
				["Instance"] = "Mesh",
				["Name"] = "Tip",
				["Size"] = Vector3.new(0.37700000405311584, 0.328000009059906, 0.37400001287460327),
				["CFrame"] = CFrame.new(-0.621873856, 0.0263288021, 0.00502586365, -1, 3.88713488e-08, 2.91103174e-06, -1.36291813e-08, 0.999996185, -3.10204257e-07, -2.91137076e-06, -3.12861516e-07, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/RoCat Cocktip.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Rod",
				},
				["Function"] = "DarkPart",
				["Scale"] = "CockScale",
				["AdjustScale"] = {"Size", "CFrame"}
			},
			["Left Breast Type 2"] = {
				["Instance"] = "Part",
				["Name"] = "Left Breast",
				["Size"] = Vector3.new(0.8140669465065002, 0.8140669465065002, 0.8140669465065002),
				["CFrame"] = CFrame.new(0, 0.883000016, -0.344000012, -1, 0, 8.74227766e-08, 0, 1, 0, -8.74227766e-08, 0, -1),
				["CFrame1"] = CFrame.new(0.400000006, 0.600000024, -0.300000012, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Shape"] = Enum.PartType.Block,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = {"BreastsType2Mesh", "AreolaDecalType2Create"},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Right Breast Type 2"] = {
				["Instance"] = "Part",
				["Name"] = "Right Breast",
				["Size"] = Vector3.new(0.8140669465065002, 0.8140669465065002, 0.8140669465065002),
				["CFrame"] = CFrame.new(0, 0.883000016, -0.344000012, -1, 0, 8.74227766e-08, 0, 1, 0, -8.74227766e-08, 0, -1),
				["CFrame1"] = CFrame.new(-0.400024414, 0.600001335, -0.299987793, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Shape"] = Enum.PartType.Block,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = {"BreastsType2Mesh", "AreolaDecalType2Create"},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Right Breast Type 3"] = {
				["Instance"] = "Part",
				["Name"] = "Right Breast",
				["Size"] = Vector3.new(1.4028211832046509, 1.4687727689743042, 1.24605131149292),
				["CFrame"] = CFrame.new(0.215000004, 0.758000016, -0.268999994, -4.37113883e-08, 0, 1, 0, 1, 0, -1, 0, -4.37113883e-08),
				["CFrame1"] = CFrame.new(-0.299987793, 0.5, -0.200012207, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["Shape"] = Enum.PartType.Block,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = {"BreastsType3Mesh", "AreolaDecalType3Create"},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Left Breast Type 3"] = {
				["Instance"] = "Part",
				["Name"] = "Left Breast",
				["Size"] = Vector3.new(1.4028211832046509, 1.4687727689743042, 1.24605131149292),
				["CFrame"] = CFrame.new(-0.215000004, 0.758000016, -0.268999994, -4.37113883e-08, 5.22728624e-06, 1, 0, 1, 0, -1, 0, -4.37113883e-08),
				["CFrame1"] = CFrame.new(-0.299987793, 0.5, 0.200012207, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["Shape"] = Enum.PartType.Block,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = {"BreastsType3Mesh", "AreolaDecalType3Create"},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Left Nipple Type 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Nipple",
				["Size"] = Vector3.new(0.10870949923992157, 0.14377030730247498, 0.11643027514219284),
				["CFrame"] = CFrame.new(0.698000014, -0.256999999, -0.367000014, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/5270413936.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167.00000524520874, 169.00000512599945),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
				},
				["Function"] = "DarkPart",
				["Scale"] = "BreastsScale"
			}, 
			["Right Nipple Type 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Nipple",
				["Size"] = Vector3.new(0.10870949923992157, 0.14377030730247498, 0.11643027514219284),
				["CFrame"] = CFrame.new(0.698000014, -0.256999999, 0.367000014, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/5270413632.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167.00000524520874, 169.00000512599945),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
				},
				["Function"] = "DarkPart",
				["Scale"] = "BreastsScale"
			},
			["Right Breast Type 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Breast",
				["Size"] = Vector3.new(1.309288501739502, 1.3237565755844116, 1.0778127908706665),
				["CFrame"] = CFrame.new(0.2, 0.67, -0.435, -0.303515047, 0.0131401122, -0.95273608, 0.386091501, 0.915834308, -0.110366784, 0.871098161, -0.401341259, -0.283042789),
				["CFrame1"] = CFrame.new(0.400146484, 0.399963379, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7220038121.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = {"BreastsType3Mesh", "AreolaDecalType3Create"},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Left Breast Type 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Breast",
				["Size"] = Vector3.new(1.309288501739502, 1.3237565755844116, 1.0778127908706665),
				["CFrame"] = CFrame.new(-0.2, 0.67, -0.435, 0.373207688, -0.0456757545, -0.926622808, 0.386091858, 0.915835142, 0.110358819, 0.843593001, -0.398948252, 0.359431773),
				["CFrame1"] = CFrame.new(0.400146484, 0.399963379, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7220038121.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = {"BreastsType3Mesh", "AreolaDecalType3Create"},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame1"}
			}, 
			["Left Areola Type 4"] = {
				["Instance"] = "Part",
				["Name"] = "Areola",
				["Size"] = Vector3.new(0.4839892089366913, 0.48398923873901367, 0.17859317362308502),
				["CFrame"] = CFrame.new(-0.559692383, 0.0360107422, 0.0500183105, -0.115508914, 0.290242553, 0.949961782, -0.0913974494, 0.949200869, -0.301123828, -0.989094198, -0.121604398, -0.0831084549),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Shape"] = Enum.PartType.Block,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
				},
				["Function"] = {"DarkPart", "AreolaType4Mesh"},
				["Scale"] = "BreastsScale"
			}, 
			["Right Areola Type 4"] = {
				["Instance"] = "Part",
				["Name"] = "Areola",
				["Size"] = Vector3.new(0.48398923873901367, 0.48398929834365845, 0.17859318852424622),
				["CFrame"] = CFrame.new(-0.559631348, 0.0362243652, -0.0501708984, 0.0580038428, 0.306949109, 0.949959099, -0.0913976729, 0.949200273, -0.301123589, -0.994123936, -0.0693574548, 0.0831099451),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Shape"] = Enum.PartType.Block,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
				},
				["Function"] = {"DarkPart", "AreolaType4Mesh"},
				["Scale"] = "BreastsScale"
			}, 
			["Left Nipple Type 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Nipple",
				["Size"] = Vector3.new(0.11428011208772659, 0.163490429520607, 0.154353529214859),
				["CFrame"] = CFrame.new(-3.05175781e-05, 0, -0.0799560547, 0.468626767, -0.125764415, 0.87440002, 0.0493227318, -0.984550238, -0.16804342, 0.882020473, 0.12187916, -0.455186784),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7223274409.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Areola",
				},
				["Function"] = "DarkPart",
				["Scale"] = "BreastsScale"
			}, 
			["Right Nipple Type 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Nipple",
				["Size"] = Vector3.new(0.11428012698888779, 0.1634904444217682, 0.1543535441160202),
				["CFrame"] = CFrame.new(0.000122070312, -7.62939453e-06, -0.0800170898, 0.468629152, -0.125764504, 0.874397278, 0.0493227914, -0.984549701, -0.168042675, 0.882019937, 0.121878669, -0.455182761),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7223274409.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Areola",
				},
				["Function"] = "DarkPart",
				["Scale"] = "BreastsScale"
			}, 
			["Pussy Closed"] = {
				["Instance"] = "Mesh",
				["Name"] = "Pussy",
				["MeshId"] = "rbxasset://RClothesContent/17633723189.mesh",
				["Size"] = Vector3.new(0.82, 0.876, 0.825),
				["CFrame"] = CFrame.new(0, -0.925573111, -0.0344238281, -1, 0, 0, 1.1765762e-13, 1, 0, 0, 0, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Clitoris Closed"] = {
				["Instance"] = "Mesh",
				["Name"] = "Clitoris",
				["MeshId"] = "rbxasset://RClothesContent/17633756976.mesh",
				["Size"] = Vector3.new(0.016, 0.032, 0.013),
				["CFrame"] = CFrame.new(0, -0.0782728195, 0.396118164, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Pussy",
				},
				["Function"] = "DarkPart"
			},
			["Vulva Closed"] = {
				["Instance"] = "Mesh",
				["Name"] = "Vulva",
				["MeshId"] = "rbxasset://RClothesContent/17633771118.mesh",
				["Size"] = Vector3.new(0.049, 0.339, 0.569),
				["CFrame"] = CFrame.new(0, -0.231252432, 0.116136551, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Pussy",
				},
				["Function"] = "DarkPart"
			},
			["Vagina Closed"] = {
				["Instance"] = "Mesh",
				["Name"] = "Vagina",
				["MeshId"] = "rbxasset://RClothesContent/17633784085.mesh",
				["Size"] = Vector3.new(0.048, 0.357, 0.555),
				["CFrame"] = CFrame.new(0, -0.218520164, 0.12276268, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 89, 89)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Pussy",
				},
				["Function"] = "Dark2Part"
			},
			["Pussy Open"] = {
				["Instance"] = "Mesh",
				["Name"] = "Pussy",
				["Size"] = Vector3.new(0.8848919868469238, 0.8711600303649902, 0.8346620202064514),
				["CFrame"] = CFrame.new(-0.00100517273, -0.964430332, -0.0420532227, -0.999993682, 7.40205633e-06, -4.17192183e-07, 9.17161924e-06, 0.999999881, -1.33617547e-07, -4.1726986e-07, 1.33675684e-07, -1.00000024),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17108921573.mesh",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Clitoris Open"] = {
				["Instance"] = "Mesh",
				["Name"] = "Clitoris",
				["Size"] = Vector3.new(0.016096899285912514, 0.03247833997011185, 0.01232868805527687),
				["CFrame"] = CFrame.new(3.05175781e-05, -0.0711487532, 0.40284729, 0.999993682, 8.84806468e-07, 4.17230467e-07, 8.84806468e-07, 0.999999881, -1.33648342e-07, 4.17230467e-07, -1.33648342e-07, 1.00000024),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17108921543.mesh",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Pussy",
				},
				["Function"] = "DarkPart"
			}, 
			["Vulva Open"] = {
				["Instance"] = "Mesh",
				["Name"] = "Vulva",
				["Size"] = Vector3.new(0.5450000166893005, 0.375, 0.6100000143051147),
				["CFrame"] = CFrame.new(0.000427246094, -0.242344975, 0.102287292, 0.999993682, 8.84806468e-07, 4.17230467e-07, 8.84806468e-07, 0.999999881, -1.33648342e-07, 4.17230467e-07, -1.33648342e-07, 1.00000024),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17108921578.mesh",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 167, 169)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Pussy",
				},
				["Function"] = "DarkPart"
			}, 
			["Vagina Open"] = {
				["Instance"] = "Mesh",
				["Name"] = "Vagina",
				["Size"] = Vector3.new(0.5199980139732361, 0.4561500549316406, 0.6124080419540405),
				["CFrame"] = CFrame.new(0.000490188599, -0.203095198, 0.101016998, 0.999993682, 8.84806468e-07, 4.17230467e-07, 8.84806468e-07, 0.999999881, -1.33648342e-07, 4.17230467e-07, -1.33648342e-07, 1.00000024),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17108921539.mesh",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 89, 89)
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Pussy",
				},
				["Function"] = "Dark2Part"
			}, 
			["Torso2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["MeshId"] = "rbxasset://RClothesContent/137558328898044.mesh",
				["Size"] = Vector3.new(2.009, 2, 1.127),
				["CFrame"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Right Arm2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Mesh",
				["Size"] = Vector3.new(1.229590654373169, 2.055715322494507, 1.0100106000900269),
				["CFrame"] = CFrame.new(-0.0845117569, -0.000298976898, 0.000483512878, 1, -8.84762244e-07, 4.17234219e-07, 8.84762244e-07, 1, 1.33645642e-07, -4.17234361e-07, -1.33645287e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17873855289.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Right Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			}, 
			["Left Arm2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Mesh",
				["Size"] = Vector3.new(1.229590654373169, 2.055715322494507, 1.0100106000900269),
				["CFrame"] = CFrame.new(0.0504875183, -0.000301837921, 0.000484466553, 1, -8.84762244e-07, 4.17234219e-07, 8.84762244e-07, 1, 1.33645642e-07, -4.17234361e-07, -1.33645287e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17873855280.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Left Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			}, 
			["Torso3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["Size"] = Vector3.new(2.262770891189575, 2.165092706680298, 1.2769441604614258),
				["CFrame"] = CFrame.new(0.00048828125, -0.0753002167, 0.000483989716, 1, -8.84762244e-07, 4.17234219e-07, 8.84762244e-07, 1, 1.33645642e-07, -4.17234361e-07, -1.33645287e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17873855318.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			["Right Leg3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Mesh",
				["Size"] = Vector3.new(1.4192306995391846, 2.530543327331543, 1.411695957183838),
				["CFrame"] = CFrame.new(0.0505523682, 0.149428248, 0.050807476, 1, -8.84762244e-07, 4.17234219e-07, 8.84762244e-07, 1, 1.33645642e-07, -4.17234361e-07, -1.33645287e-07, 1),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17873855309.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			["Left Leg3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Mesh",
				["Size"] = Vector3.new(1.4192306995391846, 2.530543327331543, 1.411695957183838),
				["CFrame"] = CFrame.new(-0.049446106, 0.149427295, 0.0508079529, 1, -8.84762244e-07, 4.17234219e-07, 8.84762244e-07, 1, 1.33645642e-07, -4.17234361e-07, -1.33645287e-07, 1),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17873855322.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Left Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			["Torso4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["MeshId"] = "rbxasset://RClothesContent/7829803053.mesh",
				["Size"] = Vector3.new(2.009, 2, 1.127),
				["CFrame"] = CFrame.new(0, 0, 0, -1, 0, -8.74227766e-08, 0, 1, -0, 8.74227766e-08, -0, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Left Leg2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Mesh",
				["MeshId"] = "rbxasset://RClothesContent/9067190251.mesh",
				["Size"] = Vector3.new(1.402345895767212, 2.247053861618042, 1.5714069604873657),
				["CFrame"] = CFrame.new(-0.0995101929, 0.0462403297, 0.000484466553, -1, -8.84762244e-07, -4.17234219e-07, -8.84762244e-07, 1, -1.33645642e-07, 4.17234361e-07, -1.33645287e-07, -1),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Right Leg2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Mesh",
				["MeshId"] = "rbxasset://RClothesContent/9067191575.mesh",
				["Size"] = Vector3.new(1.399999976158142, 2.2464888095855713, 1.5719980001449585),
				["CFrame"] = CFrame.new(0.10049057, 0.0462414026, 0.000483989716, -1, -8.84762244e-07, -4.17234219e-07, -8.84762244e-07, 1, -1.33645642e-07, 4.17234361e-07, -1.33645287e-07, -1),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},

			["Torso5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["Size"] = Vector3.new(2, 2, 1),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://489667862",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			["Left Leg4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Mesh",
				["MeshId"] = "rbxassetid://488154609",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0,0,0),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Right Leg4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Mesh",
				["MeshId"] = "rbxassetid://488154808",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0,0,0),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Right Arm3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Mesh",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://488154808",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Right Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			}, 
			["Left Arm3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Mesh",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://488154609",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Left Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			}, 

			["Torso6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["Size"] = Vector3.new(2.035, 2.036, 1.125),
				["CFrame"] = CFrame.new(0, 0, -0.0405553579, -1, 0, 0, 0, 1, 0, 0, 0, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9329354422.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},
			["Right Arm4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Mesh",
				["Size"] = Vector3.new(1, 2.013, 1.114),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6143439194.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Right Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			}, 
			["Left Arm4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Mesh",
				["Size"] = Vector3.new(1, 2.013, 1.114),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6143427747.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Left Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "ShirtTexture"
			}, 

			["Torso7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["Size"] = Vector3.new(2.077857255935669, 1.998084545135498, 0.966502845287323),
				["CFrame"] = CFrame.new(0, 0.0520000458, 0, -1, -1.63851337e-06, 1.50995803e-07, -1.63851337e-06, 1, -1.11045296e-11, -1.50995803e-07, -1.13519385e-11, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/13755434958.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent",
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			},

			["Left Butt2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt",
				["MeshId"] = "rbxasset://RClothesContent/9067214532.mesh",
				["Size"] = Vector3.new(1.2358614206314087, 1.3677444458007812, 1.3591549396514893),
				["CFrame"] = CFrame.new(-0.48058036, -0.935174763, 0.246622816, -0.939691007, 0.342023283, -0.000989110908, 0.340629935, 0.936115921, 0.087511301, 0.0308568217, 0.0818966553, -0.996163011),
				["CFrame1"] = CFrame.new(-0.0004, 0, 0.001),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "PantsTexture",
				["Scale"] = "ButtsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=800}
			},
			["Right Butt2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt",
				["MeshId"] = "rbxasset://RClothesContent/9067214532.mesh",
				["Size"] = Vector3.new(1.2358601093292236, 1.3675915002822876, 1.359156847000122),
				["CFrame"] = CFrame.new(0.484511584, -0.935167909, 0.228578746, -0.939691842, -0.342021823, -0.000567939656, -0.340772927, 0.936116099, 0.0869510695, -0.0292075071, 0.0819007531, -0.996212423),
				["CFrame1"] = CFrame.new(0.0004, 0, 0.001),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "PantsTexture",
				["Scale"] = "ButtsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=800}
			},
			["Left Butt3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt",
				["MeshId"] = "rbxasset://RClothesContent/15333488402.mesh",
				["Size"] = Vector3.new(1.292526125907898, 1.421129584312439, 1.2406930923461914),
				["CFrame"] = CFrame.new(-0.5449543, -1.01682138, 0.493936539, -0.999996841, -4.42379047e-07, -2.08616072e-07, 4.42379076e-07, 0.99999994, -6.68224871e-08, -2.08616157e-07, 6.68224942e-08, -1.00000012),
				["CFrame1"] = CFrame.new(-0.0004, 0, 0.001),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "PantsTexture",
				["Scale"] = "ButtsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=800}
			},
			["Right Butt3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt",
				["MeshId"] = "rbxasset://RClothesContent/15333488459.mesh",
				["Size"] = Vector3.new(1.292526125907898, 1.4211293458938599, 1.2406928539276123),
				["CFrame"] = CFrame.new(0.544282913, -1.01682186, 0.493938446, -0.999996841, -4.42379047e-07, -2.08616072e-07, 4.42379076e-07, 0.99999994, -6.68224871e-08, -2.08616157e-07, 6.68224942e-08, -1.00000012),
				["CFrame1"] = CFrame.new(0.0004, 0, 0.001),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "PantsTexture",
				["Scale"] = "ButtsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=800}
			},

			["Right Leg5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Mesh",
				["MeshId"] = "rbxasset://RClothesContent/15689547573.mesh",
				["Size"] = Vector3.new(1.8530000448226929, 2.299999952316284, 1.8250000476837158),
				["CFrame"] = CFrame.new(0.101165771, 0.120700002, -0.0378417969, 0.0227066502, -8.84762244e-07, -0.999742389, 1.53700825e-07, 1, -8.81499716e-07, 0.999742389, -1.33645287e-07, 0.0227066502),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			["Left Leg5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Mesh",
				["MeshId"] = "rbxasset://RClothesContent/15689547567.mesh",
				["Size"] = Vector3.new(1.8530000448226929, 2.299999952316284, 1.8250000476837158),
				["CFrame"] = CFrame.new(-0.020614624, 0.120699167, -0.0112304688, 0.0227067191, -8.84762244e-07, -0.99974215, 1.53700853e-07, 1, -8.81499545e-07, 0.99974215, -1.33645287e-07, 0.0227067191),
				["CFrame1"] = CFrame.new(0, -0.001, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Leg"
				},
				["Scale"] = "LegsScale",
				["AdjustScale"] = {"Size", ["CFrame1"]=300},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			["Torso8"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Mesh",
				["MeshId"] = "rbxasset://RClothesContent/13085030579.mesh",
				["Size"] = Vector3.new(1.0990766286849976, 2.240330934524536, 2.252163887023926),
				["CFrame"] = CFrame.new(0.0160980225, -0.10021019, -0.0673675537, 0.00548222661, -7.65554717e-07, -0.999985158, 1.38493746e-07, 1, -7.64807226e-07, 0.999985158, -1.34298816e-07, 0.00548222661),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "PantsTexture"
			}, 
			-- CLOTHES PARTS
			["School Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "School Shirt",
				["MeshId"] = "rbxasset://RClothesContent/8708773284.mesh",
				["Size"] = Vector3.new(1.95, 1.237, 2.063),
				["CFrame"] = CFrame.new(0., 0.395723343, -0.401777267, -4.4567679e-07, 4.7127628e-06, -1, 1.06013331e-05, 1, 4.71275825e-06, 1, -1.06013313e-05, -4.4572667e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248, 248, 248)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["School Collor"] = {
				["Instance"] = "Mesh",
				["Name"] = "Collor",
				["MeshId"] = "rbxasset://RClothesContent/8708773488.mesh",
				["Size"] = Vector3.new(1.833, 0.681, 2.05),
				["CFrame"] = CFrame.new(0.0488710403, 0.292836428, -0.00204086304, 1, -7.24058646e-06, -2.78201196e-06, 8.68098778e-06, 0.999997139, -1.66889549e-06, 2.3908276e-06, -1.04128333e-06, 1.00000143),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17, 17, 17)
				},
				["Recolor"] = "Tertiary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "School Shirt",
				},
			},
			["School Bow"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bow",
				["MeshId"] = "rbxasset://RClothesContent/8708773674.mesh",
				["Size"] = Vector3.new(0.87, 1.255, 1.917),
				["CFrame"] = CFrame.new(-0.598809242, -0.0214169025, -0.00198173523, 1, -7.24058646e-06, -2.78201196e-06, 8.68098778e-06, 0.999997139, -1.66889549e-06, 2.3908276e-06, -1.04128333e-06, 1.00000143),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(117, 0, 0)
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "School Shirt",
				},
			},
			["Skirt 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Skirt",
				["MeshId"] = "rbxasset://RClothesContent/8609086938.mesh",
				["Size"] = Vector3.new(1.85, 1.405, 2.619),
				["CFrame"] = CFrame.new(-0.0003657341, -0.680291414, 0.209050179, -2.56359476e-06, -2.94868323e-06, -1.00000048, -2.50712965e-05, 0.999999046, -3.85198973e-06, 1, 2.55514824e-05, 1.07363007e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17, 17, 17)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Skirt 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Skirt",
				["MeshId"] = "rbxasset://RClothesContent/11389496406.mesh",
				["Size"] = Vector3.new(2.666, 1.507, 2.062),
				["CFrame"] = CFrame.new(0.0089969635, -0.731234312, 0.254065514, -1.00000048, 2.71013369e-06, 3.48198853e-07, 1.80675625e-06, 0.999999046, 9.60324201e-07, -4.78581001e-07, 1.44048965e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17, 17, 17)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["School Left Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Clothes",
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["Size"] = Vector3.new(1.089, 0.983, 1.051),
				["CFrame"] = CFrame.new(0.038, 0.517, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248, 248, 248)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
			},
			["School Right Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Clothes",
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["Size"] = Vector3.new(1.089, 0.983, 1.051),
				["CFrame"] = CFrame.new(-0.038, 0.517, 0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248, 248, 248)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
			},
			["Bra"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bra",
				["MeshId"] = "rbxasset://RClothesContent/11381019021.mesh",
				["Size"] = Vector3.new(1.86, 1.101, 1.868),
				["CFrame"] = CFrame.new(0.00900268555, 0.499922037, -0.390037537, -1, 5.42022599e-06, -8.69745577e-07, 5.42022826e-06, 1, -2.88098545e-06, 8.69729888e-07, -2.88098977e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248, 248, 248)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Panty"] = {
				["Instance"] = "Mesh",
				["Name"] = "Panty",
				["MeshId"] = "rbxasset://RClothesContent/11377850676.mesh",
				["Size"] = Vector3.new(1.783, 1.12, 1.484),
				["CFrame"] = CFrame.new(-1.90734863e-06, -0.912999868, 0.160000801, -1, 5.42022508e-06, -1.01899627e-06, 5.42022826e-06, 1, -2.88098499e-06, 1.01898058e-06, -2.88099e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248, 248, 248)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Apron 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Apron",
				["MeshId"] = "rbxasset://RClothesContent/6491183076.mesh",
				["Size"] = Vector3.new(1.893, 2.61, 1.989),
				["CFrame"] = CFrame.new(7.62939453e-06, -0.251567364, -0.391598701, -1.83562111e-06, 1.28747515e-05, 1, -6.72226906e-06, 1, -1.28747643e-05, -1, -6.72229271e-06, -1.83553448e-06),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(231, 231, 236)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Apron 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Apron",
				["MeshId"] = "rbxasset://RClothesContent/11405661031.mesh",
				["Size"] = Vector3.new(2.001, 3.588, 1.835),
				["CFrame"] = CFrame.new(0, -0.756999969, -0.472000122, -1, -3.24366835e-12, 1.50995803e-07, 3.24366835e-12, 1, -4.8978031e-19, -1.50995803e-07, 0, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(117, 0, 0)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Bodyless Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Shirt",
				["MeshId"] = "rbxasset://RClothesContent/9867233353.mesh",
				["Size"] = Vector3.new(2.121, 0.538, 1.158),
				["CFrame"] = CFrame.new(1.71661377e-05, 0.797148228, 0.00380325317, 1, 6.32340789e-06, -1.3013792e-07, -6.32385991e-06, 1, -4.80156132e-07, 1.3065187e-07, 4.80156814e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17,17,17)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			},
			["Bodyless Neck"] = {
				["Instance"] = "Mesh",
				["Name"] = "Neck",
				["MeshId"] = "rbxasset://RClothesContent/4342469442.mesh",
				["Size"] = Vector3.new(1.312, 0.301, 1.354),
				["CFrame"] = CFrame.new(0.00418663025, 1.09489012, 0.00360298157, 1, -5.37213937e-12, 6.13908924e-12, -5.37213937e-12, 1, -1.63373362e-23, 6.13908924e-12, -1.63373346e-23, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17,17,17)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			},
			["Bodyless Right Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sleeve",
				["MeshId"] = "rbxasset://RClothesContent/9867233367.mesh",
				["Size"] = Vector3.new(1.175, 1.87, 1.133),
				["CFrame"] = CFrame.new(-0.0374875069, 0.0970358849, 0, 1, 6.3234088e-06, -1.30139284e-07, -6.32385809e-06, 0.999999881, -4.80156075e-07, 1.30650506e-07, 4.80156814e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17,17,17)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Bodyless Left Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sleeve",
				["MeshId"] = "rbxasset://RClothesContent/9867233360.mesh",
				["Size"] = Vector3.new(1.175, 1.87, 1.133),
				["CFrame"] = CFrame.new(0.0415430069, 0.0967195034, 0.0065574646, 1, 6.3234138e-06, -1.30144741e-07, -6.32385309e-06, 0.999999881, -4.80156075e-07, 1.30645049e-07, 4.80156814e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17,17,17)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Dress Bra"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bra",
				["MeshId"] = "rbxasset://RClothesContent/8811986211.mesh",
				["TextureId"] = "rbxasset://RClothesContent/395191839.png",
				["Size"] = Vector3.new(2.054, 1.488, 2),
				["CFrame"] = CFrame.new(1.90734863e-05, 0.295036316, -0.409999847, 6.08214521e-07, 1.17440368e-05, -1, 2.40081545e-06, 1, 1.17440377e-05, 1, -2.4008225e-06, 6.08186326e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163, 162, 165)
				},
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Dress Rope"] = {
				["Instance"] = "Mesh",
				["Name"] = "Rope",
				["MeshId"] = "rbxasset://RClothesContent/8811988447.mesh",
				["Size"] = Vector3.new(1.463, 0.492, 1.826),
				["CFrame"] = CFrame.new(7.62939453e-06, -0.292956591, -0.172002792, 6.08214521e-07, 1.17440368e-05, -1, 2.40081545e-06, 1, 1.17440377e-05, 1, -2.4008225e-06, 6.08186326e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(204, 187, 198)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Dress Skirt In"] = {
				["Instance"] = "Mesh",
				["Name"] = "Skirt In",
				["MeshId"] = "rbxasset://RClothesContent/8811988165.mesh",
				["Size"] = Vector3.new(2.052, 1.423, 2.684),
				["CFrame"] = CFrame.new(3.81469727e-06, -0.948948383, 0.077996254, 6.08214521e-07, 1.17440368e-05, -1, 2.40081545e-06, 1, 1.17440377e-05, 1, -2.4008225e-06, 6.08186326e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(204, 187, 198)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Dress Skirt Out"] = {
				["Instance"] = "Mesh",
				["Name"] = "Skirt Out",
				["MeshId"] = "rbxasset://RClothesContent/8811987828.mesh",
				["TextureId"] = "rbxasset://RClothesContent/395191839.png",
				["Size"] = Vector3.new(2.139, 1.438, 2.702),
				["CFrame"] = CFrame.new(7.62939453e-06, -0.83894968, 0.0949964523, 6.08214521e-07, 1.17440368e-05, -1, 2.40081545e-06, 1, 1.17440377e-05, 1, -2.4008225e-06, 6.08186326e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163, 162, 165)
				},
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Birdly Dress"] = {
				["Instance"] = "Mesh",
				["Name"] = "Dress",
				["MeshId"] = "rbxasset://RClothesContent/8533956808.mesh",
				["Size"] = Vector3.new(2.55, 2.649, 2.777),
				["CFrame"] = CFrame.new(7.62939453e-06, -0.255959034, -0.136188507, -5.48989405e-08, -1.88403271e-09, -1, -4.65476489e-07, 1, -1.88494753e-09, 1, 4.65473931e-07, -5.48980879e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(34, 34, 34)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Birdly Dress Bottom"] = {
				["Instance"] = "Mesh",
				["Name"] = "Dress Bottom",
				["MeshId"] = "rbxasset://RClothesContent/8533957053.mesh",
				["Size"] = Vector3.new(2.253, 1.889, 3.177),
				["CFrame"] = CFrame.new(0.0135879517, -0.964025736, 0.237159729, -5.42543361e-08, 1.51019786e-09, -1, -4.65476489e-07, 1, -1.88494731e-09, 1, 4.92539243e-07, -5.55426922e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(219, 219, 219)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			},
			["Birdly Dress Sling"] = {
				["Instance"] = "Mesh",
				["Name"] = "Sling",
				["MeshId"] = "rbxasset://RClothesContent/8533957545.mesh",
				["Size"] = Vector3.new(2.003, 1.454, 1.783),
				["CFrame"] = CFrame.new(-0.0349998474, 0.305000067, -0.469562531, -4.3711843e-08, -1.44881884e-09, -1, -4.69112194e-07, 1, -1.44980017e-09, 1, 4.69109466e-07, -4.37109335e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(202, 203, 209)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Birdly Dress Mail 1"] = {
				["Instance"] = "Part",
				["Name"] = "Mail 1",
				["Shape"] = Enum.PartType.Cylinder,
				["Size"] = Vector3.new(0.313, 0.762, 0.704),
				["CFrame"] = CFrame.new(0.0663223267, -0.0400261879, 0.839624405, 0.57357651, -7.94940647e-08, 0.819150627, 0.819151998, -5.04924913e-07, -0.573575318, 4.75954096e-07, 1, -2.35058806e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(202, 203, 209)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Birdly Dress Mail 2"] = {
				["Instance"] = "Part",
				["Name"] = "Mail 2",
				["Shape"] = Enum.PartType.Cylinder,
				["Size"] = Vector3.new(0.308, 0.727, 0.693),
				["CFrame"] = CFrame.new(0.653236389, 0.786733389, 0.835962296, 0.57357651, -7.94940647e-08, 0.819150627, 0.819151998, -5.04924913e-07, -0.573575318, 4.75954096e-07, 1, -2.35058806e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(202, 203, 209)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Birdly Dress Mail 3"] = {
				["Instance"] = "Part",
				["Name"] = "Mail 3",
				["Shape"] = Enum.PartType.Cylinder,
				["Size"] = Vector3.new(2.126, 0.704, 0.681),
				["CFrame"] = CFrame.new(0.355201721, 0.356162071, 0.838983536, 0.57357651, -7.94940647e-08, 0.819150627, 0.819151998, -5.04924913e-07, -0.573575318, 4.75954096e-07, 1, -2.35058806e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(34, 34, 34)
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Birdly Dress Right Sleeve"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sleeve",
				["MeshId"] = "rbxasset://RClothesContent/8477756263.mesh",
				["Size"] = Vector3.new(1.068, 1.202, 1.052),
				["CFrame"] = CFrame.new(-0.0390014648, -0.245999813, 0.00850009918, 1.13686838e-13, 3.7566391e-13, 1, 3.41060459e-13, 0.999999881, 1.25221285e-13, -1, -1.02318154e-12, -3.41060513e-13),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(219, 219, 219)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Birdly Dress Right Sleeve 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sleeve 2",
				["MeshId"] = "rbxasset://RClothesContent/8533957322.mesh",
				["Size"] = Vector3.new(1.059, 0.947, 1.152),
				["CFrame"] = CFrame.new(-0.0125274658, -0.134218693, 0.00903892517, -4.9860995e-07, -1.62974948e-06, -0.999995708, -9.83640348e-06, 0.99999845, -2.19345497e-06, 1.00000191, 1.45387166e-05, -7.21604636e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(34, 34, 34)
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Arm",
				},
			},
			["Birdly Dress Left Sleeve"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sleeve",
				["MeshId"] = "rbxasset://RClothesContent/8477756263.mesh",
				["Size"] = Vector3.new(1.068, 1.202, 1.052),
				["CFrame"] = CFrame.new(0.0390014648, -0.250999689, 0.00899982452, -4.37112746e-08, -3.23716395e-13, 1, -1.59999963e-05, 0.999999881, 1.25221299e-13, -1, -1.6e-05, -4.37117293e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(219, 219, 219)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Birdly Dress Left Sleeve 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sleeve 2",
				["MeshId"] = "rbxasset://RClothesContent/8533957322.mesh",
				["Size"] = Vector3.new(1.059, 0.947, 1.152),
				["CFrame"] = CFrame.new(0.0060005188, -0.133999825, 0.00899982452, -4.37106387e-08, 2.26175061e-07, 1, 2.81108601e-06, 0.999999881, -2.26174407e-07, -1, 2.81108487e-06, -4.37117293e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(34, 34, 34)
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Arm",
				},
			},
			["Right Shoe"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe",
				["MeshId"] = "rbxasset://RClothesContent/6860788547.mesh",
				["Size"] = Vector3.new(1.108, 0.771, 1.15),
				["CFrame"] = CFrame.new(-7.62939453e-06, -0.689962208, 0.0800008774, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(34, 34, 34)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg",
				},
			},
			["Left Shoe"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe",
				["MeshId"] = "rbxasset://RClothesContent/6860787685.mesh",
				["Size"] = Vector3.new(1.108, 0.771, 1.15),
				["CFrame"] = CFrame.new(-7.62939453e-06, -0.689962208, 0.0800008774, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(34, 34, 34)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Leg",
				},
			},
			["Right Sock"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sock",
				["MeshId"] = "rbxasset://RClothesContent/6721517477.mesh",
				["Size"] = Vector3.new(1.296, 1.524, 1.189),
				["CFrame"] = CFrame.new(0.0279846191, -0.307503283, 0.0619983673, -4.37113883e-08, 0, 1, 0, 1, 0, -1, 0, -4.37113883e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237, 234, 234)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg",
				},
				["Function"] = "TurtleTexture"
			},
			["Left Sock"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sock",
				["MeshId"] = "rbxasset://RClothesContent/6721513769.mesh",
				["Size"] = Vector3.new(1.296, 1.524, 1.189),
				["CFrame"] = CFrame.new(-0.0279998779, -0.307499111, 0.0620002747, -4.37113883e-08, 0, 1, 0, 1, 0, -1, 0, -4.37113883e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237, 234, 234)
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Leg",
				},
				["Function"] = "TurtleTexture"
			},
			["Killer Sweater"] = {
				["Instance"] = "Mesh",
				["CFrame"] = CFrame.new(1.14440918e-05, -0.0547757149, -0.143913269, -1.00000191, 8.13039424e-06, -2.1779843e-07, 4.51686174e-06, 0.999996185, -4.80170343e-07, -3.03737522e-07, 1.44048386e-06, -1),
				["Color"] = {
					["Color"] = Color3.fromRGB(215, 215, 215),
					["Tone"] = "Base"
				},
				["Recolor"] = "Primary",
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/10080455422.mesh",
				["Name"] = "Sweater",
				["Parent"] = {
					[1] = "Torso"
				},
				["Size"] = Vector3.new(2.621, 2.224, 2.378),
				["Transparency"] = 0,
				["Function"] = "TurtleTexture"
			},
			["Killer Sweater Tie"] = {
				["Instance"] = "Mesh",
				["CFrame"] = CFrame.new(-6.48498535e-05, 0.589792967, -0.781671524, -1, 3.46809134e-06, 1.14109309e-06, 3.61355137e-06, 0.984807909, 0.173647463, -5.21532229e-07, 0.173647463, -0.984807909),
				["Color"] = {
					["Color"] = Color3.fromRGB(215, 215, 215),
					["Tone"] = "Base"
				},
				["Recolor"] = "Primary",
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/4729777667.mesh",
				["Name"] = "Tie",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Sweater"
				},
				["Size"] = Vector3.new(0.645, 1.120, 0.144),
				["Transparency"] = 0
			},
			["Killer Sweater Neck"] = {
				["Instance"] = "Mesh",
				["CFrame"] = CFrame.new(-7.62939453e-06, 1.13563347, -0.154616356, -1, 3.61355274e-06, 6.08947687e-07, 3.6135516e-06, 1, -1.92066636e-06, -6.08954679e-07, -1.92066432e-06, -1),
				["Color"] = {
					["Color"] = Color3.fromRGB(163, 162, 165),
					["Tone"] = "Base"
				},
				["Recolor"] = "Secondary",
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/4342469442.mesh",
				["Name"] = "Neck",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Sweater"
				},
				["Size"] = Vector3.new(1.209999918937683, 0.18462184071540833, 1.2289236783981323),
				["Transparency"] = 0
			},
			["Cow Bra"] = {
				["CFrame"] = CFrame.new(-0.00286865234, 0.475341082, -0.362598419, -6.51926314e-07, 1.17439922e-05, 1.00000191, -2.4008159e-06, 0.999996185, -8.13043971e-06, -1, -4.80170684e-07, -1.30372001e-07),
				["Color"] = {
					["Color"] = Color3.fromRGB(248, 248, 248),
					["Tone"] = "Base"
				},
				["Instance"] = "Mesh",
				["Material"] = Enum.Material.Fabric,
				["MeshId"] = "rbxasset://RClothesContent/6297176322.mesh",
				["Name"] = "Bra",
				["Parent"] = {
					[1] = "Torso"
				},
				["Size"] = Vector3.new(1.8829039335250854, 1.1392192840576172, 1.8722314834594727),
				["TextureId"] = "rbxasset://RClothesContent/12038926049.png",
				["Transparency"] = 0
			},
			["Cow Panty"] = {
				["CFrame"] = CFrame.new(5.7220459e-06, -0.986361265, 0.0423326492, -1.30375597e-07, 8.13039424e-06, 1.00000191, -4.80171025e-07, 0.999996185, -4.51686174e-06, -1, 1.44048408e-06, 3.91160427e-07),
				["Color"] = {
					["Color"] = Color3.fromRGB(248, 248, 248),
					["Tone"] = "Base"
				},
				["Instance"] = "Mesh",
				["Material"] = Enum.Material.Fabric,
				["MeshId"] = "rbxasset://RClothesContent/6297229742.mesh",
				["Name"] = "Panty",
				["Parent"] = {
					[1] = "Torso"
				},
				["Size"] = Vector3.new(1.1498957872390747, 0.9570162296295166, 1.8741321563720703),
				["TextureId"] = "rbxasset://RClothesContent/12038931250.png",
				["Transparency"] = 0
			},
			["Right Bunny Band"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Bunny Band",
				["Size"] = Vector3.new(1.0540573596954346, 0.4127587676048279, 1.6175404787063599),
				["CFrame"] = CFrame.new(0.249682188, -0.632135391, -0.000693321228, -1.30402327e-07, 9.93718913e-06, -1.00000191, -4.80150504e-07, 0.999996066, 6.32364572e-06, 1, 2.40081181e-06, -6.51925802e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6861074681.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Arm"
				},
				["Function"] = "BunnyBandPin"
			}, 
			["Bow"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bow",
				["Size"] = Vector3.new(0.4615969657897949, 0.24014821648597717, 0.14512182772159576),
				["CFrame"] = CFrame.new(-0.00239944458, 0.94911027, -0.584125519, 1.00000191, 7.52851292e-06, -6.48738978e-06, -6.32364663e-06, 0.766041756, -0.642784894, 6.51925802e-07, 0.642788827, 0.766043425),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/4596067364.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(25.000000409781933, 25.000000409781933, 25.000000409781933),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Left Bunny Band"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Bunny Band",
				["Size"] = Vector3.new(1.0540573596954346, 0.4127587676048279, 1.6175404787063599),
				["CFrame"] = CFrame.new(-0.250300884, -0.632102489, -0.000693321228, 1.30402327e-07, 9.93718913e-06, 1.00000191, 4.80150504e-07, 0.999996066, -6.32364572e-06, -1, 2.40081181e-06, 6.51925802e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6861074681.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Arm"
				},
				["Function"] = "BunnyBandPin"
			}, 
			["Bunny Tail"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bunny Tail",
				["Size"] = Vector3.new(0.4436146914958954, 0.38189801573753357, 0.4354999363422394),
				["CFrame"] = CFrame.new(-0.000400066376, -0.507106781, 0.837873459, -1.30402327e-07, 9.93718913e-06, -1.00000191, -4.80150561e-07, 0.999996185, 6.32364663e-06, 1, 2.40081181e-06, -6.51925802e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/5620377615.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Tertiary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Torso String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso String",
				["Size"] = Vector3.new(1.0775585174560547, 0.7826404571533203, 2.07892107963562),
				["CFrame"] = CFrame.new(-0.00040102005, -0.65, -0.00508785248, -1.30402327e-07, 9.93718913e-06, -1.00000191, -4.80150561e-07, 0.999996185, 6.32364663e-06, 1, 2.40081181e-06, -6.51925802e-07),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6859161870.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0,0,0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "StringTexture"
			}, 
			["Bunny Suit"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bunny Suit",
				["Size"] = Vector3.new(2.4018478393554688, 1.802707552909851, 1.9974936246871948),
				["CFrame"] = CFrame.new(-0.000400781631, -0.583568573, -0.142845154, -1.30402327e-07, 9.93718913e-06, -1.00000191, -4.80150561e-07, 0.999996185, 6.32364663e-06, 1, 2.40081181e-06, -6.51925802e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6858823726.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "ToarBreastsOffset"
			}, 
			["Bunny Ears"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bunny Ears",
				["Size"] = Vector3.new(1.9797463417053223, 1.5675334930419922, 0.9315749406814575),
				["CFrame"] = CFrame.new(-0.0499756336, 1.00000286, -0.400989532, 1.00000191, 9.93718913e-06, -1.30402327e-07, -6.32364663e-06, 0.999996185, -4.80150561e-07, 6.51925802e-07, 2.40081181e-06, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/227430350.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/709231552.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Right Leg String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg String",
				["MeshId"] = "Parent",
				["Size"] = "Overlay",
				["CFrame"] = CFrame.new(-0.000350952148, -2.38418579e-07, 0.000198364258, 1, -6.42401909e-10, 5.82085699e-11, 6.44266418e-10, 1, 3.74475617e-20, -5.82085699e-11, -5.42651863e-23, 1),
				--["Size"] = Vector3.new(1.2139999866485596, 2.180999994277954, 1.2020000219345093),
				--["CFrame"] = CFrame.new(0.036002636, 0.0627008677, 0.0440006256, 5.10434063e-07, 3.83933411e-06, -1.00000405, 2.04068738e-06, 0.999991536, -3.83933548e-06, 1, 2.0406876e-06, -5.97857024e-07),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				--["MeshId"] = "rbxasset://RClothesContent/7332415457.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0,0,0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Leg Mesh"
				},
				["Function"] = "StringTexture"
			}, 
			["Left Leg String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg String",
				["MeshId"] = "Parent",
				["Size"] = "Overlay",
				["CFrame"] = CFrame.new(-0.000350952148, -2.38418579e-07, 0.000198364258, 1, -6.42401909e-10, 5.82085699e-11, 6.44266418e-10, 1, 3.74475617e-20, -5.82085699e-11, -5.42651863e-23, 1),
				--["Size"] = Vector3.new(1.2139999866485596, 2.180999994277954, 1.2020000219345093),
				--["CFrame"] = CFrame.new(-0.0349985957, 0.0630007982, 0.0440015793, 5.10434063e-07, 3.83933411e-06, -1.00000405, 2.04068738e-06, 0.999991536, -3.83933548e-06, 1, 2.0406876e-06, -5.97857024e-07),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				--["MeshId"] = "rbxasset://RClothesContent/7332360863.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0,0,0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Leg Mesh"
				},
				["Function"] = "StringTexture"
			}, 
			["Left Butt String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt String",
				["MeshId"] = "Parent",
				["Size"] = "Overlay",
				--["Size"] = Vector3.new(1.253000020980835, 1.2400000095367432, 1.2640000581741333),
				["CFrame"] = CFrame.new(0,0,0),
				--["CFrame"] = CFrame.new(-0.531559527, -0.961991549, 0.329221725, -1.00000381, 3.73439707e-06, -5.2154769e-07, -3.73439661e-06, 0.999992371, -1.9206509e-06, -5.21547918e-07, 1.9206509e-06, -1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				--["MeshId"] = "rbxasset://RClothesContent/11617724988.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
				["Function"] = "StringTexture"
			}, 
			["Right Butt String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt String",
				["MeshId"] = "Parent",
				["Size"] = "Overlay",
				--["Size"] = Vector3.new(1.253000020980835, 1.2400000095367432, 1.2640000581741333),
				["CFrame"] = CFrame.new(0,0,0),
				--["CFrame"] = CFrame.new(0.531559527, -0.961991549, 0.329221725, 1.00000381, 3.73836701e-06, 5.21722257e-07, 3.73908415e-06, 0.999992371, 1.92064363e-06, 5.21373238e-07, 1.92065818e-06, 1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				--["MeshId"] = "rbxasset://RClothesContent/11617724536.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
				["Function"] = "StringTexture"
			}, 
			["Pussy String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Pussy String",
				["MeshId"] = "rbxasset://RClothesContent/17633723189.mesh",
				["Size"] = Vector3.new(0.825, 0.881, 0.83),
				["CFrame"] = CFrame.new(-0.00103759766, -0.925573111, -0.0344238281, -1, 0, 0, 1.1765762e-13, 1, 0, 0, 0, -1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "StringTexture"
			},
			["Kitty Bra"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Bra",
				["Size"] = Vector3.new(1.9721193313598633, 1.0569336414337158, 2.2100000381469727),
				["CFrame"] = CFrame.new(-0.0158348083, 0.137589216, -0.375313759, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755484302.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Ears"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Ears",
				["Size"] = Vector3.new(1.2489010095596313, 0.5518813133239746, 0.04031287133693695),
				["CFrame"] = CFrame.new(9.53674316e-06, 0.838002682, -0.133995056, 1.00000191, 6.32366346e-06, -3.91171568e-07, -2.71014164e-06, 0.999996185, -1.44047965e-06, 9.12697146e-07, 3.36114272e-06, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6552973009.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6552973038.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Right Kitty Band Black"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Kitty Band Black",
				["Size"] = Vector3.new(1.22230064868927, 0.24095074832439423, 1.1991701126098633),
				["CFrame"] = CFrame.new(0.0173130035, 0.400683284, 0.0307683945, 3.91171568e-07, 0.140735254, 0.990049183, 1.44047942e-06, 0.990043938, -0.140730858, -1, 3.4561358e-06, 4.30604814e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755489604.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Right Kitty Band Pink"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Kitty Band Pink",
				["Size"] = Vector3.new(1.2141307592391968, 0.14765559136867523, 1.189651608467102),
				["CFrame"] = CFrame.new(0.0169596672, 0.398624897, 0.0307683945, 3.91171568e-07, 0.140735254, 0.990049183, 1.44047942e-06, 0.990043938, -0.140730858, -1, 3.4561358e-06, 4.30604814e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755488785.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 145.00000655651093, 187.00000405311584),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Kitty Panty"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Panty",
				["Size"] = Vector3.new(1.4091557264328003, 1.1474609375, 1.8525354862213135),
				["CFrame"] = CFrame.new(-6.19888306e-06, -0.942862988, 0.134953499, 3.47460087e-07, 6.32366346e-06, 1.00000191, 1.44047976e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 8.68985751e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755486346.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Left Kitty Panty Paw"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Kitty Panty Paw",
				["Size"] = Vector3.new(0.2164660096168518, 0.17595499753952026, 0.17607498168945312),
				["CFrame"] = CFrame.new(-1.10927677, -0.976359367, -0.527161598, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755510910.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6755510955.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Left Kitty Panty String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Kitty Panty String",
				["Size"] = Vector3.new(0.24030999839305878, 0.4237639904022217, 0.22017496824264526),
				["CFrame"] = CFrame.new(-0.939169407, -0.702218771, -0.459594727, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755513230.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Right Kitty Panty Paw"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Kitty Panty Paw",
				["Size"] = Vector3.new(0.23073700070381165, 0.19345200061798096, 0.11431992053985596),
				["CFrame"] = CFrame.new(1.09738016, -0.995746374, -0.421038628, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755512558.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6755512610.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Right Kitty Panty String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Kitty Panty String",
				["Size"] = Vector3.new(0.19103001058101654, 0.4363189935684204, 0.2340969443321228),
				["CFrame"] = CFrame.new(0.958770752, -0.695994139, -0.425095558, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755511825.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Tail"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Tail",
				["Size"] = Vector3.new(1.6323256492614746, 2.419999837875366, 0.39649876952171326),
				["CFrame"] = CFrame.new(-0.0492196083, 0.450606108, 1.06449509, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/6747382163.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Black Collar"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Black Collar",
				["Size"] = Vector3.new(1.2043366432189941, 0.4051337242126465, 1.3428915739059448),
				["CFrame"] = CFrame.new(5.7220459e-06, 0.895759344, -0.0647373199, 1.00000191, 6.32366346e-06, -3.91171568e-07, -2.71014164e-06, 0.999996185, -1.44047965e-06, 9.12697146e-07, 3.36114272e-06, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/4487737814.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/4503276365.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Left Kitty Bra String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Kitty Bra String",
				["Size"] = Vector3.new(1.5687050819396973, 0.4173647165298462, 0.10608401894569397),
				["CFrame"] = CFrame.new(-0.600448608, 0.825362921, -0.182882309, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755487966.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Right Kitty Bra String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Kitty Bra String",
				["Size"] = Vector3.new(1.561113715171814, 0.4175761640071869, 0.10608401894569397),
				["CFrame"] = CFrame.new(0.568787098, 0.825255632, -0.179076195, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755487288.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Bra Top Whiskers"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Bra Top Whiskers",
				["Size"] = Vector3.new(0.05027654394507408, 0.09344801306724548, 0.8574493527412415),
				["CFrame"] = CFrame.new(-0.0150403976, 0.318082809, -1.26292038, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/6764807950.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 145.00000655651093, 187.00000405311584),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Bra Middle Whiskers"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Bra Middle Whiskers",
				["Size"] = Vector3.new(0.05217599868774414, 0.026417016983032227, 0.9154670238494873),
				["CFrame"] = CFrame.new(-0.0169978142, 0.197001457, -1.33299923, 3.47460087e-07, 6.32366346e-06, 1.00000191, 1.44047976e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 8.68985751e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/6764749054.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 145.00000655651093, 187.00000405311584),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Bra Bottom Whiskers"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Bra Bottom Whiskers",
				["Size"] = Vector3.new(0.05000000074505806, 0.10528962314128876, 0.7846659421920776),
				["CFrame"] = CFrame.new(-0.0162010193, 0.0697808266, -1.3160944, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755508155.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 145.00000655651093, 187.00000405311584),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Kitty Bra Cat"] = {
				["Instance"] = "Mesh",
				["Name"] = "Kitty Bra Cat",
				["Size"] = Vector3.new(0.23005041480064392, 0.5448338389396667, 0.5179228186607361),
				["CFrame"] = CFrame.new(-0.0158338547, 0.233896255, -1.20333481, 3.91171568e-07, 6.32366346e-06, 1.00000191, 1.44047965e-06, 0.999996185, -2.71014164e-06, -1, 3.36114272e-06, 9.12697146e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6755507454.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 145.00000655651093, 187.00000405311584),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Side Skirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Side Skirt",
				["Size"] = Vector3.new(2.3988521099090576, 1.9694759845733643, 1.7265270948410034),
				["CFrame"] = CFrame.new(-0.00039768219, -1.25011444, 0.194470406, -1.00000381, 5.42021326e-06, -1.30387627e-06, -1.80679251e-06, 0.999992371, -4.80162407e-06, 2.60781945e-07, -9.60322382e-07, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/5971239783.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Workwear Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Workwear Shirt",
				["Size"] = Vector3.new(2.166167736053467, 1.366474986076355, 1.8761940002441406),
				["CFrame"] = CFrame.new(1.90734863e-06, 0.343997478, -0.375999451, 1.00000191, 5.42023372e-06, 7.82324321e-07, -1.80671861e-06, 0.999996185, 2.88097726e-06, -2.60770037e-07, -9.60333523e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6671745090.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(63.000000044703484, 63.000000044703484, 63.000000044703484),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "FabricTexture"
			}, 
			["Left Workwear Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Workwear Arm",
				["Size"] = Vector3.new(1.1083070039749146, 1.8436574935913086, 1.108305811882019),
				["CFrame"] = CFrame.new(0.0396080017, 0.0808815956, -0.000538825989, -1.00000191, 5.42023372e-06, -7.82324321e-07, 1.80671839e-06, 0.999996066, -2.88097681e-06, 2.60770037e-07, -9.60333523e-07, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(63.000000044703484, 63.000000044703484, 63.000000044703484),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm"
				},
				["Function"] = "FabricTexture"
			}, 
			["Right Workwear Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Workwear Arm",
				["Size"] = Vector3.new(1.1083039045333862, 1.8441107273101807, 1.1083028316497803),
				["CFrame"] = CFrame.new(-0.040397644, 0.081091404, -0.000540733337, 1.00000191, 5.42023372e-06, 7.82324321e-07, -1.80671839e-06, 0.999996066, 2.88097681e-06, -2.60770037e-07, -9.60333523e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(63.000000044703484, 63.000000044703484, 63.000000044703484),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm"
				},
				["Function"] = "FabricTexture"
			},
			["Bodysuit"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bodysuit",
				["Size"] = Vector3.new(2.102139949798584, 2.4996907711029053, 2.250253915786743),
				["CFrame"] = CFrame.new(-0.00216674805, -0.184390783, -0.217723846, 1.00000191, 5.42023372e-06, 7.82324321e-07, -1.80671861e-06, 0.999996185, 2.88097726e-06, -2.60770037e-07, -9.60333523e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6671818838.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			},
			["String Bikini"] = {
				["Instance"] = "Mesh",
				["Name"] = "String Bikini",
				["Size"] = Vector3.new(1.3721306324005127, 2.5299999713897705, 2.2300000190734863),
				["CFrame"] = CFrame.new(-1.90734863e-06, -0.212999821, -0.229743958, 1, 1.35507053e-05, -1.30411507e-07, -1.35507053e-05, 1, -4.80143228e-07, 1.30405496e-07, 4.80145786e-07, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6745689310.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "ToarBreastsOffset"
			}, 
			["Left Cross Tape"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Cross Tape",
				["Size"] = Vector3.new(0.48899999260902405, 0.3409999907016754, 0.5080000162124634),
				["CFrame"] = CFrame.new(-0.492490768, -0.214658141, 0.00777053833, -0.147934914, -0.964880586, 0.217073083, -0.953003764, 0.197749659, 0.229518548, -0.264384061, -0.172917604, -0.94878912),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6567309030.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast"
				},
			}, 
			["Right Cross Tape"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Cross Tape",
				["Size"] = Vector3.new(0.48865801095962524, 0.34089401364326477, 0.5081570148468018),
				["CFrame"] = CFrame.new(-0.491999626, -0.215000153, -0.00799942017, 0.151539236, -0.967152357, 0.204088852, 0.95300144, 0.197756082, 0.229523182, -0.262343675, 0.159715176, 0.951665103),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6567308335.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast"
				},
			},
			["Bra 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bra 2",
				["Size"] = Vector3.new(1.8899999856948853, 1.4352024793624878, 2.078070640563965),
				["CFrame"] = CFrame.new(0, 0.343346596, -0.393656731, 1.26016982e-06, 9.03369892e-06, -1.00000191, 4.80163362e-06, 0.999996185, 5.42016687e-06, 1, -2.88100068e-06, 7.38593769e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6697964510.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Panty 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Panty 2",
				["Size"] = Vector3.new(1.789075255393982, 1.1999999284744263, 1.5199999809265137),
				["CFrame"] = CFrame.new(-9.53674316e-06, -0.942420244, 0.204673767, 1.00000191, 9.12287305e-06, -2.84610906e-07, -5.42016687e-06, 0.984804869, -0.173642576, -7.82305165e-07, 0.173645124, 0.984808266),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6668707772.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			},
			["Collar"] = {
				["Instance"] = "Mesh",
				["Name"] = "Collar",
				["Size"] = Vector3.new(1.5257108211517334, 0.3845224380493164, 1.297229528427124),
				["CFrame"] = CFrame.new(9.89437103e-06, 0.999995947, 1.90734863e-06, 1.00000191, 9.93718913e-06, -1.30402327e-07, -6.32364663e-06, 0.999996185, -4.80150561e-07, 6.51925802e-07, 2.40081181e-06, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/4857299880.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Breasts Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Breasts Shirt",
				["Size"] = Vector3.new(1.24, 1.355, 1.89),
				["CFrame"] = CFrame.new(0, 0.689, -0.419) * CFrame.Angles(0, math.rad(-90.75), math.rad(-10)),
				["CFrame1"] = CFrame.new(0, 0.3, 0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7606070501.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame", ["CFrame1"] = 4.5},
				["Function"] = {"TorsoShirtTexture", "BreastPhysics"}
			}, 
			["Breasts Pants"] = {
				["Instance"] = "Mesh",
				["Name"] = "Breasts Pants",
				["Size"] = Vector3.new(1.239, 1.354, 1.889),
				["CFrame"] = CFrame.new(0, 0.689, -0.419) * CFrame.Angles(0, math.rad(-90.75), math.rad(-10)),
				["CFrame1"] = CFrame.new(0, 0.3, 0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7606070501.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Scale"] = "BreastsScale",
				["AdjustScale"] = {"Size", "CFrame", ["CFrame1"] = 4.5},
				["Function"] = {"TorsoPantsTexture", "BreastPhysics"}
			},
			["Torso Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Shirt",
				["MeshId"] = "Parent",
				["Size"] = "Overlay",
				["CFrame"] = CFrame.new(-0.000350952148, -2.38418579e-07, 0.000198364258, 1, -6.42401909e-10, 5.82085699e-11, 6.44266418e-10, 1, 3.74475617e-20, -5.82085699e-11, -5.42651863e-23, 1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Torso Mesh"
				},
				["MeshBasePartTransparency"] = 1,
				["Function"] = "TorsoShirtTexture"
			},
			["Right Butt Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Shirt",
				--[[
				["MeshId"] = "rbxasset://RClothesContent/13181475636.mesh",
				["Size"] = Vector3.new(1.248, 0.563, 1.259),
				["CFrame"] = CFrame.new(0, 0.339, 0),
				["Scale"] = "ButtsScale",
				]]
				["MeshId"] = "Parent",
				["Size"] = "Underlay",
				["CFrame"] = CFrame.new(0, 0.01, 0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
				["Function"] = "TorsoShirtTexture"
			},
			["Left Butt Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Shirt",
				--[[
				["MeshId"] = "rbxasset://RClothesContent/13181475635.mesh",
				["Size"] = Vector3.new(1.248, 0.563, 1.259),
				["CFrame"] = CFrame.new(0, 0.339, 0),
				["Scale"] = "ButtsScale",
				]]
				["MeshId"] = "Parent",
				["Size"] = "Underlay",
				["CFrame"] = CFrame.new(0, 0.01, 0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
				["Function"] = "TorsoShirtTexture"
			},
			["Left Breast 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Breast 2",
				["Size"] = Vector3.new(1.242, 1.252, 0.993),
				["CFrame"] = CFrame.new(-0.00666618347, -0.00726795197, 0.34, 0.922279179, -0.191880912, 0.335533708, 0.0711436272, 0.937517881, 0.340585262, -0.379920751, -0.290244073, 0.878304482),
				--["CFrame"] = CFrame.new(-0.360874176, 0.38800168, -0.483547688, 0.36783731, 0.290563017, -0.883328319, -0.0900876448, 0.956592739, 0.27714473, 0.925514758, -0.0223651696, 0.378048182),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7220038121.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Breasts Shirt"
				},
				["Scale"] = "BreastsScale",
				["Function"] = "AreolaDecalCreate"
			},
			["Right Breast 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Breast 2",
				["Size"] = Vector3.new(1.242, 1.252, 0.993),
				["CFrame"] = CFrame.new(-0.00666618347, -0.00726795197, -0.34, 0.922279179, -0.191880912, -0.335533708, 0.0711436272, 0.937517881, -0.340585262, 0.379920751, 0.290244073, 0.878304482),
				--["CFrame"] = CFrame.new(0.360874176, 0.38800168, -0.483547688, -0.36783731, -0.290563017, -0.883328319, -0.0900876448, 0.956592739, -0.27714473, 0.925514758, -0.0223651696, -0.378048182),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7220038121.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Breasts Shirt"
				},
				["Scale"] = "BreastsScale",
				["Function"] = "AreolaDecalCreate"
			},
			["Left Sweater Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sweater Arm",
				["Size"] = Vector3.new(1.1462839841842651, 1.9422149658203125, 1.1462829113006592),
				["CFrame"] = CFrame.new(0.0349998474, 0.0500049591, 6.68022949e-07, 1, 3.61347907e-06, 5.2154661e-07, -3.61347952e-06, 0.999999881, 1.92065818e-06, -5.21539732e-07, -1.92066045e-06, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm"
				},
				["Function"] = "TurtleTexture"
			},
			["Sweater Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Sweater Shirt",
				["Size"] = Vector3.new(2.72, 2.401642084121704, 2.58),
				["CFrame"] = CFrame.new(-5.7220459e-06, -0.150007486, -0.0499997325, 4.77835215e-07, 3.61347907e-06, -1, 1.92065863e-06, 1, 3.61347998e-06, 1, -1.92066045e-06, 4.77828337e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8279606564.mesh",
				["TextureId"] = "rbxasset://RClothesContent/187645444.png",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "SurfaceTexture"
			},
			["Right Sweater Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sweater Arm",
				["Size"] = Vector3.new(1.1462839841842651, 1.9422149658203125, 1.1462829113006592),
				["CFrame"] = CFrame.new(-0.0349988937, 0.0499947071, -8.60088221e-07, 1, 3.61347907e-06, 5.2154661e-07, -3.61347952e-06, 0.999999881, 1.92065818e-06, -5.21539732e-07, -1.92066045e-06, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://6866262171",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm"
				},
				["Function"] = "TurtleTexture"
			},
			["Left Nipple Piercing 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.119, 0.234, 0.131),
				["CFrame"] = CFrame.new(-0.000124454498, 6.77108765e-05, 5.24520874e-05, -0.843650639, 0.0103908479, 0.536791861, -0.46789664, 0.476090997, -0.744587123, -0.26329869, -0.879334688, -0.39679274),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/8745487512.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.119, 0.234, 0.131),
				["CFrame"] = CFrame.new(-9.15527344e-05, -6.10351562e-05, 0.000244140625, 0.897830784, -0.402056038, -0.179584816, 0.0126717985, -0.384072006, 0.923216105, -0.440158159, -0.831167638, -0.339736879),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/8745487512.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.133, 0.102, 0.096),
				["CFrame"] = CFrame.new(0.0437135696, -0.0103340149, -0.00108528137, -0.0263926424, -0.725746155, -0.687458217, -0.00533926487, -0.687584579, 0.726083398, -0.99964118, 0.0228355527, 0.0142710507),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/4932869451.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.133, 0.102, 0.096),
				["CFrame"] = CFrame.new(0.0437135696, -0.0103340149, -0.00108528137, -0.0263926424, -0.725746155, -0.687458217, -0.00533926487, -0.687584579, 0.726083398, -0.99964118, 0.0228355527, 0.0142710507),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/4932869451.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.135, 0.12, 0.11),
				["CFrame"] = CFrame.new(0.0435810089, -0.0102119446, -0.000776290894, -0.0263970345, -0.725711107, -0.687493086, -0.00526610017, -0.687622249, 0.726049662, -0.999637723, 0.0227859654, 0.014329521),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/6773710025.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.135, 0.12, 0.11),
				["CFrame"] = CFrame.new(0.0435810089, -0.0102119446, -0.000776290894, -0.0263970345, -0.725711107, -0.687493086, -0.00526610017, -0.687622249, 0.726049662, -0.999637723, 0.0227859654, 0.014329521),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/6773710025.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.137, 0.135, 0.014),
				["CFrame"] = CFrame.new(0.0250000004, -0.00749999983, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12625658678.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.137, 0.135, 0.014),
				["CFrame"] = CFrame.new(0.0250000004, -0.00749999983, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12625658678.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.05, 0.135, 0.086),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/7791686946.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.05, 0.135, 0.086),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/7791686946.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.124, 0.125, 0.033),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/11394330816.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.124, 0.125, 0.033),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/11394330816.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.137, 0.091, 0.094),
				["CFrame"] = CFrame.new(0.0250000004, -0.00700000022, 0, 1.5048154e-07, -0.707106769, -0.707106829, 1.06770166e-07, -0.707106829, 0.707106769, -1, -1.81904426e-07, -3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/13050350514.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.137, 0.091, 0.094),
				["CFrame"] = CFrame.new(0.0250000004, -0.00700000022, 0, 1.5048154e-07, -0.707106769, -0.707106829, 1.06770166e-07, -0.707106829, 0.707106769, -1, -1.81904426e-07, -3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/13050350514.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 8"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.092, 0.19, 0.107),
				["CFrame"] = CFrame.new(0.0253143311, -0.00280761719, -0.0009765625, -0.517758846, 0.0350331329, -0.854810536, 0.845839381, -0.128981292, -0.517609715, -0.128386974, -0.991031468, 0.037148416),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/7063311226.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 8"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.092, 0.19, 0.107),
				["CFrame"] = CFrame.new(0.0253143311, -0.00280761719, -0.0009765625, -0.517758846, 0.0350331329, -0.854810536, 0.845839381, -0.128981292, -0.517609715, -0.128386974, -0.991031468, 0.037148416),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/7063311226.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 9"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.131, 0.162, 0.114),
				["CFrame"] = CFrame.new(0.0500000007, 0.00249999994, 0, -6.30587635e-08, -0.707106769, -0.707106829, -1.06770166e-07, -0.707106829, 0.707106769, -1, 1.20087179e-07, -3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12488261246.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 9"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.131, 0.162, 0.114),
				["CFrame"] = CFrame.new(0.0500000007, 0.00249999994, 0, -6.30587635e-08, -0.707106769, -0.707106829, -1.06770166e-07, -0.707106829, 0.707106769, -1, 1.20087179e-07, -3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12488261246.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 10"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.147, 0.095, 0.102),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, -0.707106769, 0, -0.707106769, 0.707106769, -1, 3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/13076200715.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 10"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.147, 0.095, 0.102),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, -0.707106769, 0, -0.707106769, 0.707106769, -1, 3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/13076200715.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 11"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.101, 0.182, 0.074),
				["CFrame"] = CFrame.new(0.0850000009, -0.0149999997, 0, -2.24199738e-07, -0.98480773, -0.173648342, -2.62201709e-08, -0.173648342, 0.98480773, -1, 2.25346724e-07, 1.31100855e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/8184647568.mesh",
				["TextureId"] = "rbxasset://RClothesContent/8184767343.png",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 11"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.101, 0.182, 0.074),
				["CFrame"] = CFrame.new(0.0850000009, -0.0149999997, 0, -2.24199738e-07, -0.98480773, -0.173648342, -2.62201709e-08, -0.173648342, 0.98480773, -1, 2.25346724e-07, 1.31100855e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/8184647568.mesh",
				["TextureId"] = "rbxasset://RClothesContent/8184767343.png",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 12"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.148, 0.102, 0.094),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, 0.707106769, 0, -0.707106769, -0.707106769, 1, -3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12755883933.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 12"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.148, 0.102, 0.094),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, 0.707106769, 0, -0.707106769, -0.707106769, 1, -3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12755883933.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 13"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.153, 0.136, 0.128),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, -0.707106769, 0, 0.707106769, -0.707106769, 1, -3.09086197e-08, -3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12005265476.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 13"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.153, 0.136, 0.128),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, -0.707106769, 0, 0.707106769, -0.707106769, 1, -3.09086197e-08, -3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12005265476.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 14"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.148, 0.138, 0.113),
				["CFrame"] = CFrame.new(0.0500000007, 0, 0, -1.82268053e-07, -0.707106769, 0.707106829, -1.06770166e-07, -0.707106829, -0.707106769, 1, -2.04380882e-07, 5.3385083e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12576150000.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 14"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.148, 0.138, 0.113),
				["CFrame"] = CFrame.new(0.0500000007, 0, 0, -1.82268053e-07, -0.707106769, 0.707106829, -1.06770166e-07, -0.707106829, -0.707106769, 1, -2.04380882e-07, 5.3385083e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12576150000.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 15"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.174, 0.12, 0.112),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, 0.707106769, 0, -0.707106769, -0.707106769, 1, -3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12157209535.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 15"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.174, 0.12, 0.112),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, 0.707106769, 0, -0.707106769, -0.707106769, 1, -3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12157209535.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 16"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.144, 0.101, 0.108),
				["CFrame"] = CFrame.new(0.0250000004, -0.00700000022, 0, 1.36806619e-08, -0.707106769, -0.707106829, 6.18172393e-08, 0.707106829, -0.707106769, 1, -3.40377007e-08, 5.3385083e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12720313083.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 16"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.144, 0.101, 0.108),
				["CFrame"] = CFrame.new(0.0250000004, -0.00700000022, 0, 1.36806619e-08, -0.707106769, -0.707106829, 6.18172393e-08, 0.707106829, -0.707106769, 1, -3.40377007e-08, 5.3385083e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12720313083.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 17"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.165, 0.121, 0.111),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, 0.707106769, 0, -0.707106769, -0.707106769, 1, -3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/5385291202.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 17"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.165, 0.121, 0.111),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -4.37113883e-08, -0.707106769, 0.707106769, 0, -0.707106769, -0.707106769, 1, -3.09086197e-08, 3.09086197e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/5385291202.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 18"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.144, 0.128, 0.115),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -1.82268053e-07, -0.707106769, 0.707106829, -1.06770166e-07, -0.707106829, -0.707106769, 1, -2.04380882e-07, 5.3385083e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/7601850077.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 18"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.144, 0.128, 0.115),
				["CFrame"] = CFrame.new(0.0500000007, -0.00700000022, 0, -1.82268053e-07, -0.707106769, 0.707106829, -1.06770166e-07, -0.707106829, -0.707106769, 1, -2.04380882e-07, 5.3385083e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/7601850077.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 19"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.145, 0.214, 0.119),
				["CFrame"] = CFrame.new(0.075000003, -0.00700000022, 0, -4.37113883e-08, -0.866025448, -0.49999997, 0, 0.49999997, -0.866025448, 1, -3.78551732e-08, -2.18556924e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/11486064816.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 19"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.145, 0.214, 0.119),
				["CFrame"] = CFrame.new(0.075000003, -0.00700000022, 0, -4.37113883e-08, -0.866025448, -0.49999997, 0, 0.49999997, -0.866025448, 1, -3.78551732e-08, -2.18556924e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/11486064816.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Left Nipple Piercing 20"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.123, 0.294, 0.096),
				["CFrame"] = CFrame.new(0.0700000003, -0.00700000022, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12662159629.mesh",
				["TextureId"] = "rbxasset://RClothesContent/12662175794.png",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple"
				},
			},
			["Right Nipple Piercing 20"] = {
				["Instance"] = "Mesh",
				["Name"] = "Piercing",
				["Size"] = Vector3.new(0.123, 0.294, 0.096),
				["CFrame"] = CFrame.new(0.0700000003, -0.00700000022, 0, -4.37113883e-08, -1, 4.37113883e-08, 0, -4.37113883e-08, -1, 1, -4.37113883e-08, 1.91068547e-15),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/12662159629.mesh",
				["TextureId"] = "rbxasset://RClothesContent/12662175794.png",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple"
				},
			},
			["Armor"] = {
				["Instance"] = "Mesh",
				["Name"] = "Armor",
				["Size"] = Vector3.new(2.2660112380981445, 1.833153247833252, 2.1519999504089355),
				["CFrame"] = CFrame.new(0, 0.200000048, -0.412475586, -4.37121699e-08, 1.87848313e-13, -1, -1.25055521e-12, 1, 6.26161585e-14, 1, 3.75166564e-12, -4.37137331e-08),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6866883591.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6866883603.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "ToarBreastsOffset"
			},
			["Maid Left Arm Band"] = {
				["Instance"] = "Mesh",
				["Name"] = "Maid Left Arm Band",
				["Size"] = Vector3.new(1.080613136291504, 0.21970787644386292, 1.0806132555007935),
				["CFrame"] = CFrame.new(0.0307617188, 0.412641048, 0.00299072266, 1.09897246e-06, 1.28800411e-05, 0.999997139, -1.31012484e-06, 0.999996185, -1.06076859e-05, -0.999998212, 3.49747182e-07, -1.35971584e-06),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6771341341.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm"
				},
			}, 
			["Maid Left Arm Band 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Maid Left Arm Band 2",
				["Size"] = Vector3.new(1.0597753524780273, 0.4851457476615906, 1.0597742795944214),
				["CFrame"] = CFrame.new(0.0307617188, 0.415190697, 0.00299072266, 1.09897246e-06, 1.28800411e-05, 0.999997139, -1.31012484e-06, 0.999996185, -1.06076859e-05, -0.999998212, 3.49747182e-07, -1.35971584e-06),
				["Transparency"] = 0.3499999940395355,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6771345897.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Arm"
				},
			}, 
			["Maid Leg Band"] = {
				["Instance"] = "Mesh",
				["Name"] = "Maid Leg Band",
				["Size"] = Vector3.new(1.2040982246398926, 0.2598014175891876, 1.1960158348083496),
				["CFrame"] = CFrame.new(0.020690918, 0.338274598, 0.0269775391, 1.09897246e-06, 1.28800411e-05, 0.999997139, -1.31012484e-06, 0.999996185, -1.06076859e-05, -0.999998212, 3.49747182e-07, -1.35971584e-06),
				["Transparency"] = 0.3499999940395355,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6771356972.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Maid Leg Band Bow"] = {
				["Instance"] = "Mesh",
				["Name"] = "Maid Leg Band Bow",
				["Size"] = Vector3.new(0.46772417426109314, 0.39912867546081543, 0.11819032579660416),
				["CFrame"] = CFrame.new(0.0297241211, 0.189261675, -0.575317383, 0.999997139, 1.2926811e-05, 2.77690333e-08, -1.06076859e-05, 0.996190906, 0.0871559456, -1.35971584e-06, -0.0871544704, 0.996193111),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/6237876025.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6237701996.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Maid Right Arm Band 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Maid Right Arm Band 2",
				["Size"] = Vector3.new(1.0597753524780273, 0.4851457476615906, 1.0597742795944214),
				["CFrame"] = CFrame.new(-0.0392456055, 0.415163279, 0.00299072266, 1.09897246e-06, 1.28800411e-05, 0.999997139, -1.31012484e-06, 0.999996185, -1.06076859e-05, -0.999998212, 3.49747182e-07, -1.35971584e-06),
				["Transparency"] = 0.3499999940395355,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6771345897.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Arm"
				},
			}, 
			["Maid Right Arm Band"] = {
				["Instance"] = "Mesh",
				["Name"] = "Maid Right Arm Band",
				["Size"] = Vector3.new(1.080613136291504, 0.21970787644386292, 1.0806132555007935),
				["CFrame"] = CFrame.new(-0.0392456055, 0.41261363, 0.00299072266, 1.09897246e-06, 1.28800411e-05, 0.999997139, -1.31012484e-06, 0.999996185, -1.06076859e-05, -0.999998212, 3.49747182e-07, -1.35971584e-06),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6771341341.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm"
				},
			},
			["PussyCumAttacher"] = {
				["Instance"] = "Mesh",
				["Name"] = "PussyC",
				["Size"] = Vector3.new(0.8848919868469238, 0.8711600303649902, 0.8346620202064514),
				["CFrame"] = CFrame.new(-0.00100517273, -0.964430332, -0.0420532227, -0.999993682, 7.40205633e-06, -4.17192183e-07, 9.17161924e-06, 0.999999881, -1.33617547e-07, -4.1726986e-07, 1.33675684e-07, -1.00000024),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/17108921573.mesh",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Pussy Cum"] = {
				["Instance"] = "Mesh",
				["Name"] = "Pussy Cum",
				["Size"] = Vector3.new(0.5803003311157227, 1.487269401550293, 0.653281033039093),
				["CFrame"] = CFrame.new(-0.00202941895, -0.538755774, 0.0320339203, -1, 8.29489272e-06, -3.93924893e-11, 8.27883741e-06, 1, 2.73453864e-11, 3.93924893e-11, 2.73450602e-11, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/93789077116999.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "PussyC"
				},
				["Function"] = "CumDripDisplay"
			}, 
			["Pussy Cum Trailless"] = {
				["Instance"] = "Mesh",
				["Name"] = "Pussy Cum",
				["Size"] = Vector3.new(0.5803003311157227, 1.487269401550293, 0.653281033039093),
				["CFrame"] = CFrame.new(-0.00202941895, -0.538755774, 0.0320339203, -1, 8.29489272e-06, -3.93924893e-11, 8.27883741e-06, 1, 2.73453864e-11, 3.93924893e-11, 2.73450602e-11, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/93789077116999.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "PussyC"
				}
			}, 
			["Torso Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Cum 1",
				["Size"] = Vector3.new(1.897, 1.963, 1.21),
				["CFrame"] = CFrame.new(-0.106853485, 0.0230622292, -0.000331878662, 1, 5.76812259e-26, 0, 5.76812259e-26, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/116742308897287.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Torso Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso Cum 2",
				["Size"] = Vector3.new(2.168, 2.006, 1.204),
				["CFrame"] = CFrame.new(-0.00250244141, 0.019197464, -0.00451469421, 1, 2.88406129e-26, 0, 2.88406129e-26, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/134989273944289.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso"
				},
			}, 
			["Right Butt Cum2 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Cum2 1",
				["Size"] = Vector3.new(1.3999004364013672, 1.1739400625228882, 0.8418998718261719),
				["CFrame"] = CFrame.new(0.00823974609, 0.0469186306, -0.0775756836, -1, -1.37563238e-05, 6.08962978e-07, -1.39233034e-05, 1, -1.92066227e-06, -6.08935238e-07, -1.92066705e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/124409748030346.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
			}, 
			["Right Butt Cum2 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Cum2 2",
				["Size"] = Vector3.new(1.0894012451171875, 0.8902299404144287, 0.7180004119873047),
				["CFrame"] = CFrame.new(-0.10760498, 0.101624727, -0.373779297, -1, 4.05314222e-06, 6.08964342e-07, 3.1738175e-06, 1, -1.92067114e-06, -6.08966729e-07, -1.92064749e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/97919823001964.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
			}, 
			["Left Butt Cum2 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Cum2 1",
				["Size"] = Vector3.new(1.3999004364013672, 1.1739400625228882, 0.8418998718261719),
				["CFrame"] = CFrame.new(0.00823974609, 0.0469186306, -0.0775756836, -1, -1.37563238e-05, 6.08962978e-07, -1.39233034e-05, 1, -1.92066227e-06, -6.08935238e-07, -1.92066705e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/124409748030346.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
			}, 
			["Left Butt Cum2 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Cum2 2",
				["Size"] = Vector3.new(1.0894012451171875, 0.8902299404144287, 0.7180004119873047),
				["CFrame"] = CFrame.new(-0.10760498, 0.101624727, -0.373779297, -1, 4.05314222e-06, 6.08964342e-07, 3.1738175e-06, 1, -1.92067114e-06, -6.08966729e-07, -1.92064749e-06, -1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/97919823001964.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
			}, 
			["Left Leg Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Cum 1",
				["Size"] = Vector3.new(1.3149986267089844, 2.0903515815734863, 1.3302993774414062),
				["CFrame"] = CFrame.new(-0.0576171875, 0.0808916092, 0.0733642578, 1, 9.61663045e-06, -3.68424423e-11, -3.91788808e-06, 1, 2.41017956e-10, 1.50158809e-11, -1.02547082e-10, 1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/92395350432537.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg"
				},
			}, 
			["Left Leg Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Cum 2",
				["Size"] = Vector3.new(1.2453994750976562, 2.010192394256592, 1.0966987609863281),
				["CFrame"] = CFrame.new(0.0411376953, 0.0286072493, 0.0229492188, 1, 8.90428691e-06, -3.41141143e-11, -3.20554523e-06, 1, 2.23737515e-10, 1.22873265e-11, -8.52666895e-11, 1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/79202531181173.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg"
				},
			}, 
			["Left Leg Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Cum 3",
				["Size"] = Vector3.new(1.3429012298583984, 1.8412518501281738, 1.363698959350586),
				["CFrame"] = CFrame.new(-0.0220947266, 0.229360819, 0.0676269531, -1, 6.76725767e-06, 2.5929061e-11, -8.19194156e-06, 0.999999881, -1.71896053e-10, 3.14262331e-11, 1.90652966e-10, -1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/83679944172074.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg"
				},
			}, 
			["Left Leg Cum 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Leg Cum 4",
				["Size"] = Vector3.new(0.9825992584228516, 2.062309503555298, 1.1525993347167969),
				["CFrame"] = CFrame.new(0.173706055, 0.0612518787, -0.0537109375, 1, 9.97280131e-06, -3.8256058e-11, -4.27405939e-06, 1, 2.41472425e-10, 1.64295366e-11, -1.03001552e-10, 1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/90596906849364.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg"
				},
			}, 
			["Right Leg Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Cum 1",
				["Size"] = Vector3.new(1.2238998413085938, 2.049046039581299, 0.4566001892089844),
				["CFrame"] = CFrame.new(-0.0194091797, 0.0417599678, 0.48638916, -1, 0.000171318519, -4.36796235e-08, 0.000181291311, 1, 2.047435e-10, 4.37178507e-08, -4.48728277e-11, -1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/105937959636862.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Right Leg Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Cum 2",
				["Size"] = Vector3.new(1.344400405883789, 2.0599472522735596, 1.3069992065429688),
				["CFrame"] = CFrame.new(0.0360717773, 0.027289629, 0.0775756836, 1, 0.000186990059, 4.37397176e-08, -0.000186990059, 1, 1.75166048e-10, -4.37396857e-08, -1.83117535e-10, 1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/75884203722318.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Right Leg Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Leg Cum 3",
				["Size"] = Vector3.new(1.2632999420166016, 2.0255203247070312, 0.9050998687744141),
				["CFrame"] = CFrame.new(0.0109863281, -0.0138293505, -0.188842773, 1, 0.000182003656, 4.37205969e-08, -0.000191976447, 1, 5.39888828e-11, -4.37587815e-08, -3.04080205e-10, 1),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/118417825061565.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Right Leg"
				},
			}, 
			["Right Arm Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Cum 1",
				["Size"] = Vector3.new(1.1801013946533203, 2.184769868850708, 1.213399887084961),
				["CFrame"] = CFrame.new(-0.0297241211, -0.00793719292, -0.0162353516, 1, -5.48508253e-11, -3.41060513e-13, 5.24692442e-11, 1, 7.14060565e-14, 3.41060513e-13, 1.55967619e-13, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/125202318335961.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm"
				},
			}, 
			["Right Arm Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Cum 2",
				["Size"] = Vector3.new(1.1706008911132812, 1.9911398887634277, 1.2106990814208984),
				["CFrame"] = CFrame.new(-0.0294799805, 0.0965681076, -0.00408935547, 1, -5.48508253e-11, -3.41060513e-13, 5.24692442e-11, 1, 7.14060565e-14, 3.41060513e-13, 1.55967619e-13, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/83504910801572.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm"
				},
			}, 
			["Left Arm Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Cum 1",
				["Size"] = Vector3.new(1.159200668334961, 2.019089698791504, 1.202301025390625),
				["CFrame"] = CFrame.new(0.0450439453, 0.082224369, 0.0104980469, 1, -5.48508253e-11, -3.41060513e-13, 5.24692442e-11, 1, 7.14060565e-14, 3.41060513e-13, 1.55967619e-13, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/95320080609346.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm"
				},
			}, 
			["Left Arm Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Cum 2",
				["Size"] = Vector3.new(1.1226997375488281, 2.184769868850708, 1.1623001098632812),
				["CFrame"] = CFrame.new(0.0413818359, -0.00853848457, -0.00238037109, 1, -5.48508253e-11, -3.41060513e-13, 5.24692442e-11, 1, 7.14060565e-14, 3.41060513e-13, 1.55967619e-13, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/119168308079386.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm"
				},
			}, 
			["Face Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 2",
				["Size"] = Vector3.new(0.16119936108589172, 0.6649244427680969, 0.2429739236831665),
				["CFrame"] = CFrame.new(-0.422241211, 0.163582802, -0.427978516, -0.496243387, 0.165055707, 0.852343678, -0.0562241822, 0.973587394, -0.221271366, -0.866356492, -0.157726616, -0.473860145),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Face Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 3",
				["Size"] = Vector3.new(0.17822431027889252, 0.4747651219367981, 0.17150172591209412),
				["CFrame"] = CFrame.new(-0.177307129, 0.401250362, -0.555358887, -0.355953306, 0.934499025, -1.0984179e-06, 9.28247482e-06, 5.56737234e-09, -0.999998927, -0.934500456, -0.355956137, -9.1735601e-06),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Face Cum 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 4",
				["Size"] = Vector3.new(0.07113267481327057, 0.16356100142002106, 0.08625094592571259),
				["CFrame"] = CFrame.new(0.0985107422, -0.38054657, -0.576965332, 0.965921223, -5.12373163e-07, -0.258819193, 0.0268451702, 0.994606495, 0.100190066, 0.257421494, -0.103724286, 0.960714638),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Face Cum 5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 5",
				["Size"] = Vector3.new(0.09613265842199326, 0.4885610044002533, 0.13625092804431915),
				["CFrame"] = CFrame.new(0.43737793, -0.163431168, -0.373474121, 2.88029014e-07, 1.26513214e-06, 0.99999547, -0.0705631599, 0.997506678, -3.15570605e-06, -0.997505426, -0.0705628172, -2.0076036e-06),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Face Cum 6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 6",
				["Size"] = Vector3.new(0.16119936108589172, 0.37851041555404663, 0.14999999105930328),
				["CFrame"] = CFrame.new(0.352539062, -0.0939350128, -0.450317383, 0.666839063, 0.48791337, -0.563255787, -0.372748435, 0.872888863, 0.314836085, 0.645273268, 7.02903571e-06, 0.763949275),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Face Cum 7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 7",
				["Size"] = Vector3.new(0.16119936108589172, 0.464013934135437, 0.2429739236831665),
				["CFrame"] = CFrame.new(0.44128418, 0.244832039, -0.364379883, -2.02121782e-07, 0.288140208, -0.957583427, -8.72514192e-06, 0.957586229, 0.288143337, 0.999998033, 8.19637535e-06, 4.37895324e-06),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			}, 
			["Face Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum 1",
				["Size"] = Vector3.new(0.16119936108589172, 0.4367606043815613, 0.2429739236831665),
				["CFrame"] = CFrame.new(-0.251525879, -0.239318848, -0.54888916, 0.717032015, 0.345024675, -0.605651677, -0.137268469, 0.92177707, 0.362604737, 0.683384418, -0.176863149, 0.708308637),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			},
			["Left Breast Cum"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Breast Cum",
				["Size"] = Vector3.new(0.9000000357627869, 1.0029999017715454, 0.9050000905990601),
				["CFrame"] = CFrame.new(-0.168945312, -0.0475158691, -0.0146484375, -0.903787792, -0.421040893, 0.0767331123, -0.40288651, 0.897506237, 0.179342642, -0.144383878, 0.131173998, -0.980785906),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/7660134717.mesh",
				["DoubleSided"] = false,
				["Scale"] = "BreastsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast"
				},
			}, 
			["Right Breast Cum"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Breast Cum",
				["Size"] = Vector3.new(0.9000000357627869, 1.1029999256134033, 0.9300000667572021),
				["CFrame"] = CFrame.new(-0.136535645, -0.0603485107, 0.0240478516, -0.894259214, -0.415139675, -0.167196825, -0.399148285, 0.90878731, -0.121600553, 0.202425659, -0.0420068502, -0.978384972),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/7660134717.mesh",
				["DoubleSided"] = false,
				["Scale"] = "BreastsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast"
				},
			},
			["Left Breast Cum Type2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Breast Cum Type2",
				["Size"] = Vector3.new(1.1121561527252197, 1.180999755859375, 0.9050717949867249),
				["CFrame"] = CFrame.new(-0.0822753906, -0.077545166, -0.00912475586, -0.866024375, -0.481984288, 0.133011624, -0.500000715, 0.834820151, -0.230378717, -4.529953e-06, -0.266019404, -0.963965297),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/OX_7115693161.mesh",
				["DoubleSided"] = false,
				["Scale"] = "BreastsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast"
				},
			}, 
			["Right Breast Cum Type2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Breast Cum Type2",
				["Size"] = Vector3.new(1.076904296875, 1.1731266975402832, 0.9200000166893005),
				["CFrame"] = CFrame.new(-0.0802612305, -0.0796127319, 0.00048828125, -0.866026342, -0.499999702, 1.34110451e-06, -0.500000477, 0.866024554, 1.8812716e-06, 1.93715096e-06, -9.983778e-07, -0.999993801),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/OX_7115703261.mesh",
				["DoubleSided"] = false,
				["Scale"] = "BreastsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast"
				},
			}, 
			["Face Cum Type2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Face Cum Type2",
				["Size"] = Vector3.new(0.8184931874275208, 0.23144881427288055, 1.1218310594558716),
				["CFrame"] = CFrame.new(0.0479736328, -0.0687346458, -0.523132324, 0.999995232, 1.49011169e-06, -6.70550605e-07, -6.70550605e-07, 1.30384535e-07, 1, -1.49011169e-06, -0.999998212, -1.30384535e-07),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6720355129.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Head"
				},
			},
			["Left Butt Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Cum 1",
				["Size"] = Vector3.new(0.5180783271789551, 0.3023378252983093, 0.4937683343887329),
				["CFrame"] = CFrame.new(-0.0766601562, 0.514653921, -0.24230957, 0.787097275, -0.498641491, 0.363077641, 0.451583117, 0.866802633, 0.211485073, -0.420175463, -0.00249786698, 0.907437563),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/7004864019.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
			}, 
			["Left Butt Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Cum 2",
				["Size"] = Vector3.new(0.11107902973890305, 0.28349998593330383, 0.1674281358718872),
				["CFrame"] = CFrame.new(0.120727539, 0.514345884, -0.31817627, 0.999995232, 1.59744775e-06, -2.7102883e-06, -1.44849582e-06, 0.771619797, -0.63608402, -1.90503056e-06, 0.636083126, 0.771618247),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
			}, 
			["Left Butt Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Cum 3",
				["Size"] = Vector3.new(0.5300646424293518, 0.26003220677375793, 0.37633076310157776),
				["CFrame"] = CFrame.new(0.102844238, 0.38935113, -0.46282959, -0.938311875, 0.179826811, 0.295336485, -0.0692516118, 0.739090443, -0.670036972, -0.338769197, -0.649158537, -0.681047142),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/7004863745.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
			}, 
			["Left Butt Cum 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Butt Cum 4",
				["Size"] = Vector3.new(0.0997346043586731, 0.5813705325126648, 0.15032881498336792),
				["CFrame"] = CFrame.new(0.0443115234, 0.255191326, -0.58782959, 0.999995232, 2.68465783e-06, -1.64015682e-06, -1.44849582e-06, 0.980140269, -0.198305607, -1.90503056e-06, 0.198305503, 0.980138481),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
			}, 
			["Right Butt Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Cum 2",
				["Size"] = Vector3.new(0.0997346043586731, 0.5117958188056946, 0.15032881498336792),
				["CFrame"] = CFrame.new(0.237976074, 0.271583557, -0.505615234, 0.999995232, 2.44005037e-06, -2.04078469e-06, -1.4637908e-06, 0.94541508, -0.325868547, -1.845979e-06, 0.325868189, 0.945413351),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
			}, 
			["Right Butt Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Cum 3",
				["Size"] = Vector3.new(0.5180783271789551, 0.3023378252983093, 0.4937683343887329),
				["CFrame"] = CFrame.new(0.0971069336, 0.504099846, -0.206848145, 0.0925252661, 0.0484154634, 0.994527757, 0.202760041, 0.976973116, -0.0664230064, -0.974845827, 0.20779705, 0.0805752203),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/7004864019.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
			}, 
			["Right Butt Cum 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Cum 4",
				["Size"] = Vector3.new(0.0997346043586731, 0.37853536009788513, 0.15032881498336792),
				["CFrame"] = CFrame.new(-0.178894043, 0.144503593, -0.581176758, 0.999995232, 2.59762965e-06, -1.84204657e-06, -1.46700393e-06, 0.968367994, -0.24952662, -1.84463056e-06, 0.249526426, 0.968366146),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/6976475976.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
			}, 
			["Right Butt Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Butt Cum 1",
				["Size"] = Vector3.new(0.5300646424293518, 0.26003220677375793, 0.37633076310157776),
				["CFrame"] = CFrame.new(-0.123840332, 0.291390419, -0.522583008, 0.0280825775, -0.340392381, 0.939859033, -0.710923135, 0.654169858, 0.258166909, -0.702707767, -0.675418377, -0.223625451),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/7004863745.mesh",
				["DoubleSided"] = false,
				["Scale"] = "ButtsScale",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
			},
			["RightArm2 Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "RightArm2 Cum 1",
				["Size"] = Vector3.new(1.252504587173462, 2.2361180782318115, 1.213399887084961),
				["CFrame"] = CFrame.new(-0.0823383331, -0.0102884769, -0.0162353516, 0.994650841, -0.103276134, 0, 0.103276335, 0.994652808, 0, 0, 0, 0.999998033),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/125202318335961.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
			}, 
			["RightArm2 Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "RightArm2 Cum 2",
				["Size"] = Vector3.new(1.2119125127792358, 1.9911398887634277, 1.2106990814208984),
				["CFrame"] = CFrame.new(-0.119886398, 0.0890517235, -0.00408935547, 0.996276021, -0.0862001404, 0, 0.0862003118, 0.996277988, 0, 0, 0, 0.999998033),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/83504910801572.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
			}, 
			["Torso3 Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso3 Cum 2",
				["Size"] = Vector3.new(1.884933352470398, 1.9555860757827759, 1.2296398878097534),
				["CFrame"] = CFrame.new(-0.000686645508, -0.0060095787, -0.0635070801, 0.999998689, 2.8840576e-26, 0, 2.88406129e-26, 1, 0, 0, 0, 0.999998689),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/134989273944289.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Torso3 Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Torso3 Cum 1",
				["Size"] = Vector3.new(1.7728790044784546, 1.916404128074646, 1.3221521377563477),
				["CFrame"] = CFrame.new(0.0676631927, 6.31809235e-05, -0.0373191833, 0.999999344, 0, 0, 0, 0.999234259, -0.0391268283, 0, 0.0391268283, 0.999231637),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/116742308897287.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["LeftLeg3 Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "LeftLeg3 Cum 1",
				["Size"] = Vector3.new(1.5047883987426758, 2.392045736312866, 1.5222975015640259),
				["CFrame"] = CFrame.new(-0.0354804993, 0.111342311, 0.0753307343, 0.995205522, -0.0977662057, 0, 0.0977665931, 0.995209396, 0, 0, 0, 0.999996066),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/92395350432537.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["LeftLeg3 Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "LeftLeg3 Cum 2",
				["Size"] = Vector3.new(1.4104979038238525, 2.215325355529785, 1.2549819946289062),
				["CFrame"] = CFrame.new(0.0781288147, 0.035821557, 0.0176429749, 0.995205462, -0.0977669209, 0, 0.0977673158, 0.995209336, 0, 0, 0, 0.999996066),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/79202531181173.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["LeftLeg3 Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "LeftLeg3 Cum 3",
				["Size"] = Vector3.new(1.5367182493209839, 2.1069939136505127, 1.5605175495147705),
				["CFrame"] = CFrame.new(-0.0466079712, 0.283895731, 0.0687656403, -0.999892235, -0.0144098504, 0, -0.0144099072, 0.999896169, 0, 0, 0, -0.999996066),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/83679944172074.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["LeftLeg3 Cum 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "LeftLeg3 Cum 4",
				["Size"] = Vector3.new(1.3470991849899292, 2.2558815479278564, 1.297986388206482),
				["CFrame"] = CFrame.new(0.170196533, 0.0613889694, -0.0805625916, 0.998748839, -0.0499298647, 0, 0.0499300621, 0.998752773, 0, 0, 0, 0.999996066),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/90596906849364.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["RightLeg3 Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "RightLeg3 Cum 1",
				["Size"] = Vector3.new(1.369568109512329, 2.2929229736328125, 0.5757184028625488),
				["CFrame"] = CFrame.new(-0.0164585114, 0.0817826986, 0.509117126, -0.989584684, 0.143492222, 0.0113353021, 0.143936574, 0.986997843, 0.0715413019, -0.000922298874, 0.0724277273, -0.997371435),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/105937959636862.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Right Leg",
				},
			}, 
			["RightLeg3 Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "RightLeg3 Cum 2",
				["Size"] = Vector3.new(1.6039903163909912, 2.305121660232544, 1.4935210943222046),
				["CFrame"] = CFrame.new(0.046672821, 0.0744107962, 0.0671405792, 0.999674022, -0.0251320247, -0.00422650203, 0.0250301491, 0.999429941, -0.0226508547, 0.0047933613, 0.0225376748, 0.999732614),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/75884203722318.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Right Leg",
				},
			}, 
			["RightLeg3 Cum 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "RightLeg3 Cum 3",
				["Size"] = Vector3.new(1.413657546043396, 2.266597270965576, 1.0128246545791626),
				["CFrame"] = CFrame.new(0.0114574432, 0.0324647427, -0.247650146, 0.989580512, 0.143886238, -0.00422657933, -0.143946007, 0.989326298, -0.0226510186, 0.000922296196, 0.023023406, 0.999729991),
				["CFrame1"] = CFrame.new(0,-0.001,0),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/118417825061565.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Scale"] = "LegsScale",
				["AdjustScale"] = {["Size"]=1.4, ["CFrame1"]=300},
				["Parent"] = {
					[1] = "Right Leg",
				},
			}, 
			["LeftArm2 Cum 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "LeftArm2 Cum 2",
				["Size"] = Vector3.new(1.1597402095794678, 2.192622184753418, 1.1958216428756714),
				["CFrame"] = CFrame.new(0.0616283417, -0.0131552219, -0.0191383362, 0.994674206, 0.10305576, 0, -0.103055961, 0.994676173, 0, 0, 0, 0.999998033),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/119168308079386.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
			}, 
			["LeftArm2 Cum 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "LeftArm2 Cum 1",
				["Size"] = Vector3.new(1.2493823766708374, 2.0285511016845703, 1.2473194599151611),
				["CFrame"] = CFrame.new(0.07771492, 0.0861301422, 0.00582313538, 0.993857265, 0.110640615, 0, -0.110640831, 0.993859231, 0, 0, 0, 0.999998033),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Glass,
				["MeshId"] = "rbxasset://RClothesContent/95320080609346.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
			}, 
			["Right Round Cross Tape"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Round Cross Tape",
				["Size"] = Vector3.new(0.4668737053871155, 0.46883949637413025, 0.31550830602645874),
				["CFrame"] = CFrame.new(-0.437194824, -0.205078125, 0.0119628906, -0.320861846, -0.184718683, 0.928938448, -0.223419741, 0.967879891, 0.115291417, -0.920397341, -0.170550585, -0.351825505),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8447877878.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
				},
			}, 
			["Left Round Cross Tape"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Round Cross Tape",
				["Size"] = Vector3.new(0.4668915867805481, 0.46835005283355713, 0.31574997305870056),
				["CFrame"] = CFrame.new(-0.436035156, -0.207580566, 0.00335693359, 0.320874423, -0.184720829, 0.92893368, 0.223427966, 0.967878342, 0.115288086, -0.920390904, 0.170556754, 0.351839215),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8447851356.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
				},
			}, 
			["Jacket Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Jacket Shirt",
				["Size"] = Vector3.new(2.1246931552886963, 1.2849375009536743, 1.8374121189117432),
				["CFrame"] = CFrame.new(6.10351562e-05, 0.394865274, -0.360229492, 1, -3.35278219e-06, -7.45061106e-06, 3.35277741e-06, 1, -6.5194979e-07, 7.45061334e-06, 6.51924836e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/6885999097.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Right Jacket Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Jacket Arm",
				["Size"] = Vector3.new(1.0490915775299072, 1.0586410760879517, 0.9782295823097229),
				["CFrame"] = CFrame.new(-0.0333251953, 0.504268646, 0, -1, 3.50377809e-06, -7.45061106e-06, -3.50377331e-06, -1, -6.5194979e-07, -7.45061334e-06, -6.51923699e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/4803707231.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Left Jacket Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Jacket Arm",
				["Size"] = Vector3.new(1.0490915775299072, 1.0586410760879517, 0.9782295823097229),
				["CFrame"] = CFrame.new(0.0321044922, 0.504693747, 0, 1, 3.20178628e-06, 7.29961539e-06, 3.20178151e-06, -1, 6.51949222e-07, 7.29961766e-06, -6.5192603e-07, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/4803707231.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Left Jacket Arm 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Jacket Arm 2",
				["Size"] = Vector3.new(1.0604690313339233, 0.2345172017812729, 1.0229588747024536),
				["CFrame"] = CFrame.new(-6.10351562e-05, 0.41206646, -6.10351562e-05, 1.00000012, -1.16486223e-10, 0, -1.16486376e-10, 1, 1.00058062e-09, 0, 1.00058073e-09, 1.00000012),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/4803707231.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
					[2] = "Left Jacket Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Right Jacket Arm 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Jacket Arm 2",
				["Size"] = Vector3.new(1.0604690313339233, 0.2345172017812729, 1.0229588747024536),
				["CFrame"] = CFrame.new(-6.10351562e-05, 0.41206646, -6.10351562e-05, 1.00000012, -1.16244792e-10, 0, -1.16244792e-10, 1, 1.00044417e-09, 0, 1.00044417e-09, 1.00000012),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/4803707231.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
					[2] = "Right Jacket Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Dress 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Dress 2",
				["Size"] = Vector3.new(2.7847559452056885, 2.5671539306640625, 3.031595468521118),
				["CFrame"] = CFrame.new(0, -0.208409309, -0.0530395508, -7.49432184e-06, -3.35279583e-06, -1, -6.51851735e-07, 1, -3.35279105e-06, 1, 6.5182661e-07, -7.49432411e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8313398285.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Off Shoulder Hoodie Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Off Shoulder Hoodie Shirt",
				["Size"] = Vector3.new(2.699094772338867, 1.7776050567626953, 3.248256206512451),
				["CFrame"] = CFrame.new(0, -0.82975769, 0.0211181641, -7.49432184e-06, -3.35279469e-06, -1, -6.51860375e-07, 1, -3.35278992e-06, 1, 6.51835251e-07, -7.49432411e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8313398067.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Scarf"] = {
				["Instance"] = "Mesh",
				["Name"] = "Scarf",
				["Size"] = Vector3.new(1.4015450477600098, 0.787646472454071, 1.8566548824310303),
				["CFrame"] = CFrame.new(0, 0.971000195, -0.0109863281, -7.49432184e-06, -3.35279401e-06, -1, -6.48123716e-07, 1, -3.35278924e-06, 1, 6.48098592e-07, -7.49432411e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8371312822.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Left Off Shoulder Hoodie Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Off Shoulder Hoodie Arm",
				["Size"] = Vector3.new(1.12151038646698, 1.0230109691619873, 1.1215095520019531),
				["CFrame"] = CFrame.new(0.0349731445, -0.460499525, 0, 0.999995649, -3.20382128e-06, -7.70616225e-06, 3.23355698e-06, 1, -7.99406826e-06, 7.70619681e-06, 7.99412464e-06, 0.999995708),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Right Off Shoulder Hoodie Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Off Shoulder Hoodie Arm",
				["Size"] = Vector3.new(1.12151038646698, 1.0230109691619873, 1.1215095520019531),
				["CFrame"] = CFrame.new(-0.049987793, -0.460489511, 0, -0.999995708, -8.16582087e-06, 9.80021741e-06, -8.15093154e-06, 0.99999994, -6.73443901e-06, -9.80017194e-06, -6.73459681e-06, -0.999995708),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Left Off Shoulder Hoodie Arm 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Off Shoulder Hoodie Arm 2",
				["Size"] = Vector3.new(1.3092328310012817, 0.48147743940353394, 1.2631609439849854),
				["CFrame"] = CFrame.new(-0.00897216797, 0.425494671, 0, 0.984803438, 0.173647508, -2.55073701e-07, -0.173648238, 0.98480773, -7.38557173e-06, -1.03128741e-06, 7.31767796e-06, 0.999995708),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7980629618.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
					[2] = "Left Off Shoulder Hoodie Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Right Off Shoulder Hoodie Arm 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Off Shoulder Hoodie Arm 2",
				["Size"] = Vector3.new(1.3092328310012817, 0.48147743940353394, 1.2631609439849854),
				["CFrame"] = CFrame.new(-0.00897216797, 0.425494671, 0, 0.984803557, 0.173647508, -2.55073246e-07, -0.173648223, 0.98480767, -7.38556992e-06, -1.0312873e-06, 7.31767977e-06, 0.999995708),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/7980629618.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
					[2] = "Right Off Shoulder Hoodie Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Right Shoe 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe",
				["Size"] = Vector3.new(1.2970000505447388, 0.9210000038146973, 1.281999945640564),
				["CFrame"] = CFrame.new(0, -0.586998343, 0.0999755859, -7.4943232e-06, -3.41061286e-06, -1, -1.69796408e-07, 1, -3.41061173e-06, 1, 1.69770829e-07, -7.49432365e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/8915312843.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6888586040.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg",
				},
			}, 
			["Left Shoe 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe",
				["Size"] = Vector3.new(1.2969107627868652, 0.9213905334472656, 1.2823134660720825),
				["CFrame"] = CFrame.new(0, -0.587000251, 0.0999755859, -6.65991229e-06, -3.65386131e-06, -1, 1.46066986e-05, 1, -3.65395863e-06, 1, -1.46067232e-05, -6.65985863e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/8915312502.mesh",
				["DoubleSided"] = false,
				["TextureId"] = "rbxasset://RClothesContent/6888586040.png",
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["Short Hoodie"] = {
				["Instance"] = "Mesh",
				["Name"] = "Short Hoodie",
				["Size"] = Vector3.new(1.9278204441070557, 1.3146330118179321, 2.0916900634765625),
				["CFrame"] = CFrame.new(0, 0.419000626, -0.414001465, -7.49432866e-06, -3.58408306e-06, -1, 1.2767174e-06, 1, -3.58409261e-06, 1, -1.27674434e-06, -7.49432365e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8592346019.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Hood"] = {
				["Instance"] = "Mesh",
				["Name"] = "Hood",
				["Size"] = Vector3.new(1.8383543491363525, 0.9809532165527344, 1.5533300638198853),
				["CFrame"] = CFrame.new(0.321289062, 0.307279825, 0, 0.999998569, 3.3752076e-06, -2.47072336e-08, 2.95585778e-12, 1, -2.94368994e-13, -1.34934993e-07, -4.04803927e-07, 0.999998569),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8592346452.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(225.00000178813934, 162.00000554323196, 181.0000044107437),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Short Hoodie",
				},
			},
			["Left Shoe 3 Lower"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Lower",
				["Size"] = Vector3.new(1.2799999713897705, 0.3240000009536743, 1.156000018119812),
				["CFrame"] = CFrame.new(0.0310058594, 0.266000003, 0.0369873047, 1, 8.74227766e-08, 8.74227766e-08, 8.74227766e-08, -1, 0, 8.74227766e-08, 7.63972219e-15, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033680123.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(229.00000154972076, 229.00000154972076, 229.00000154972076),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Right Shoe 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3",
				["Size"] = Vector3.new(1.3413711786270142, 0.6485494375228882, 1.1897692680358887),
				["CFrame"] = CFrame.new(0, -0.783998132, 0, 1, -3.35278173e-06, -7.45059606e-06, 3.35277696e-06, 1, -6.5194979e-07, 7.45062653e-06, 6.51924836e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033692280.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg",
				},
			}, 
			["Left Shoe 3 Line"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Line",
				["Size"] = Vector3.new(1.3580000400543213, 0.25600001215934753, 1.2070000171661377),
				["CFrame"] = CFrame.new(0, -0.229000017, 0, 1, 5.08943965e-18, 0, 5.08943965e-18, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033858168.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3",
				["Size"] = Vector3.new(1.340999960899353, 0.6489999890327454, 1.190000057220459),
				["CFrame"] = CFrame.new(0, -0.783685327, 0.00378417969, 1, 3.44020441e-06, 7.53803306e-06, 3.44019963e-06, -1, 6.51891867e-07, 7.53803533e-06, -6.51866003e-07, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033822343.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["Left Shoe 3 Nurbs Path 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 1",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0299072266, -0.224247113, 0.547058105, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.76637888, 0.64238894, 0, 0.64238894, -0.76637888),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Tongue"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Tongue",
				["Size"] = Vector3.new(0.5189999938011169, 0.7070000171661377, 0.3840000033378601),
				["CFrame"] = CFrame.new(0.020690918, -0.0267600566, 0.366149902, 1, 5.08943965e-18, 0, 5.08943965e-18, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8965126164.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(230.00000149011612, 230.00000149011612, 230.00000149011612),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Right Shoe 3 Line"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Line",
				["Size"] = Vector3.new(1.3583815097808838, 0.25575077533721924, 1.206850528717041),
				["CFrame"] = CFrame.new(0, 0.229000002, 0, 1, 3.53166015e-21, 2.85549293e-11, 3.53166015e-21, 1, 2.52115767e-32, 2.85549293e-11, 2.52115767e-32, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033714666.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Lower"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Lower",
				["Size"] = Vector3.new(1.2799372673034668, 0.3243541717529297, 1.155938744544983),
				["CFrame"] = CFrame.new(-0.03125, -0.266092539, -0.0369873047, 1.00000429, 3.53166015e-21, 2.85550524e-11, 3.53167549e-21, 1, 2.52116855e-32, 2.85550524e-11, -2.77555756e-17, 1.00000429),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033680123.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 1",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.0308837891, -0.205637783, -0.558898926, -1.00000429, -1.92592157e-11, 2.10825402e-11, -3.53167549e-21, -0.738312185, -0.674459159, -2.85550524e-11, -0.67446202, 0.738315344),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 10"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 10",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.032409668, 0.0162534714, -0.558898926, -1.00000429, -1.82962239e-11, 2.19234873e-11, -3.53167549e-21, -0.767762125, -0.64073503, -2.85550524e-11, -0.640737832, 0.767765403),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 11"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 11",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.032409668, 0.241619349, -0.5546875, -1.00000429, -2.11587241e-11, 1.91754893e-11, -3.53167549e-21, -0.671527088, -0.740980089, -2.85550524e-11, -0.740983248, 0.671529949),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 12"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 12",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.032409668, 0.236827761, -0.556640625, -1.00000429, -1.83433581e-11, 2.18840675e-11, -3.53167549e-21, -0.766381621, -0.642385721, -2.85550524e-11, -0.642388523, 0.7663849),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 13"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 13",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.0308837891, -0.097597301, -0.556762695, -1.00000429, -2.19566275e-11, 1.82564398e-11, -3.53167549e-21, -0.639341772, -0.768922687, -2.85550524e-11, -0.768926024, 0.639344573),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 14"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 14",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.0308837891, -0.102301925, -0.558898926, -1.00000429, -1.92592157e-11, 2.10825402e-11, -3.53167549e-21, -0.738312185, -0.674459159, -2.85550524e-11, -0.67446202, 0.738315344),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 15"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 15",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.0308837891, -0.200933158, -0.556762695, -1.00000429, -2.19566275e-11, 1.82564398e-11, -3.53167549e-21, -0.639341772, -0.768922687, -2.85550524e-11, -0.768926024, 0.639344573),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 16"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 16",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.0308837891, -0.146044254, -0.556762695, -1.00000429, -2.19566275e-11, 1.82564398e-11, -3.53167549e-21, -0.639341772, -0.768922687, -2.85550524e-11, -0.768926024, 0.639344573),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 2",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.032409668, -0.0350132585, -0.556762695, -1.00000429, -2.19566275e-11, 1.82564398e-11, -3.53167549e-21, -0.639341772, -0.768922687, -2.85550524e-11, -0.768926024, 0.639344573),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 3",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.032409668, -0.039717868, -0.558898926, -1.00000429, -1.92592157e-11, 2.10825402e-11, -3.53167549e-21, -0.738312185, -0.674459159, -2.85550524e-11, -0.67446202, 0.738315344),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 4",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.032409668, 0.0837644339, -0.557006836, -1.00000429, -2.07467082e-11, 1.96205222e-11, -3.53167549e-21, -0.687112212, -0.726551235, -2.85550524e-11, -0.726554334, 0.687115133),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 5",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.032409668, 0.0789314806, -0.558898926, -1.00000429, -1.78744328e-11, 2.22687129e-11, -3.53167549e-21, -0.779851973, -0.625963986, -2.85550524e-11, -0.625966668, 0.779855311),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 6",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.032409668, 0.150958091, -0.548278809, -1.00000429, -2.19566275e-11, 1.82564398e-11, -3.53167549e-21, -0.639341772, -0.768922687, -2.85550524e-11, -0.768926024, 0.639344573),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 7",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.032409668, 0.14625451, -0.550476074, -1.00000429, -1.92592157e-11, 2.10825402e-11, -3.53167549e-21, -0.738312185, -0.674459159, -2.85550524e-11, -0.67446202, 0.738315344),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 8"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 8",
				["Size"] = Vector3.new(0.45041221380233765, 0.10332677513360977, 0.0839836597442627),
				["CFrame"] = CFrame.new(-0.0308837891, -0.150748864, -0.558898926, -1.00000429, -1.92592157e-11, 2.10825402e-11, -3.53167549e-21, -0.738312185, -0.674459159, -2.85550524e-11, -0.67446202, 0.738315344),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Nurbs Path 9"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Nurbs Path 9",
				["Size"] = Vector3.new(0.45041221380233765, 0.09745233505964279, 0.09584693610668182),
				["CFrame"] = CFrame.new(-0.032409668, 0.021050036, -0.556945801, -1.00000429, -2.11174342e-11, 1.92209512e-11, -3.53167549e-21, -0.673119068, -0.73953408, -2.85550524e-11, -0.739537239, 0.673121929),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Right Shoe 3 Tongue"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Shoe 3 Tongue",
				["Size"] = Vector3.new(0.5186595320701599, 0.7065155506134033, 0.3840503990650177),
				["CFrame"] = CFrame.new(-0.0209960938, 0.02700001, -0.366027832, 1, 3.53166015e-21, 2.85549293e-11, 3.53166015e-21, 1, 2.52115767e-32, 2.85549293e-11, 2.52115767e-32, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8964755042.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 10"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 10",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0299072266, -0.13410075, 0.538330078, -1, -7.10542736e-15, 0, -5.08943965e-18, 0.639338553, 0.768925428, 0, 0.768925428, -0.639338553),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 11"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 11",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0299072266, -0.229278401, 0.545043945, -1, 7.10542736e-15, 0, -5.08943965e-18, 0.671523869, 0.74098289, 0, 0.74098289, -0.671523869),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 12"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 12",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0314941406, 0.240260854, 0.549438477, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.738309264, 0.674462318, 0, 0.674462259, -0.738309324),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 13"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 13",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0299072266, 0.0611363053, 0.547180176, -1, -7.10542736e-15, 0, -5.08943965e-18, 0.639338553, 0.768925428, 0, 0.768925428, -0.639338553),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 14"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 14",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0314941406, 0.235321864, 0.547180176, -1, -7.10542736e-15, 0, -5.08943965e-18, 0.639338553, 0.768925428, 0, 0.768925428, -0.639338553),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 15"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 15",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0299072266, 0.0660752952, 0.549438477, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.738309264, 0.674462318, 0, 0.674462259, -0.738309324),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 16"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 16",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0299072266, -0.0584848672, 0.549438477, -1, -3.55271368e-15, 0, -5.08943965e-18, 0.77984935, 0.625967264, 0, 0.625967264, -0.779849291),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 2",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0314941406, 0.131777063, 0.549438477, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.738309264, 0.674462318, 0, 0.674462259, -0.738309324),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 3",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0299072266, 0.00731565058, 0.549438477, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.767759383, 0.640738249, 0, 0.640738308, -0.767759383),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 4",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0299072266, -0.12916173, 0.540588379, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.738309264, 0.674462318, 0, 0.674462259, -0.738309324),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 5",
				["Size"] = Vector3.new(0.47285038232803345, 0.10847420245409012, 0.0881674736738205),
				["CFrame"] = CFrame.new(0.0314941406, 0.182637557, 0.549438477, -1, 3.55271368e-15, 0, -5.08943965e-18, 0.738309264, 0.674462318, 0, 0.674462259, -0.738309324),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769902.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 6",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0299072266, 0.00228008628, 0.547424316, -1, 7.10542736e-15, 0, -5.08943965e-18, 0.673115909, 0.739537001, 0, 0.739536941, -0.673115969),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 7",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0314941406, 0.177698568, 0.547180176, -1, -7.10542736e-15, 0, -5.08943965e-18, 0.639338553, 0.768925428, 0, 0.768925428, -0.639338553),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 8"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 8",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0299072266, -0.0635585934, 0.547485352, -1, 0, 0, -5.08943965e-18, 0.687109172, 0.726554215, 0, 0.726554215, -0.687109172),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Shoe 3 Nurbs Path 9"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Shoe 3 Nurbs Path 9",
				["Size"] = Vector3.new(0.47285038232803345, 0.10230711847543716, 0.10062173753976822),
				["CFrame"] = CFrame.new(0.0314941406, 0.126838088, 0.547180176, -1, -7.10542736e-15, 0, -5.08943965e-18, 0.639338553, 0.768925428, 0, 0.768925428, -0.639338553),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Sand,
				["MeshId"] = "rbxasset://RClothesContent/8964769904.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Shoe 3",
				},
			}, 
			["Left Sock 2 Line"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sock 2 Line",
				["Size"] = Vector3.new(1.2200000286102295, 0.2630000114440918, 1.1399999856948853),
				["CFrame"] = CFrame.new(0.0109863281, -0.134000003, 0, 1, 5.08944089e-18, 0, 5.08944089e-18, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033508047.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Left Leg",
					[2] = "Left Sock 2",
				},
			}, 
			["Right Sock 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sock 2",
				["Size"] = Vector3.new(1.248340129852295, 1.6054649353027344, 1.1879241466522217),
				["CFrame"] = CFrame.new(0.0399780273, -0.379998088, 0.0289916992, 1, -3.34590186e-06, -7.45066836e-06, 3.34589708e-06, 1, -6.52313588e-07, 7.45067064e-06, 6.52288691e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033874623.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Leg",
				},
			}, 
			["Right Sock 2 Line"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sock 2 Line",
				["Size"] = Vector3.new(1.2200000286102295, 0.2627984881401062, 1.1399999856948853),
				["CFrame"] = CFrame.new(-0.0109863281, 0.134000003, 0, 1, 2.11755555e-20, 0, 2.11755555e-20, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033906005.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(237.0000010728836, 234.00000125169754, 234.00000125169754),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Right Leg",
					[2] = "Right Sock 2",
				},
			}, 
			["Left Sock 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sock 2",
				["Size"] = Vector3.new(1.2480000257492065, 1.6050000190734863, 1.187999963760376),
				["CFrame"] = CFrame.new(-0.0396118164, -0.379751742, 0.0290527344, 1, 3.44020441e-06, 7.53803306e-06, 3.44019963e-06, -1, 6.51891867e-07, 7.53803533e-06, -6.51866003e-07, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9033511985.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Leg",
				},
			}, 
			["Right Glove"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Glove",
				["Size"] = Vector3.new(1.1095958948135376, 0.5799999833106995, 1.1239572763442993),
				["CFrame"] = CFrame.new(-0.0235595703, -0.753230095, 0, 2.62359708e-06, 0.132776141, -0.991146207, 2.91995934e-06, 0.991146088, 0.132776126, 1, -3.24245821e-06, 2.21266691e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8914802954.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Left Glove"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Glove",
				["Size"] = Vector3.new(1.1100000143051147, 0.5799999833106995, 1.1236982345581055),
				["CFrame"] = CFrame.new(0.0233764648, -0.753238678, 0, 1.58050398e-06, -0.132768989, 0.991147161, -9.21357014e-07, 0.991147041, 0.132768974, -1, -5.64854076e-07, -2.72268881e-06),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8914802954.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Tanktop"] = {
				["Instance"] = "Mesh",
				["Name"] = "Tanktop",
				["Size"] = Vector3.new(2.1060984134674072, 1.2894705533981323, 1.8871744871139526),
				["CFrame"] = CFrame.new(-6.10351562e-05, 0.425208092, -0.37512207, 1, 3.61347907e-06, 5.2154661e-07, -3.61347998e-06, 1, 1.92065841e-06, -5.21539732e-07, -1.92066045e-06, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9020948490.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(14.000000115484, 12.000000234693289, 25.000000409781933),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Uncover Hoodie Breasts Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Breasts Shirt",
				["Size"] = Vector3.new(1.5199998617172241, 1.2713755369186401, 1.878353238105774),
				["CFrame"] = CFrame.new(-0.00048828125, 0.526566029, -0.476257324, 0, 1.15608044e-12, -1, 0, 1, -4.95463046e-13, 1, 0, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8896526740.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(159.0000057220459, 161.0000056028366, 172.00000494718552),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Uncover Hoodie Hoodie"] = {
				["Instance"] = "Mesh",
				["Name"] = "Hoodie",
				["Size"] = Vector3.new(1.7240039110183716, 0.9828771352767944, 1.639330506324768),
				["CFrame"] = CFrame.new(-0.00250244141, 0.815545082, 0.165344238, 0, 1.15608044e-12, -1, 0, 1, -4.95463046e-13, 1, 0, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8896528338.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(159.0000057220459, 161.0000056028366, 172.00000494718552),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Uncover Hoodie Ropes"] = {
				["Instance"] = "Mesh",
				["Name"] = "Ropes",
				["Size"] = Vector3.new(0.5868240594863892, 0.4892089068889618, 1.0775095224380493),
				["CFrame"] = CFrame.new(-0.00250244141, 0.864024162, -0.844543457, -2.35031166e-15, 1.15607805e-12, -1, -0.00203300011, 0.999997973, -4.95463046e-13, 0.999997973, 0.00203300011, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8896528503.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(202.00000315904617, 203.00000309944153, 209.00000274181366),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Uncover Hoodie Shirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "Shirt",
				["Size"] = Vector3.new(1.2195119857788086, 0.9750000238418579, 2.0747084617614746),
				["CFrame"] = CFrame.new(0.00152587891, 0.603111982, -0.0159301758, 0, 1.15608044e-12, 1, 0, 1, 4.95463046e-13, -1, 0, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/8896526539.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(159.0000057220459, 161.0000056028366, 172.00000494718552),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Uncover Hoodie Right Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Sleeve",
				["Size"] = Vector3.new(1.1956502199172974, 1.696764349937439, 1.1899999380111694),
				["CFrame"] = CFrame.new(-0.0390625, 0.234402895, 0.00048828125, 1, 1.15608044e-12, 0, 4.95463046e-13, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9867233367.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(159.0000057220459, 161.0000056028366, 172.00000494718552),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Uncover Hoodie Left Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Sleeve",
				["Size"] = Vector3.new(1.1897786855697632, 1.701037049293518, 1.209999918937683),
				["CFrame"] = CFrame.new(0.0385742188, 0.231792927, -0.0110473633, 1, 1.15608044e-12, 0, 4.95463046e-13, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/9867233360.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(159.0000057220459, 161.0000056028366, 172.00000494718552),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
				["Function"] = "TurtleTexture"
			},
			["Yoru Bra"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bra",
				["Size"] = Vector3.new(2.051358699798584, 0.5040243268013, 1.8845497369766235),
				["CFrame"] = CFrame.new(0, 0.138999701, -0.375, 1, 1.81669783e-12, 0, 1.65154457e-13, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/10858752208.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Yoru Middle String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Middle String",
				["Size"] = Vector3.new(1.709999918937683, 0.07728225737810135, 1.1152044534683228),
				["CFrame"] = CFrame.new(0, -0.374747038, 0.0178222656, -1, 1.81669783e-12, 0, -1.65154457e-13, 1, 0, 0, 0, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/10858752190.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Yoru Left String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left String",
				["Size"] = Vector3.new(1.2910000085830688, 1.5080000162124634, 1.8939999341964722),
				["CFrame"] = CFrame.new(-0.0778808594, 0.313557863, -0.348876953, 1, 1.81694276e-12, -2.95997612e-19, 1.64909536e-13, 1, -1.62920685e-07, -1.99520294e-23, 1.62920685e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/10859058245.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Yoru Right String"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right String",
				["Size"] = Vector3.new(1.2899999618530273, 1.5084857940673828, 1.8938651084899902),
				["CFrame"] = CFrame.new(0.0780029297, 0.313999891, -0.348999023, 1, 1.81694276e-12, -2.95997587e-19, 1.64909536e-13, 1, -1.62920671e-07, -1.99518511e-23, 1.62920671e-07, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/10859058249.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Yoru Ring"] = {
				["Instance"] = "Mesh",
				["Name"] = "Ring",
				["Size"] = Vector3.new(0.29135453701019287, 0.29135429859161377, 0.0546705536544323),
				["CFrame"] = CFrame.new(0, 0.134058237, -1.13592529, 1, 1.81669783e-12, 0, 1.65154457e-13, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Metal,
				["MeshId"] = "rbxasset://RClothesContent/10858752173.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(248.0000004172325, 248.0000004172325, 248.0000004172325),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Right Glove 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Glove",
				["Size"] = Vector3.new(1.121999979019165, 0.5379999876022339, 1.027999997138977),
				["CFrame"] = CFrame.new(-0.0250244141, -0.825000048, 0, 0.990581274, 0.136925936, 0, -0.136925936, 0.990581274, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/10858752241.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
			}, 
			["Left Glove 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Glove",
				["Size"] = Vector3.new(1.1215732097625732, 0.5384082794189453, 1.028199315071106),
				["CFrame"] = CFrame.new(0.0250854492, -0.824991465, 0, 0.990580142, -0.136934355, 0, 0.136934355, 0.990580142, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/10858752221.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
			},

			["Cumdiction"] = {
				["Instance"] = "Mesh",
				["Name"] = "Cumdiction",
				["Size"] = Vector3.new(0.6470000147819519, 0.004000000189989805, 0.5299999713897705),
				["CFrame"] = CFrame.new(-0.000549316406, -0.650450706, -0.495361328, 1, -2.22728073e-22, 6.54676313e-12, 6.54676313e-12, 1.47310792e-32, 1, -2.57267065e-21, -1, -2.11156236e-33),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9534436982.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Deep Focus"] = {
				["Instance"] = "Mesh",
				["Name"] = "Deep Focus",
				["Size"] = Vector3.new(0.6470000147819519, 0.004000000189989805, 0.5299999713897705),
				["CFrame"] = CFrame.new(-0.000610351562, -0.650450706, -0.495361328, 1, -3.01812679e-21, -9.02877773e-12, 2.2122304e-11, 4.89692197e-32, 1, -5.36806936e-21, -1, 7.2499913e-32),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9533965499.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Diction"] = {
				["Instance"] = "Mesh",
				["Name"] = "Diction",
				["Size"] = Vector3.new(0.022204026579856873, 0.5899999737739563, 0.578689694404602),
				["CFrame"] = CFrame.new(0.00494384766, -0.626008272, -0.494689941, 0, 0, 1, 0.0814488083, 0.996677518, 0, -0.996677518, 0.0814488083, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9739471829.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Gaze"] = {
				["Instance"] = "Mesh",
				["Name"] = "Gaze",
				["Size"] = Vector3.new(0.025125805288553238, 0.6972464323043823, 0.7196773290634155),
				["CFrame"] = CFrame.new(0.0112304688, -0.655378103, -0.479370117, 0, 0, 1, 0.114882283, 0.993379116, 0, -0.993379116, 0.114882283, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9752288922.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Glow"] = {
				["Instance"] = "Mesh",
				["Name"] = "Glow",
				["Size"] = Vector3.new(1.214523196220398, 0.010409533977508545, 0.4721943140029907),
				["CFrame"] = CFrame.new(6.10351562e-05, -0.650449991, -0.494995117, 1, 1.19433894e-21, 1.44424472e-11, -1.13309362e-12, -5.32728015e-33, 1, -1.19433894e-21, -1, -3.97395702e-33),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9513009034.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Libido"] = {
				["Instance"] = "Mesh",
				["Name"] = "Libido",
				["Size"] = Vector3.new(0.027331100776791573, 0.5099999904632568, 1.2347478866577148),
				["CFrame"] = CFrame.new(-0.0115356445, -0.638379812, -0.477233887, 0, 0, 1, 0.0682274997, 0.997669876, 0, -0.997669876, 0.0682274997, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9738589498.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Phermone"] = {
				["Instance"] = "Mesh",
				["Name"] = "Phermone",
				["Size"] = Vector3.new(0.9368154406547546, 0.004757822956889868, 0.6051806211471558),
				["CFrame"] = CFrame.new(-0.000183105469, -0.650450706, -0.495361328, 1, 3.78349629e-10, -1.2410125e-12, 1.43345336e-11, 1.32422073e-09, 1.00000393, 3.78348158e-10, -1.00000393, 1.32422073e-09),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9522843947.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["TorsoMesh"] = {
				["Instance"] = "Mesh",
				["Name"] = "TorsoMesh",
				["Size"] = Vector3.new(2.0399999618530273, 2.059999942779541, 1.059999942779541),
				["CFrame"] = CFrame.new(-0.000366210938, -2.38418579e-07, 0.000183105469, 1, -6.42401909e-10, 5.82085699e-11, 6.44266418e-10, 1, 3.74475617e-20, -5.82085699e-11, -5.42651863e-23, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxasset://RClothesContent/6867647037.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(163.00000548362732, 162.00000554323196, 165.00000536441803),
				},
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Triggered"] = {
				["Instance"] = "Mesh",
				["Name"] = "Triggered",
				["Size"] = Vector3.new(0.019866948947310448, 0.5014975666999817, 0.9317648410797119),
				["CFrame"] = CFrame.new(0, -0.663594007, -0.494995117, 0, 0, 1, -5.32728015e-33, 1, 0, -1, -5.32728015e-33, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/9730141165.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Animalistic"] = {
				["Instance"] = "Mesh",
				["Name"] = "Animalistic",
				["Size"] = Vector3.new(0.019999999552965164, 0.5999999642372131, 0.9918341636657715),
				["CFrame"] = CFrame.new(0.00152587891, -0.653445959, -0.492126465, 0, 0, 1, 0.136425257, 0.990650415, 0, -0.990650415, 0.136425257, 0),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/10399620886.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			},
			["Womb Tattoo 4"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 4",
				["Size"] = Vector3.new(0.27947998046875, 0.03008289635181427, 0.37007877230644226),
				["CFrame"] = CFrame.new(0.00140380859, -0.748365164, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863982580.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 5"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 5",
				["Size"] = Vector3.new(0.6513441801071167, 0.030082978308200836, 0.3700510859489441),
				["CFrame"] = CFrame.new(0.016418457, -0.585365534, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863945719.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 3"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 3",
				["Size"] = Vector3.new(0.22565507888793945, 0.030082952231168747, 0.09696586430072784),
				["CFrame"] = CFrame.new(-0.170593262, -0.516367435, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863959589.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 2",
				["Size"] = Vector3.new(0.3088366389274597, 0.03008296899497509, 0.26607292890548706),
				["CFrame"] = CFrame.new(-0.212585449, -0.601366282, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863962668.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 6"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 6",
				["Size"] = Vector3.new(0.2736760079860687, 0.030082950368523598, 0.2558222711086273),
				["CFrame"] = CFrame.new(0.00140380859, -0.689365387, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863964841.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 7"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 7",
				["Size"] = Vector3.new(0.3318948745727539, 0.030082905665040016, 0.1173192709684372),
				["CFrame"] = CFrame.new(0.000427246094, -0.671365738, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863985603.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 8"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 8",
				["Size"] = Vector3.new(0.5496751666069031, 0.030082983896136284, 0.3700457513332367),
				["CFrame"] = CFrame.new(0.0934448242, -0.585365534, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863941262.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Womb Tattoo 1"] = {
				["Instance"] = "Mesh",
				["Name"] = "Womb Tattoo 1",
				["Size"] = Vector3.new(0.29123565554618835, 0.03008296899497509, 0.19048599898815155),
				["CFrame"] = CFrame.new(-0.221557617, -0.63936615, -0.475158691, 1, 1.8544597e-09, 4.01560417e-11, 8.76780593e-11, -2.6284539e-09, -0.999997139, -9.26775101e-09, 1, -1.25223751e-08),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxasset://RClothesContent/8863966579.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["SuspensionBikini1"] = {
				["Instance"] = "Mesh",
				["Name"] = "SuspensionBikini1",
				["Size"] = Vector3.new(1.5101003646850586, 0.25635242462158203, 0.17945683002471924),
				["CFrame"] = CFrame.new(-9.31862928e-07, 0.194564581, -1.2371527, -1, 0, -1.50995803e-07, 0, 1, 0, 1.50995803e-07, 0, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://17657009853",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Buttplug"] = {
				["Instance"] = "Mesh",
				["Name"] = "Buttplug",
				["Size"] = Vector3.new(0.35049957036972046, 0.3662424087524414, 0.4094148874282837),
				["CFrame"] = CFrame.new(-6.41732356e-07, -1.12597048, 0.684295177, -1, 0, -1.50995803e-07, 0, 1, 0, 1.50995803e-07, 0, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://17657009757",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(159.0000057220459, 161.0000056028366, 172.00000494718552),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["ButtplugGem"] = {
				["Instance"] = "Mesh",
				["Name"] = "ButtplugGem",
				["Size"] = Vector3.new(0.21904124319553375, 0.1938542127609253, 0.1314373016357422),
				["CFrame"] = CFrame.new(-6.20070068e-07, -1.19932258, 0.827758193, -1, 0, -1.50995803e-07, 0, 1, 0, 1.50995803e-07, 0, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Neon,
				["MeshId"] = "rbxassetid://17657009721",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(167.00000524520874, 94.0000019967556, 155.00000596046448),
				},
				["Recolor"] = "Tertiary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["SuspensionBikini"] = {
				["Instance"] = "Mesh",
				["Name"] = "SuspensionBikini",
				["Size"] = Vector3.new(1.4737727642059326, 1.638237714767456, 2.0904557704925537),
				["CFrame"] = CFrame.new(-7.8531383e-07, -0.666520596, -0.266601741, -1, 0, -1.50995803e-07, 0, 1, 0, 1.50995803e-07, 0, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["MeshId"] = "rbxassetid://17657009742",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["NewWomanTorsoShirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "New Woman Torso Shirt Mesh",
				["MeshId"] = "rbxassetid://5679232242",
				["Size"] = Vector3.new(1.4, 2.313, 0.907),
				["CFrame"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanTorsoShirtClothing"
			},
			["NewWomanTorsoPants"] = {
				["Instance"] = "Mesh",
				["Name"] = "New Woman Torso Pants Mesh",
				["MeshId"] = "rbxassetid://5679232242",
				["Size"] = Vector3.new(1.399, 2.312, 0.906),
				["CFrame"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanTorsoPantsClothing"
			},
			["NewWomanLeftLeg"] = {
				["Instance"] = "Mesh",
				["Name"] = "New Woman Left Leg Mesh",
				["MeshId"] = "rbxassetid://14069694330",
				["Size"] = Vector3.new(0.976, 2.394, 1.315),
				["CFrame"] = CFrame.new(0, 0.2, -0.1, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Leg"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanPantsClothing"
			},
			["NewWomanRightLeg"] = {
				["Instance"] = "Mesh",
				["Name"] = "New Woman Right Leg Mesh",
				["MeshId"] = "rbxassetid://14069694284",
				["Size"] = Vector3.new(0.976, 2.394, 1.315),
				["CFrame"] = CFrame.new(0, 0.2, -0.1, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Leg"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanPantsClothing"
			},
			["NewWomanRightArm"] = {
				["Instance"] = "Part",
				["Name"] = "New Woman Right Arm Mesh",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Right Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanShirtClothing"
			},
			["NewWomanLeftArm"] = {
				["Instance"] = "Part",
				["Name"] = "New Woman Left Arm Mesh",
				["Size"] = Vector3.new(1, 2, 1),
				["CFrame"] = CFrame.new(0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Left Arm"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanShirtClothing"
			},
			["NewWomanBreastShirt"] = {
				["Instance"] = "Mesh",
				["Name"] = "New Woman Breast Mesh",
				["MeshId"] = "rbxassetid://7606070501",
				["Size"] = Vector3.new(1.143, 1.222, 1.375),
				["CFrame"] = CFrame.new(0.001, 0.23, -0.401, 0, 0, -1, -0.26, 1, 0, 1, 0.25, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanBreastShirtClothing"
			},
			["NewWomanBreastPants"] = {
				["Instance"] = "Mesh",
				["Name"] = "New Woman Breast Mesh",
				["MeshId"] = "rbxassetid://7606070501",
				["Size"] = Vector3.new(1.143, 1.222, 1.375),
				["CFrame"] = CFrame.new(0.001, 0.23, -0.401, 0, 0, -1, -0.26, 1, 0, 1, 0.25, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.SmoothPlastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = "Parent"
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["ParentTransparency"] = 1,
				["Function"] = "NewWomanBreastPantsClothing"
			},
			["Croptop Neck"] = {
				["Instance"] = "Mesh",
				["Name"] = "Croptop Neck",
				["Size"] = Vector3.new(1.293561577796936, 0.4219806492328644, 1.3588359355926514),
				["CFrame"] = CFrame.new(0.00418663025, 1.09489012, 0.00360298157, 1, -5.37213937e-12, 6.13908924e-12, -5.37213937e-12, 1, -1.63373362e-23, 6.13908924e-12, -1.63373346e-23, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/4342469442.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Croptop"] = {
				["Instance"] = "Mesh",
				["Name"] = "Croptop",
				["Size"] = Vector3.new(1.924189567565918, 1.3496313095092773, 2.021623373031616),
				["CFrame"] = CFrame.new(-0.00561904907, 0.359501839, -0.399815559, -0.00869339053, 5.57615342e-14, -0.999962211, -1.46950747e-14, 1, -5.56358853e-14, 0.999962211, -1.42108547e-14, -0.00869339053),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/8609087425.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Lift Croptop"] = {
				["Instance"] = "Mesh",
				["Name"] = "Croptop",
				["Size"] = Vector3.new(1.600000023841858, 1.1349999904632568, 1.9170000553131104),
				["CFrame"] = CFrame.new(0.00980949402, 0.488786697, -0.226898193, -0.00869352184, -8.84762244e-07, -0.999962211, 1.25948532e-07, 1, -8.85890699e-07, 0.999962211, -1.33645287e-07, -0.00869352184),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/9286995426.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "TurtleTexture"
			}, 
			["Cloth Bra"] = {
				["Instance"] = "Mesh",
				["Name"] = "Cloth",
				["Size"] = Vector3.new(1.7875815629959106, 0.468290239572525, 1.9307326078414917),
				["CFrame"] = CFrame.new(-0.00817108154, 0.188874245, -0.374444962, -2.84217094e-14, 5.57615342e-14, -1, -1.42108547e-14, 1, -5.57615342e-14, 1, -1.42108547e-14, 2.84217094e-14),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/12776336375.mesh",
				["DoubleSided"] = true,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(17.00000088661909, 17.00000088661909, 17.00000088661909),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Crop Sweater"] = {
				["Instance"] = "Mesh",
				["Name"] = "Crop Sweater",
				["Size"] = Vector3.new(2.0879037380218506, 1.4744689464569092, 1.8795204162597656),
				["CFrame"] = CFrame.new(-0.00158691406, 0.315901041, -0.376700401, -1, 1.11645536e-13, 5.67209548e-14, -1.11400601e-13, 1, 2.85441735e-14, 5.69658863e-14, -2.82992454e-14, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/15649620886.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(182, 174, 151),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Uncovered Crop Sweater"] = {
				["Instance"] = "Mesh",
				["Name"] = "Uncovered Crop",
				["Size"] = Vector3.new(2.399881601333618, 2.161713123321533, 2.1647732257843018),
				["CFrame"] = CFrame.new(0.00048828125, -0.000299930573, -0.0355734825, -1, 2.23046137e-13, 1.13686838e-13, -2.23046137e-13, 1, 5.68434189e-14, 1.13686838e-13, -5.68434189e-14, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/15640279907.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(182, 174, 151),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Crop Sweater 2"] = {
				["Instance"] = "Mesh",
				["Name"] = "Crop Sweater2",
				["Size"] = Vector3.new(2.162240505218506, 1.1933902502059937, 1.8561198711395264),
				["CFrame"] = CFrame.new(-0.00385284424, 0.470192909, -0.365337133, -1, 4.46092273e-13, 2.27373675e-13, -4.46092273e-13, 1, 1.13686838e-13, 2.27373675e-13, -1.13686838e-13, -1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/15640502788.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(182, 174, 151),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
			}, 
			["Sweater Left Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Left Arm Clothes",
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["Size"] = Vector3.new(1.1328604221343994, 1.823657512664795, 1.1202536821365356),
				["CFrame"] = CFrame.new(0.0394668579, 0.137500286, -0.000893115997, 1, 1.11645536e-13, -5.67209548e-14, 1.11400601e-13, 1, -2.85441735e-14, -5.69658863e-14, -2.82992454e-14, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(182, 174, 151),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Left Arm",
				},
			},
			["Sweater Right Arm"] = {
				["Instance"] = "Mesh",
				["Name"] = "Right Arm Clothes",
				["MeshId"] = "rbxasset://RClothesContent/6866262171.mesh",
				["Size"] = Vector3.new(1.1236231327056885, 1.824110746383667, 1.1236631870269775),
				["CFrame"] = CFrame.new(-0.0385055542, 0.137500286, -0.000893115997, 1, 1.11645536e-13, -5.67209548e-14, 1.11400601e-13, 1, -2.85441735e-14, -5.69658863e-14, -2.82992454e-14, 1),
				["Transparency"] = 0,
				["Material"] = Enum.Material.Plastic,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(182, 174, 151),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Right Arm",
				},
			},
			["Vibrator Buttons"] = {
				["Instance"] = "Mesh",
				["Name"] = "Buttons",
				["Size"] = Vector3.new(1.2282028198242188, 0.33578991889953613, 0.11236000061035156),
				["CFrame"] = CFrame.new(0.00048828125, -0.665299892, -0.479880333, 1, 5.57615342e-14, -2.84217094e-14, 5.57615342e-14, 1, -1.42108547e-14, -2.84217094e-14, -1.42108547e-14, 1),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/77284727360409.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
				},
				["Function"] = "VibratorStrings"
			}, 
			["Left Vibrator Bullet"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bullet",
				["Size"] = Vector3.new(0.19999957084655762, 0.10001015663146973, 0.23160171508789062),
				["CFrame"] = CFrame.new(-2.88486481e-05, 0.0206165314, 0.00458526611, 1, -6.88433647e-06, -2.46614218e-06, 6.88433647e-06, 1.00000012, 3.9935112e-06, 2.48476863e-06, -4.02331352e-06, 0.99999994),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/101087111632562.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple",
				},
			}, 
			["Right Vibrator Bullet"] = {
				["Instance"] = "Mesh",
				["Name"] = "Bullet",
				["Size"] = Vector3.new(0.19999957084655762, 0.10001015663146973, 0.23160171508789062),
				["CFrame"] = CFrame.new(-2.88486481e-05, 0.0206165314, 0.00458526611, 1, -6.88433647e-06, -2.46614218e-06, 6.88433647e-06, 1.00000012, 3.9935112e-06, 2.48476863e-06, -4.02331352e-06, 0.99999994),
				["Transparency"] = 0,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Plastic,
				["MeshId"] = "rbxasset://RClothesContent/101087111632562.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 152.0000061392784, 220.00000208616257),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple",
				},
			}, 
			["Vibrator Tape"] = {
				["Instance"] = "Mesh",
				["Name"] = "Tape",
				["Size"] = Vector3.new(1.4522018432617188, 0.1102597713470459, 0.13035011291503906),
				["CFrame"] = CFrame.new(0, -0.000999927521, 0.00539565086, 1, 0, 0, 0, 1, 0, 0, 0, 1),
				["Transparency"] = 0.6499999761581421,
				["Reflectance"] = 0,
				["Material"] = Enum.Material.Wood,
				["MeshId"] = "rbxasset://RClothesContent/76388853104288.mesh",
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(226.0000017285347, 220.00000208616257, 188.0000039935112),
				},
				["Recolor"] = "Secondary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Buttons",
				},
			}, 
			["Left Nipple Lactation"] = {
				["Instance"] = "Part",
				["Name"] = "Lactation",
				["Size"] = Vector3.new(0.025, 0.025, 0.025),
				["CFrame"] = CFrame.new(0.000348567963, -0.000116348267, 0.000267028809, 0.99999994, 5.09619713e-06, -1.43423676e-06, -5.11109829e-06, 1, -4.05311584e-06, 1.39325857e-06, 4.11272049e-06, 1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast",
					[3] = "Nipple",
				},
				["Function"] = "Lactation"
			}, 
			["Right Nipple Lactation"] = {
				["Instance"] = "Part",
				["Name"] = "Lactation",
				["Size"] = Vector3.new(0.025, 0.025, 0.025),
				["CFrame"] = CFrame.new(0.000348567963, -0.000116348267, 0.000267028809, 0.99999994, 5.09619713e-06, -1.43423676e-06, -5.11109829e-06, 1, -4.05311584e-06, 1.39325857e-06, 4.11272049e-06, 1),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(255, 255, 255),
				},
				["Recolor"] = "Primary",
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast",
					[3] = "Nipple",
				},
				["Function"] = "Lactation"
			}, 
			["theOilerFunction"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "OilUp"
			}, 
			["theOilerFunction2"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "OilUp2"
			}, 
			["theOilerFunction3"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso"
				},
				["Function"] = "OilUp3"
			}, 
			["RBreastFreckles"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Breast"
				},
				["Function"] = "addFreckles"
			},
			["LBreastFreckles"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Breast"
				},
				["Function"] = "addFreckles"
			},
			["RButtFreckles"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Right Butt"
				},
				["Function"] = "addFreckles"
			},
			["LButtFreckles"] = {
				["Instance"] = "Part",
				["Name"] = "UnnecessaryPart",
				["Size"] = Vector3.new(0,0,0),
				["CFrame"] = CFrame.new(0,0,0),
				["Transparency"] = 1,
				["Material"] = Enum.Material.Plastic,
				["DoubleSided"] = false,
				["Color"] = {
					["Tone"] = "Base",
					["Color"] = Color3.fromRGB(0, 0, 0),
				},
				["Parent"] = {
					[1] = "Torso",
					[2] = "Left Butt"
				},
				["Function"] = "addFreckles"
			},
		}
	end

	local PlayerData = {
		[Player.Name] = Function.PlayerDataDefault()
	}

	local DummyMesh = {
		["Head"] = {
			Size = Vector3.new(2, 1, 1),
			Offset = CFrame.new(0, 1.5, 0)
		},
		["Torso"] = {
			Size = Vector3.new(2, 2, 1),
			Offset = CFrame.new(0,0,0)
		},
		["Right Arm"] = {
			Size = Vector3.new(1, 2, 1),
			Offset = CFrame.new(1.5, 0, 0)
		},
		["Left Arm"] = {
			Size = Vector3.new(1, 2, 1),
			Offset = CFrame.new(-1.5, 0, 0)
		},
		["Right Leg"] = {
			Size = Vector3.new(1, 2, 1),
			Offset = CFrame.new(0.5, -2, 0)
		},
		["Left Leg"] = {
			Size = Vector3.new(1, 2, 1),
			Offset = CFrame.new(-0.5, -2, 0)
		}
	}

	local EditableProperty = {
		"TextureId",
		"Offset",
		"Size",
		"Transparency",
		"MeshBasePartTransparency",
		"Color",
		"Reflectance",
	}

	local Method2BodyPart = {
		"Torso",
		"Left Arm",
		"Right Arm",
		"Left Leg",
		"Right Leg",
		"Head",
	}

	local BodyColorPart = {
		["HeadColor3"] = "Head",
		["LeftArmColor3"] = "Left Arm",
		["RightArmColor3"] = "Right Arm",
		["LeftLegColor3"] ="Left Leg",
		["RightLegColor3"] = "Right Leg",
		["TorsoColor3"] = "Torso"
	}

	local BodyPartSize = {
		["Head"] = Vector3.new(2, 1, 1),
		["HeadMeshFix"] = Vector3.new(1, 1, 1),
		["Torso"] = Vector3.new(2, 2, 1),
		["Left Arm"] = Vector3.new(1, 2, 1),
		["Left Leg"] = Vector3.new(1, 2, 1),
		["Right Arm"] = Vector3.new(1, 2, 1),
		["Right Leg"] = Vector3.new(1, 2, 1),
		["HumanoidRootPart"] = Vector3.new(2, 2, 1),
	}

	local AttachmentCFrame = {
		["RootAttachment"] = CFrame.new(0,0,0),

		["FaceCenterAttachment"] = CFrame.new(0,0,0),
		["FaceFrontAttachment"] = CFrame.new(0, 0, -0.6),
		["HairAttachment"] = CFrame.new(0,0.6,0),
		["HatAttachment"] = CFrame.new(0,0.6,0),

		["LeftGripAttachment"] = CFrame.new(0, -1, 0),
		["LeftShoulderAttachment"] = CFrame.new(0,1,0),

		["LeftFootAttachment"] = CFrame.new(0, -1, 0),

		["RightGripAttachment"] = CFrame.new(0, -1, 0),
		["RightShoulderAttachment"] = CFrame.new(0,1,0),

		["RightFootAttachment"] = CFrame.new(0, -1, 0),

		["BodyBackAttachment"] = CFrame.new(0, 0, 0.5),
		["BodyFrontAttachment"] = CFrame.new(0, 0, -0.5),
		["LeftCollarAttachment"] = CFrame.new(-1, 1, 0),
		["NeckAttachment"] = CFrame.new(0, 1, 0),
		["RightCollarAttachment"] = CFrame.new(1, 1, 0),
		["WaistBackAttachment"] = CFrame.new(0, -1, 0.5),
		["WaistCenterAttachment"] = CFrame.new(0, -1, 0),
		["WaistFrontAttachment"] = CFrame.new(0, -1, -0.5),
	}

	local AttachmentParent = {
		["RootAttachment"] = "HumanoidRootPart",

		["FaceCenterAttachment"] = "Head",
		["FaceFrontAttachment"] = "Head",
		["HairAttachment"] = "Head",
		["HatAttachment"] = "Head",

		["LeftGripAttachment"] = "Left Arm",
		["LeftShoulderAttachment"] = "Left Arm",

		["LeftFootAttachment"] = "Left Leg",

		["RightGripAttachment"] = "Right Arm",
		["RightShoulderAttachment"] = "Right Arm",

		["RightFootAttachment"] = "Right Leg",

		["BodyBackAttachment"] = "Torso",
		["BodyFrontAttachment"] = "Torso",
		["LeftCollarAttachment"] = "Torso",
		["NeckAttachment"] = "Torso",
		["RightCollarAttachment"] = "Torso",
		["WaistBackAttachment"] = "Torso",
		["WaistCenterAttachment"] = "Torso",
		["WaistFrontAttachment"] = "Torso",
	}

	local HumanoidAccessoryName = {
		"HairAccessory",
		"BackAccessory",
		"FaceAccessory",
		"FrontAccessory",
		"HatAccessory",
		"NeckAccessory",
		"ShouldersAccessory",
		"WaistAccessory",
	}

	local AccessoryType = {
		[8] = "HatAccessory",
		[41] = "HairAccessory",
		[42] = "FaceAccessory",
		[43] = "NeckAccessory",
		[44] = "ShouldersAccessory",
		[45] = "FrontAccessory",
		[46] = "BackAccessory",
		[47] = "WaistAccessory",
	}

	local Bundle = {
		["nil"] = "nil",
		["Bald"] = {},
		["Test"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				5920341268,
				6441537838,
				6472725579
			}
		},
		["Black 1"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7392396295,
				7863333749,
				7675263201
			}
		},
		["Brown 1"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7284085462,
				6441537838,
			}
		},
		["Black 2"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				10752612567, 
				6812033514, 
				12283951209, 
				12815729656, 
				12931195148
			}
		},
		["Black 3"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				6036143892, 
				6413085241, 
				6754455467, 
				7896143574,
				7133439522
			}
		},
		["Black 4"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7097787052,
				7335390462,
				8923597159,
				6310032618
			}
		},
		["Black 5"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				11416699089,
				8273712381,
				11959885521,
				8923597159
			}
		},
		["White 1"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7240955578, 
				9244453644,
				9240826224,
				8275349855,
				9241889306
			}
		},
		["White 2"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				8082861034,
				8089294103,
				8089443065
			}
		},
		["White With Hat 1"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7175904988,
				7214725742,
				9008202379
			}
		},
		["White With Hat 2"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				8207715434, 
				7175904988,
				6216526940
			}
		},
		["White 3"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7240955578,
				9244453644,
				8275349855, 
				9241889306,
				9240826224
			}
		},
		["Black 6"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				8089495899, 
				398672920,
				12982832975
			}
		},
		["Black 7"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				8082486982,
				6441072389,
				9241886323
			}
		},
		["Black 8"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				6752624930,
				7240994068,
				7259123616, 
				8207687270
			}
		},
		["Black 9"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				12410899973,
				7486725420, 
				12485469802,
				11095474871, 
				10001005299
			}
		},
		["Black Fade Green"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				10661041028,
				11387061216, 
				7280442851
			}
		},
		["White 4"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7222659174,
				12726002629,
				10088463133,
				7628287080
			}
		},
		["White 5"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				6475395916,
				7063887536,
				8652761405
			}
		},
		["White Mix Pink"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7486035624,
				8275245292,
				8614911363
			}
		},
		["Black Mix Red"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				9731173784,
				11050607388,
				11405828721
			}
		},
		["Black 10"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				11180024054,
				9240831931, 
				10001005299,
				9241886323
			}
		},
		["Black 11"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7141674388,
				7168295329, 
				8040379705, 
				8821393761, 
				9571729576
			}
		},
		["Red"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				6842683595, 
				6840001710, 
				8031588258
			}
		},
		["White 6"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7259147441,
				7733302642
			}
		},
		["Sportsy"] = {
			["Body Color"] = {
				["HeadColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftArmColor3"] = Color3.fromRGB(255, 204, 153),
				["RightArmColor3"] = Color3.fromRGB(255, 204, 153),
				["LeftLegColor3"] = Color3.fromRGB(255, 204, 153),
				["RightLegColor3"] = Color3.fromRGB(255, 204, 153),
				["TorsoColor3"] = Color3.fromRGB(255, 204, 153),
			},
			["Accessory"] = {
				7097787052,
				7335390462,
				8923597159,
				6310032618
			},
			["Clothing"] = {
				"Croptop",
				"Pussy Closed",
				"Panty 2",
				"Shoe 3",
				"Sock 2",
				"Skirt 2",
				"Glove"
			}
		},
		-- Clothing Bundles --
		["Roblox Clothing"] = {
			["Clothing"] = {
				"Roblox Breasts Clothing",
				"Roblox Shirt",
				"Roblox Butt Shirt",
				"Roblox Pants",
			},
			["ClothingBundle"] = true
		},
		["Roblox Clothing w/o Breasts"] = {
			["Clothing"] = {
				"Roblox Shirt",
				"Roblox Butt Shirt",
				"Roblox Pants",
			},
			["ClothingBundle"] = true
		},
		["Birdly Outfit"] = {
			["Clothing"] = {
				"Birdly Dress",
				"Birdly Backpack",
				"Birdly Bottom Dress",
				"Birdly Sleeves"
			},
			["ClothingBundle"] = true
		},
		["Cow Bikini"] = {
			["Clothing"] = {
				"Cow Bra",
				"Cow Panty"
			},
			["Preset"] = {
				BreastsScale = 1
			},
			["ClothingBundle"] = true
		},
		["Kitty Outfit"] = {
			["Clothing"] = {
				"Kitty Bra",
				"Kitty Panty",
				"Kitty Band",
				"Kitty Aspects"
			},
			["Preset"] = {
				BreastsScale = 1
			},
			["ClothingBundle"] = true
		},
		["Bunny Suit"] = {
			["Clothing"] = {
				"Bunny Suit",
				"Collar w/ Bow",
				"Bunny Bands",
				"Bunny Aspects",
				"Fishnet Stockings"
			},
			["Preset"] = {
				BreastsScale = 1,
				ButtsScale = 1
			},
			["ClothingBundle"] = true
		},
		["Messy"] = {
			["Clothing"] = {
				"Torso Cum",
				"Leg Cum",
				"Arm Cum",
				"Butts Cum",
				"Butts Cum 2",
				"Breasts Cum",
				"Breasts Cum Type2",
				"Face Cum",
				"Face Cum 2",
				"Pussy Cum",
			},
			["ClothingBundle"] = true
		},
		["Messy [Rudolph]"] = {
			["Clothing"] = {
				"[Rudolph] Torso Cum",
				"[Rudolph] Leg Cum",
				"[Rudolph] Arm Cum",
				"Butts Cum",
				"Butts Cum 2",
				"Breasts Cum",
				"Breasts Cum Type2",
				"Face Cum",
				"Face Cum 2",
				"Pussy Cum",
			},
			["ClothingBundle"] = true
		},
		["Freckles"] = {
			["Clothing"] = {
				"Breast Freckles",
				"Butt Freckles",
			},
			["ClothingBundle"] = true
		},
		-- Presets --
		["[PRESET] Dance Physics"] = {
			["Preset"] = {
				BodyPartPhysics = true,
				PositionPhysicsMultiply = 8,
				RotationPhysicsMultiply = 12
			},
			["IsPreset"] = true
		},
		["[PRESET] First Person Compatibility"] = {
			["Preset"] = {
				Method = 3,
				LocalTransparency = {
					["Head"] = false,
					["Right Arm"] = true,
					["Left Arm"] = true,
					["Torso"] = true,
					["Right Leg"] = true,
					["Left Leg"] = true,
					["Hat"] = true
				}
			},
			["IsPreset"] = true
		},
		["[PRESET] First Person"] = {
			["Preset"] = {
				FPerson = true,
				Method = 3,
				LocalTransparency = {
					["Head"] = false,
					["Right Arm"] = true,
					["Left Arm"] = true,
					["Torso"] = true,
					["Right Leg"] = true,
					["Left Leg"] = true,
					["Hat"] = true
				}
			},
			["IsPreset"] = true
		},
		["[PRESET] FPerson Snap"] = {
			["Preset"] = {
				FPerson = true,
				FPsnap = true,
			},
			["IsPreset"] = true
		},
		["[PRESET] FPerson SnapOff"] = {
			["Preset"] = {
				FPerson = true,
				FPsnap = false,
			},
			["IsPreset"] = true
		},
		["[PRESET] Rudolph's Body Type"] = {
			["Preset"] = {
				TorsoType = 3,
				ArmType = 2,
				LegsType = 3
			},
			["IsPreset"] = true
		},
		["[PRESET] ROBLOX Body Type"] = {
			["Preset"] = {
				TorsoType = 5,
				ArmType = 3,
				LegsType = 4
			},
			["IsPreset"] = true
		},
		["[PRESET] Buff Body Type"] = {
			["Preset"] = {
				TorsoType = 6,
				ArmType = 4
			},
			["IsPreset"] = true
		},
		["[PRESET] Male"] = {
			["Preset"] = {
				TorsoType = 5,
				ArmType = 3,
				LegsType = 4
			},
			["Clothing"] = {
				"Cock",
				"Remove Breasts",
			},
			["IsPreset"] = true
		},
		["[PRESET] Thicc"] = {
			["Preset"] = {
				ButtsScale = 1.3,
				LegsScale = 1.2,
				ButtType = 3,
				LegsType = 2
			},
			["IsPreset"] = true
		},
	}

	local Clothes = {
		["School Shirt"] = {
			["Weld"] = {
				[1] = "School Shirt",
				[2] = "School Collor",
				[3] = "School Bow",
				[5] = "School Left Arm",
				[6] = "School Right Arm",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Skirt 1"] = {
			["Weld"] = {
				[1] = "Skirt 1",
			}
		},
		["Skirt 2"] = {
			["Weld"] = {
				[1] = "Skirt 2",
			}
		},
		["Bra"] = {
			["Weld"] = {
				[1] = "Bra",
			}
		},
		["Panty"] = {
			["Weld"] = {
				[1] = "Panty"
			}
		},
		["Bodyless Clothes"] = {
			["Weld"] = {
				[1] = "Bodyless Shirt",
				[2] = "Bodyless Neck",
				[3] = "Bodyless Right Arm",
				[4] = "Bodyless Left Arm"
			}
		},
		["Dress"] = {
			["Weld"] = {
				[1] = "Dress Bra",
				[2] = "Dress Rope",
				[3] = "Dress Skirt In",
				[4] = "Dress Skirt Out",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Birdly Dress"] = {
			["Weld"] = {
				[1] = "Birdly Dress",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Birdly Backpack"] = {
			["Weld"] = {
				[1] = "Birdly Dress Sling",
				[2] = "Birdly Dress Mail 1",
				[3] = "Birdly Dress Mail 2",
				[4] = "Birdly Dress Mail 3",
			},
		},
		["Birdly Sleeves"] = {
			["Weld"] = {
				[1] = "Birdly Dress Right Sleeve",
				[2] = "Birdly Dress Right Sleeve 2",
				[3] = "Birdly Dress Left Sleeve",
				[4] = "Birdly Dress Left Sleeve 2",
			},
		},
		["Birdly Bottom Dress"] = {
			["Weld"] = {
				[1] = "Birdly Dress Bottom",
			},
		},
		["Suspension bikini"] = {
			["Weld"] = {
				[1] = "SuspensionBikini1",
				[2] = "Buttplug",
				[3] = "ButtplugGem",
				[4] = "SuspensionBikini",
			}
		},
		["Apron"] = {
			["Weld"] = {
				[1] = "Apron 1"
			}
		},
		["Apron 2"] = {
			["Weld"] = {
				[1] = "Apron 2"
			}
		},
		["Killer Sweater"] = {
			["Weld"] = {
				[1] = "Killer Sweater",
				[2] = "Killer Sweater Tie",
				[3] = "Killer Sweater Neck",
			}
		},
		["Cow Bra"] = {
			["Weld"] = {
				[1] = "Cow Bra",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Cow Panty"] = {
			["Weld"] = {
				[1] = "Cow Panty",
			},
		},
		["Bunny Aspects"] = {
			["Weld"] = {
				[1] = "Bunny Tail",
				[2] = "Bunny Ears",
			}
		},
		["Bunny Suit"] = {
			["Weld"] = {
				[1] = "Bunny Suit",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Bunny Bands"] = {
			["Weld"] = {
				[1] = "Right Bunny Band",
				[2] = "Left Bunny Band",
			}
		},
		["Collar w/ Bow"] = {
			["Weld"] = {
				[1] = "Collar",
				[2] = "Bow",
			}
		},
		["Kitty Bra"] = {
			["Weld"] = {
				[1] = "Kitty Bra",
				[2] = "Kitty Black Collar",
				[3] = "Left Kitty Bra String",
				[4] = "Right Kitty Bra String",
				[5] = "Kitty Bra Top Whiskers",
				[6] = "Kitty Bra Middle Whiskers",
				[7] = "Kitty Bra Bottom Whiskers",
				[8] = "Kitty Bra Cat",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Kitty Aspects"] = {
			["Weld"] = {
				[1] = "Kitty Ears",
				[2] = "Kitty Tail",
			}
		},
		["Kitty Panty"] = {
			["Weld"] = {
				[1] = "Kitty Panty",
				[2] = "Left Kitty Panty Paw",
				[3] = "Left Kitty Panty String",
				[4] = "Right Kitty Panty Paw",
				[5] = "Right Kitty Panty String"
			},
		},
		["Kitty Band"] = {
			["Weld"] = {
				[1] = "Right Kitty Band Black",
				[2] = "Right Kitty Band Pink",
			},
		},
		["Workwear Shirt"] = {
			["Weld"] = {
				[1] = "Workwear Shirt",
				[2] = "Left Workwear Arm",
				[3] = "Right Workwear Arm",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			},
		},
		["Side Skirt"] = {
			["Weld"] = {
				[1] = "Side Skirt",
			},
		},
		["Bodysuit"] = {
			["Weld"] = {
				[1] = "Bodysuit",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			},
		},
		["String Bikini"] = {
			["Weld"] = {
				[1] = "String Bikini",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Bra 2"] = {
			["Weld"] = {
				[1] = "Bra 2",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Panty 2"] = {
			["Weld"] = {
				[1] = "Panty 2",
			},
		},
		["Roblox Breasts Clothing"] = {
			["Weld"] = {
				[1] = "Breasts Pants",
				[2] = "Breasts Shirt",
				[3] = "Left Breast 2",
				[4] = "Right Breast 2"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
				"Left Breast",
				"Right Breast",
			}
		},
		["Roblox Shirt"] = {
			["Weld"] = {
				[1] = "Torso Shirt",
			}
		},
		["Roblox Butt Shirt"] = {
			["Weld"] = {
				[1] = "Left Butt Shirt",
				[2] = "Right Butt Shirt",
			}
		},
		["Roblox Pants"] = {
			["Weld"] = {
			}
		},
		["Sweater"] = {
			["Weld"] = {
				[1] = "Sweater Shirt",
				[2] = "Left Sweater Arm",
				[3] = "Right Sweater Arm"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
			}
		},
		["Nipple Piercing 1"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 1",
				[2] = "Right Nipple Piercing 1",
			}
		},
		["Nipple Piercing 2"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 2",
				[2] = "Right Nipple Piercing 2",
			}
		},
		["Nipple Piercing 3"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 3",
				[2] = "Right Nipple Piercing 3",
			}
		},
		["Nipple Piercing 4"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 4",
				[2] = "Right Nipple Piercing 4",
			}
		},
		["Nipple Piercing 5"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 5",
				[2] = "Right Nipple Piercing 5",
			}
		},
		["Nipple Piercing 6"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 6",
				[2] = "Right Nipple Piercing 6",
			}
		},
		["Nipple Piercing 7"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 7",
				[2] = "Right Nipple Piercing 7",
			}
		},
		["Nipple Piercing 8"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 8",
				[2] = "Right Nipple Piercing 8",
			}
		},
		["Nipple Piercing 9"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 9",
				[2] = "Right Nipple Piercing 9",
			}
		},
		["Nipple Piercing 10"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 10",
				[2] = "Right Nipple Piercing 10",
			}
		},
		["Nipple Piercing 11"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 11",
				[2] = "Right Nipple Piercing 11",
			}
		},
		["Nipple Piercing 12"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 12",
				[2] = "Right Nipple Piercing 12",
			}
		},
		["Nipple Piercing 13"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 13",
				[2] = "Right Nipple Piercing 13",
			}
		},
		["Nipple Piercing 14"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 14",
				[2] = "Right Nipple Piercing 14",
			}
		},
		["Nipple Piercing 15"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 15",
				[2] = "Right Nipple Piercing 15",
			}
		},
		["Nipple Piercing 16"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 16",
				[2] = "Right Nipple Piercing 16",
			}
		},
		["Nipple Piercing 17"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 17",
				[2] = "Right Nipple Piercing 17",
			}
		},
		["Nipple Piercing 18"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 18",
				[2] = "Right Nipple Piercing 18",
			}
		},
		["Nipple Piercing 19"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 19",
				[2] = "Right Nipple Piercing 19",
			}
		},
		["Nipple Piercing 20"] = {
			["Weld"] = {
				[1] = "Left Nipple Piercing 20",
				[2] = "Right Nipple Piercing 20",
			}
		},
		["Nipple Cross Tape"] = {
			["Weld"] = {
				[1] = "Right Cross Tape",
				[2] = "Left Cross Tape",
			}
		},
		["Sock 1"] = {
			["Weld"] = {
				[1] = "Left Sock",
				[2] = "Right Sock",
			}
		},
		["Shoe 1"] = {
			["Weld"] = {
				[1] = "Right Shoe",
				[2] = "Left Shoe",
			}
		},
		["Vest"] = {
			["Weld"] = {
				[1] = "Armor",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
			}
		},
		["Maid Arm Band"] = {
			["Weld"] = {
				[1] = "Maid Left Arm Band",
				[2] = "Maid Left Arm Band 2",
				[3] = "Maid Right Arm Band",
				[4] = "Maid Right Arm Band 2",
			}
		},
		["Maid Leg Band"] = {
			["Weld"] = {
				[1] = "Maid Leg Band",
				[2] = "Maid Leg Band Bow",
			}
		},
		["Face Cum"] = {
			["Weld"] = {
				[1] = "Face Cum 2",
				[2] = "Face Cum 3",
				[3] = "Face Cum 4",
				[4] = "Face Cum 5",
				[5] = "Face Cum 6",
				[6] = "Face Cum 7",
				[7] = "Face Cum 1",
			}
		},
		["Breasts Cum"] = {
			["Weld"] = {
				[1] = "Left Breast Cum",
				[2] = "Right Breast Cum",
			}
		},
		["Breasts Cum Type2"] = {
			["Weld"] = {
				[1] = "Left Breast Cum Type2",
				[2] = "Right Breast Cum Type2",
			}
		},
		["Face Cum 2"] = {
			["Weld"] = {
				[1] = "Face Cum Type2",
			}
		},
		["Butts Cum"] = {
			["Weld"] = {
				[1] = "Right Butt Cum 1",
				[2] = "Right Butt Cum 2",
				[3] = "Right Butt Cum 3",
				[4] = "Right Butt Cum 4",
				[5] = "Left Butt Cum 2",
				[6] = "Left Butt Cum 3",
				[7] = "Left Butt Cum 4",
				[8] = "Left Butt Cum 1",
			}
		},
		["Butts Cum 2"] = {
			["Weld"] = {
				[1] = "Right Butt Cum2 1",
				[2] = "Right Butt Cum2 2",
				[3] = "Left Butt Cum2 1",
				[4] = "Left Butt Cum2 2",
			}
		},
		["Torso Cum"] = {
			["Weld"] = {
				[1] = "Torso Cum 1",
				[2] = "Torso Cum 2",
			}
		},
		["Leg Cum"] = {
			["Weld"] = {
				[1] = "Left Leg Cum 1",
				[2] = "Left Leg Cum 2",
				[3] = "Left Leg Cum 3",
				[4] = "Left Leg Cum 4",
				[5] = "Right Leg Cum 1",
				[6] = "Right Leg Cum 2",
				[7] = "Right Leg Cum 3",
			}
		},
		["Arm Cum"] = {
			["Weld"] = {
				[1] = "Left Arm Cum 1",
				[2] = "Left Arm Cum 2",
				[3] = "Right Arm Cum 1",
				[4] = "Right Arm Cum 2",
			}
		},
		["[Rudolph] Arm Cum"] = {
			["Weld"] = {
				[1] = "RightArm2 Cum 1",
				[2] = "RightArm2 Cum 2",
				[3] = "LeftArm2 Cum 2",
				[4] = "LeftArm2 Cum 1",
			}
		},
		["[Rudolph] Leg Cum"] = {
			["Weld"] = {
				[1] = "LeftLeg3 Cum 1",
				[2] = "LeftLeg3 Cum 2",
				[3] = "LeftLeg3 Cum 3",
				[4] = "LeftLeg3 Cum 4",
				[5] = "RightLeg3 Cum 1",
				[6] = "RightLeg3 Cum 2",
				[7] = "RightLeg3 Cum 3",
			}
		},
		["[Rudolph] Torso Cum"] = {
			["Weld"] = {
				[1] = "Torso3 Cum 2",
				[2] = "Torso3 Cum 1",
			}
		},
		["Nipple Round Cross Tape"] = {
			["Weld"] = {
				[1] = "Right Round Cross Tape",
				[2] = "Left Round Cross Tape",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
			}
		},
		["Jacket"] = {
			["Weld"] = {
				[1] = "Jacket Shirt",
				[2] = "Right Jacket Arm",
				[3] = "Left Jacket Arm",
				[4] = "Left Jacket Arm 2",
				[5] = "Right Jacket Arm 2",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
			}
		},
		["Dress 2"] = {
			["Weld"] = {
				[1] = "Dress 2",
			}
		},
		["Scarf"] = {
			["Weld"] = {
				[1] = "Scarf"
			}
		},
		["Off Shoulder Hoodie"] = {
			["Weld"] = {
				[1] = "Off Shoulder Hoodie Shirt",
				[2] = "Left Off Shoulder Hoodie Arm",
				[3] = "Right Off Shoulder Hoodie Arm",
				[4] = "Left Off Shoulder Hoodie Arm 2",
				[5] = "Right Off Shoulder Hoodie Arm 2",
			}
		},
		["Short Hoodie"] = {
			["Weld"] = {
				[1] = "Short Hoodie",
				[2] = "Hood",
				[3] = "School Left Arm",
				[4] = "School Right Arm",
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
			}
		},
		["Shoe 2"] = {
			["Weld"] = {
				[1] = "Right Shoe 2",
				[2] = "Left Shoe 2",
			}
		},
		["Shoe 3"] = {
			["Weld"] = {
				[1] = "Right Shoe 3",
				[2] = "Left Shoe 3",
				[3] = "Left Shoe 3 Lower",
				[4] = "Left Shoe 3 Line",
				[5] = "Left Shoe 3 Nurbs Path 1",
				[6] = "Left Shoe 3 Tongue",
				[7] = "Right Shoe 3 Line",
				[8] = "Right Shoe 3 Lower",
				[9] = "Right Shoe 3 Nurbs Path 1",
				[10] = "Right Shoe 3 Nurbs Path 10",
				[11] = "Right Shoe 3 Nurbs Path 11",
				[12] = "Right Shoe 3 Nurbs Path 12",
				[13] = "Right Shoe 3 Nurbs Path 13",
				[14] = "Right Shoe 3 Nurbs Path 14",
				[15] = "Right Shoe 3 Nurbs Path 15",
				[16] = "Right Shoe 3 Nurbs Path 16",
				[17] = "Right Shoe 3 Nurbs Path 2",
				[18] = "Right Shoe 3 Nurbs Path 3",
				[19] = "Right Shoe 3 Nurbs Path 4",
				[20] = "Right Shoe 3 Nurbs Path 5",
				[21] = "Right Shoe 3 Nurbs Path 6",
				[22] = "Right Shoe 3 Nurbs Path 7",
				[23] = "Right Shoe 3 Nurbs Path 8",
				[24] = "Right Shoe 3 Nurbs Path 9",
				[25] = "Right Shoe 3 Tongue",
				[26] = "Left Shoe 3 Nurbs Path 10",
				[27] = "Left Shoe 3 Nurbs Path 11",
				[28] = "Left Shoe 3 Nurbs Path 12",
				[29] = "Left Shoe 3 Nurbs Path 13",
				[30] = "Left Shoe 3 Nurbs Path 14",
				[31] = "Left Shoe 3 Nurbs Path 15",
				[32] = "Left Shoe 3 Nurbs Path 16",
				[33] = "Left Shoe 3 Nurbs Path 2",
				[34] = "Left Shoe 3 Nurbs Path 3",
				[35] = "Left Shoe 3 Nurbs Path 4",
				[36] = "Left Shoe 3 Nurbs Path 5",
				[37] = "Left Shoe 3 Nurbs Path 6",
				[38] = "Left Shoe 3 Nurbs Path 7",
				[39] = "Left Shoe 3 Nurbs Path 8",
				[40] = "Left Shoe 3 Nurbs Path 9",
			}
		},
		["Sock 2"] = {
			["Weld"] = {
				[1] = "Right Sock 2",
				[2] = "Left Sock 2",
				[3] = "Left Sock 2 Line",
				[4] = "Right Sock 2 Line",
			}
		},
		["Glove"] = {
			["Weld"] = {
				[1] = "Right Glove",
				[2] = "Left Glove",
			}
		},
		["Tanktop"] = {
			["Weld"] = {
				[1] = "Tanktop",
			}
		},
		["Uncover Hoodie"] = {
			["Weld"] = {
				[1] = "Uncover Hoodie Breasts Shirt",
				[2] = "Uncover Hoodie Hoodie",
				[3] = "Uncover Hoodie Ropes",
				[4] = "Uncover Hoodie Shirt",
				[5] = "Uncover Hoodie Right Arm",
				[6] = "Uncover Hoodie Left Arm",
			}
		},
		["Yoru Bra"] = {
			["Weld"] = {
				[1] = "Yoru Bra",
				[5] = "Yoru Ring",
			}
		},
		["Yoru String"] = {
			["Weld"] = {
				[2] = "Yoru Middle String",
				[3] = "Yoru Left String",
				[4] = "Yoru Right String",
			}
		},
		["Glove 2"] = {
			["Weld"] = {
				[1] = "Right Glove 2",
				[2] = "Left Glove 2",
			}
		},
		["Womb Mark Cumdiction"] = {
			["Weld"] = {
				[1] = "Cumdiction",
			}
		},
		["Womb Mark Deep Focus"] = {
			["Weld"] = {
				[1] = "Deep Focus",
			}
		},
		["Womb Mark Diction"] = {
			["Weld"] = {
				[1] = "Diction",
			}
		},
		["Womb Mark Gaze"] = {
			["Weld"] = {
				[1] = "Gaze",
			}
		},
		["Womb Mark Glow"] = {
			["Weld"] = {
				[1] = "Glow",
			}
		},
		["Womb Mark Libido"] = {
			["Weld"] = {
				[1] = "Libido",
			}
		},
		["Womb Mark Phermone"] = {
			["Weld"] = {
				[1] = "Phermone",
			}
		},
		["Womb Mark Triggered"] = {
			["Weld"] = {
				[1] = "Triggered",
			}
		},
		["Womb Mark Animalistic"] = {
			["Weld"] = {
				[1] = "Animalistic",
			}
		},
		["Womb Tattoo"] = {
			["Weld"] = {
				[1] = "Womb Tattoo 4",
				[2] = "Womb Tattoo 5",
				[3] = "Womb Tattoo 3",
				[4] = "Womb Tattoo 2",
				[5] = "Womb Tattoo 6",
				[6] = "Womb Tattoo 7",
				[7] = "Womb Tattoo 8",
				[8] = "Womb Tattoo 1",
			}
		},
		["BBC Cock"] = {
			["Weld"] = {
				[1] = "BBC Rod",
				[2] = "BBC Tip",
				[3] = "BBC Balls",
			}
		},
		["BBC Cock w/ Easter Ball Paint"] = {
			["Weld"] = {
				[1] = "BBC Rod",
				[2] = "BBC Tip",
				[3] = "EasterSack",
			}
		},
		["Cock"] = {
			["Weld"] = {
				[1] = "Cock",
				[2] = "Tip",
				[3] = "Balls",
			}
		},
		["Remove Breasts"] = {
			["Unvisible"] = {
				"Left Breast",
				"Right Breast",
				"Left Nipple",
				"Right Nipple",
				"Left Areola",
				"Right Areola",
			}
		},
		["New Woman"] = {
			["Weld"] = {
				[1] = "NewWomanTorsoShirt",
				[2] = "NewWomanLeftArm",
				[3] = "NewWomanRightArm",
				[4] = "NewWomanRightLeg",
				[5] = "NewWomanLeftLeg",
				[6] = "NewWomanTorsoPants",
				[7] = "Left Butt Shirt",
				[8] = "Right Butt Shirt",
			},
		},
		["New Woman Breast"] = {
			["Weld"] = {
				[1] = "NewWomanBreastShirt",
				[2] = "NewWomanBreastPants"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple",
				"Left Breast",
				"Right Breast",
			}
		},
		["Pussy Closed"] = {
			["Weld"] = {
				[1] = "Pussy Closed",
				[2] = "Clitoris Closed",
				[3] = "Vulva Closed",
				[4] = "Vagina Closed",
			}
		},
		["Pussy Open"] = {
			["Weld"] = {
				[1] = "Pussy Open",
				[2] = "Clitoris Open",
				[3] = "Vulva Open",
				[4] = "Vagina Open",
			}
		},
		["Pussy Cum"] = {
			["Weld"] = {
				[1] = "PussyCumAttacher",
				[2] = "Pussy Cum"
			}
		},
		["Pussy Cum w/o Trail"] = {
			["Weld"] = {
				[1] = "PussyCumAttacher",
				[2] = "Pussy Cum Trailless"
			}
		},
		["Buttplug"] = {
			["Weld"] = {
				[1] = "Buttplug",
				[2] = "ButtplugGem"
			}
		},
		["Croptop"] = {
			["Weld"] = {
				[1] = "Croptop",
				[2] = "Croptop Neck"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Uncover Croptop"] = {
			["Weld"] = {
				[1] = "Lift Croptop",
				[2] = "Croptop Neck"
			}
		},
		["Croptop w/o Neck"] = {
			["Weld"] = {
				[1] = "Croptop"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Uncover Croptop w/o Neck"] = {
			["Weld"] = {
				[1] = "Lift Croptop"
			}
		},
		["Cloth Bra"] = {
			["Weld"] = {
				[1] = "Cloth Bra"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Cropped Sweater"] = {
			["Weld"] = {
				[1] = "Crop Sweater",
				[2] = "Sweater Left Arm",
				[3] = "Sweater Right Arm"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Cropped Sweater 2"] = {
			["Weld"] = {
				[1] = "Crop Sweater 2",
				[2] = "Sweater Left Arm",
				[3] = "Sweater Right Arm"
			},
			["Unvisible"] = {
				"Left Nipple",
				"Right Nipple"
			}
		},
		["Cropped Uncover Sweater"] = {
			["Weld"] = {
				[1] = "Uncovered Crop Sweater",
				[2] = "Sweater Left Arm",
				[3] = "Sweater Right Arm"
			}
		},
		["Nipple Vibrators"] = {
			["Weld"] = {
				[1] = "Left Vibrator Bullet",
				[2] = "Right Vibrator Bullet",
				[3] = "Vibrator Buttons",
				[4] = "Vibrator Tape"
			}
		},
		["Lactation"] = {
			["Weld"] = {
				[1] = "Left Nipple Lactation",
				[2] = "Right Nipple Lactation"
			}
		},
		["Fishnet Stockings"] = {
			["Weld"] = {
				[1] = "Torso String",
				[2] = "Right Leg String",
				[3] = "Left Leg String",
				[4] = "Left Butt String",
				[5] = "Right Butt String",
				[6] = "Pussy String",
			}
		},
		["Oiled"] = {
			["Weld"] = {
				[1] = "theOilerFunction",
			}
		},
		["Oiled [ALT]"] = {
			["Weld"] = {
				[1] = "theOilerFunction2",
			}
		},
		["Oiled [SKINONLY]"] = {
			["Weld"] = {
				[1] = "theOilerFunction3",
			}
		},
		["Breast Freckles"] = {
			["Weld"] = {
				[1] = "RBreastFreckles",
				[2] = "LBreastFreckles",
			}
		},
		["Butt Freckles"] = {
			["Weld"] = {
				[1] = "RButtFreckles",
				[2] = "LButtFreckles",
			}
		},
	}

	local PartList = Function.PartListDefault()

	local MetaClothes = {
		__index = {
			["Name"] = "Clothes",
			["TextureId"] = "",
			["DoubleSided"] = false,
			["Size"] = Vector3.new(1,1,1),
			["CFrame"] = CFrame.new(0,0,0),
			["CFrame1"] = CFrame.new(0,0,0),
			["Offset"] = Vector3.new(0,0,0),
			["Transparency"] = 0,
			["Reflectance"] = 0,
			["MeshBasePartTransparency"] = 0,
			["Material"] = Enum.Material.SmoothPlastic,
			["Shape"] = Enum.PartType.Block,
			["Color"] = {
				["Tone"] = "Base",
				["Color"] = Color3.fromRGB(163, 162, 165)
			},
			["Parent"] = {
				[1] = "Torso",
			},
			["Function"] = "",
			["Scale"] = nil,
			["AdjustScale"] = {"Size", "CFrame", "CFrame1"}
		}
	}

	--[[
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	
                      ███████╗██╗░░░██╗███╗░░██╗░█████╗░████████╗██╗░█████╗░███╗░░██╗░██████╗
                      ██╔════╝██║░░░██║████╗░██║██╔══██╗╚══██╔══╝██║██╔══██╗████╗░██║██╔════╝
                      █████╗░░██║░░░██║██╔██╗██║██║░░╚═╝░░░██║░░░██║██║░░██║██╔██╗██║╚█████╗░
                      ██╔══╝░░██║░░░██║██║╚████║██║░░██╗░░░██║░░░██║██║░░██║██║╚████║░╚═══██╗
                      ██║░░░░░╚██████╔╝██║░╚███║╚█████╔╝░░░██║░░░██║╚█████╔╝██║░╚███║██████╔╝
                      ╚═╝░░░░░░╚═════╝░╚═╝░░╚══╝░╚════╝░░░░╚═╝░░░╚═╝░╚════╝░╚═╝░░╚══╝╚═════╝░
                                  
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	]]

	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------PartList----------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------

	function Function.CumDripDisplay(ObjectInstance, Character, Extra, Data)
		local attach = Instance.new("Attachment",ObjectInstance)
		PlayerData[Data].CurrentPartList.RealtimeUpdateList.Special["Attachment"] = attach

		local particle = Instance.new("ParticleEmitter",attach)
		particle.Orientation = Enum.ParticleOrientation.VelocityPerpendicular
		particle.Size = NumberSequence.new(
			{NumberSequenceKeypoint.new(0,1.5,1),
				NumberSequenceKeypoint.new(1,1.5,1)}
		)
		particle.Texture = "rbxasset://RClothesContent/16235774309.png"
		particle.Transparency = NumberSequence.new(
			{NumberSequenceKeypoint.new(0,1),
				NumberSequenceKeypoint.new(.2,.5),
				NumberSequenceKeypoint.new(1,1)}
		)
		particle.ZOffset = .1
		particle.LightInfluence = 1
		particle.Lifetime = NumberRange.new(2,6)
		particle.Rate = 10
		particle.Rotation = NumberRange.new(-360,360)
		particle.Speed = NumberRange.new(0.001)
		task.delay(0,function()
			particle.Color = ColorSequence.new(ObjectInstance.Color)
		end)
	end

	function Function.Lactation(ObjectInstance, Character, Extra, Data)
		local particle = Instance.new("ParticleEmitter",ObjectInstance)
		particle.Orientation = Enum.ParticleOrientation.VelocityParallel
		particle.LightEmission = .1
		particle.LightInfluence = 1
		particle.EmissionDirection = Enum.NormalId.Bottom
		particle.Size = NumberSequence.new(.05)
		particle.Texture = "http://www.roblox.com/asset/?id=296981321"
		particle.Squash = NumberSequence.new(
			{NumberSequenceKeypoint.new(0,.7),
				NumberSequenceKeypoint.new(.752,.95),
				NumberSequenceKeypoint.new(1,.45)}
		)
		particle.Transparency = NumberSequence.new(
			{NumberSequenceKeypoint.new(0,.169),
				NumberSequenceKeypoint.new(.251,.557),
				NumberSequenceKeypoint.new(.519,.814),
				NumberSequenceKeypoint.new(.772,.918),
				NumberSequenceKeypoint.new(1,1)}
		)
		particle.Lifetime = NumberRange.new(.5)
		particle.Rate = 100
		particle.Rotation = NumberRange.new(90)
		particle.Speed = NumberRange.new(1,1.5)
		particle.SpreadAngle = Vector2.new(-10,10)
		particle.Acceleration = Vector3.new(0,-25,0)
		particle.Drag = 2
		particle.VelocityInheritance = .3
		task.delay(0,function()
			particle.Color = ColorSequence.new(ObjectInstance.Color)
		end)
	end

	function Function.OilUp(ObjectInstance, Character, Extra, Data)
		local function oil(v)
			if game:GetService("RunService"):IsStudio() then
				local mat
				if game:GetService("MaterialService"):FindFirstChild("wetSmoothROCLOTHES") then
					mat = game:GetService("MaterialService")["wetSmoothROCLOTHES"]
				else
					mat = Instance.new("MaterialVariant",game:GetService("MaterialService"))
					mat.Name="wetSmoothROCLOTHES"
					mat.BaseMaterial = Enum.Material.SmoothPlastic
					mat.MaterialPattern = Enum.MaterialPattern.Organic
					mat.RoughnessMap = "rbxassetid://14142895952"
					mat:AddTag("RoClothes")
				end

				v.Material = Enum.Material.SmoothPlastic
				v.MaterialVariant = "wetSmoothROCLOTHES"
				if v:FindFirstChildOfClass("SurfaceAppearance") then
					v.TextureID = v:FindFirstChildOfClass("SurfaceAppearance").ColorMap
					if v:FindFirstChildOfClass("SurfaceAppearance").AlphaMode == Enum.AlphaMode.Transparency then
						v.Transparency = 0.01
						v:SetAttribute("Alpha",0.01)
					end
					v:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
				end
			else
				v.Material = Enum.Material.Glass
				if v:FindFirstChildOfClass("SurfaceAppearance") then
					v.TextureID = v:FindFirstChildOfClass("SurfaceAppearance").ColorMap
					if v:FindFirstChildOfClass("SurfaceAppearance").AlphaMode == Enum.AlphaMode.Transparency then
						v.Transparency = 0.01
						v:SetAttribute("Alpha",0.01)
					end
					v:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
				end
			end
		end
		task.delay(0,function()
			for i, v in pairs(PlayerData[Data].CurrentPartList.Organ) do
				oil(v)
			end
			for i, v in pairs(PlayerData[Data].CurrentPartList.Clothes) do
				if string.find(string.lower(v.Name),"shirt") then
					oil(v)
					v.Transparency = 0.01
				end
			end
		end)
	end
	function Function.OilUp2(ObjectInstance, Character, Extra, Data)
		local function oil(v)
			if game:GetService("RunService"):IsStudio() then
				v.Material = Enum.Material.Glass
				if v:FindFirstChildOfClass("SurfaceAppearance") then
					v.TextureID = v:FindFirstChildOfClass("SurfaceAppearance").ColorMap
					if v:FindFirstChildOfClass("SurfaceAppearance").AlphaMode == Enum.AlphaMode.Transparency then
						v.Transparency = 0.01
						v:SetAttribute("Alpha",0.01)
					end
					v:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
				end
			else
				local mat
				if game:GetService("MaterialService"):FindFirstChild("wetSmoothROCLOTHES") then
					mat = game:GetService("MaterialService")["wetSmoothROCLOTHES"]
				else
					mat = Instance.new("MaterialVariant",game:GetService("MaterialService"))
					mat.Name="wetSmoothROCLOTHES"
					mat.BaseMaterial = Enum.Material.SmoothPlastic
					mat.MaterialPattern = Enum.MaterialPattern.Organic
					mat.RoughnessMap = "rbxassetid://14142895952"
					mat:AddTag("RoClothes")
				end

				v.Material = Enum.Material.SmoothPlastic
				v.MaterialVariant = "wetSmoothROCLOTHES"
				if v:FindFirstChildOfClass("SurfaceAppearance") then
					v.TextureID = v:FindFirstChildOfClass("SurfaceAppearance").ColorMap
					if v:FindFirstChildOfClass("SurfaceAppearance").AlphaMode == Enum.AlphaMode.Transparency then
						v.Transparency = 0.01
						v:SetAttribute("Alpha",0.01)
					end
					v:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
				end
			end
		end
		task.delay(0,function()
			for i, v in pairs(PlayerData[Data].CurrentPartList.Organ) do
				oil(v)
			end
			for i, v in pairs(PlayerData[Data].CurrentPartList.Clothes) do
				if string.find(string.lower(v.Name),"shirt") then
					oil(v)
					v.Transparency = 0.01
				end
			end
		end)
	end
	function Function.OilUp3(ObjectInstance, Character, Extra, Data)
		local function oil(v)
			if game:GetService("RunService"):IsStudio() then
				local mat
				if game:GetService("MaterialService"):FindFirstChild("wetSmoothROCLOTHES") then
					mat = game:GetService("MaterialService")["wetSmoothROCLOTHES"]
				else
					mat = Instance.new("MaterialVariant",game:GetService("MaterialService"))
					mat.Name="wetSmoothROCLOTHES"
					mat.BaseMaterial = Enum.Material.SmoothPlastic
					mat.MaterialPattern = Enum.MaterialPattern.Organic
					mat.RoughnessMap = "rbxassetid://14142895952"
					mat:AddTag("RoClothes")
				end

				v.Material = Enum.Material.SmoothPlastic
				v.MaterialVariant = "wetSmoothROCLOTHES"
			else
				v.Material = Enum.Material.Glass
			end
		end
		task.delay(0,function()
			for i, v in pairs(PlayerData[Data].CurrentPartList.Organ) do
				oil(v)
			end
		end)
	end

	function Function.addFreckles(ObjectInstance, Character, Extra, Data)
		if ObjectInstance.Name == "UnnecessaryPart" then
			ObjectInstance = ObjectInstance.Parent
		end
		for i = 1, 6 do
			local Texture = Instance.new("Decal", ObjectInstance)
			Texture.Color3 = Color3.fromRGB(255,255,255)
			Texture.Texture = "rbxassetid://7317286674"
			Texture.Transparency = 0.55
			PlayerData[Data].CurrentPartList.TransparencyLink[Texture] = {T=ObjectInstance,Define=.55}

			if i == 1 then
				Texture.Face = "Left"
			elseif i == 2 then
				Texture.Face = "Right"
			elseif i == 3 then
				Texture.Face = "Back"
			elseif i == 4 then
				Texture.Face = "Front"
			elseif i == 5 then
				Texture.Face = "Bottom"
			elseif i == 6 then
				Texture.Face = "Top"
			end
		end
	end

	function Function.TurtleTexture(ObjectInstance, Character, Extra, Data)
		for i = 1, 6 do
			local Texture = Instance.new("Texture", ObjectInstance)
			Texture.Color3 = Color3.fromRGB(255,255,255)
			Texture.Texture = "rbxasset://RClothesContent/187645444.png"
			Texture.Transparency = 0.3

			if i == 1 then
				Texture.Face = "Left"
			elseif i == 2 then
				Texture.Face = "Right"
			elseif i == 3 then
				Texture.Face = "Back"
			elseif i == 4 then
				Texture.Face = "Front"
			elseif i == 5 then
				Texture.Face = "Bottom"
			elseif i == 6 then
				Texture.Face = "Top"
			end
		end
	end


	function Function.StringTexture(ObjectInstance, Character, Extra, Data)
		for i = 1, 6 do
			local Texture = Instance.new("Texture", ObjectInstance)
			Texture.Texture = "rbxassetid://12083492516"
			Texture.Transparency = 0.3
			Texture.StudsPerTileU = 10
			Texture.StudsPerTileV = 12
			task.delay(0,function()
				Texture.Color3 = ObjectInstance.Color
			end)

			if i == 1 then
				Texture.Face = "Left"
			elseif i == 2 then
				Texture.Face = "Right"
			elseif i == 3 then
				Texture.Face = "Back"
			elseif i == 4 then
				Texture.Face = "Front"
			elseif i == 5 then
				Texture.Face = "Bottom"
			elseif i == 6 then
				Texture.Face = "Top"
			end
		end
	end

	function Function.FabricTexture(ObjectInstance, Character, Extra, Data)
		for i = 1, 6 do
			local Texture = Instance.new("Texture", ObjectInstance)
			Texture.Color3 = Color3.fromRGB(55, 55, 55)
			Texture.Texture = "rbxasset://RClothesContent/739677490.png"
			Texture.Transparency = 0.3

			if i == 1 then
				Texture.Face = "Left"
			elseif i == 2 then
				Texture.Face = "Right"
			elseif i == 3 then
				Texture.Face = "Back"
			elseif i == 4 then
				Texture.Face = "Front"
			elseif i == 5 then
				Texture.Face = "Bottom"
			elseif i == 6 then
				Texture.Face = "Top"
			end
		end
	end

	function Function.SockLineDecal(ObjectInstance, Character, Extra, Data)
		for i = 1, 4 do
			local Texture = Instance.new("Texture", ObjectInstance)
			Texture.Color3 = Color3.fromRGB(255, 255, 255)
			Texture.Texture = "rbxasset://RClothesContent/8131038954.png"
			Texture.Transparency = 0.3

			if i == 1 then
				Texture.Face = "Left"
			elseif i == 2 then
				Texture.Face = "Right"
			elseif i == 3 then
				Texture.Face = "Back"
			elseif i == 4 then
				Texture.Face = "Front"
			--[[elseif i == 5 then
				Texture.Face = "Bottom"
			elseif i == 6 then
				Texture.Face = "Top"]]
			end
		end
	end

	function Function.AreolaDecalCreate(ObjectInstance, Character, Extra, Data)
		if not table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing") and ObjectInstance.Transparency ~= 1 or table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing") and (ObjectInstance.Name ~= "Left Breast" and ObjectInstance.Name ~= "Right Breast") and ObjectInstance.Transparency ~= 1 then
			for i = 1, 2 do
				local Decal = Instance.new("Decal", ObjectInstance)
				Decal.Color3 = Color3.fromRGB(255, 167, 169)
				Decal.Texture = "rbxasset://RClothesContent/6667257628.png"
				Decal.Face = "Left"
				Decal.Name = "Areola Decal".." "..tostring(i)
				PlayerData[Data].CurrentPartList.AreolaDecal[Decal] = ObjectInstance

				if Extra.Tone == "Dark" then
					local H,S,V = ObjectInstance.Color:ToHSV()
					local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

					Decal.Color3 = DarkerColorCode
				elseif Extra.Tone == "Use NippleColor" then
					if Extra.NippleColor ~= nil then
						Decal.Color3 = Extra.NippleColor
					end
				end
			end
		else
			for i = 1, 2 do
				local Decal = Instance.new("Decal", ObjectInstance)
				Decal.Transparency = 1
				Decal.Color3 = Color3.fromRGB(255, 167, 169)
				Decal.Texture = "rbxasset://RClothesContent/6667257628.png"
				Decal.Face = "Left"
				Decal.Name = "Areola Decal".." "..tostring(i)
				PlayerData[Data].CurrentPartList.AreolaDecal[Decal] = ObjectInstance

				if Extra.Tone == "Dark" then
					local H,S,V = ObjectInstance.Color:ToHSV()
					local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

					Decal.Color3 = DarkerColorCode
				elseif Extra.Tone == "Use NippleColor" then
					if Extra.NippleColor ~= nil then
						Decal.Color3 = Extra.NippleColor
					end
				end
			end
		end
	end

	function Function.AreolaDecalType2Create(ObjectInstance, Character, Extra, Data)
		if not table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing") and ObjectInstance.Transparency ~= 1 or table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing") and (ObjectInstance.Name ~= "Left Breast" and ObjectInstance.Name ~= "Right Breast") and ObjectInstance.Transparency ~= 1 then
			local Decal = Instance.new("Decal", ObjectInstance)
			Decal.Color3 = Color3.fromRGB(255, 167, 169)
			Decal.Texture = "rbxasset://RClothesContent/10374562715.png"
			Decal.Face = "Front"
			Decal.Name = "Areola Decal"
			PlayerData[Data].CurrentPartList.AreolaDecal[Decal] = ObjectInstance

			if Extra.Tone == "Dark" then
				local H,S,V = ObjectInstance.Color:ToHSV()
				local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

				Decal.Color3 = DarkerColorCode
			elseif Extra.Tone == "Use NippleColor" then
				if Extra.NippleColor ~= nil then
					Decal.Color3 = Extra.NippleColor
				end
			end
		else
			local Decal = Instance.new("Decal", ObjectInstance)
			Decal.Transparency = 1
			Decal.Color3 = Color3.fromRGB(255, 167, 169)
			Decal.Texture = "rbxasset://RClothesContent/10374562715.png"
			Decal.Face = "Front"
			Decal.Name = "Areola Decal"
			PlayerData[Data].CurrentPartList.AreolaDecal[Decal] = ObjectInstance

			if Extra.Tone == "Dark" then
				local H,S,V = ObjectInstance.Color:ToHSV()
				local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

				Decal.Color3 = DarkerColorCode
			elseif Extra.Tone == "Use NippleColor" then
				if Extra.NippleColor ~= nil then
					Decal.Color3 = Extra.NippleColor
				end
			end
		end
	end

	function Function.AreolaDecalType3Create(ObjectInstance, Character, Extra, Data)
		if not table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing") and ObjectInstance.Transparency ~= 1 or table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing") and (ObjectInstance.Name ~= "Left Breast" and ObjectInstance.Name ~= "Right Breast") and ObjectInstance.Transparency ~= 1 then
			local Decal = Instance.new("Decal", ObjectInstance)
			Decal.Color3 = Color3.fromRGB(255, 167, 169)
			Decal.Texture = "rbxasset://RClothesContent/9065282081.png"
			Decal.Face = "Right"
			Decal.Name = "Areola Decal"
			PlayerData[Data].CurrentPartList.AreolaDecal[Decal] = ObjectInstance

			if Extra.Tone == "Dark" then
				local H,S,V = ObjectInstance.Color:ToHSV()
				local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

				Decal.Color3 = DarkerColorCode
			elseif Extra.Tone == "Use NippleColor" then
				if Extra.NippleColor ~= nil then
					Decal.Color3 = Extra.NippleColor
				end
			end
		else
			local Decal = Instance.new("Decal", ObjectInstance)
			Decal.Transparency = 1
			Decal.Color3 = Color3.fromRGB(255, 167, 169)
			Decal.Texture = "rbxasset://RClothesContent/9065282081.png"
			Decal.Face = "Right"
			Decal.Name = "Areola Decal"
			PlayerData[Data].CurrentPartList.AreolaDecal[Decal] = ObjectInstance

			if Extra.Tone == "Dark" then
				local H,S,V = ObjectInstance.Color:ToHSV()
				local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

				Decal.Color3 = DarkerColorCode
			elseif Extra.Tone == "Use NippleColor" then
				if Extra.NippleColor ~= nil then
					Decal.Color3 = Extra.NippleColor
				end
			end
		end
	end

	function Function.DarkPart(ObjectInstance, Character, Extra, Data)
		if Extra.Tone == "Dark" then
			local H,S,V = ObjectInstance.Parent.Color:ToHSV()
			local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

			ObjectInstance.Color = DarkerColorCode
		elseif Extra.Tone == "Use NippleColor" then
			if Extra.NippleColor ~= nil then
				ObjectInstance.Color = Extra.NippleColor
			end
		end
	end

	function Function.Dark2Part(ObjectInstance, Character, Extra, Data)
		if Extra.Tone == "Dark" then
			local H,S,V = ObjectInstance.Parent.Color:ToHSV()
			local DarkerColorCode = Color3.fromHSV(H,S,V+(-Darker2ColorPercentage * V/100))

			ObjectInstance.Color = DarkerColorCode
		elseif Extra.Tone == "Use NippleColor" then
			if Extra.NippleColor ~= nil then
				local H,S,V = Extra.NippleColor:ToHSV()
				local DarkerColorCode = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))

				ObjectInstance.Color = DarkerColorCode
			end
		end
	end

	function Function.ToarBreastsOffset(ObjectInstance, Character, Extra, Data)
		local Torso = Character:WaitForChild("Torso")
		local LB = Torso:WaitForChild("Left Breast")
		local RB = Torso:WaitForChild("Right Breast")
		local LBW = LB:WaitForChild("Left Breast Weld")
		local RBW = RB:WaitForChild("Right Breast Weld")

		local LCF0 = CFrame.new(-0.24647522, 0.635473013, -0.450714111, 0.171514884, 0.185762599, -0.967509627, -0.0996441022, 0.980297148, 0.170553446, 0.980129421, 0.067154184, 0.186645687)
		local LCF1 = CFrame.new(0.200012207, 0.400001526, -1.52587891e-05, 1, 0, 0, 0, 1, 0, 0, 0, 1)
		local RCF0 = CFrame.new(0.246000007, 0.63499999, -0.451000005, -0.157161966, -0.1847606, -0.970135868, -0.0996441022, 0.980297148, -0.170553446, 0.982533038, 0.0698638037, -0.172475725)
		local RCF1 = CFrame.new(0.200000003, 0.400000006, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)

		local XM, YM, ZM = Function.MultiplyCalculate(Torso.Size, BodyPartSize[Torso.Name])

		local RealtimeProperty = PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[LB]

		RealtimeProperty.CFrame = LCF0

		RealtimeProperty.CFrame1 = LCF1

		PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[LB] = RealtimeProperty

		local RealtimeProperty2 = PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[RB]
		RealtimeProperty2.CFrame = RCF0
		RealtimeProperty2.CFrame1 = RCF1
		PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[RB] = RealtimeProperty2

		if PlayerData[Data].MeshSizeLock == false then
			LBW.C0 = CFrame.new(LCF0.Position.X * XM, LCF0.Position.Y * YM, LCF0.Position.Z * ZM) * LCF0.Rotation
			LBW.C1 = CFrame.new(LCF1.Position.X * XM, LCF1.Position.Y * YM, LCF1.Position.Z * ZM) * LCF1.Rotation
			RBW.C0 = CFrame.new(RCF0.Position.X * XM, RCF0.Position.Y * YM, RCF0.Position.Z * ZM) * RCF0.Rotation
			RBW.C1 = CFrame.new(RCF1.Position.X * XM, RCF1.Position.Y * YM, RCF1.Position.Z * ZM) * RCF1.Rotation
		else
			LBW.C0 = LCF0
			LBW.C1 = LCF1
			RBW.C0 = RCF0
			RBW.C1 = RCF1
		end
	end

	function Function.BunnyBandPin(ObjectInstance, Character, Extra, Data)
		local BasePart

		if ObjectInstance.Name == "Left Bunny Band" then
			BasePart = Character:FindFirstChild("Left Arm")
		else
			BasePart = Character:FindFirstChild("Right Arm")
		end

		local Pin = Instance.new("Part", ObjectInstance)
		Pin.Shape = Enum.PartType.Cylinder
		Pin.Color = Color3.fromRGB(253, 234, 141)
		Pin.Material = Enum.Material.Metal
		Pin.CanCollide = false
		Pin.CanQuery = false
		Pin.CanTouch = false
		Pin.Massless = true
		Pin.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)
		Pin.Size = Vector3.new(0.052, 0.269, 0.218)

		local Weld = Instance.new("Weld", Pin)
		Weld.Part0 = ObjectInstance
		Weld.Part1 = Pin
		Weld.C0 = CFrame.new(0.007, 0, -0.593) * CFrame.Angles(0, 0, math.rad(180))

		PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[Pin] = {Size = Pin.Size, CFrame = Weld.C0, CFrame1 = CFrame.new(0,0,0), Base = BasePart, Weld = Weld}
	end

	function Function.SurfaceTexture(ObjectInstance, Character, Extra, Data)	
		local SP = Instance.new("SurfaceAppearance", ObjectInstance)
		SP.ColorMap = ObjectInstance.TextureID
		ObjectInstance.TextureID = ""
	end

	function Function.ShirtTexture(ObjectInstance, Character, Extra, Data)	
		if Extra.Shirt and table.find(PlayerData[Data].CurrentClothes, "Roblox Shirt") then
			local SP = Instance.new("SurfaceAppearance", ObjectInstance)
			SP.ColorMap = Extra.Shirt.ShirtTemplate
		end
	end

	function Function.PantsTexture(ObjectInstance, Character, Extra, Data)
		if Extra.Pants and table.find(PlayerData[Data].CurrentClothes, "Roblox Pants") then
			local SP = Instance.new("SurfaceAppearance", ObjectInstance)
			SP.ColorMap = Extra.Pants.PantsTemplate
		end
	end

	function Function.TorsoShirtTexture(ObjectInstance, Character, Extra, Data)
		if Extra.Shirt and (table.find(PlayerData[Data].CurrentClothes, "Roblox Shirt") or table.find(PlayerData[Data].CurrentClothes, "New Woman") or table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing")) then
			local SP = Instance.new("SurfaceAppearance", ObjectInstance)
			SP.ColorMap = Extra.Shirt.ShirtTemplate
			SP.AlphaMode = Enum.AlphaMode.Transparency
			ObjectInstance.Transparency = 0
		end
	end

	function Function.TorsoPantsTexture(ObjectInstance, Character, Extra, Data)
		if Extra.Pants and (table.find(PlayerData[Data].CurrentClothes, "Roblox Pants") or table.find(PlayerData[Data].CurrentClothes, "Roblox Breasts Clothing")) then
			local SP = Instance.new("SurfaceAppearance", ObjectInstance)
			SP.ColorMap = Extra.Pants.PantsTemplate
			SP.AlphaMode = Enum.AlphaMode.Transparency
			ObjectInstance.Transparency = 0
		end
	end

	function Function.TorsoShirtGraphic(ObjectInstance, Character, Extra, Data)
		if Extra.TShirt and table.find(PlayerData[Data].CurrentClothes, "Roblox Shirt") then
			local Decal = Instance.new("SurfaceAppearance", ObjectInstance)
			Decal.Texture = Extra.TShirt.Graphic
		end
	end

	function Function.NewWomanShirtClothing(ObjectInstance, Character, Extra, Data)
		local Model = Instance.new("Model", ObjectInstance)
		if ObjectInstance.Name == "New Woman Left Arm Mesh" then
			local Arm = ObjectInstance:Clone()
			Arm.Transparency = 0
			Arm.Parent = Model
			Arm.Name = "Left Arm"
			local weld = Instance.new("Weld", Model)
			weld.Part0 = ObjectInstance
			weld.Part1 = Arm
			local Cmesh = Instance.new("CharacterMesh", Model)
			Cmesh.BodyPart = Enum.BodyPart.LeftArm
			Cmesh.MeshId = 83001137
		else
			local Arm = ObjectInstance:Clone()
			Arm.Transparency = 0
			Arm.Parent = Model
			Arm.Name = "Right Arm"
			local weld = Instance.new("Weld", Model)
			weld.Part0 = ObjectInstance
			weld.Part1 = Arm
			local Cmesh = Instance.new("CharacterMesh", Model)
			Cmesh.BodyPart = Enum.BodyPart.RightArm
			Cmesh.MeshId = 83001181
		end
		Instance.new("Humanoid", Model)
		if Extra.Shirt and table.find(PlayerData[Data].CurrentClothes, "New Woman") then
			Extra.Shirt:Clone().Parent = Model
		end
	end

	function Function.NewWomanBreastShirtClothing(ObjectInstance, Character, Extra, Data)
		if Extra.Shirt and table.find(PlayerData[Data].CurrentClothes, "New Woman") then
			local Decal = Instance.new("SurfaceAppearance", ObjectInstance)
			Decal.ColorMap = Extra.Shirt.ShirtTemplate
			Decal.AlphaMode = Enum.AlphaMode.Transparency
			for i, v in pairs(PlayerData[Data].CurrentPartList.AreolaDecal) do
				for i1, v1 in pairs(v:GetDescendants()) do
					if v1.ClassName == "Decal" then
						v1.Transparency = 1
					end
				end
			end
		end
	end
	function Function.NewWomanBreastPantsClothing(ObjectInstance, Character, Extra, Data)
		if Extra.Shirt and table.find(PlayerData[Data].CurrentClothes, "New Woman") then
			local Decal = Instance.new("SurfaceAppearance", ObjectInstance)
			Decal.ColorMap = Extra.Shirt.ShirtTemplate
			Decal.AlphaMode = Enum.AlphaMode.Transparency
			for i, v in pairs(PlayerData[Data].CurrentPartList.AreolaDecal) do
				for i1, v1 in pairs(v:GetDescendants()) do
					if v1.ClassName == "Decal" then
						v1.Transparency = 1
					end
				end
			end
		end
	end

	function Function.NewWomanTorsoShirtClothing(ObjectInstance, Character, Extra, Data)
		if Extra.Shirt and table.find(PlayerData[Data].CurrentClothes, "New Woman") then
			local Decal = Instance.new("SurfaceAppearance", ObjectInstance)
			Decal.ColorMap = Extra.Shirt.ShirtTemplate
		end
	end

	function Function.NewWomanTorsoPantsClothing(ObjectInstance, Character, Extra, Data)
		if Extra.Pants and table.find(PlayerData[Data].CurrentClothes, "New Woman") then
			local Decal = Instance.new("SurfaceAppearance", ObjectInstance)
			Decal.ColorMap = Extra.Pants.PantsTemplate
			Decal:Clone().Parent = PlayerData[Data].CurrentPartList.Organ["Right Butt"]
			Decal:Clone().Parent = PlayerData[Data].CurrentPartList.Organ["Left Butt"]
		end
	end

	function Function.NewWomanPantsClothing(ObjectInstance, Character, Extra, Data)
		if Extra.Pants and table.find(PlayerData[Data].CurrentClothes, "New Woman") then
			local Decal = Instance.new("SurfaceAppearance", ObjectInstance)
			Decal.ColorMap = Extra.Pants.PantsTemplate
		end
	end

	function Function.BreastsType2Mesh(ObjectInstance, Character, Extra, Data)
		local SpecialMesh = Instance.new("SpecialMesh")
		local Scale = PlayerData[Data]["BreastsScale"]

		SpecialMesh.MeshType = Enum.MeshType.FileMesh

		if ObjectInstance.Name == "Left Breast" then
			SpecialMesh.MeshId = "rbxasset://RClothesContent/99196487433776.mesh"
		else
			SpecialMesh.MeshId = "rbxasset://RClothesContent/135832822984550.mesh"
		end

		if Scale ~= nil then
			SpecialMesh.Scale = Function.Vector3Multiply(Vector3.new(1, 1, 1), {X = Scale, Y = Scale, Z = Scale})
		else
			SpecialMesh.Scale = Vector3.new(1, 1, 1)
		end

		SpecialMesh.Parent = ObjectInstance
	end

	function Function.BreastsType3Mesh(ObjectInstance, Character, Extra, Data)
		local SpecialMesh = Instance.new("SpecialMesh")
		local Scale = PlayerData[Data]["BreastsScale"]

		SpecialMesh.MeshType = Enum.MeshType.FileMesh

		if ObjectInstance.Name == "Left Breast" then
			SpecialMesh.MeshId = "rbxasset://RClothesContent/5270415437.mesh"
		else
			SpecialMesh.MeshId = "rbxasset://RClothesContent/5270413797.mesh"
		end

		if Scale ~= nil then
			SpecialMesh.Scale = Function.Vector3Multiply(Vector3.new(0.541, 0.541, 0.541), {X = Scale, Y = Scale, Z = Scale})
		else
			SpecialMesh.Scale = Vector3.new(0.541, 0.541, 0.541)
		end

		SpecialMesh.Parent = ObjectInstance
	end

	function Function.AreolaType4Mesh(ObjectInstance, Character, Extra, Data)
		local SpecialMesh = Instance.new("SpecialMesh")

		SpecialMesh.MeshType = Enum.MeshType.Sphere
		SpecialMesh.Parent = ObjectInstance
	end

	function Function.BreastPhysics(ObjectInstance, Character, Extra, Data)
		if PlayerData[Data].BodyPartPhysics then
			local Torso = Character:FindFirstChild("Torso")

			if Torso then
				local Rotation = {
					X = 2.5,
					Y = -5,
					Z = 0
				}
				local Position = {
					X = 0,
					Y = 0,
					Z = 0
				}	

				Function.SpringCreate(
					ObjectInstance, 
					Torso, 
					Vector3.new(1,1,1) * 5, 
					Vector3.new(0,0,0), 
					10, 
					0.2, 
					{
						X = "X",
						Y = "Y",
						Z = "Z",
					},
					Position,
					{
						X = "Z",
						Y = "X",
						Z = "Y",
					},
					Rotation,
					Data
				)
			end
		end
	end

	function Function.VibratorStrings(ObjectInstance, Character, Extra, Data)
		for i = 1, 6 do
			local Right = Instance.new("Attachment", ObjectInstance)
			Right.CFrame = CFrame.new(0.499897003, -0.149800062, 0.0025343895, 4.35450538e-08, 7.4505806e-09, 1, 3.80969833e-09, 1, -7.4505806e-09, -1, 3.80969878e-09, 4.35450538e-08)
			local Left = Instance.new("Attachment", ObjectInstance)
			Left.CFrame = CFrame.new(-0.500102997, -0.150360584, -0.00253152847, 4.35450538e-08, 7.4505806e-09, 1, 3.80969833e-09, 1, -7.4505806e-09, -1, 3.80969878e-09, 4.35450538e-08)

			local LB = PlayerData[Data].CurrentPartList.Clothes["Left Vibrator Bullet"]
			local LBR = Instance.new("Attachment", LB)
			LBR.CFrame = CFrame.new(0.0799999982, 0, -0.0649999976, 1, 7.45057704e-08, 4.09781755e-08, -7.45057704e-08, 1, -1.22124469e-15, -4.09781755e-08, -1.83186587e-15, 1)
			local LBL = Instance.new("Attachment", LB)
			LBL.CFrame = CFrame.new(0.0799999982, 0, 0.0700000003, 1, 1.043081e-07, 5.215405e-08, -1.043081e-07, 1, -3.10862362e-15, -5.215405e-08, -2.33146623e-15, 1)

			local RB = PlayerData[Data].CurrentPartList.Clothes["Right Vibrator Bullet"]
			local RBR = Instance.new("Attachment", RB)
			RBR.CFrame = CFrame.new(0.0799999982, 0, -0.0649999976, 1, 7.45057704e-08, 4.09781755e-08, -7.45057704e-08, 1, -1.22124469e-15, -4.09781755e-08, -1.83186587e-15, 1)
			local RBL = Instance.new("Attachment", RB)
			RBL.CFrame = CFrame.new(0.0799999982, 0, 0.0700000003, 1, 1.043081e-07, 5.215405e-08, -1.043081e-07, 1, -3.10862362e-15, -5.215405e-08, -2.33146623e-15, 1)

			local l1 = Instance.new("RopeConstraint",LB)
			l1.Thickness = 0.02
			l1.Length = 1.5
			l1.Color = BrickColor.new("Carnation pink")
			l1.Visible = true
			l1.Attachment0 = LBR
			l1.Attachment1 = Left
			local l2 = Instance.new("RopeConstraint",LB)
			l2.Thickness = 0.02
			l2.Length = 1.5
			l2.Color = BrickColor.new("Carnation pink")
			l2.Visible = true
			l2.Attachment0 = LBL
			l2.Attachment1 = Left

			local r1 = Instance.new("RopeConstraint",RB)
			r1.Thickness = 0.02
			r1.Length = 1.5
			r1.Color = BrickColor.new("Carnation pink")
			r1.Visible = true
			r1.Attachment0 = RBL
			r1.Attachment1 = Right
			local r2 = Instance.new("RopeConstraint",RB)
			r2.Thickness = 0.02
			r2.Length = 1.5
			r2.Color = BrickColor.new("Carnation pink")
			r2.Visible = true
			r2.Attachment0 = RBR
			r2.Attachment1 = Right
		end
	end

	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	-----------------------------------------------Module-----------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------

	function Function.Spring.new(initial, clock)
		local target = initial or 0
		clock = clock or os.clock
		return setmetatable({
			_clock = clock;
			_time0 = clock();
			_position0 = target;
			_velocity0 = 0*target;
			_target = target;
			_damper = 1;
			_speed = 1;
		}, Function.Spring)
	end
	function Function.Spring:Impulse(velocity)
		self.Velocity = self.Velocity + velocity
	end
	function Function.Spring:TimeSkip(delta)
		local now = self._clock()
		local position, velocity = self:_positionVelocity(now+delta)
		self._position0 = position
		self._velocity0 = velocity
		self._time0 = now
	end
	function Function.Spring:__index(index)
		if Function.Spring[index] then
			return Function.Spring[index]
		elseif index == "Value" or index == "Position" or index == "p" then
			local position, _ = self:_positionVelocity(self._clock())
			return position
		elseif index == "Velocity" or index == "v" then
			local _, velocity = self:_positionVelocity(self._clock())
			return velocity
		elseif index == "Target" or index == "t" then
			return self._target
		elseif index == "Damper" or index == "d" then
			return self._damper
		elseif index == "Speed" or index == "s" then
			return self._speed
		elseif index == "Clock" then
			return self._clock
		else
			error(("%q is not a valid member of Spring"):format(tostring(index)), 2)
		end
	end
	function Function.Spring:__newindex(index, value)
		local now = self._clock()

		if index == "Value" or index == "Position" or index == "p" then
			local _, velocity = self:_positionVelocity(now)
			self._position0 = value
			self._velocity0 = velocity
			self._time0 = now
		elseif index == "Velocity" or index == "v" then
			local position, _ = self:_positionVelocity(now)
			self._position0 = position
			self._velocity0 = value
			self._time0 = now
		elseif index == "Target" or index == "t" then
			local position, velocity = self:_positionVelocity(now)
			self._position0 = position
			self._velocity0 = velocity
			self._target = value
			self._time0 = now
		elseif index == "Damper" or index == "d" then
			local position, velocity = self:_positionVelocity(now)
			self._position0 = position
			self._velocity0 = velocity
			self._damper = value
			self._time0 = now
		elseif index == "Speed" or index == "s" then
			local position, velocity = self:_positionVelocity(now)
			self._position0 = position
			self._velocity0 = velocity
			self._speed = value < 0 and 0 or value
			self._time0 = now
		elseif index == "Clock" then
			local position, velocity = self:_positionVelocity(now)
			self._position0 = position
			self._velocity0 = velocity
			self._clock = value
			self._time0 = value()
		else
			error(("%q is not a valid member of Spring"):format(tostring(index)), 2)
		end
	end
	function Function.Spring:_positionVelocity(now)
		local p0 = self._position0
		local v0 = self._velocity0
		local p1 = self._target
		local d = self._damper
		local s = self._speed

		local t = s*(now - self._time0)
		local d2 = d*d

		local h, si, co
		if d2 < 1 then
			h = math.sqrt(1 - d2)
			local ep = math.exp(-d*t)/h
			co, si = ep*math.cos(h*t), ep*math.sin(h*t)
		elseif d2 == 1 then
			h = 1
			local ep = math.exp(-d*t)/h
			co, si = ep, ep*t
		else
			h = math.sqrt(d2 - 1)
			local u = math.exp((-d + h)*t)/(2*h)
			local v = math.exp((-d - h)*t)/(2*h)
			co, si = u + v, u - v
		end

		local a0 = h*co + d*si
		local a1 = 1 - (h*co + d*si)
		local a2 = si/s

		local b0 = -s*si
		local b1 = s*si
		local b2 = h*co - d*si

		return a0*p0 + a1*p1 + a2*v0,b0*p0 + b1*p1 + b2*v0
	end

	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------Function----------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------
	----------------------------------------------------------------------------------------------------

	function Function.AttachmentCreate(Character)
		for Attach, ParentName in pairs(AttachmentParent) do
			local Base = Character:FindFirstChild(ParentName)

			if Base and not Base:FindFirstChild(Attach) then
				local Attachment = Instance.new("Attachment", Base)
				Attachment.Name = Attach
				Attachment.CFrame = AttachmentCFrame[Attach]
			end
		end
	end

	function Function.HeadMesh(Part)
		local SpecialMesh = Instance.new("SpecialMesh", Part)
		SpecialMesh.MeshType = Enum.MeshType.Head
		SpecialMesh.Scale = Vector3.new(1.25, 1.25, 1.25)
	end

	function Function.Dummy(CF)
		local DummyModel = Instance.new("Model")
		local DummyHumanoid = Instance.new("Humanoid", DummyModel)

		local RootPart = Instance.new("Part", DummyModel)
		RootPart.Name = "HumanoidRootPart"
		RootPart.Size = Vector3.new(2,2,1)
		RootPart.Anchored = true
		RootPart.Transparency = 1

		DummyModel.PrimaryPart = RootPart

		for Name, Property in pairs(DummyMesh) do
			local Part = Instance.new("Part", DummyModel)
			Part.Size = Property.Size
			Part.CFrame = RootPart.CFrame * Property.Offset
			Part.Anchored = true
			Part.Name = Name

			if Name == "Head" then
				Function.HeadMesh(Part)
			end
		end

		Function.AttachmentCreate(DummyModel)

		return DummyModel
	end

	function Function.CharacterPreview(Data)
		if CharacterPreviewLoading == false then
			CharacterPreviewLoading = true
			GUIObject.ViewportFrame:ClearAllChildren()

			local Dummy = Function.Dummy()

			local DataCharacter = game.Players:FindFirstChild(Data)

			if DataCharacter then
				for _, v in pairs(DataCharacter.Character:GetChildren()) do
					if v:IsA("Shirt") or v:IsA("Pants") or v:IsA("ShirtGraphic") or v:IsA("Accessory") or v:IsA("BodyColors") then
						local cv = v:Clone()

						cv.Parent = Dummy

						if cv:IsA("Accessory") then
							local Handle = cv:FindFirstChildOfClass("Part") or v:FindFirstChildOfClass("MeshPart")

							if Handle then
								local Weld = Handle:FindFirstChildOfClass("Weld")

								Weld.Part0 = Dummy:FindFirstChild(Weld.Part0.Name)
							end
						end
					elseif v:IsA("Part") then
						local Base = Dummy:FindFirstChild(v.Name)

						if Base then
							Base.Color = v.Color
						end
					end
				end
			end

			Dummy.Parent = game.Workspace
			Function.CharacterReset(SelectPlayer, Data)
			Function.CharacterExecute(Dummy, Data)

			task.wait()
			Dummy.Parent = GUIObject.ViewportFrame

			CharacterPreviewLoading = false

			return Dummy
		end
	end

	function Function.SpringCreate(Object, Base, Target, Velocity, Speed, Damper, PositionOffset, Position, RotationOffset, Rotation, Data)

		local Weld = Object:FindFirstChildOfClass("Weld")
		if Weld then
			--[[
			if Base.Name == "Torso" and Weld.Part0 == Base then
				local invert0 = Weld.Part1.CFrame:ToObjectSpace(Weld.Part1.CFrame:ToWorldSpace(Weld.C1))
				local invert1 = Weld.Part1.CFrame:ToObjectSpace(Weld.Part1.CFrame:ToWorldSpace(Weld.C0))
				PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[Object].CFrame = invert0
				PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[Object].CFrame1 = invert1
				Weld.Part0 = Object
				Weld.Part1 = Base
				Weld.C0 = invert0
				Weld.C1 = invert1
				
			end
			]]
			local CF = Weld.C0
			local CF1 = Weld.C1

			local Spring = Function.Spring.new(Vector3.new(0,0,0))
			Spring.Target = Target;
			Spring.Velocity = Velocity;
			Spring.Speed = Speed;
			Spring.Damper = Damper;


			PlayerData[Data].CurrentPartList.BodyPartPhysics[Object] = {
				Spring = Spring,
				Base = Base,
				Weld = Weld,
				CF = CF,
				CF1 = CF1,
				OriginCFrame = Base.CFrame,
				PositionOffset = PositionOffset,
				Position = Position,
				RotationOffset = RotationOffset,
				Rotation = Rotation,
				BreastsType = PlayerData[Data].BreastsType
			}
		end
	end

	function Function.MinMaxCalulate(Base, Min, Max)
		return math.max(math.min(Base, Max), Min)
	end

	function Function.CFrameOrientation(CF)
		local x, y, z = CF:ToOrientation()
		return Vector3.new(math.deg(x), math.deg(y), math.deg(z))
	end

	function Function.MultiplyCalculate(Base, Default)
		local X = Base.X / Default.X
		local Y = Base.Y / Default.Y
		local Z = Base.Z / Default.Z

		return X,Y,Z
	end

	function Function.UIStrokeCreate(Parent)
		local UIStroke = Instance.new("UIStroke")
		UIStroke.Color = Color3.fromRGB(255,255,255)
		UIStroke.Thickness = 2
		UIStroke.Transparency = 0
		UIStroke.Parent = Parent
		return UIStroke
	end

	function Function.ButtonCreate(ButtonName, ButtonParent, IsTextbox, TextboxOption)
		local Button = Instance.new("Frame")
		local Button_2

		if IsTextbox == true then
			Button_2 = Instance.new("TextBox")
		else
			Button_2 = Instance.new("TextButton")
		end

		local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
		local UICorner_2 = Instance.new("UICorner")
		local UIGradient_2 = Instance.new("UIGradient")

		Button.Name = ButtonName
		Button.Parent = ButtonParent
		Button.BackgroundColor3 = Color3.fromRGB(6, 0, 76)
		Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
		Button.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
		Button.Size = UDim2.new(0, 200, 0, 50)

		UIAspectRatioConstraint.Parent = Button

		UICorner_2.CornerRadius = UDim.new(0.25, 0)
		UICorner_2.Parent = Button

		Button_2.Parent = Button
		Button_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		Button_2.BackgroundTransparency = 1.000
		Button_2.Size = UDim2.new(1, 0, 1, 0)
		Button_2.Font = Enum.Font.Code
		Button_2.TextColor3 = Color3.fromRGB(255, 255, 255)
		Button_2.TextScaled = true
		Button_2.TextSize = 14.000
		Button_2.TextStrokeTransparency = 0.000
		Button_2.TextWrapped = true

		if IsTextbox and TextboxOption then
			Button_2.ClearTextOnFocus = false
			Button_2.PlaceholderText = TextboxOption.Text
			Button_2.PlaceholderColor3 = TextboxOption.Color
		else
			Button_2.Text = ButtonName
		end

		UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(48, 48, 48)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
		UIGradient_2.Rotation = -90
		UIGradient_2.Parent = Button

		Function.UIStrokeCreate(Button)

		if ButtonName == "nil" then
			Button.LayoutOrder = -1
		end

		return Button
	end

	function Function.CatalogAccessoryFrameAdd(Data)
		if not GUIObject.Catalog_3:FindFirstChild(Data) then
			local CatalogListFrame = Instance.new("ScrollingFrame")

			CatalogListFrame.Name = Data
			CatalogListFrame.Parent = GUIObject.Catalog_3
			CatalogListFrame.Active = true
			CatalogListFrame.AnchorPoint = Vector2.new(0.5, 0.5)
			CatalogListFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			CatalogListFrame.BackgroundTransparency = 1.000
			CatalogListFrame.BorderSizePixel = 0
			CatalogListFrame.Position = UDim2.new(0.499999911, 0, 0.76, 0)
			CatalogListFrame.Size = UDim2.new(0.949999988, 0, 0.45, 0)
			CatalogListFrame.BottomImage = "rbxassetid://5946093983"
			CatalogListFrame.MidImage = ""
			CatalogListFrame.ScrollBarThickness = 0
			CatalogListFrame.CanvasSize = UDim2.new(1, 0, 1, 0)
			CatalogListFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
			CatalogListFrame.TopImage = "rbxassetid://5946093983"

			local UIGridLayout_3 = Instance.new("UIGridLayout")

			UIGridLayout_3.Parent = CatalogListFrame
			UIGridLayout_3.SortOrder = Enum.SortOrder.LayoutOrder
			UIGridLayout_3.CellPadding = UDim2.new(0, 0, .1, 0)
			UIGridLayout_3.CellSize = UDim2.new(0.315, 0, 0.262, 0)
		end
	end

	function Function.PlayerDataAdd(Name)
		if not PlayerData[Name] then
			PlayerData[Name] = Function.PlayerDataDefault()
			PlayerData[Name].AutoExecute = false
		end
	end

	function Function.CFrameMultiply(CF, Multiply)
		return CFrame.new(
			CF.Position.X * Multiply.X,
			CF.Position.Y * Multiply.Y,
			CF.Position.Z * Multiply.Z
		) * CF.Rotation
	end

	function Function.Vector3Multiply(Vector, Multiply)
		return Vector3.new(
			Vector.X * Multiply.X,
			Vector.Y * Multiply.Y,
			Vector.Z * Multiply.Z
		)
	end

	local printed={}
	function Function.Weld(MeshDetail, Character, Extra, Data)
		if Character.Parent ~= nil then
			setmetatable(MeshDetail, MetaClothes)

			local INSTANCE = MeshDetail["Instance"]
			local NAME = MeshDetail["Name"]

			local SIZE = MeshDetail["Size"]
			local CFRAME = MeshDetail["CFrame"]
			local CFRAME1 = MeshDetail["CFrame1"]
			local OFFSET = MeshDetail["Offset"]
			if OFFSET then
				CFRAME = CFRAME+OFFSET
			end
			local TRANSPARENCY = MeshDetail["Transparency"]
			local REFLECTANCE = MeshDetail["Reflectance"]
			local MESHBASEPARTTRANSPARENCY = MeshDetail["MeshBasePartTransparency"]
			local MATERIAL = MeshDetail["Material"]
			local COLOR = MeshDetail["Color"]
			local PARENT = MeshDetail["Parent"]
			local PARENTTRANSPARENCY = MeshDetail["ParentTransparency"]
			local FUNCTION = MeshDetail["Function"]
			local SCALE = MeshDetail["Scale"]
			local ADJUSTSCALE = MeshDetail["AdjustScale"]

			local MESHID = MeshDetail["MeshId"]
			local TEXTUREID = MeshDetail["TextureId"]
			local DOUBLESIDED = MeshDetail["DoubleSided"]

			local SHAPE = MeshDetail["Shape"]

			if Debug == true then
				for i, v in pairs(PartList) do
					if NAME == v.Name and MESHID == v.MeshId then
						if not printed[i] or printed[i] == false then
							printed[i] = true
							task.delay(.1,function()
								printed[i] = false
							end)
							print(i)
							break
						end
					end
				end
			end

			local BodyPart = Character:FindFirstChild(PARENT[1])

			local OldCharacter
			if Method == 3 then
				if BodyPart and PlayerData[Data].LocalTransparency[BodyPart.Name] == true then
					OldCharacter = Character

					Character = Method2CharacterFolder:FindFirstChild(Data)

					if not Character then
						Character = Instance.new("Model", Method2CharacterFolder)
						Character.Name = Data

						local CharacterValue = Instance.new("ObjectValue", Character)
						CharacterValue.Value = OldCharacter

						for _, v in pairs(CharacterValue.Value:GetChildren()) do
							if v:IsA("BasePart") and table.find(Method2BodyPart, v.Name) then
								PlayerData[Data].CurrentPartList.ParentTransparency[v] = {v = v.Transparency}
								if v.Name ~= "Head" then
									PlayerData[Data].CurrentPartList.ParentTransparency[v] = {v = v.Transparency, T = 1}
								end

								local Part = Instance.new("Part", Character)
								Part.Size = v.Size
								Part.Name = v.Name
								Part.Transparency = 1
								Part.CanCollide = false
								Part.CanQuery = false
								Part.CanTouch = false
								Part.Massless = true
								Part.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)
								Part.Color = v.Color

								local Weld = Instance.new("Weld", Part)
								Weld.Part0 = v
								Weld.Part1 = Part
							end
						end
					end
				end
			elseif Method == 2 then
				OldCharacter = PlayerData[Data].Character
			end

			if BodyPart then
				local XMultiply, YMultiply, ZMultiply = Function.MultiplyCalculate(BodyPart.Size, BodyPartSize[PARENT[1]])

				local ObjectInstance

				local Parent = Character
				local Scale = 1

				for Index = 1, #PARENT do
					Parent = Parent:FindFirstChild(PARENT[Index])
				end

				if SCALE then
					Scale = PlayerData[Data][SCALE]
				end

				if SIZE == "Overlay" then
					SIZE = Vector3.new(Parent.Size.X+0.003,Parent.Size.Y+0.003,Parent.Size.Z+0.003)
				elseif SIZE == "Underlay" then
					SIZE = Vector3.new(Parent.Size.X-0.003,Parent.Size.Y-0.003,Parent.Size.Z-0.003)
				end

				for i, Adjust in pairs(ADJUSTSCALE) do
					if SCALE == "LegsScale" then
						if Adjust == "Size" then
							SIZE = Function.Vector3Multiply(SIZE, {X = Scale, Y = 1+((Scale-1)*.2), Z = Scale})
						elseif Adjust == "CFrame" then
							CFRAME = Function.CFrameMultiply(CFRAME, {X = Scale, Y = 1+((Scale-1)*.2), Z = Scale})
						elseif Adjust == "CFrame1" then
							CFRAME1 = Function.CFrameMultiply(CFRAME1, {X = Scale, Y = 1+((Scale-1)*.2), Z = Scale})
						end
						if i == "Size" then
							local Scale = 1+((Scale-1)*Adjust)
							SIZE = Function.Vector3Multiply(SIZE, {X = Scale, Y = 1+((Scale-1)*.2), Z = Scale})
						elseif i == "CFrame" then
							local Scale = 1+((Scale-1)*Adjust)
							CFRAME = Function.CFrameMultiply(CFRAME, {X = Scale, Y = Scale, Z = Scale})
						elseif i == "CFrame1" then
							local Scale = 1+((Scale-1)*Adjust)
							CFRAME1 = Function.CFrameMultiply(CFRAME1, {X = Scale, Y = Scale, Z = Scale})
						end
					else
						if Adjust == "Size" then
							SIZE = Function.Vector3Multiply(SIZE, {X = Scale, Y = Scale, Z = Scale})
						elseif Adjust == "CFrame" then
							CFRAME = Function.CFrameMultiply(CFRAME, {X = Scale, Y = Scale, Z = Scale})
						elseif Adjust == "CFrame1" then
							CFRAME1 = Function.CFrameMultiply(CFRAME1, {X = Scale, Y = Scale, Z = Scale})
						end
						if i == "Size" then
							local Scale = 1+((Scale-1)*Adjust)
							SIZE = Function.Vector3Multiply(SIZE, {X = Scale, Y = Scale, Z = Scale})
						elseif i == "CFrame" then
							local Scale = 1+((Scale-1)*Adjust)
							CFRAME = Function.CFrameMultiply(CFRAME, {X = Scale, Y = Scale, Z = Scale})
						elseif i == "CFrame1" then
							local Scale = 1+((Scale-1)*Adjust)
							CFRAME1 = Function.CFrameMultiply(CFRAME1, {X = Scale, Y = Scale, Z = Scale})
						end
					end
				end

				if PARENTTRANSPARENCY ~= nil then
					if OldCharacter and OldCharacter:FindFirstChild(Parent.Name) then
						PlayerData[Data].CurrentPartList.ParentTransparency[OldCharacter:FindFirstChild(Parent.Name)] = {D = OldCharacter:FindFirstChild(Parent.Name).Transparency, T = PARENTTRANSPARENCY}
						--OldCharacter:FindFirstChild(Parent.Name).Transparency = PARENTTRANSPARENCY
					end
					PlayerData[Data].CurrentPartList.ParentTransparency[Parent] = {D = Parent.Transparency, T = PARENTTRANSPARENCY}
					--Parent.Transparency = PARENTTRANSPARENCY
				end

				if INSTANCE == "Mesh" then
					if MESHID == "Parent" then
						MESHID = Parent.MeshId
					end
					ObjectInstance = IS:CreateMeshPartAsync(MESHID, Enum.CollisionFidelity.Box, Enum.RenderFidelity.Performance)
					ObjectInstance:AddTag("RoClothes")

					ObjectInstance.TextureID = TEXTUREID
					ObjectInstance.DoubleSided = DOUBLESIDED
				elseif INSTANCE == "Part" then
					ObjectInstance = Instance.new("Part")
					ObjectInstance:AddTag("RoClothes")
					ObjectInstance.Shape = SHAPE
				end

				local Color

				if COLOR["Color"] == "Parent" then
					Color = Parent.Color
				else
					Color = COLOR["Color"]
				end

				local H,S,V = Color:ToHSV()

				if COLOR["Tone"] == "Darker" then
					Color = Color3.fromHSV(H,S,V+(-DarkerColorPercentage * V/100))
				elseif COLOR["Tone"] == "Darker2" then
					Color = Color3.fromHSV(H,S,V+(-Darker2ColorPercentage * V/100))
				end

				if PlayerData[Data].MeshBasePartInvisible then
					ObjectInstance.Transparency = MESHBASEPARTTRANSPARENCY
				end

				ObjectInstance.Color = Color

				ObjectInstance.CanCollide = false
				ObjectInstance.CanQuery = false
				ObjectInstance.CanTouch = false
				ObjectInstance.Massless = true
				ObjectInstance.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)

				ObjectInstance.Name = NAME
				ObjectInstance.Transparency = TRANSPARENCY
				ObjectInstance.Reflectance = REFLECTANCE
				ObjectInstance.Material = MATERIAL

				local WeldInstance = Instance.new("Weld", ObjectInstance)
				WeldInstance.Name = NAME.." Weld"
				WeldInstance.Part0 = Parent
				WeldInstance.Part1 = ObjectInstance

				ObjectInstance.Size = SIZE

				WeldInstance.C0 = CFRAME

				WeldInstance.C1 = CFRAME1



				if PlayerData[Data].MeshSizeLock == false then
					ObjectInstance.Size = Function.Vector3Multiply(SIZE, {X = XMultiply, Y = YMultiply, Z = ZMultiply})
					WeldInstance.C0 = Function.CFrameMultiply(CFRAME, {X = XMultiply, Y = YMultiply, Z = ZMultiply})
					WeldInstance.C1 = Function.CFrameMultiply(CFRAME1, {X = XMultiply, Y = YMultiply, Z = ZMultiply})
				end


				ObjectInstance.Parent = Parent

				if FUNCTION ~= "" then
					if typeof(FUNCTION) == "string" then
						Function[FUNCTION](ObjectInstance, Character, Extra, Data)
					elseif typeof(FUNCTION) == "table" then
						for i, v in pairs(FUNCTION) do
							Function[v](ObjectInstance, Character, Extra, Data)
						end
					end
				end
				PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[ObjectInstance] = {Size = SIZE, CFrame = CFRAME, CFrame1 = CFRAME1, Base = BodyPart, Weld = WeldInstance}
				return ObjectInstance
			end 
		end

	end

	function Function.CharacterFunction(Character, Data)
		local CharacterAttachment = {}

		for _, v in pairs(Character:GetDescendants()) do
			if v:IsA("Attachment") and v.Parent.Name ~= "Handle" then
				CharacterAttachment[v.Name] = v
			end
		end

		for _, v in pairs(Character:GetDescendants()) do
			if v:IsA("Accessory") then
				local Handle = v:FindFirstChildOfClass("Part") or v:FindFirstChildOfClass("MeshPart")

				if Handle then
					if PlayerData[Data].CurrentBundle ~= "nil" then
						Handle.Transparency = 1

						PlayerData[Data].CurrentPartList.ParentTransparency[Handle] = {D = 0, T = 1}
					else
						local Attachment = Handle:FindFirstChildOfClass("Attachment")
						local SpecialMesh = Handle:FindFirstChildOfClass("SpecialMesh")
						local Weld = Handle:FindFirstChildOfClass("Weld")
						local ParentAttachment = CharacterAttachment[Attachment.Name]

						if Weld and SpecialMesh and ParentAttachment and Attachment then

							local HandleParent = ParentAttachment.Parent
							local Size = HandleParent.Size
							local HandleSize = Handle.Size

							if Size and BodyPartSize[HandleParent.Name] then
								local XMultiply, YMultiply, ZMultiply = Function.MultiplyCalculate(Size, BodyPartSize[HandleParent.Name])

								local AttachCF = Attachment.CFrame
								local PAttachCF = AttachmentCFrame[ParentAttachment.Name]
								local Scale = SpecialMesh.Scale

								PlayerData[Data].CurrentPartList.RealtimeUpdateList.Accessory[Handle] = {Scale = Scale, SpecialMesh = SpecialMesh, Size = Size, CFrame = AttachCF, Attachment = Attachment, ParentAttachment = ParentAttachment, Base = HandleParent, Weld = Weld}
							end
						end
					end
				end
			end
		end

		return CharacterAttachment
	end

	function Function.BodyColorForceSet(Character, Color)
		for i, v in pairs(BodyColorPart) do
			local Base = Character:FindFirstChild(v)

			if Base then
				Base.Color = Color
			end
		end
	end

	function Function.BodyColorSet(Character, BodyColor)
		for i, v in pairs(BodyColorPart) do
			local Base = Character:FindFirstChild(v)

			if Base then
				Base.Color = BodyColor[i]
			end
		end
	end

	function Function.BodyColorsFunction(Character, SelectBundle, Data)
		if Bundle[SelectBundle]["Body Color"] ~= nil and PlayerData[Data].BundleBodyColor then
			local BodyColors = Character:FindFirstChildOfClass("BodyColors") or Instance.new("BodyColors", Character)

			for i, v in pairs(Bundle[SelectBundle]["Body Color"]) do
				BodyColors[i] = v
			end

			Function.BodyColorSet(Character, BodyColors)

			if Method == 2 then
				Character = Character:FindFirstChildOfClass("ObjectValue").Value

				local BodyColors = Character:FindFirstChildOfClass("BodyColors") or Instance.new("BodyColors", Character)

				for i, v in pairs(Bundle[SelectBundle]["Body Color"]) do
					BodyColors[i] = v
				end

				Function.BodyColorSet(Character, BodyColors)
			end
		end
	end

	function Function.AccessoryAdd(Character, v, CharacterAttachment, Data)
		local CAccessory = v:Clone()
		local CHandle = CAccessory:FindFirstChildOfClass("Part")
		local CAttachment = CHandle:FindFirstChildOfClass("Attachment")
		local CSpecialMesh = CHandle:FindFirstChildOfClass("SpecialMesh")
		CAccessory:AddTag("RoClothes")

		PlayerData[Data].CurrentPartList["Accessory"][CAccessory.Name] = CAccessory

		local CParentAttachment = CharacterAttachment[CAttachment.Name]

		if CParentAttachment then
			local HandleParent = CParentAttachment.Parent
			local Size = HandleParent.Size
			local HandleSize = CHandle.Size

			local BodySize = BodyPartSize[HandleParent.Name]
			if not BodySize then
				if HandleParent.Name == "UpperTorso" or HandleParent.Name == "LowerTorso" then
					BodySize = BodyPartSize["Torso"]
				elseif HandleParent.Name == "RightUpperArm" or HandleParent.Name == "LeftLowerArm" then
					BodySize = BodyPartSize["Left Arm"]
				elseif HandleParent.Name == "RightUpperArm" or HandleParent.Name == "RightLowerArm" then
					BodySize = BodyPartSize["Right Arm"]
				elseif HandleParent.Name == "LeftUpperLeg" or HandleParent.Name == "LeftLowerLeg" then
					BodySize = BodyPartSize["Left Leg"]
				elseif HandleParent.Name == "RightUpperLeg" or HandleParent.Name == "RightLowerrLeg" then
					BodySize = BodyPartSize["Right Leg"]
				end
			end

			local XMultiply, YMultiply, ZMultiply = Function.MultiplyCalculate(Size, BodySize)

			local CAttachCF = CAttachment.CFrame
			local PAttachCF = AttachmentCFrame[CParentAttachment.Name]
			local Scale = CSpecialMesh.Scale

			if PlayerData[Data].AccessorySizeLock == false then
				CHandle.Size = Vector3.new(HandleSize.X * XMultiply, HandleSize.Y * YMultiply, HandleSize.Z * ZMultiply)
				CSpecialMesh.Scale = Vector3.new(Scale.X * XMultiply, Scale.Y * YMultiply, Scale.Z * ZMultiply)CAttachment.CFrame = CFrame.new(CAttachCF.Position.X * XMultiply, CAttachCF.Position.Y * YMultiply, CAttachCF.Position.Z * ZMultiply) * CAttachCF.Rotation
				CParentAttachment.CFrame = CFrame.new(PAttachCF.Position.X * XMultiply, PAttachCF.Position.Y * YMultiply, PAttachCF.Position.Z * ZMultiply) * PAttachCF.Rotation
			else
				CHandle.Size = HandleSize
				CSpecialMesh.Scale = Scale
			end

			CHandle.CanCollide = false
			CHandle.CanQuery = false
			CHandle.CanTouch = false
			CHandle.Massless = true
			CHandle.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)

			CAccessory.Parent = Character
			v:Destroy()

			local Weld = Instance.new("Weld", CHandle)
			Weld.Part0 = CHandle
			Weld.Part1 = CParentAttachment.Parent

			Weld.C0 = CAttachment.CFrame
			Weld.C1 = CParentAttachment.CFrame

			PlayerData[Data].CurrentPartList.RealtimeUpdateList.Accessory[CHandle] = {Scale = Scale, SpecialMesh = CSpecialMesh, Size = Size, CFrame = CAttachCF, Attachment = CAttachment, ParentAttachment = CParentAttachment, Base = HandleParent, Weld = Weld}
		end
	end

	function Function.HumanoidDescriptionSet(AccessoryList, ClothesList, HumanoidDescription)
		local IsAdded = false

		if AccessoryList ~= nil then
			for _, Id in pairs(AccessoryList) do
				local AccessoryInfo = MPS:GetProductInfo(Id)
				local Type = AccessoryType[AccessoryInfo.AssetTypeId]

				if HumanoidDescription[Type] == "" then
					HumanoidDescription[Type] = Id
				else
					HumanoidDescription[Type] = HumanoidDescription[Type]..", "..Id
				end

				IsAdded = true
			end
		end

		if ClothesList ~= nil then
			for Type, Id in pairs(ClothesList) do
				if Id ~= "" then
					if Type == "Shirt" then
						HumanoidDescription.Shirt = Id
					elseif Type == "Pants" then
						HumanoidDescription.Pants = Id
					elseif Type == "ShirtGraphic" then
						HumanoidDescription.GraphicTShirt = Id
					end

					IsAdded = true
				end
			end
		end

		return IsAdded
	end

	function Function.HumanoidDescriptionLoader(Character, HumanoidDescription, CharacterAttachment, UseBodyColor, Data, isCatalogUsername)
		local AccessoryLoaderModel = Instance.new("Model", game.workspace)
		local HumanoidAccessoryLoader = Instance.new("Humanoid", AccessoryLoaderModel)

		HumanoidAccessoryLoader:ApplyDescription(HumanoidDescription)
		repeat task.wait() until #AccessoryLoaderModel:GetChildren() > 2

		for _, v in pairs(AccessoryLoaderModel:GetChildren()) do
			if v:IsA("Accessory") then
				Function.AccessoryAdd(Character, v, CharacterAttachment, Data)
			elseif v:IsA("Shirt") or v:IsA("Pants") or v:IsA("ShirtGraphic") then
				local OldCloth = Character:FindFirstChildOfClass(v.ClassName)

				if OldCloth then
					if PlayerData[Data].OldestClothings[v.ClassName] == nil then
						PlayerData[Data].OldestClothings[v.ClassName] = OldCloth:Clone()
					end
					OldCloth:Destroy()
				end

				v.Parent = Character
			elseif v:IsA("BodyColors") and UseBodyColor == true then
				local OldBC = Character:FindFirstChildOfClass("BodyColors")

				if OldBC then
					OldBC:Destroy()
				end

				v.Parent = Character

				Function.BodyColorSet(Character, v)
			end
		end

		if isCatalogUsername == true then

			if Character:FindFirstChild("Head") then
				local LoadedAvatar = game:GetService("Players"):CreateHumanoidModelFromDescription(HumanoidDescription, Enum.HumanoidRigType.R6)
				local head = LoadedAvatar:WaitForChild("Head")

				local OldFC = Character:FindFirstChild("Head"):FindFirstChildOfClass("Decal")
				local OldSM = Character:FindFirstChild("Head"):FindFirstChildOfClass("SpecialMesh")

				if Character:FindFirstChild("Head"):IsA("MeshPart") then
					local v = Character:FindFirstChild("Head")
					local newHead = Instance.new("Part",Character)
					newHead:AddTag("RoClothes")
					newHead.Size = v.Size
					newHead.Name = v.Name
					newHead.CanCollide = false
					newHead.CanQuery = false
					newHead.CanTouch = false
					newHead.Massless = true
					newHead.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)
					newHead.Color = v.Color
					newHead.Material = v.Material
					newHead.Reflectance = v.Reflectance
					PlayerData[Data].CurrentPartList.Organ["Head"] = newHead

					local Weld = Instance.new("Weld", newHead)
					Weld.Part0 = v
					Weld.Part1 = newHead

					if PlayerData[Data].Face == true then
						if head:FindFirstChildOfClass("Decal") then
							if OldFC then
								OldFC:Destroy()
							end
							head:FindFirstChildOfClass("Decal"):Clone().Parent = newHead
						elseif OldFC then
							OldFC.Parent = newHead
						end
					elseif OldFC then
						OldFC:Destroy()
					end
					if head:FindFirstChildOfClass("SpecialMesh") then
						PlayerData[Data].CurrentPartList.ParentTransparency[v] = {v = v.Transparency, T = 1}
						local mesh = head:FindFirstChildOfClass("SpecialMesh"):Clone()
						mesh.Parent = newHead
						if mesh.MeshType == Enum.MeshType.Head then
							mesh.Scale = Vector3.new(1,1,1)
						end
					else
						local mesh = Instance.new("SpecialMesh",newHead)
						mesh.MeshId = v.MeshId
					end
				elseif Method == 2 then
					local oChar = game:GetService("Players")[Data].Character
					local h = Character:FindFirstChild("Head")
					PlayerData[Data].CurrentPartList.RealtimeUpdateList.Mesh[h] = {Base = h}
					h.Transparency = 0
					PlayerData[Data].CurrentPartList.ParentTransparency[h] = {D = 1}
					PlayerData[Data].CurrentPartList.ParentTransparency[oChar:FindFirstChild("Head")] = {D = oChar:FindFirstChild("Head").Transparency, T = 1}
					if OldFC then
						OldFC:Destroy()
					end
					if OldSM then
						OldSM:Destroy()
					end
					local OldFC = oChar:FindFirstChild("Head"):FindFirstChildOfClass("Decal")
					local OldSM = oChar:FindFirstChild("Head"):FindFirstChildOfClass("SpecialMesh")

					if PlayerData[Data].Face == true then
						if head:FindFirstChildOfClass("Decal") then
							if OldFC then
								OldFC.Transparency = 1
								PlayerData[Data].CurrentPartList.ParentTransparency[OldFC] = {D = 0}
							end
							local d = head:FindFirstChildOfClass("Decal"):Clone()
							PlayerData[Data].CurrentPartList.ParentTransparency[d] = {D = 1}
							d.Parent = Character:FindFirstChild("Head")
						elseif OldFC then
							local o = OldFC:Clone()
							PlayerData[Data].CurrentPartList.ParentTransparency[o] = {D = 1}
							o.Parent = Character:FindFirstChild("Head")
						end
					elseif OldFC then
						OldFC.Transparency = 1
						PlayerData[Data].CurrentPartList.ParentTransparency[OldFC] = {D = 0}
					end
					if head:FindFirstChildOfClass("SpecialMesh") then
						head:FindFirstChildOfClass("SpecialMesh"):Clone().Parent = Character:FindFirstChild("Head")
					elseif OldSM then
						OldSM:Clone().Parent = Character:FindFirstChild("Head")
					end
				else
					if head:FindFirstChildOfClass("Decal") and PlayerData[Data].Face == true then
						if OldFC then
							OldFC:Destroy()
						end
						head:FindFirstChildOfClass("Decal"):Clone().Parent = Character:FindFirstChild("Head")
					elseif OldFC then
						OldFC:Destroy()
					end
					if head:FindFirstChildOfClass("SpecialMesh") then
						if OldSM then
							OldSM:Destroy()
						end
						head:FindFirstChildOfClass("SpecialMesh"):Clone().Parent = Character:FindFirstChild("Head")
					end
				end

				LoadedAvatar:Destroy()
			end
		end

		AccessoryLoaderModel:Destroy()
		HumanoidDescription:Destroy()
	end

	function Function.AccessoryLoaderFunction(Character, CharacterAttachment, SelectBundle, Data)
		local Human = Character:FindFirstChildOfClass("Humanoid")

		local HumanoidDescription = Instance.new("HumanoidDescription", game.workspace)

		local IsAdded = Function.HumanoidDescriptionSet(Bundle[SelectBundle]["Accessory"], Bundle[SelectBundle]["Clothes"], HumanoidDescription)

		if IsAdded == true then

			Function.HumanoidDescriptionLoader(Character, HumanoidDescription, CharacterAttachment, false, Data)
		end

		HumanoidDescription:Destroy()
	end

	function Function.CatalogLoader(Character, CharacterAttachment, Data)
		local Human = Character:FindFirstChildOfClass("Humanoid")

		if PlayerData[Data].CatalogUsername ~= "" then

			pcall(function()
				local UsernameId = game.Players:GetUserIdFromNameAsync(PlayerData[Data].CatalogUsername)

				local HumanoidDescription = game.Players:GetHumanoidDescriptionFromUserId(UsernameId)

				for Type, Id in pairs(PlayerData[Data].CatalogClothes) do
					if Id ~= "" then
						if Type == "Shirt" then
							HumanoidDescription.Shirt = Id
						elseif Type == "Pants" then
							HumanoidDescription.Pants = Id
						elseif Type == "ShirtGraphic" then
							HumanoidDescription.GraphicTShirt = Id
						end
					end
				end

				if #PlayerData[Data].CatalogRemove > 0 then
					local accessories = HumanoidDescription:GetAccessories(true)
					for _, remove in pairs(PlayerData[Data].CatalogRemove) do
						for asset, accessory in pairs(accessories) do
							if accessory.AssetId == remove then
								table.remove(accessories,asset)
							end
						end
					end
					HumanoidDescription:SetAccessories(accessories,true)
				end

				Function.HumanoidDescriptionLoader(Character, HumanoidDescription, CharacterAttachment, true, Data, true)
			end)
		end
		if PlayerData[Data].CatalogOutfitId ~= "" then
			pcall(function()
				local HumanoidDescription =  game.Players:GetHumanoidDescriptionFromOutfitId(PlayerData[Data].CatalogOutfitId)

				for Type, Id in pairs(PlayerData[Data].CatalogClothes) do
					if Id ~= "" then
						if Type == "Shirt" then
							HumanoidDescription.Shirt = Id
						elseif Type == "Pants" then
							HumanoidDescription.Pants = Id
						elseif Type == "ShirtGraphic" then
							HumanoidDescription.GraphicTShirt = Id
						end
					end
				end

				if #PlayerData[Data].CatalogRemove > 0 then
					local accessories = HumanoidDescription:GetAccessories(true)
					for _, remove in pairs(PlayerData[Data].CatalogRemove) do
						for asset, accessory in pairs(accessories) do
							if accessory.AssetId == remove then
								table.remove(accessories,asset)
							end
						end
					end
					HumanoidDescription:SetAccessories(accessories,true)
				end

				Function.HumanoidDescriptionLoader(Character, HumanoidDescription, CharacterAttachment, true, Data)
			end)
		end
		local HumanoidDescription = Instance.new("HumanoidDescription", game.Workspace)

		local IsAdded = Function.HumanoidDescriptionSet(PlayerData[Data].CatalogAccessory, PlayerData[Data].CatalogClothes, HumanoidDescription)

		if IsAdded == true then
			Function.HumanoidDescriptionLoader(Character, HumanoidDescription, CharacterAttachment, false, Data)
		else
			HumanoidDescription:Destroy()
		end
	end
	function Function.TableFind(Table, Value)
		for i, v in pairs(Table) do
			if v == Value then
				return i
			end
		end
	end
	function Function.TableClone(Table)
		local newtable = {}
		for i, v in pairs(Table) do
			newtable[i] = v
		end
		return newtable
	end

	function Function.CharacterReset(PlayerName,NPCClear)
		local ExecutePlayer
		if typeof(PlayerName) ~= "Instance" then
			ExecutePlayer = game.Players:FindFirstChild(PlayerName) -- check if this function is called by Player name target(most of time 'Self')
		end

		local DataList = nil
		local PartListPlayer = nil

		if not ExecutePlayer then
			if GUIObject.PlayerExecute.Text == "Self" then
				ExecutePlayer = Player
				DataList = PlayerData[ExecutePlayer.Name]
				PartListPlayer = DataList.CurrentPartList
			end
		else
			if PlayerData[ExecutePlayer.Name] == nil then
				return
			end
			DataList = PlayerData[ExecutePlayer.Name]
			PartListPlayer = DataList.CurrentPartList
		end
		--[[ below if is for ClickExecute
		if type(PlayerName) ~= "string" and Function.IsCharacter(PlayerName) then
			if Function.TableFind(NPCs, PlayerName) == nil then
				return
			else
				local NPC = Function.TableFind(NPCs, PlayerName)
				for i, v in pairs(PlayerName:GetDescendants()) do
					if v.ClassName == "MeshPart" or v:HasTag("RoClothes") then
						if v.Parent == PlayerName:FindFirstChild("Torso") or v.Parent == PlayerName:FindFirstChild("Left Leg") or v.Parent == PlayerName:FindFirstChild("Right Leg") or
							v.Parent == PlayerName:FindFirstChild("Left Arm") or v.Parent == PlayerName:FindFirstChild("Right Arm") or v:HasTag("RoClothes") then
							v:Destroy()
						end
					end
				end
				if Method2CharacterFolder:FindFirstChild(NPC) then
					for i, v in pairs(Method2CharacterFolder[NPC]:GetDescendants()) do
						if v.ClassName == "MeshPart" or v:HasTag("RoClothes") then
							if v.Parent == PlayerName:FindFirstChild("Torso") or v.Parent == PlayerName:FindFirstChild("Left Leg") or v.Parent == PlayerName:FindFirstChild("Right Leg") or
								v.Parent == PlayerName:FindFirstChild("Left Arm") or v.Parent == PlayerName:FindFirstChild("Right Arm") or v:HasTag("RoClothes") then
								v:Destroy()
							end
						end
					end
				end
				if NPCClear == true then
					PlayerData[Function.TableFind(NPCs, PlayerName)] = nil
				end
			end
			return
		end]]

		if type(PlayerName) ~= "string" and Function.IsCharacter(PlayerName) then
			if Function.TableFind(NPCs, PlayerName) == nil or not PlayerData[Function.TableFind(NPCs, PlayerName)] then
				return
			else
				DataList = PlayerData[Function.TableFind(NPCs, PlayerName)]
				PartListPlayer = DataList.CurrentPartList
				if NPCClear == true then
					PlayerData[Function.TableFind(NPCs, PlayerName)] = nil
				end
			end
		end

		if DataList["Cooldown"] == true then
			return
		end

		if PartListPlayer then
			local OrganList = PartListPlayer["Organ"]
			local ClothesList = PartListPlayer["Clothes"]
			local AccessoryList = PartListPlayer["Accessory"]
			local ParentTransparencyList = PartListPlayer["ParentTransparency"]

			if OrganList then
				for _, v in pairs(OrganList) do
					v:Destroy()
				end
			end

			if ClothesList then
				for _, v in pairs(ClothesList) do
					v:Destroy()
				end
			end

			if AccessoryList then
				for _, v in pairs(AccessoryList) do
					v:Destroy()
				end
			end

			if ParentTransparencyList then
				for Object, Property in pairs(ParentTransparencyList) do
					local D = Property.D
					if D ~= nil then
						Object.Transparency = D
						Object.LocalTransparencyModifier = Object.Transparency
					end
				end
			end

			PlayerData[ExecutePlayer.Name].CurrentPartList = Function.PlayerDataDefault().CurrentPartList

			--[[
			if Method == 2 then
				local Character = Method2CharacterFolder:FindFirstChild(PlayerName)

				if Character then
					for _, v in pairs(Character:GetChildren()) do
						if v:IsA("BasePart") then
							v.Transparency = 1
						end
					end
				end
			end
			]]

			for i, v in pairs(game:GetService("CollectionService"):GetTagged("Visibility")) do
				v.Transparency = v:GetAttribute("Visibility")
				v.LocalTransparencyModifier = v.Transparency
				v:SetAttribute("Visibility",nil)
				v:RemoveTag("Visibility")
			end
			if PlayerData[ExecutePlayer.Name].OldestClothings.Shirt then
				if ExecutePlayer.Character:FindFirstChildOfClass("Shirt") then
					ExecutePlayer.Character:FindFirstChildOfClass("Shirt"):Destroy()
				end
				PlayerData[ExecutePlayer.Name].OldestClothings.Shirt:Clone().Parent = ExecutePlayer.Character
				PlayerData[ExecutePlayer.Name].OldestClothings.Shirt = nil
			end
			if PlayerData[ExecutePlayer.Name].OldestClothings.Pants then
				if ExecutePlayer.Character:FindFirstChildOfClass("Pants") then
					ExecutePlayer.Character:FindFirstChildOfClass("Pants"):Destroy()
				end
				PlayerData[ExecutePlayer.Name].OldestClothings.Pants:Clone().Parent = ExecutePlayer.Character
				PlayerData[ExecutePlayer.Name].OldestClothings.Pants = nil
			end
			if PlayerData[ExecutePlayer.Name].OldestClothings.ShirtGraphic then
				if ExecutePlayer.Character:FindFirstChildOfClass("ShirtGraphic") then
					ExecutePlayer.Character:FindFirstChildOfClass("ShirtGraphic"):Destroy()
				end
				PlayerData[ExecutePlayer.Name].OldestClothings.ShirtGraphic:Clone().Parent = ExecutePlayer.Character
				PlayerData[ExecutePlayer.Name].OldestClothings.ShirtGraphic = nil
			end

		end
	end

	function Function.BBCRodPhysics(ObjectInstance, Character, Extra, Data)
		if PlayerData[Data].BodyPartPhysics then
			local PhysicsRotationOffset = {
				X = "Y",
				Y = "X",
				Z = "Z",
			}
			Function.SpringCreate(
				ObjectInstance, 
				PlayerData[Data].CurrentPartList["Organ"]["Torso"], 
				Vector3.new(1,1,1) * 5, 
				Vector3.new(0,0,0), 
				10, 
				0.2, 
				{
					X = "X",
					Y = "Y",
					Z = "Z",
				},
				{
					X = 0,
					Y = 0,
					Z = 0
				},
				PhysicsRotationOffset,
				{
					X = 2,
					Y = 7,
					Z = 5
				},
				Data
			)
		end
	end

	function Function.BBCBallPhysics(ObjectInstance, Character, Extra, Data)
		if PlayerData[Data].BodyPartPhysics then
			local PhysicsRotationOffset = {
				X = "Y",
				Y = "X",
				Z = "Z",
			}
			local Rod
			if tostring(ObjectInstance) == "BBC Balls" then
				Rod = PlayerData[Data].CurrentPartList["Clothes"]["BBC Rod"]
			else
				Rod = PlayerData[Data].CurrentPartList["Clothes"]["Cock"]
			end
			Function.SpringCreate(
				ObjectInstance,
				Rod, 
				Vector3.new(1,1,1) * 5, 
				Vector3.new(0,0,0), 
				10, 
				0.2, 
				{
					X = "X",
					Y = "Y",
					Z = "Z",
				},
				{
					X = 0,
					Y = 0,
					Z = 0
				},
				PhysicsRotationOffset,
				{
					X = 2,
					Y = 1/10,
					Z = 5
				},
				Data
			)
		end
	end

	function Function.Converter(Character, Data)
		for _, v in pairs(Character:GetChildren()) do
			if v:IsA("BasePart") and table.find(R15Transparency, v.Name) then
				--v.Transparency = 1
				PlayerData[Data].CurrentPartList.ParentTransparency[v] = {D=0,T=1}
			end
		end
		--[[
		if Method == 2 then
			local OldCharacter = Character

			Character = Method2CharacterFolder:FindFirstChild(OldCharacter.Name)

			if not Character then
				Character = Instance.new("Model", Method2CharacterFolder)
				Character.Name = OldCharacter.Name

				local Humanoid = Instance.new("Humanoid", Character)
				Humanoid.RigType = Enum.HumanoidRigType.R6
				Humanoid.PlatformStand = true

				local CharacterValue = Instance.new("ObjectValue", Character)
				CharacterValue.Value = OldCharacter

				for _, v in pairs(CharacterValue.Value:GetChildren()) do
					if v:IsA("BasePart") and table.find(Method2BodyPart, v.Name) then
						local Part

						if v.Name ~= "Head" then
							Part = Instance.new("Part", Character)
						else
							Part = Instance.new("MeshPart", Character)
						end

						Part.Size = v.Size
						Part.Name = v.Name
						Part.Transparency = 1
						Part.CanCollide = false
						Part.CanQuery = false
						Part.CanTouch = false
						Part.Massless = true
						Part.Color = v.Color

						local Weld = Instance.new("Weld", Part)
						Weld.Part0 = v
						Weld.Part1 = Part
					end
				end
			end
		end
		]]
		if Character:FindFirstChild("UpperTorso") and not Character:FindFirstChild("Torso") then
			for New, Base in pairs(ConvertPart) do
				local BasePart = Character:FindFirstChild(Base)

				if BasePart then
					local Part

					if New == "Torso" then
						Part = IS:CreateMeshPartAsync(R6Mesh[New.."Female"], Enum.CollisionFidelity.Box, Enum.RenderFidelity.Performance)
					else
						Part = IS:CreateMeshPartAsync(R6Mesh[New], Enum.CollisionFidelity.Box, Enum.RenderFidelity.Performance)
					end

					Part.Name = New
					Part.Color = BasePart.Color
					Part.CanCollide = false
					Part.CanQuery = false
					Part.CanTouch = false
					Part.Massless = true
					Part.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)
					Part.Size = R6Size[New]
					Part.Material = Enum.Material.SmoothPlastic
					Part:SetAttribute("Visibility",1)
					Part:AddTag("Visibility")

					local Weld = Instance.new("Weld", Part)
					Weld.Part0 = BasePart
					Weld.Part1 = Part
					Weld.C0 = WeldCFrame[New]

					Part.Parent = Character

					Part:AddTag("RoClothes")
					PlayerData[Data].ConvertedPart[New] = {Part = Part, Weld = Weld, Base = BasePart}
				end
			end
		elseif Character:FindFirstChild("UpperTorso") and Character:FindFirstChild("Torso") then
			for i, v in pairs(PlayerData[Data].ConvertedPart) do
				v.Part.Transparency = 0
				v.Part:SetAttribute("Visibility",1)
				v.Part:AddTag("Visibility")
			end
		end
	end

	function Function.CharacterExecute(Character, Data, bool)

		if Character then
			Function.CharacterReset(Character)

			Function.PlayerDataAdd(Data)

			local DataDetail = PlayerData[Data]

			if DataDetail["Cooldown"] == true then
				return
			end
			DataDetail["Cooldown"] = true
			DataDetail["Character"] = Character

			local Human = Character:FindFirstChildOfClass("Humanoid")
			local Head = Character:WaitForChild("Head")
			local FaceDecal = Head:FindFirstChild("face") or Head:FindFirstChild("Face")

			Function.Converter(Character,Data)
			Function.AttachmentCreate(Character)

			local CharacterAttachment = Function.CharacterFunction(Character, Data)

			DataDetail.SavedPreviousHP = Human.Health
			if DataDetail.TopHP ~= "" then
				DataDetail.SavedTopHP = DataDetail.TopHP
			end
			if DataDetail.BottomHP ~= "" then
				DataDetail.SavedBottomHP = DataDetail.BottomHP
			end
			DataDetail.TopRipped = false
			DataDetail.BottomRipped = false
			if Method == 2 then
				local OldCharacter = Character

				Character = Method2CharacterFolder:FindFirstChild(Data)

				if not Character then
					Character = Instance.new("Model", Method2CharacterFolder)
					Character.Name = Data
					--[[
					local Humanoid = Instance.new("Humanoid", Character)
					Humanoid.RigType = Enum.HumanoidRigType.R6
					Humanoid.PlatformStand = true
					]]
					local CharacterValue = Instance.new("ObjectValue", Character)
					CharacterValue.Value = OldCharacter

					for _, v in pairs(CharacterValue.Value:GetChildren()) do
						if v:IsA("BasePart") and table.find(Method2BodyPart, v.Name) then
							if v.Name ~= "Head" then
								DataDetail.CurrentPartList.ParentTransparency[v] = {D = v.Transparency,T = 1}
							end

							local Part = Instance.new("Part", Character)
							Part.Size = v.Size
							Part.Name = v.Name
							Part.Transparency = 1
							Part.CanCollide = false
							Part.CanQuery = false
							Part.CanTouch = false
							Part.Massless = true
							Part.CustomPhysicalProperties = PhysicalProperties.new(0.0001,0,0,0,0)
							Part.Color = v.Color

							local Weld = Instance.new("Weld", Part)
							Weld.Part0 = v
							Weld.Part1 = Part
						end
					end
				end
				if OldCharacter:FindFirstChildOfClass("Shirt") then
					if Character:FindFirstChildOfClass("Shirt") then
						Character:FindFirstChildOfClass("Shirt"):Destroy()
					end
					OldCharacter:FindFirstChildOfClass("Shirt"):Clone().Parent = Character
				end
				if OldCharacter:FindFirstChildOfClass("Pants") then
					if Character:FindFirstChildOfClass("Pants") then
						Character:FindFirstChildOfClass("Pants"):Destroy()
					end
					OldCharacter:FindFirstChildOfClass("Pants"):Clone().Parent = Character
				end
			end

			if Bundle[DataDetail.CurrentBundle]["TClothes"] then
				for i, v in pairs(Bundle[DataDetail.CurrentBundle]["TClothes"]) do
					DataDetail.HPClothes[i] = v
				end
			end

			if Bundle[DataDetail.CurrentBundle]["NippleColor"] and DataDetail.Tone == "Use NippleColor" and DataDetail.NippleColor == nil then
				DataDetail.NippleColor = Bundle[DataDetail.CurrentBundle]["NippleColor"]
			end

			local TShirt = Character:FindFirstChildOfClass("ShirtGraphic")
			local Shirt = Character:FindFirstChildOfClass("Shirt")
			local Pants = Character:FindFirstChildOfClass("Pants")

			if DataDetail.CurrentBundle ~= "nil" and (not Bundle[DataDetail.CurrentBundle]["Override"] or Bundle[DataDetail.CurrentBundle]["Override"] == false) then

				if TShirt then
					if DataDetail.OldestClothings.ShirtGraphic == nil then
						DataDetail.OldestClothings.ShirtGraphic = TShirt:Clone()
					end
					TShirt:Destroy()
					TShirt = nil
				end
				if Shirt then
					if DataDetail.OldestClothings.Shirt == nil then
						DataDetail.OldestClothings.Shirt = Shirt:Clone()
					end
					Shirt:Destroy()
					Shirt = nil
				end
				if Pants then
					if DataDetail.OldestClothings.Pants == nil then
						DataDetail.OldestClothings.Pants = Pants:Clone()
					end
					Pants:Destroy()
					Pants = nil
				end

				if DataDetail.CurrentBundle ~= "Bald" then

					Function.AccessoryLoaderFunction(Character, CharacterAttachment, DataDetail.CurrentBundle, Data)

					if DataDetail.SkinTone == nil then
						Function.BodyColorsFunction(Character, DataDetail.CurrentBundle, Data)
					end
				end
			end

			Function.CatalogLoader(Character, CharacterAttachment, Data)
			if DataDetail.SkinTone ~= nil then
				Function.BodyColorForceSet(Character, DataDetail.SkinTone)
			end

			if DataDetail.CurrentBundle ~= "nil" and Bundle[DataDetail.CurrentBundle]["Override"] == true then

				if TShirt then
					if DataDetail.OldestClothings.ShirtGraphic == nil then
						DataDetail.OldestClothings.ShirtGraphic = TShirt:Clone()
					end
					TShirt:Destroy()
					TShirt = nil
				end
				if Shirt then
					if DataDetail.OldestClothings.Shirt == nil then
						DataDetail.OldestClothings.Shirt = Shirt:Clone()
					end
					Shirt:Destroy()
					Shirt = nil
				end
				if Pants then
					if DataDetail.OldestClothings.Pants == nil then
						DataDetail.OldestClothings.Pants = Pants:Clone()
					end
					Pants:Destroy()
					Pants = nil
				end

				if DataDetail.CurrentBundle ~= "Bald" then

					Function.AccessoryLoaderFunction(Character, CharacterAttachment, DataDetail.CurrentBundle, Data)

					if DataDetail.SkinTone == nil then
						Function.BodyColorsFunction(Character, DataDetail.CurrentBundle, Data)
					end
				end
			end

			TShirt = Character:FindFirstChildOfClass("ShirtGraphic")
			Shirt = Character:FindFirstChildOfClass("Shirt")
			Pants = Character:FindFirstChildOfClass("Pants")

			local Extra = {["TShirt"] = TShirt, ["Shirt"] = Shirt, ["Pants"] = Pants, ["Tone"] = DataDetail.Tone, ["SkinTone"] = DataDetail.SkinTone, ["NippleColor"] = DataDetail.NippleColor}

			if DataDetail.HPClothes.Shirt ~= "" or DataDetail.HPClothes.Pants ~= "" then
				local HumanoidDescription = Instance.new("HumanoidDescription")
				for Type, Id in pairs(DataDetail.HPClothes) do
					if Id ~= "" then
						if Type == "Shirt" then
							HumanoidDescription.Shirt = Id
						elseif Type == "Pants" then
							HumanoidDescription.Pants = Id
						elseif Type == "ShirtGraphic" then
							HumanoidDescription.GraphicTShirt = Id
						end
					end
				end
				local AccessoryLoaderModel = Instance.new("Model", game.workspace)
				local HumanoidAccessoryLoader = Instance.new("Humanoid", AccessoryLoaderModel)
				HumanoidAccessoryLoader:ApplyDescription(HumanoidDescription)

				for _, v in pairs(AccessoryLoaderModel:GetChildren()) do
					if v:IsA("Shirt") or v:IsA("Pants") or v:IsA("ShirtGraphic") then
						DataDetail.HPClothes[v.ClassName] = v
					end
				end
				AccessoryLoaderModel:Destroy()
				HumanoidDescription:Destroy()
			end

			local PartListData = DataDetail.PartList

			local PhysicsRotationOffset = {
				X = "Z",
				Y = "X",
				Z = "Y",
			}

			local TORSO
			local LEFTLEG
			local RIGHTLEG
			local LEFTARM
			local RIGHTARM
			local LEFTBUTT
			local RIGHTBUTT

			local LEFTBREAST
			local RIGHTBREAST

			if DataDetail.TorsoType == 1 then
				TORSO = Function.Weld(PartListData["Torso"], Character, Extra, Data)
			else
				TORSO = Function.Weld(PartListData["Torso".. DataDetail.TorsoType], Character, Extra, Data)
			end

			if DataDetail.ArmType == 1 then
				LEFTARM = Function.Weld(PartListData["Left Arm"], Character, Extra, Data)
				RIGHTARM = Function.Weld(PartListData["Right Arm"], Character, Extra, Data)
			else
				LEFTARM = Function.Weld(PartListData["Left Arm".. DataDetail.ArmType], Character, Extra, Data)
				RIGHTARM = Function.Weld(PartListData["Right Arm".. DataDetail.ArmType], Character, Extra, Data)
			end

			if DataDetail.LegsType == 1 then
				LEFTLEG = Function.Weld(PartListData["Left Leg"], Character, Extra, Data)
				RIGHTLEG = Function.Weld(PartListData["Right Leg"], Character, Extra, Data)
			else
				LEFTLEG = Function.Weld(PartListData["Left Leg".. DataDetail.LegsType], Character, Extra, Data)
				RIGHTLEG = Function.Weld(PartListData["Right Leg".. DataDetail.LegsType], Character, Extra, Data)
			end

			if DataDetail.ButtType == 1 then
				LEFTBUTT = Function.Weld(PartListData["Left Butt"], Character, Extra, Data)
				RIGHTBUTT = Function.Weld(PartListData["Right Butt"], Character, Extra, Data)
			else
				LEFTBUTT = Function.Weld(PartListData["Left Butt".. DataDetail.ButtType], Character, Extra, Data)
				RIGHTBUTT = Function.Weld(PartListData["Right Butt".. DataDetail.ButtType], Character, Extra, Data)
			end

			PlayerData[Data].CurrentPartList["Organ"]["Torso"] = TORSO
			PlayerData[Data].CurrentPartList["Organ"]["Left Leg"] = LEFTLEG
			PlayerData[Data].CurrentPartList["Organ"]["Right Leg"] = RIGHTLEG
			PlayerData[Data].CurrentPartList["Organ"]["Left Arm"] = LEFTARM
			PlayerData[Data].CurrentPartList["Organ"]["Right Arm"] = RIGHTARM
			PlayerData[Data].CurrentPartList["Organ"]["Left Butt"] = LEFTBUTT
			PlayerData[Data].CurrentPartList["Organ"]["Right Butt"] = RIGHTBUTT

			if DataDetail.BreastsType == 1 then
				LEFTBREAST = Function.Weld(PartListData["Left Breast"], Character, Extra, Data)
				RIGHTBREAST = Function.Weld(PartListData["Right Breast"], Character, Extra, Data)

				local LEFTNIPPLE = Function.Weld(PartListData["Left Nipple"], Character, Extra, Data)
				local RIGHTNIPPLE = Function.Weld(PartListData["Right Nipple"], Character, Extra, Data)

				PlayerData[Data].CurrentPartList["Organ"]["Left Nipple"] = LEFTNIPPLE
				PlayerData[Data].CurrentPartList["Organ"]["Right Nipple"] = RIGHTNIPPLE
			elseif DataDetail.BreastsType == 2 then
				LEFTBREAST = Function.Weld(PartListData["Left Breast Type 2"], Character, Extra, Data)
				RIGHTBREAST = Function.Weld(PartListData["Right Breast Type 2"], Character, Extra, Data)

				PhysicsRotationOffset = {
					X = "Y",
					Y = "X",
					Z = "Z",
				}
			elseif DataDetail.BreastsType == 3 then
				LEFTBREAST = Function.Weld(PartListData["Left Breast Type 3"], Character, Extra, Data)
				RIGHTBREAST = Function.Weld(PartListData["Right Breast Type 3"], Character, Extra, Data)

				local LEFTNIPPLE = Function.Weld(PartListData["Left Nipple Type 3"], Character, Extra, Data)
				local RIGHTNIPPLE = Function.Weld(PartListData["Right Nipple Type 3"], Character, Extra, Data)

				PlayerData[Data].CurrentPartList["Organ"]["Left Nipple"] = LEFTNIPPLE
				PlayerData[Data].CurrentPartList["Organ"]["Right Nipple"] = RIGHTNIPPLE
			elseif DataDetail.BreastsType == 4 then
				LEFTBREAST = Function.Weld(PartListData["Left Breast Type 4"], Character, Extra, Data)
				RIGHTBREAST = Function.Weld(PartListData["Right Breast Type 4"], Character, Extra, Data)

				local LEFTAREOLA = Function.Weld(PartListData["Left Areola Type 4"], Character, Extra, Data)
				local RIGHTAREOLA = Function.Weld(PartListData["Right Areola Type 4"], Character, Extra, Data)
				local LEFTNIPPLE = Function.Weld(PartListData["Left Nipple Type 4"], Character, Extra, Data)
				local RIGHTNIPPLE = Function.Weld(PartListData["Right Nipple Type 4"], Character, Extra, Data)

				PlayerData[Data].CurrentPartList["Organ"]["Left Areola"] = LEFTAREOLA
				PlayerData[Data].CurrentPartList["Organ"]["Right Areola"] = RIGHTAREOLA
				PlayerData[Data].CurrentPartList["Organ"]["Left Nipple"] = LEFTNIPPLE
				PlayerData[Data].CurrentPartList["Organ"]["Right Nipple"] = RIGHTNIPPLE
			end

			PlayerData[Data].CurrentPartList["Organ"]["Left Breast"] = LEFTBREAST
			PlayerData[Data].CurrentPartList["Organ"]["Right Breast"] = RIGHTBREAST

			if DataDetail.BodyPartPhysics then
				local Torso = Character:FindFirstChild("Torso")

				if Torso then
					Function.SpringCreate(
						RIGHTBUTT, 
						Torso, 
						Vector3.new(1,1,1) * 3, 
						Vector3.new(0,0,0), 
						10, 
						0.1,
						{
							X = "X",
							Y = "Y",
							Z = "Z",
						},
						{
							X = 1/20,
							Y = 1/40,
							Z = 1/20
						},
						{
							X = "Y",
							Y = "X",
							Z = "Z",
						},
						{
							X = 3,
							Y = 2,
							Z = 2
						},
						Data
					)
					Function.SpringCreate(
						LEFTBUTT, 
						Torso, 
						Vector3.new(1,1,1) * 3, 
						Vector3.new(0,0,0), 
						10, 
						0.1, 
						{
							X = "X",
							Y = "Y",
							Z = "Z",
						},
						{
							X = 1/20,
							Y = 1/40,
							Z = 1/20
						},
						{
							X = "Y",
							Y = "X",
							Z = "Z",
						},
						{
							X = 3,
							Y = 2,
							Z = 2
						},
						Data
					)
					Function.SpringCreate(
						RIGHTBREAST, 
						Torso, 
						Vector3.new(1,1,1) * 5, 
						Vector3.new(0,0,0), 
						10, 
						0.2, 
						{
							X = "X",
							Y = "Y",
							Z = "Z",
						},
						{
							X = 0,
							Y = 0,
							Z = 0
						},
						PhysicsRotationOffset,
						{
							X = 5,
							Y = -5,
							Z = 5
						},
						Data
					)
					Function.SpringCreate(
						LEFTBREAST, 
						Torso, 
						Vector3.new(1,1,1) * 5, 
						Vector3.new(0,0,0), 
						10, 
						0.2, 
						{
							X = "X",
							Y = "Y",
							Z = "Z",
						},
						{
							X = 0,
							Y = 0,
							Z = 0
						},
						PhysicsRotationOffset,
						{
							X = 5,
							Y = -5,
							Z = 5
						},
						Data
					)
				end
			end

			if DataDetail.MeshBasePartInvisible then
				TORSO.Transparency = 1
				LEFTLEG.Transparency = 1
				RIGHTLEG.Transparency = 1
				LEFTARM.Transparency = 1
				RIGHTARM.Transparency = 1
				DataDetail.CurrentPartList.ParentTransparency[TORSO] = {D = 0, T = 1}
				DataDetail.CurrentPartList.ParentTransparency[LEFTLEG] = {D = 0, T = 1}
				DataDetail.CurrentPartList.ParentTransparency[RIGHTLEG] = {D = 0, T = 1}
				DataDetail.CurrentPartList.ParentTransparency[LEFTARM] = {D = 0, T = 1}
				DataDetail.CurrentPartList.ParentTransparency[RIGHTARM] = {D = 0, T = 1}
			end

			for _, SelectClothes in pairs(DataDetail.CurrentClothes) do
				if SelectClothes ~= "nil" then
					if Clothes[SelectClothes]["Weld"] then
						for i, v in pairs(Clothes[SelectClothes]["Weld"]) do

							local ClothesPart = Function.Weld(PartListData[v], Character, Extra, Data)
							DataDetail.CurrentPartList["Clothes"][v] = ClothesPart
							if DataDetail.ClothesRecolor[SelectClothes] and PartListData[v].Recolor then
								if DataDetail.ClothesRecolor[SelectClothes].Primary ~= "nil" then
									if PartListData[v].Recolor == "Primary" then
										ClothesPart.Color = DataDetail.ClothesRecolor[SelectClothes].Primary
									end
								end
								if DataDetail.ClothesRecolor[SelectClothes].Secondary ~= "nil" then
									if PartListData[v].Recolor == "Secondary" then
										ClothesPart.Color = DataDetail.ClothesRecolor[SelectClothes].Secondary
									end
								end
								if DataDetail.ClothesRecolor[SelectClothes].Tertiary ~= "nil" then
									if PartListData[v].Recolor == "Tertiary" then
										ClothesPart.Color = DataDetail.ClothesRecolor[SelectClothes].Tertiary
									end
								end
							end
						end
					end

					if Clothes[SelectClothes]["Unvisible"] ~= nil then
						for i, v in pairs(Clothes[SelectClothes]["Unvisible"]) do
							local UnvisiblePart = DataDetail.CurrentPartList["Organ"][v]

							if UnvisiblePart then
								UnvisiblePart.Transparency = 1
							elseif string.find(string.lower(v),"areola") then
								for areola, parent in pairs(DataDetail.CurrentPartList["AreolaDecal"]) do
									if parent and 
										(string.find(string.lower(v),"left") and string.find(string.lower(parent.Name),"left")) or
										(string.find(string.lower(v),"right") and string.find(string.lower(parent.Name),"right")) then
										areola.Transparency = 1
									end
								end
							end
						end
					end
				end
			end

			if FaceDecal and DataDetail.Face == false then
				FaceDecal.Transparency = 1
				DataDetail.CurrentPartList.ParentTransparency[FaceDecal] = {D = 0, T = 1}
			end
			DataDetail["Cooldown"] = false
		end
	end

	function Function.CharacterConnection(Player)
		local CharacterConnect = Player.CharacterAdded:Connect(function(Character)
			if PlayerData[Player.Name] ~= nil and PlayerData[Player.Name].AutoExecute then
				repeat task.wait(0.5) until Character.Parent ~= nil
				task.wait(PlayerData[Player.Name].DelayTime)

				Function.CharacterExecute(Character, Player.Name)
			end
		end)

		table.insert(AllConnect, CharacterConnect)
	end

	function Function.StringTo(String, Type)
		local Split = string.split(String, ",")

		if Type == "CFrame" then
			return CFrame.new(Split[1],Split[2],Split[3],Split[4],Split[5],Split[6],Split[7],Split[8],Split[9],Split[10],Split[11],Split[12])
		elseif Type == "RGB" then
			return Color3.fromRGB(Split[1],Split[2],Split[3])
		elseif Type == "Vector3" then
			return Vector3.new(Split[1],Split[2],Split[3])
		end
	end

	function Function.MeshEditButton(Name)
		for _, v in pairs(GUIObject.PropertyListFrame:GetChildren()) do
			if v:IsA(("Frame")) then
				v:Destroy()
			end
		end
		Debug = false

		for _, v in pairs(MeshEditConnect) do
			v:Disconnect()
		end

		MeshEditConnect = {}

		local PlayerPartList = PlayerData[SelectPlayer]["PartList"]
		local MeshDetail = PlayerPartList[Name]

		if MeshDetail then
			setmetatable(MeshDetail, MetaClothes)

			if MeshDetail then
				if MeshDetail["Scale"] == "CockScale" then
					local Button = Function.ButtonCreate("CockScale", GUIObject.PropertyListFrame, true, {Color = Color3.fromRGB(93, 93, 93), Text = "CockScale"})
					local Textbox = Button:FindFirstChildOfClass("TextBox")
					Textbox.Text = PlayerData[SelectPlayer].CockScale

					local TextboxConnect = Textbox.FocusLost:Connect(function()
						PlayerData[SelectPlayer].CockScale = tonumber(Textbox.Text)
					end)

					table.insert(MeshEditConnect, TextboxConnect)
					table.insert(AllConnect, TextboxConnect)
				end
				for _, PropertyName in pairs(EditableProperty) do
					local Value = MeshDetail[PropertyName]
					if Value == nil then Value = "" end
					local Button = Function.ButtonCreate(PropertyName, GUIObject.PropertyListFrame, true, {Color = Color3.fromRGB(93, 93, 93), Text = PropertyName})
					local Textbox = Button:FindFirstChildOfClass("TextBox")

					if PropertyName == "Color" then
						local Split = string.split(tostring(Value.Color), ",")

						if tonumber(Split[1]) and tonumber(Split[2]) and tonumber(Split[3]) then
							Textbox.Text = math.round(Split[1]*255)..","..math.round(Split[2]*255)..","..math.round(Split[3]*255)
							Textbox.TextColor3 = Value.Color
							Textbox.TextStrokeTransparency = 0
							Textbox.TextStrokeColor3 = Color3.new(1,1,1)
						else
							Textbox.Text = ""
						end
					else
						Textbox.Text = tostring(Value)
					end

					local TextboxConnect = Textbox.FocusLost:Connect(function()
						if PropertyName == "Size" then
							PlayerData[SelectPlayer]["PartList"][Name][PropertyName] = Function.StringTo(Textbox.Text, "Vector3")
						elseif PropertyName == "Offset" then
							PlayerData[SelectPlayer]["PartList"][Name][PropertyName] = Function.StringTo(Textbox.Text, "Vector3")
						elseif PropertyName == "TextureId" then
							PlayerData[SelectPlayer]["PartList"][Name][PropertyName] = Textbox.Text
						elseif PropertyName == "Color" then
							local RGB = Function.StringTo(Textbox.Text, "RGB")

							PlayerData[SelectPlayer]["PartList"][Name][PropertyName].Color = RGB
							Textbox.TextColor3 = RGB
						else
							PlayerData[SelectPlayer]["PartList"][Name][PropertyName] = tonumber(Textbox.Text)
						end
					end)

					table.insert(MeshEditConnect, TextboxConnect)
					table.insert(AllConnect, TextboxConnect)
				end
			end
		elseif Name == "DEBUG" then
			Debug = true
		end
	end




	function Function.DragUpdate()
		--[[
		if IsEnterFrame == true and IsMouseDown == true and MouseDownStart and GuiPositionStart then
			local CurrentPosition = UIS:GetMouseLocation() - MouseDownStart
			local ToChangePosition = UDim2.new(GuiPositionStart.X.Scale, GuiPositionStart.X.Offset + CurrentPosition.X, GuiPositionStart.Y.Scale, GuiPositionStart.Y.Offset + CurrentPosition.Y)

			GUIObject.MainFrame.Position = GUIObject.MainFrame.Position:Lerp(ToChangePosition, 0.5)
		end
		]]
	end

	function Function.IsCharacter(Model)
		return Model:FindFirstChild("Torso") or Model:FindFirstChild("Head") or Model:FindFirstChild("Right Arm") or Model:FindFirstChild("Left Arm") or Model:FindFirstChild("Right Leg") or Model:FindFirstChild("Left Leg")
	end

	function Function.GUIUpdate()
		for i, v in pairs(GUIObject.ClothesButtonFrame:GetChildren()) do
			if v:IsA("Frame") then
				if table.find(PlayerData[SelectPlayer].CurrentClothes, v.Name) then
					v.BackgroundColor3 = Color3.fromRGB(255, 242, 67)
				else
					v.BackgroundColor3 = Color3.fromRGB(6, 0, 76)
				end 

				if GUIObject.ClothesSearch.Text ~= "" then
					v.Visible = string.find(string.lower(v.Name),string.lower(GUIObject.ClothesSearch.Text))
				else
					v.Visible = true
				end
			end
		end
		for i, v in pairs(GUIObject.BundlesButtonFrame:GetChildren()) do
			if v:IsA("Frame") then
				if GUIObject.BundleSearch.Text ~= "" then
					v.Visible = string.find(string.lower(v.Name),string.lower(GUIObject.BundleSearch.Text))
				else
					v.Visible = true
				end
			end
		end

		if PlayerData[SelectPlayer].AutoExecute then
			GUIObject.AutoExecuteButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.AutoExecuteButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].BundleBodyColor then
			GUIObject.BundleBodyColorButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.BundleBodyColorButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].Face then
			GUIObject.FaceButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.FaceButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].MeshSizeLock then
			GUIObject.MeshSizeLockButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.MeshSizeLockButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].AccessorySizeLock then
			GUIObject.AccessorySizeLockButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.AccessorySizeLockButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].MeshBasePartInvisible then
			GUIObject.MeshBasePartInvisibleButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.MeshBasePartInvisibleButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].BodyPartPhysics then
			GUIObject.BodyPartPhysicsButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.BodyPartPhysicsButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		for BodyP, Bool in pairs(PlayerData[SelectPlayer].LocalTransparency) do
			local Button = GUIObject.CharacterFrame:FindFirstChild(BodyP)

			if Button then
				if BodyP == "Hat" then
					if Bool == true then
						Button.ImageTransparency = 0
					else
						Button.ImageTransparency = 0.5
					end
				else
					if Bool == true then
						Button.BackgroundTransparency = 0
					else
						Button.BackgroundTransparency = 0.5
					end
				end
			end
		end

		if ClickExecute then
			GUIObject.ClickExecuteButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.ClickExecuteButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].FPerson then
			GUIObject.FPExecute.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.FPExecute.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].PhysicsObeyGravity then
			GUIObject.GravityButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.GravityButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].TearParticles then
			GUIObject.TPToggle.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.TPToggle.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].HealParticles then
			GUIObject.PHToggle.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.PHToggle.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].SkinTone then
			GUIObject.SkinToneText.Text = math.round(PlayerData[SelectPlayer].SkinTone.R*255) ..", "..math.round(PlayerData[SelectPlayer].SkinTone.G*255) ..", "..math.round(PlayerData[SelectPlayer].SkinTone.B*255)
			GUIObject.SkinToneText.TextColor3 = PlayerData[SelectPlayer].SkinTone
		end

		if PlayerData[SelectPlayer].NippleColor then
			GUIObject.NippleColorText.Text = math.round(PlayerData[SelectPlayer].NippleColor.R*255) ..", "..math.round(PlayerData[SelectPlayer].NippleColor.G*255) ..", "..math.round(PlayerData[SelectPlayer].NippleColor.B*255)
			GUIObject.NippleColorText.TextColor3 = PlayerData[SelectPlayer].NippleColor
		end

		if PlayerData[SelectPlayer].RealtimeBodyTransparency then
			GUIObject.BodyTransparencyButton.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.BodyTransparencyButton.TextStrokeColor3 = Color3.new(255,0,0)
		end

		if PlayerData[SelectPlayer].HardcoreHP then
			GUIObject.HardcoreToggle.TextStrokeColor3 = Color3.new(0,255,0)
		else
			GUIObject.HardcoreToggle.TextStrokeColor3 = Color3.new(255,0,0)
		end

		GUIObject.PositionPhysicsMultiplyText.Text = PositionPhysicsMultiply
		GUIObject.RotationPhysicsMultiplyText.Text = RotationPhysicsMultiply
		GUIObject.MethodButton.Text = "Method: "..Method
		GUIObject.BundleText.Text = "Bundle: "..PlayerData[SelectPlayer].CurrentBundle
		GUIObject.ToneButton.Text = "Tone: "..PlayerData[SelectPlayer].Tone
		GUIObject.UsernameTextbox.Text = PlayerData[SelectPlayer].CatalogUsername
		GUIObject.ShirtTextbox.Text = PlayerData[SelectPlayer].CatalogClothes.Shirt
		GUIObject.PantsTextbox.Text = PlayerData[SelectPlayer].CatalogClothes.Pants
		GUIObject.ShirtGraphicTextbox.Text = PlayerData[SelectPlayer].CatalogClothes.ShirtGraphic
		GUIObject.BreastsScaleText.Text = PlayerData[SelectPlayer].BreastsScale
		GUIObject.ButtsScaleText.Text = PlayerData[SelectPlayer].ButtsScale
		GUIObject.LegsScaleText.Text = PlayerData[SelectPlayer].LegsScale
		GUIObject.BreastsTypeButton.Text = "Breasts Type: "..PlayerData[SelectPlayer].BreastsType
		GUIObject.TorsoTypeButton.Text = "Torso Type: "..PlayerData[SelectPlayer].TorsoType
		GUIObject.ArmTypeButton.Text = "Arm Type: "..PlayerData[SelectPlayer].ArmType
		GUIObject.LegsTypeButton.Text = "Legs Type: "..PlayerData[SelectPlayer].LegsType
		GUIObject.ButtTypeButton.Text = "Butt Type: "..PlayerData[SelectPlayer].ButtType
		GUIObject.OutfitIdTextbox.Text = PlayerData[SelectPlayer].CatalogOutfitId

		GUIObject.TopHPText.Text = PlayerData[SelectPlayer].TopHP
		GUIObject.BottomHPText.Text = PlayerData[SelectPlayer].BottomHP
		GUIObject.DamageSFX.Text = PlayerData[SelectPlayer].DamageSFX
		GUIObject.VolumeText.Text = PlayerData[SelectPlayer].Volume

		Function.CatalogAccessoryFrameAdd(SelectPlayer)
		Function.MeshEditButton(GUIObject.MeshNameTextbox.Text)
	end

	function Function.FallenPartCheck(Object)
		if Object:IsA("BasePart") then
			return Object.Position.Y < game.Workspace.FallenPartsDestroyHeight
		end
	end

	function Function.IsParentNil(Object)
		if Object then
			local Target = Object

			while Target and Target.Parent ~= nil and Target ~= game do
				Target = Target.Parent
			end

			if Target ~= game then
				return true
			end
		end
		return false
	end

	function Function.GetMiddleNumber(Numbers)
		table.sort(Numbers, function(a,b)
			return a < b
		end)

		local Count = #Numbers

		if Count % 2 == 0 then
			local middleIndex1 = Count / 2
			local middleIndex2 = middleIndex1 + 1
			local middleNumber = (Numbers[middleIndex1] + Numbers[middleIndex2]) / 2

			return middleNumber
		else
			local middleIndex = math.ceil(Count / 2)
			local middleNumber = Numbers[middleIndex]

			return middleNumber
		end
	end

	--[[
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	
                  ░█████╗░░█████╗░███╗░░██╗███╗░░██╗███████╗░█████╗░████████╗██╗░█████╗░███╗░░██╗
                  ██╔══██╗██╔══██╗████╗░██║████╗░██║██╔════╝██╔══██╗╚══██╔══╝██║██╔══██╗████╗░██║
                  ██║░░╚═╝██║░░██║██╔██╗██║██╔██╗██║█████╗░░██║░░╚═╝░░░██║░░░██║██║░░██║██╔██╗██║
                  ██║░░██╗██║░░██║██║╚████║██║╚████║██╔══╝░░██║░░██╗░░░██║░░░██║██║░░██║██║╚████║
                  ╚█████╔╝╚█████╔╝██║░╚███║██║░╚███║███████╗╚█████╔╝░░░██║░░░██║╚█████╔╝██║░╚███║
                  ░╚════╝░░╚════╝░╚═╝░░╚══╝╚═╝░░╚══╝╚══════╝░╚════╝░░░░╚═╝░░░╚═╝░╚════╝░╚═╝░░╚══╝
                                  
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	]]

	for _, v in pairs(game.Players:GetPlayers()) do
		Function.CharacterConnection(v)
	end

	game.Players.PlayerAdded:Connect(function(v)
		Function.CharacterConnection(v)
	end)

	local tap = false
	local cd = false
	local UISBeganConnect = UIS.InputBegan:Connect(function(Keycode, Process)
		if Process then return end

		if KeybindDetect == true then
			KEYBIND = Keycode.KeyCode
			GUIObject.KeybindButton.Text = string.sub(tostring(KEYBIND), 14, #tostring(KEYBIND))
			KeybindDetect = false
		else
			if Keycode.KeyCode == KEYBIND then
				GUIObject.Screen.Enabled = not GUIObject.Screen.Enabled
			end
		end
		if hpKeybindDetect == true then
			hpKEYBIND = Keycode.KeyCode
			--GUIObject.KeybindButton.Text = string.sub(tostring(hpKEYBIND), 14, #tostring(hpKEYBIND))
			hpKeybindDetect = false
		else
			if Keycode.KeyCode == hpKEYBIND and cd == false then
				local LP = game:GetService("Players").LocalPlayer
				local data = PlayerData[LP.Name]
				if LP.Character and LP.Character.Humanoid and data 
					and data["HardcoreHP"] == true and (data["TopHP"] ~= "" or data["BottomHP"] ~= "") then
					if data["Healing"] == false then
						data["Healing"] = true
						cd = true
						tap = true
						task.wait(.25)
						cd = false
						tap = false
						if data["Healing"] == true and (data["SavedTopHP"] < data["TopHP"] or data["SavedBottomHP"] < data["BottomHP"]) then
							local healTime = 0
							local timeAccumulated = 0
							local totalTime = 0
							if data["TopHP"] ~= "" then
								healTime += (data["TopHP"]/math.max(data["SavedTopHP"],1))*0.03
							end
							if data["BottomHP"] ~= "" then
								healTime += (data["BottomHP"]/math.max(data["SavedBottomHP"],1))*0.03
							end
							repeat
								if LP.Character.Humanoid.Health < data["SavedPreviousHP"] then
									data["Healing"] = false
								end
								local focus
								local timeRequired
								if data["BottomHP"] ~= "" and (data["SavedBottomHP"] <= 0 or data["SavedTopHP"]/data["TopHP"] >= data["SavedBottomHP"]/data["BottomHP"]) then
									focus = "BottomHP"
									timeRequired = (data["BottomHP"]/math.max(data["SavedBottomHP"],1))*0.03
								elseif data["TopHP"] ~= "" and (data["SavedTopHP"] <= 0 or data["SavedTopHP"]/data["TopHP"] < data["SavedBottomHP"]/data["BottomHP"]) then
									focus = "TopHP"
									timeRequired = (data["TopHP"]/math.max(data["SavedTopHP"],1))*0.03
								end
								local t = task.wait()
								timeAccumulated += t
								totalTime += t
								-- TODO: u gotta add a progress bar & thingy to show hp
								if timeAccumulated >= timeRequired then
									timeAccumulated = 0
									if focus == "TopHP" then
										data["SavedTopHP"]=data["TopHP"]
									else
										data["SavedBottomHP"]=data["BottomHP"]
									end
								end
							until data["Healing"] == false
						end
					end
				end
			end
		end
	end)

	local UISEndedConnect = UIS.InputEnded:Connect(function(Keycode,Process)
		if Process then return end

		if Keycode.KeyCode == hpKEYBIND then
			local LP = game:GetService("Players").LocalPlayer
			local data = PlayerData[LP.Name]
			if LP.Character and LP.Character.Humanoid and data and data["HardcoreHP"] == true then
				if data["Healing"] == true then
					data["Healing"] = false
				end
			end
		end
	end)

	local collisionList = {}
	local collisionChecks = {}
	for i, v in pairs(workspace:GetDescendants()) do
		if v:IsA("BasePart") and v.CanCollide == false then
			table.insert(collisionList,v)
			local collisionChange = v:GetPropertyChangedSignal("CanCollide"):Connect(function()
				if v.CanCollide == false and not table.find(collisionList,v) then
					table.insert(collisionList,v)
				elseif v.CanCollide == true then
					table.remove(collisionList,table.find(collisionList,v))
				end
			end)
			collisionChecks[v] = collisionChange
			table.insert(AllConnect, collisionChange)
		end
	end
	--[[
	local collisionAdded = workspace.DescendantAdded:Connect(function(v)
		if v:IsA("BasePart") and v.CanCollide == false then
			table.insert(collisionList,v)
			local collisionChange = v:GetPropertyChangedSignal("CanCollide"):Connect(function()
				if v.CanCollide == false and not table.find(collisionList,v) then
					table.insert(collisionList,v)
				elseif v.CanCollide == true then
					table.remove(collisionList,table.find(collisionList,v))
				end
			end)
			table.insert(AllConnect, collisionChange)
		end
	end)
	table.insert(AllConnect, collisionAdded)
	]]

	local RunConnect = RS.RenderStepped:Connect(function()
		for _, v in pairs(Method2CharacterFolder:GetChildren()) do
			local CharacterValue = v:FindFirstChildOfClass("ObjectValue")

			if CharacterValue and CharacterValue.Value.Parent == nil then
				v:Destroy()
			end
		end

		local lP = game:GetService("Players").LocalPlayer
		if PlayerData[lP.Name].FPerson == true and PlayerData[lP.Name].updateCooldown == false then
			PlayerData[lP.Name].updateCooldown = true
			local ti = TweenInfo.new(0.3,Enum.EasingStyle.Quad,Enum.EasingDirection.Out)
			local ti2 = TweenInfo.new(0.1,Enum.EasingStyle.Quad,Enum.EasingDirection.Out)

			if lP and lP.Character then
				local char = lP.Character
				local hed = char:WaitForChild("Head")
				local rootpart = char:WaitForChild("HumanoidRootPart")
				local ray = Ray.new(hed.Position, ((hed.CFrame + hed.CFrame.LookVector * 2) - hed.Position).Position.Unit)

				local currentCamera = workspace.CurrentCamera
				local function Round(num: number, places: number): number
					local decimalPivot = 10^places
					return math.floor(num * decimalPivot + 0.5) / decimalPivot
				end
				if currentCamera then
					local distance = (currentCamera.Focus.p - currentCamera.CoordinateFrame.p).magnitude
					local d = (distance<2) and (1.0-(distance-0.5)/1.5) or 0
					if d < 0.5 then
						d = 0
					end

					local ignoreList = {}
					for i, v in pairs(collisionList) do
						table.insert(ignoreList,v)
					end
					for i, v in pairs(Player.Character:GetDescendants()) do
						if v:IsA("BasePart") then
							table.insert(ignoreList,v)
						end
					end
					for i, v in pairs(Method2CharacterFolder:GetDescendants()) do
						if v:IsA("BasePart") then
							table.insert(ignoreList,v)
						end
					end

					local hit, pos = game.Workspace:FindPartOnRayWithIgnoreList(ray, ignoreList)

					if hit and hit.CanCollide == false and not collisionChecks[hit] then
						table.insert(collisionList,hit)
						local collisionChange = hit:GetPropertyChangedSignal("CanCollide"):Connect(function()
							if hit.CanCollide == false and not table.find(collisionList,hit) then
								table.insert(collisionList,hit)
							elseif hit.CanCollide == true then
								table.remove(collisionList,table.find(collisionList,hit))
							end
						end)
						collisionChecks[hit] = collisionChange
						table.insert(AllConnect, collisionChange)
						PlayerData[lP.Name].updateCooldown = false
					end

					if PlayerData[lP.Name].updateCooldown == true then
						-- (workspace.CurrentCamera.CFrame.p - hed.Position).Magnitude <= 1.65
						-- (hed.LocalTransparencyModifier >= .6 or (workspace.CurrentCamera.CFrame.p - hed.Position).Magnitude <= 1)
						if hit and d >= .8 then
							if PlayerData[lP.Name].FPsnap == false then
								TS:Create(char.Humanoid,ti2,{CameraOffset = ((rootpart.CFrame+Vector3.new(0,1.5,0)):pointToObjectSpace(hed.CFrame.p))+Vector3.new(0, 0, -(hed.Position - pos).magnitude)}):Play()
							else
								char.Humanoid.CameraOffset = ((rootpart.CFrame+Vector3.new(0,1.5,0)):pointToObjectSpace(hed.CFrame.p))+Vector3.new(0, 0, -(hed.Position - pos).magnitude)
							end
						elseif d >= .8 then
							if PlayerData[lP.Name].FPsnap == false then
								TS:Create(char.Humanoid,ti2,{CameraOffset = ((rootpart.CFrame+Vector3.new(0,1.5,0)):pointToObjectSpace(hed.CFrame.p))+Vector3.new(0, 0, -1)}):Play()
							else
								char.Humanoid.CameraOffset = ((rootpart.CFrame+Vector3.new(0,1.5,0)):pointToObjectSpace(hed.CFrame.p))+Vector3.new(0, 0, -1)
							end
						else
							TS:Create(char.Humanoid,ti,{CameraOffset = (rootpart.CFrame+Vector3.new(0,1.5,0)):pointToObjectSpace(hed.CFrame.p)}):Play()
						end
					end
				end
			end
			task.delay(.03,function()
				PlayerData[lP.Name].updateCooldown = false
			end)
		end

		for PlayerName, DataList in pairs(PlayerData) do
			for Name, Property in pairs(DataList.ConvertedPart) do
				local Part = Property.Part
				local Weld = Property.Weld
				local Base = Property.Base
				local BaseSize = R15Size[Base.Name]

				if Base:IsA("MeshPart") and Base.MeshId == "http://www.roblox.com/asset/?id=542765884" then
					BaseSize = R15Size["UpperTorsoFemale"]
				end

				Part.Color = Base.Color
				Part.Transparency = Base.Transparency
			end

			for Part, Property in pairs(DataList.CurrentPartList.RealtimeUpdateList.Mesh) do
				local Removed = false
				if Part.Parent == nil or Function.FallenPartCheck(Part) then
					DataList.CurrentPartList.RealtimeUpdateList.Mesh[Part] = nil
					Removed = true
				end

				if Removed == false then
					local Base = Property.Base
					local CFRAME = Property.CFrame
					local CFRAME1 = Property.CFrame1
					local SIZE = Property.Size
					local Weld = Property.Weld

					if CFRAME and CFRAME1 and SIZE and Weld then
						local XMultiply, YMultiply, ZMultiply = Function.MultiplyCalculate(Base.Size, BodyPartSize[Base.Name])

						local CCFRAME = CFrame.new(CFRAME.Position.X * XMultiply, CFRAME.Position.Y * YMultiply, CFRAME.Position.Z * ZMultiply) * CFRAME.Rotation
						local CCFRAME1 = CFrame.new(CFRAME1.Position.X * XMultiply, CFRAME1.Position.Y * YMultiply, CFRAME1.Position.Z * ZMultiply) * CFRAME1.Rotation

						if PlayerData[PlayerName].MeshSizeLock == false and not PlayerData[PlayerName].CurrentPartList.BodyPartPhysics[Part] then
							Part.Size = Vector3.new(SIZE.X * XMultiply, SIZE.Y * YMultiply, SIZE.Z * ZMultiply)
							Weld.C0 = CCFRAME
							Weld.C1 = CCFRAME1
						elseif PlayerData[PlayerName].CurrentPartList.BodyPartPhysics[Part] then
							PlayerData[PlayerName].CurrentPartList.BodyPartPhysics[Part].CF = CCFRAME
							PlayerData[PlayerName].CurrentPartList.BodyPartPhysics[Part].CF1 = CCFRAME1
						end
					end

					if PlayerData[PlayerName].RealtimeBodyTransparency == true then 
						local updated = false
						if Method == 2 or Method == 3 then
							Base = PlayerData[PlayerName].Character:FindFirstChild(Base.Name)
						end
						if --Part.Transparency == PlayerData[PlayerName].OldTransparency[Base] and 
							Base.Transparency ~= PlayerData[PlayerName].OldTransparency[Base] then
							Part.Transparency = math.clamp(Base.Transparency,Part:GetAttribute("maxTransparencyRC") or -math.huge,math.huge)
							updated = true
						end
						if Part.Transparency ~= Part:GetAttribute("maxTransparencyRC") and 
							(Part.Transparency ~= Base.Transparency or Part.Transparency == Base.Transparency and updated == false and Part:GetAttribute("maxDeterminedRC") == false) then
							Part:SetAttribute("maxDeterminedRC",false)
							Part:SetAttribute("maxTransparencyRC",Part.Transparency)
						elseif Part.Transparency ~= Part:GetAttribute("maxTransparencyRC") and 
							Part.Transparency == Base.Transparency and updated == true then
							Part:SetAttribute("maxDeterminedRC",true)
						end
						Part.Transparency = math.clamp(Base.Transparency,Part:GetAttribute("maxTransparencyRC") or -math.huge,math.huge)
						if Part.Transparency == Base.Transparency then
							Part:SetAttribute("maxDeterminedRC",true)
						end
					end
					if PlayerName == lP.Name then
						if PlayerData[PlayerName].LocalTransparency[Base.Name] == true then
							Part.LocalTransparencyModifier = Part.Transparency
						elseif Method == 2 then
							if lP.Character and lP.Character.HumanoidRootPart then
								local chr = lP.Character
								local human = chr.Humanoid
								local rootPart = chr.HumanoidRootPart

								local currentCamera = workspace.CurrentCamera
								local function Round(num: number, places: number): number
									local decimalPivot = 10^places
									return math.floor(num * decimalPivot + 0.5) / decimalPivot
								end
								if currentCamera then
									local distance = (currentCamera.Focus.p - currentCamera.CoordinateFrame.p).magnitude
									local transparency = (distance<2) and (1.0-(distance-0.5)/1.5) or 0
									if transparency < 0.5 then
										transparency = 0
									end

									transparency = math.clamp(Round(transparency, 2), 0, 1)
									if transparency >= 0.85 then
										transparency = 1
									end
									if Part.LocalTransparencyModifier ~= transparency then
										if math.abs(Part.LocalTransparencyModifier-transparency) > .4 or Part.LocalTransparencyModifier > .95 then
											Part.LocalTransparencyModifier = transparency
										else
											Part.LocalTransparencyModifier = Part.Transparency+math.lerp(Part.LocalTransparencyModifier,transparency,.2)
										end
									end
								end
							--[[
							local centerCam = rootPart.Position+Vector3.new(0,1.5,0)
							local camToHead = (workspace.CurrentCamera.CFrame.Position-(centerCam+(rootPart.CFrame:VectorToWorldSpace(human.CameraOffset))))
							
							local transparent
							if 1.5-camToHead.Magnitude > 0.95 then
								transparent = 1
							else
								transparent = 1.5-camToHead.Magnitude
							end
							Part.LocalTransparencyModifier = Base.Transparency+math.lerp(Part.LocalTransparencyModifier,transparent,.5)
							]]
							end
						end
					end
				end
			end

			if game:GetService("Players"):FindFirstChild(PlayerName) then
				local p = game:GetService("Players"):FindFirstChild(PlayerName)
				if p.Character then
					local c = p.Character
					local h = c:FindFirstChildOfClass("Humanoid")
					if Method == 2 and Method2CharacterFolder:FindFirstChild(PlayerName) then
						c = Method2CharacterFolder[PlayerName]
					end
					local PData = PlayerData[PlayerName]
					if h and PData.Cooldown == false then
						local function transparent(o,v)
							o:SetAttribute("maxTransparencyRC",v)
							o.Transparency = v
						end
						-- top --
						if PData.TopHP ~= "" and 
							(PData.HardcoreHP == false and h.MaxHealth-h.Health >= PData.TopHP or 
								PData.HardcoreHP == true and PData.SavedTopHP <= 0
							) then
							if PData.TopRipped == false then
								PData.TopRipped = true

								if UIS.KeyboardEnabled then
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxasset://RClothesContent/Sound/Tear/tear".. math.random(1,3) ..".mp3"
									audio.Volume = 0.75*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								else
									local sounds = {9113827650,9113827551,9113833815}
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxassetid://"..  sounds[math.random(1,#sounds)]
									audio.Volume = 0.75*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								end

								if PData.TearParticles == true then
									local particle = Instance.new("ParticleEmitter",c:FindFirstChild("HumanoidRootPart"))
									particle.Enabled = false
									particle.Texture = "rbxassetid://386425736"
									particle.Size = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,.7,.375),
											NumberSequenceKeypoint.new(1,.4)
										}
									)
									particle.Transparency = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,1),
											NumberSequenceKeypoint.new(0.214,0),
											NumberSequenceKeypoint.new(0.545,0),
											NumberSequenceKeypoint.new(1,1)
										}
									)
									particle.Lifetime = NumberRange.new(0.5,1)
									particle.Rotation = NumberRange.new(-360,360)
									particle.RotSpeed = NumberRange.new(-360,360)
									particle.Speed = NumberRange.new(15,20)
									particle.SpreadAngle = Vector2.new(75,75)
									particle.Acceleration = Vector3.new(0,-15,0)
									particle.Drag = 5
									particle:Emit(50)
									game:GetService("Debris"):AddItem(particle,3)
								end

								if PData.CurrentPartList["Organ"]["Left Arm"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Left Arm"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Right Arm"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Right Arm"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Clothes"]["Torso Shirt"] then
									transparent(PData.CurrentPartList["Clothes"]["Torso Shirt"],1)
								end
								if PData.HPClothes.Shirt ~= "" and not tonumber(PData.HPClothes.Shirt) then
									if not PData.HPClothes.Pants then
										Function.ShirtTexture(PData.CurrentPartList["Organ"]["Torso"],c,{Shirt = PData.HPClothes.Shirt},PlayerName)
									end
									Function.ShirtTexture(PData.CurrentPartList["Organ"]["Left Arm"],c,{Shirt = PData.HPClothes.Shirt},PlayerName)
									Function.ShirtTexture(PData.CurrentPartList["Organ"]["Right Arm"],c,{Shirt = PData.HPClothes.Shirt},PlayerName)
								end

								if PData.CurrentPartList["Organ"]["Left Breast"] then
									transparent(PData.CurrentPartList["Organ"]["Left Breast"],0)
									transparent(PData.CurrentPartList["Organ"]["Left Nipple"],0)
								end
								if PData.CurrentPartList["Organ"]["Right Breast"] then
									transparent(PData.CurrentPartList["Organ"]["Right Breast"],0)
									transparent(PData.CurrentPartList["Organ"]["Right Nipple"],0)
								end

								for i, v in pairs(PData.CurrentPartList.AreolaDecal) do
									if v.Name == "Left Breast" or v.Name == "Right Breast" then
										i.Transparency = 0
									else
										i.Transparency = 1
									end
								end
								if PData.CurrentPartList["Clothes"]["Breasts Shirt"] then
									transparent(PData.CurrentPartList["Clothes"]["Left Breast 2"],1)
									transparent(PData.CurrentPartList["Clothes"]["Right Breast 2"],1)
									transparent(PData.CurrentPartList["Clothes"]["Breasts Shirt"],1)
									transparent(PData.CurrentPartList["Clothes"]["Breasts Pants"],1)
								end
								if PData.CurrentPartList["Clothes"]["Right Butt Shirt"] then
									transparent(PData.CurrentPartList["Clothes"]["Left Butt Shirt"],1)
									transparent(PData.CurrentPartList["Clothes"]["Right Butt Shirt"],1)
								end
							end
						elseif PData.TopHP ~= "" and 
							(PData.HardcoreHP == false and h.MaxHealth-h.Health < PData.TopHP or
								PData.HardcoreHP == true and PData.SavedTopHP > 0
							) then
							if PData.TopRipped == true then
								PData.TopRipped = false

								if UIS.KeyboardEnabled then
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxasset://RClothesContent/Sound/Heal/heal".. math.random(1,4) ..".mp3"
									audio.Volume = 2.5*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								else
									local sounds = {9113824422,9119138453,9113384209,9113824860}
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxassetid://"..  sounds[math.random(1,#sounds)]
									audio.Volume = 2.5*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								end

								if PData.HealParticles == true then
									local particle = Instance.new("ParticleEmitter",c:FindFirstChild("HumanoidRootPart"))
									particle.Enabled = false
									particle.Texture = "rbxassetid://16291625893"
									particle.LightEmission = 1
									particle.ZOffset = 1
									particle.Size = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,0),
											NumberSequenceKeypoint.new(1,.5)
										}
									)
									particle.Transparency = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,1),
											NumberSequenceKeypoint.new(0.5,0),
											NumberSequenceKeypoint.new(1,1)
										}
									)
									particle.Lifetime = NumberRange.new(0.5,1)
									particle.Rotation = NumberRange.new(-10,10)
									particle.RotSpeed = NumberRange.new(-10,10)
									particle.Speed = NumberRange.new(-1,2)
									particle.Drag = 2
									particle:Emit(math.random(4,8))
									game:GetService("Debris"):AddItem(particle,3)
								end

								if PData.CurrentPartList["Organ"]["Left Arm"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Left Arm"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Right Arm"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Right Arm"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Clothes"]["Torso Shirt"] then
									transparent(PData.CurrentPartList["Clothes"]["Torso Shirt"],0)
								end
								if (not c:FindFirstChildOfClass("Pants") or not PData.HPClothes.Pants) and PData.CurrentPartList["Organ"]["Torso"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Torso"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if c:FindFirstChildOfClass("Shirt") then
									Function.ShirtTexture(PData.CurrentPartList["Organ"]["Left Arm"],c,{Shirt = c:FindFirstChildOfClass("Shirt")},PlayerName)
									Function.ShirtTexture(PData.CurrentPartList["Organ"]["Right Arm"],c,{Shirt = c:FindFirstChildOfClass("Shirt")},PlayerName)
								end

								if PData.CurrentPartList["Organ"]["Left Breast"] then
									transparent(PData.CurrentPartList["Organ"]["Left Breast"],1)
									transparent(PData.CurrentPartList["Organ"]["Left Nipple"],1)
								end
								if PData.CurrentPartList["Organ"]["Right Breast"] then
									transparent(PData.CurrentPartList["Organ"]["Right Breast"],1)
									transparent(PData.CurrentPartList["Organ"]["Right Nipple"],1)
								end

								for i, v in pairs(PData.CurrentPartList.AreolaDecal) do
									if v.Name == "Left Breast" or v.Name == "Right Breast" then
										i.Transparency = 1
									else
										i.Transparency = 0
									end
								end
								if PData.CurrentPartList["Clothes"]["Breasts Shirt"] then
									transparent(PData.CurrentPartList["Clothes"]["Left Breast 2"],0)
									transparent(PData.CurrentPartList["Clothes"]["Right Breast 2"],0)
									transparent(PData.CurrentPartList["Clothes"]["Breasts Shirt"],0)
									transparent(PData.CurrentPartList["Clothes"]["Breasts Pants"],0)
								end
								if PData.CurrentPartList["Clothes"]["Right Butt Shirt"] then
									transparent(PData.CurrentPartList["Clothes"]["Left Butt Shirt"],PData.CurrentPartList["Clothes"]["Left Butt Shirt"]:GetAttribute("Alpha") or 0)
									transparent(PData.CurrentPartList["Clothes"]["Right Butt Shirt"],PData.CurrentPartList["Clothes"]["Right Butt Shirt"]:GetAttribute("Alpha") or 0)
								end
							end
						end
						-- bottom --
						if PData.BottomHP ~= "" and 
							(PData.HardcoreHP == false and h.MaxHealth-h.Health >= PData.BottomHP or
								PData.HardcoreHP == true and PData.SavedBottomHP <= 0
							) then
							if PData.BottomRipped == false then
								PData.BottomRipped = true

								if UIS.KeyboardEnabled then
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxasset://RClothesContent/Sound/Tear/tear".. math.random(1,3) ..".mp3"
									audio.Volume = 0.75*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								else
									local sounds = {9113827650,9113827551,9113833815}
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxassetid://"..  sounds[math.random(1,#sounds)]
									audio.Volume = 0.75*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								end

								if PData.TearParticles == true then
									local particle = Instance.new("ParticleEmitter",c:FindFirstChild("HumanoidRootPart"))
									particle.Enabled = false
									particle.Texture = "rbxassetid://386425736"
									particle.Size = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,.7,.375),
											NumberSequenceKeypoint.new(1,.4)
										}
									)
									particle.Transparency = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,1),
											NumberSequenceKeypoint.new(0.214,0),
											NumberSequenceKeypoint.new(0.545,0),
											NumberSequenceKeypoint.new(1,1)
										}
									)
									particle.Lifetime = NumberRange.new(0.5,1)
									particle.Rotation = NumberRange.new(-360,360)
									particle.RotSpeed = NumberRange.new(-360,360)
									particle.Speed = NumberRange.new(15,20)
									particle.SpreadAngle = Vector2.new(75,75)
									particle.Acceleration = Vector3.new(0,-15,0)
									particle.Drag = 5
									particle:Emit(50)
									game:GetService("Debris"):AddItem(particle,3)
								end

								if PData.CurrentPartList["Organ"]["Left Leg"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Left Leg"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Right Leg"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Right Leg"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Left Butt"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Left Butt"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Right Butt"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Right Butt"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Torso"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Torso"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.HPClothes.Pants ~= "" and not tonumber(PData.HPClothes.Pants) then
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Torso"],c,{Pants = PData.HPClothes.Pants},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Left Leg"],c,{Pants = PData.HPClothes.Pants},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Right Leg"],c,{Pants = PData.HPClothes.Pants},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Left Butt"],c,{Pants = PData.HPClothes.Pants},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Right Butt"],c,{Pants = PData.HPClothes.Pants},PlayerName)
								end
							end
						elseif PData.BottomHP ~= "" and 
							(PData.HardcoreHP == false and h.MaxHealth-h.Health < PData.BottomHP or
								PData.HardcoreHP == true and PData.SavedBottomHP > 0
							) then
							if PData.BottomRipped == true then
								PData.BottomRipped = false

								if UIS.KeyboardEnabled then
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxasset://RClothesContent/Sound/Heal/heal".. math.random(1,4) ..".mp3"
									audio.Volume = 2.5*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								else
									local sounds = {9113824422,9119138453,9113384209,9113824860}
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxassetid://"..  sounds[math.random(1,#sounds)]
									audio.Volume = 2.5*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								end

								if PData.HealParticles == true then
									local particle = Instance.new("ParticleEmitter",c:FindFirstChild("HumanoidRootPart"))
									particle.Enabled = false
									particle.Texture = "rbxassetid://16291625893"
									particle.LightEmission = 1
									particle.ZOffset = 1
									particle.Size = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,0),
											NumberSequenceKeypoint.new(1,.5)
										}
									)
									particle.Transparency = NumberSequence.new(
										{
											NumberSequenceKeypoint.new(0,1),
											NumberSequenceKeypoint.new(0.5,0),
											NumberSequenceKeypoint.new(1,1)
										}
									)
									particle.Lifetime = NumberRange.new(0.5,1)
									particle.Rotation = NumberRange.new(-10,10)
									particle.RotSpeed = NumberRange.new(-10,10)
									particle.Speed = NumberRange.new(-1,2)
									particle.Drag = 2
									particle:Emit(math.random(4,8))
									game:GetService("Debris"):AddItem(particle,3)
								end

								if PData.CurrentPartList["Organ"]["Left Leg"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Left Leg"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Right Leg"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Right Leg"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Left Butt"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Left Butt"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Right Butt"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Right Butt"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if PData.CurrentPartList["Organ"]["Torso"]:FindFirstChildOfClass("SurfaceAppearance") then
									PData.CurrentPartList["Organ"]["Torso"]:FindFirstChildOfClass("SurfaceAppearance"):Destroy()
								end
								if c:FindFirstChildOfClass("Pants") then
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Torso"],c,{Pants = c:FindFirstChildOfClass("Pants")},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Left Leg"],c,{Pants = c:FindFirstChildOfClass("Pants")},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Right Leg"],c,{Pants = c:FindFirstChildOfClass("Pants")},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Left Butt"],c,{Pants = c:FindFirstChildOfClass("Pants")},PlayerName)
									Function.PantsTexture(PData.CurrentPartList["Organ"]["Right Butt"],c,{Pants = c:FindFirstChildOfClass("Pants")},PlayerName)
								end
							end
						end

						if (PData.SavedPreviousHP-h.Health) >= 0 and PData.HardcoreHP == true then
							PData.SavedTopHP -= (PData.SavedPreviousHP-h.Health)
							PData.SavedBottomHP -= (PData.SavedPreviousHP-h.Health)
						end
						if PData.DamageSFX ~= "" and h.Health < PData.SavedPreviousHP then
							if (PData.SavedPreviousHP-h.Health) >= PData.DamageSFX then
								if UIS.KeyboardEnabled then
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxasset://RClothesContent/Sound/Moan/".. math.random(1,14) ..".ogg"
									audio.Volume = 1.5*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								else
									local sounds = {4792913155,4792899013,4792904673,4792901644,4792915329,4792884617}
									local audio = Instance.new("Sound",c.PrimaryPart)
									audio.SoundId = "rbxassetid://".. sounds[math.random(1,#sounds)]
									audio.Volume = 1.5*PData.Volume
									audio:Play()
									game:GetService("Debris"):AddItem(audio,3)
								end
							end
						end
						PData.SavedPreviousHP = h.Health
					end
				end
			end

			for Part, Property in pairs(DataList.CurrentPartList.RealtimeUpdateList.Accessory) do
				local Removed = false

				if Part.Parent == nil or Function.IsParentNil(Part) or Function.FallenPartCheck(Part) then
					DataList.CurrentPartList.RealtimeUpdateList.Accessory[Part] = nil

					Removed = true
				end

				if Removed == false then
					local Base = Property.Base
					local Attach = Property.Attachment
					local PAttach = Property.ParentAttachment
					local CF = Property.CFrame
					local Size = Property.Size
					local Scale = Property.Scale
					local SpecialMesh = Property.SpecialMesh
					local Weld = Property.Weld

					local PAttachCFrame = AttachmentCFrame[PAttach.Name]

					local BodySize = BodyPartSize[Base.Name]
					if not BodySize then
						if Base.Name == "UpperTorso" or Base.Name == "LowerTorso" then
							BodySize = BodyPartSize["Torso"]
						elseif Base.Name == "RightUpperArm" or Base.Name == "LeftLowerArm" then
							BodySize = BodyPartSize["Left Arm"]
						elseif Base.Name == "RightUpperArm" or Base.Name == "RightLowerArm" then
							BodySize = BodyPartSize["Right Arm"]
						elseif Base.Name == "LeftUpperLeg" or Base.Name == "LeftLowerLeg" then
							BodySize = BodyPartSize["Left Leg"]
						elseif Base.Name == "RightUpperLeg" or Base.Name == "RightLowerrLeg" then
							BodySize = BodyPartSize["Right Leg"]
						end
					end

					local XMultiply, YMultiply, ZMultiply = Function.MultiplyCalculate(Base.Size, BodySize)

					if PlayerData[PlayerName].RealtimeBodyTransparency == true then
						Part.Transparency = Base.Transparency
					end
					if PlayerName == lP.Name then
						if PlayerData[PlayerName].LocalTransparency[Base.Name] == true 
							and PlayerData[PlayerName].LocalTransparency["Hat"] == true then
							Part.LocalTransparencyModifier = Part.Transparency
						elseif Method == 2 then
							if lP.Character and lP.Character.HumanoidRootPart then
								local chr = lP.Character
								local human = chr.Humanoid
								local rootPart = chr.HumanoidRootPart

								local currentCamera = workspace.CurrentCamera
								local function Round(num: number, places: number): number
									local decimalPivot = 10^places
									return math.floor(num * decimalPivot + 0.5) / decimalPivot
								end
								if currentCamera then
									local distance = (currentCamera.Focus.p - currentCamera.CoordinateFrame.p).magnitude
									local transparency = (distance<2) and (1.0-(distance-0.5)/1.5) or 0
									if transparency < 0.5 then
										transparency = 0
									end

									transparency = math.clamp(Round(transparency, 2), 0, 1)
									if transparency >= 0.85 then
										transparency = 1
									end
									if Part.LocalTransparencyModifier ~= transparency then
										if math.abs(Part.LocalTransparencyModifier-transparency) > .4 or Part.LocalTransparencyModifier > .95 then
											Part.LocalTransparencyModifier = transparency
										else
											Part.LocalTransparencyModifier = Part.Transparency+math.lerp(Part.LocalTransparencyModifier,transparency,.2)
										end
									end
								end
							end
						end
					end

					if PlayerData[PlayerName].AccessorySizeLock == false then
						Part.Size = Vector3.new(Size.X * XMultiply, Size.Y * YMultiply, Size.Z * ZMultiply)
						SpecialMesh.Scale = Vector3.new(Scale.X * XMultiply, Scale.Y * YMultiply, Scale.Z * ZMultiply)
						Attach.CFrame = CFrame.new(CF.Position.X * XMultiply, CF.Position.Y * YMultiply, CF.Position.Z * ZMultiply) * CF.Rotation
						PAttach.CFrame = CFrame.new(PAttachCFrame.Position.X * XMultiply, PAttachCFrame.Position.Y * YMultiply, PAttachCFrame.Position.Z * ZMultiply) * PAttachCFrame.Rotation
						Weld.C0 = Attach.CFrame
						Weld.C1 = PAttach.CFrame
					end
				end
			end

			for i, v in pairs(DataList.CurrentPartList.RealtimeUpdateList.Special) do
				local Removed = false

				if v.Parent == nil or Function.IsParentNil(v) then
					DataList.CurrentPartList.RealtimeUpdateList.Special[i] = nil

					Removed = true
				end

				if Removed == false then
					local origin = v.Parent
					local particle = v:FindFirstChildOfClass("ParticleEmitter")
					--[[
					local par = RaycastParams.new()
					par.FilterDescendantsInstances = {Player.Character:GetDescendants(),Method2CharacterFolder:GetDescendants()}
					par.FilterType = Enum.RaycastFilterType.Exclude
					par.RespectCanCollide = true
					local cast = workspace:Raycast(origin.Position,Vector3.new(0,-10000,0),par)
					if cast then
						particle.Enabled = true
						v.WorldCFrame = CFrame.new(Vector3.new(cast)) * cast.Instance.CFrame.Rotation
					else
						particle.Enabled = false
					end
					]]
					local ignoreList = {}
					for i, v in pairs(collisionList) do
						table.insert(ignoreList,v)
					end
					for i, v in pairs(Player.Character:GetDescendants()) do
						if v:IsA("BasePart") then
							table.insert(ignoreList,v)
						end
					end
					for i, v in pairs(Method2CharacterFolder:GetDescendants()) do
						if v:IsA("BasePart") then
							table.insert(ignoreList,v)
						end
					end
					local instance,hit = workspace:FindPartOnRayWithIgnoreList(
						Ray.new(origin.Position,Vector3.new(0,-10000,0)),
						ignoreList
					)
					if hit then
						if instance.CanCollide == false and not collisionChecks[instance] then
							table.insert(collisionList,instance)
							local collisionChange = instance:GetPropertyChangedSignal("CanCollide"):Connect(function()
								if instance.CanCollide == false and not table.find(collisionList,instance) then
									table.insert(collisionList,instance)
								elseif instance.CanCollide == true then
									table.remove(collisionList,table.find(collisionList,instance))
								end
							end)
							collisionChecks[instance] = collisionChange
							table.insert(AllConnect, collisionChange)
						else
							particle.Enabled = true
							v.WorldCFrame = CFrame.new(hit) --* instance.CFrame.Rotation
						end
					else
						particle.Enabled = false
					end
				end
			end
			for Part, Property in pairs(DataList.CurrentPartList.TransparencyLink) do
				local Removed = false

				if Part.Parent == nil or Function.IsParentNil(Part) or Function.FallenPartCheck(Part) then
					DataList.CurrentPartList.TransparencyLink[Part] = nil

					Removed = true
				end

				if Removed == false then
					local T = Property.T.Transparency
					local D = Property.Define

					Part.LocalTransparencyModifier = math.clamp(Property.T.LocalTransparencyModifier,D,math.huge)
					Part.Transparency = math.clamp(T,D,math.huge)
				end
			end

			for Part, Property in pairs(DataList.CurrentPartList.ParentTransparency) do
				local Removed = false

				if Part.Parent == nil or Function.IsParentNil(Part) or Function.FallenPartCheck(Part) then
					DataList.CurrentPartList.ParentTransparency[Part] = nil

					Removed = true
				end

				if Removed == false then
					local T = Property.T

					if T then
						PlayerData[PlayerName].OldTransparency[Part] = Part.Transparency
						if PlayerData[PlayerName].RealtimeBodyTransparency == true then
							Part.LocalTransparencyModifier = T
						else
							Part.Transparency = T
						end
					end
				end
			end

			for Decal, Part in pairs(DataList.CurrentPartList.AreolaDecal) do
				local Removed = false

				if Part.Parent == nil or Function.IsParentNil(Part) or Function.FallenPartCheck(Part) then
					DataList.CurrentPartList.AreolaDecal[Decal] = nil

					Removed = true
				end

				if Removed == false then
					Decal.Transparency = Part.Transparency
					Decal.LocalTransparencyModifier = Part.LocalTransparencyModifier
				end
			end
		end

		PreviewRotate += Circle / PreviewRotateSpeed
		GUIObject.ViewportCamera.CFrame = CFrame.lookAt(Vector3.new(math.sin(PreviewRotate)*PreviewRadius, 0, math.cos(PreviewRotate)*PreviewRadius), Vector3.new(0,0,0))
	end)

	local PhysicsConnect = RS.RenderStepped:Connect(function(d)
		for PlayerName, DataList in pairs(PlayerData) do
			for Part, Property in pairs(DataList.CurrentPartList.BodyPartPhysics) do
				task.spawn(function()
					if Function.FallenPartCheck(Part) then
						DataList.CurrentPartList.BodyPartPhysics[Part] = nil

						return
					end

					local Character = DataList.Character
					local Human = Character:FindFirstChildOfClass("Humanoid")

					if Character and Human then
						local Base = Property.Base
						local Camera = game.Workspace.CurrentCamera

						local CurrentCFrame = Base.CFrame

						local OriginCFrame = Property.OriginCFrame
						local OriginPosition = OriginCFrame.Position
						local CurrentPosition = CurrentCFrame.Position
						local PositionDistance = (OriginPosition - CurrentPosition)

						--[[local function Round(num: number, places: number): number
							local decimalPivot = 10^places
							return math.floor(num * decimalPivot + 0.5) / decimalPivot
						end
						print(Round(PositionDistance.Magnitude,2),math.max(Human.WalkSpeed/8,1),Round(Base.AssemblyLinearVelocity.Magnitude,2))]]
						if (Camera.CFrame.Position - Base.Position).Magnitude < 300 
							and (PositionDistance.Magnitude < math.max(Human.WalkSpeed/8,1) or PositionDistance.Magnitude <= Base.AssemblyLinearVelocity.Magnitude) then
							local Weld = Property.Weld
							local CF = Property.CF
							local CF1 = Property.CF1
							local Spring = Property.Spring
							local PositionOffset = Property.PositionOffset
							local RotationOffset = Property.RotationOffset
							local Position = Property.Position
							local Rotation = Property.Rotation

							local OriginLookVector = OriginCFrame.LookVector
							local CurrentLookVector = CurrentCFrame.LookVector
							local LookVectorDistance = (OriginLookVector - CurrentLookVector)
							local LookVectorAxis = Vector3.new(LookVectorDistance.X, LookVectorDistance.Y, 0)

							Spring:TimeSkip(d)
							Spring:Impulse(PositionDistance + LookVectorAxis, 0, 0)

							local PositionList = {
								X = 0,
								Y = 0,
								Z = 0
							}

							local RotationList = {
								X = 0,
								Y = 0,
								Z = 0
							}

							for From, To in pairs(PositionOffset) do
								PositionList[From] = (Position[To] * Spring.Velocity[To]) * PositionPhysicsMultiply
							end

							for From, To in pairs(RotationOffset) do
								RotationList[From] = (math.rad(Rotation[To] * Spring.Velocity[To])) * RotationPhysicsMultiply
							end

							Weld.C0 = CF * (
								CFrame.new(
									PositionList.X,
									PositionList.Y,
									PositionList.Z
								) * CFrame.Angles(
									RotationList.X,
									RotationList.Y,
									RotationList.Z
								)
							)

							if DataList["PhysicsObeyGravity"] == true then

								if Part.Name == "Left Breast" then
									Part:AddTag("AppliedPhysics")
									local frame = Base.CFrame

									if Property.BreastsType == 2 then -- type2
										Weld.C1 = CF1 * CFrame.Angles(
											math.abs(OriginLookVector.Y)*-math.clamp(frame.LookVector.Y,-math.huge,.35),
											0,
											-frame.RightVector.Y
										)
									elseif Property.BreastsType == 3 then -- type3
										Weld.C1 = CF1 * CFrame.Angles(
											(-frame.LookVector.Y*.2)-frame.RightVector.Y,
											0,
											math.abs(OriginLookVector.Y)*math.clamp(frame.LookVector.Y,-math.huge,.35)
										)
									else -- default
										Weld.C1 = CF1 * CFrame.Angles(
											(frame.LookVector.Y*.2)+frame.RightVector.Y,
											0,
											math.abs(OriginLookVector.Y)*-math.clamp(frame.LookVector.Y,-math.huge,.35)
										)
									end

								elseif Part.Name == "Right Breast" then
									Part:AddTag("AppliedPhysics")
									local frame = Base.CFrame

									if Property.BreastsType == 2 then -- type2
										Weld.C1 = CF1 * CFrame.Angles(
											math.abs(OriginLookVector.Y)*-math.clamp(frame.LookVector.Y,-math.huge,.35),
											0,
											-frame.RightVector.Y
										)
									elseif Property.BreastsType == 3 then -- type3
										Weld.C1 = CF1 * CFrame.Angles(
											(frame.LookVector.Y*.2)-frame.RightVector.Y,
											0,
											math.abs(OriginLookVector.Y)*math.clamp(frame.LookVector.Y,-math.huge,.35)
										)
									else -- default
										Weld.C1 = CF1 * CFrame.Angles(
											(-frame.LookVector.Y*.2)+frame.RightVector.Y,
											0,
											math.abs(OriginLookVector.Y)*-math.clamp(frame.LookVector.Y,-math.huge,.35)
										)
									end


								elseif Part.Name == "Breasts Shirt" or Part.Name == "Breasts Pants" then
									local frame = Base.CFrame
									Weld.C1 = CF1 * CFrame.Angles(
										frame.RightVector.Y,
										0,
										math.abs(OriginLookVector.Y)*-math.clamp(frame.LookVector.Y,-math.huge,.42)
									)
								end

							elseif Part:HasTag("AppliedPhysics") then

								if Part.Name == "Left Breast" 
									or Part.Name == "Right Breast" 
									or Part.Name == "Breasts Shirt" or Part.Name == "Breasts Pants" then
									Weld.C1 = CF1
									Part:RemoveTag("AppliedPhysics")
								end

							end
						--[[else
							warn("IT WENT ABOVE")]]
						end

						PlayerData[PlayerName].CurrentPartList.BodyPartPhysics[Part].OriginCFrame = CurrentCFrame
					end
				end)
			end
		end
	end)

	local FrameEnterConnect = GUIObject.MainFrame.MouseEnter:Connect(function()
		IsEnterFrame = true
	end)

	local FrameLeaveConnect = GUIObject.MainFrame.MouseLeave:Connect(function()
		if IsMouseDown == false then
			IsEnterFrame = false
		end
	end)
	local cooldown = false
	local MouseDown = Mouse.Button1Down:Connect(function()
		IsMouseDown = true
		MouseDownStart = UIS:GetMouseLocation()
		GuiPositionStart = GUIObject.MainFrame.Position

		if ClickExecute == true and cooldown == false then
			cooldown = true
			local Part = Mouse.Target


			if Part and Part:FindFirstAncestorOfClass("Model") ~= nil then
				if Function.IsCharacter(Part:FindFirstAncestorOfClass("Model")) then
					Function.CharacterReset(Part:FindFirstAncestorOfClass("Model"))
					if game.Players:FindFirstChild(Part:FindFirstAncestorOfClass("Model").Name) == nil and PlayerData[SelectPlayer] ~= nil then
						local NPCData = math.random(0, 999999999).. Part:FindFirstAncestorOfClass("Model").Name
						if Function.TableFind(NPCs, Part:FindFirstAncestorOfClass("Model")) == nil then
							NPCs[NPCData] = Part:FindFirstAncestorOfClass("Model")
						else
							NPCData = Function.TableFind(NPCs, Part:FindFirstAncestorOfClass("Model"))
						end
						local cDataTable = Function.TableClone(PlayerData[SelectPlayer])
						cDataTable.CurrentPartList = Function.PlayerDataDefault().CurrentPartList
						PlayerData[NPCData] = cDataTable
						Function.CharacterExecute(Part:FindFirstAncestorOfClass("Model"), NPCData)
					else
						Function.CharacterReset(Part:FindFirstAncestorOfClass("Model").Name)
						Function.CharacterExecute(Part:FindFirstAncestorOfClass("Model"), Part:FindFirstAncestorOfClass("Model").Name)
					end
				end
			end
			cooldown = false
		end
	end)
	local MouseDown2 = Mouse.Button2Down:Connect(function()

		if ClickExecute == true and cooldown == false then
			cooldown = true
			local Part = Mouse.Target


			if Part and Part:FindFirstAncestorOfClass("Model") ~= nil then
				if Function.IsCharacter(Part:FindFirstAncestorOfClass("Model")) then
					if game.Players:GetPlayerFromCharacter(Part:FindFirstAncestorOfClass("Model")) then
						Function.CharacterReset(Part:FindFirstAncestorOfClass("Model").Name,true)
					else
						Function.CharacterReset(Part:FindFirstAncestorOfClass("Model"),true)
					end
				end
			end
			cooldown = false
		end
	end)

	local MouseUp = Mouse.Button1Up:Connect(function()
		IsMouseDown = false
		IsEnterFrame = false
		MouseDownStart = nil
		GuiPositionStart = nil
	end)

	local MouseMoveConnect = Mouse.Move:Connect(Function.DragUpdate)

	table.insert(AllConnect, FrameEnterConnect)
	table.insert(AllConnect, FrameLeaveConnect)
	table.insert(AllConnect, MouseDown)
	table.insert(AllConnect, MouseDown2)
	table.insert(AllConnect, MouseUp)
	table.insert(AllConnect, MouseMoveConnect)
	table.insert(AllConnect, UISBeganConnect)
	table.insert(AllConnect, RunConnect)
	table.insert(AllConnect, PhysicsConnect)

	--[[
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------

       ██╗░░░██╗░██████╗███████╗██████╗░  ██╗███╗░░██╗████████╗███████╗██████╗░███████╗░█████╗░░█████╗░███████╗
       ██║░░░██║██╔════╝██╔════╝██╔══██╗  ██║████╗░██║╚══██╔══╝██╔════╝██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔════╝
       ██║░░░██║╚█████╗░█████╗░░██████╔╝  ██║██╔██╗██║░░░██║░░░█████╗░░██████╔╝█████╗░░███████║██║░░╚═╝█████╗░░
       ██║░░░██║░╚═══██╗██╔══╝░░██╔══██╗  ██║██║╚████║░░░██║░░░██╔══╝░░██╔══██╗██╔══╝░░██╔══██║██║░░██╗██╔══╝░░
       ╚██████╔╝██████╔╝███████╗██║░░██║  ██║██║░╚███║░░░██║░░░███████╗██║░░██║██║░░░░░██║░░██║╚█████╔╝███████╗
       ░╚═════╝░╚═════╝░╚══════╝╚═╝░░╚═╝  ╚═╝╚═╝░░╚══╝░░░╚═╝░░░╚══════╝╚═╝░░╚═╝╚═╝░░░░░╚═╝░░╚═╝░╚════╝░╚══════╝
                                  
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	]]

	function Function.GUIFunc()
		for _, Button in pairs(GUIObject.ButtonFrame:GetChildren()) do
			if Button:FindFirstChildOfClass("TextButton") then
				Button:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
					for _, Page in pairs(GUIObject.PageFrame:GetChildren()) do
						if Page:IsA("Frame") or Page:IsA("ScrollingFrame") then
							Page.Visible = false
						end
					end

					local Page = GUIObject.PageFrame:WaitForChild(Button.Name)
					Page.Visible = true
				end)
			end
		end
		local debounce = false
		local ExecuteConnect = GUIObject.ExecuteButton.MouseButton1Click:Connect(function()
			if debounce == false then
				debounce = true
				local ExecutePlayer = game.Players:FindFirstChild(SelectPlayer)

				if ExecutePlayer then
					local ExecuteCharacter = ExecutePlayer.Character

					if ExecuteCharacter then
						Function.CharacterReset(ExecutePlayer.Name)
						Function.CharacterExecute(ExecuteCharacter, ExecutePlayer.Name)
					end
				end
				debounce = false
			end
		end)

		local ResetConnect = GUIObject.ResetButton.MouseButton1Click:Connect(function()
			Function.CharacterReset(SelectPlayer)
		end)

		local DestroyConnect = GUIObject.DestroyButton.MouseButton1Click:Connect(function()
			local BreakerInstance = Instance.new("BoolValue", game.workspace)
			BreakerInstance.Name = "RoClothesBreaker"
			game:GetService("Debris"):AddItem(BreakerInstance,2)
		end)

		local DelayTimeConnect = GUIObject.DelayTimeText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.DelayTimeText.Text) then
				PlayerData[SelectPlayer].DelayTime = tonumber(GUIObject.DelayTimeText.Text)
			end
		end)

		local PlayerChangeConnect = GUIObject.PlayerExecute:GetPropertyChangedSignal("Text"):Connect(function()
			if game.Players:FindFirstChild(GUIObject.PlayerExecute.Text) then
				SelectPlayer = GUIObject.PlayerExecute.Text
				GUIObject.PlayerExecute.TextColor3 = Color3.new(1,1,1)

				Function.PlayerDataAdd(SelectPlayer)
				Function.GUIUpdate()
			elseif not game.Players:FindFirstChild(GUIObject.PlayerExecute.Text) and GUIObject.PlayerExecute.Text ~= "Self" then
				GUIObject.PlayerExecute.TextColor3 = Color3.new(1,0,0)
			elseif not game.Players:FindFirstChild(GUIObject.PlayerExecute.Text) and GUIObject.PlayerExecute.Text == "Self" then
				SelectPlayer = Player.Name
				GUIObject.PlayerExecute.TextColor3 = Color3.new(1,1,1)

				Function.GUIUpdate()
			end
		end)

		local AutoExecuteConnect = GUIObject.AutoExecuteButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].AutoExecute = not PlayerData[SelectPlayer].AutoExecute

			Function.GUIUpdate()
		end)

		local BundleBodyColorConnect = GUIObject.BundleBodyColorButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].BundleBodyColor = not PlayerData[SelectPlayer].BundleBodyColor

			Function.GUIUpdate()
		end)

		local FaceConnect = GUIObject.FaceButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].Face = not PlayerData[SelectPlayer].Face

			Function.GUIUpdate()
		end)

		local MeshSizeLockConnect = GUIObject.MeshSizeLockButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].MeshSizeLock = not PlayerData[SelectPlayer].MeshSizeLock

			Function.GUIUpdate()
		end)

		local AccessorySizeLockConnect = GUIObject.AccessorySizeLockButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].AccessorySizeLock = not PlayerData[SelectPlayer].AccessorySizeLock

			Function.GUIUpdate()
		end)

		local MeshBasePartInvisibleConnect = GUIObject.MeshBasePartInvisibleButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].MeshBasePartInvisible = not PlayerData[SelectPlayer].MeshBasePartInvisible

			Function.GUIUpdate()
		end)

		local BodyPartPhysicsConnect = GUIObject.BodyPartPhysicsButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].BodyPartPhysics = not PlayerData[SelectPlayer].BodyPartPhysics

			Function.GUIUpdate()
		end)

		local ToneConnect = GUIObject.ToneButton.MouseButton1Click:Connect(function()
			if PlayerData[SelectPlayer].Tone == "Base" then
				PlayerData[SelectPlayer].Tone = "Dark"
			elseif PlayerData[SelectPlayer].Tone == "Dark" then
				PlayerData[SelectPlayer].Tone = "Use NippleColor"
			elseif PlayerData[SelectPlayer].Tone == "Use NippleColor" then
				PlayerData[SelectPlayer].Tone = "Base"
			end

			Function.GUIUpdate()
		end)

		local KeybindConnect = GUIObject.KeybindButton.MouseButton1Click:Connect(function()
			if UIS.KeyboardEnabled then
				GUIObject.KeybindButton.Text = "Change Keybind (Click On Keyboard)"
				KeybindDetect = true
			end
		end)

		local MethodConnect = GUIObject.MethodButton.MouseButton1Click:Connect(function()
			Method += 1

			if Method > MaxMethod then
				Method = 1
			end

			GUIObject.MethodButton.Text = "Method: "..Method

			Function.GUIUpdate()
		end)
		local MethodConnect2 = GUIObject.MethodButton.MouseButton2Click:Connect(function()
			Method -= 1

			if Method < 1 then
				Method = MaxMethod
			end

			GUIObject.MethodButton.Text = "Method: "..Method

			Function.GUIUpdate()
		end)

		local UsernameConnect = GUIObject.UsernameTextbox.FocusLost:Connect(function()
			PlayerData[SelectPlayer].CatalogUsername = GUIObject.UsernameTextbox.Text

			PlayerData[SelectPlayer].CatalogRemove = {}
			if GUIObject.Catalog_3:FindFirstChild(SelectPlayer) then
				for i, v in pairs(GUIObject.Catalog_3:FindFirstChild(SelectPlayer):GetChildren()) do
					if not v:IsA("UIGridLayout") then
						v:Destroy()
					end
				end
			end
			if PlayerData[SelectPlayer].CatalogUsername ~= "" then

				pcall(function()
					local UsernameId = game.Players:GetUserIdFromNameAsync(PlayerData[SelectPlayer].CatalogUsername)

					local HumanoidDescription = game.Players:GetHumanoidDescriptionFromUserId(UsernameId)

					for i, accessory in pairs(HumanoidDescription:GetAccessories(true)) do
						if accessory then
							local AccessoryInfo = MPS:GetProductInfo(accessory.AssetId)

							local Button = Function.ButtonCreate(AccessoryInfo.Name, GUIObject.Catalog_3:FindFirstChild(SelectPlayer))

							local AccessoryRemoveButtonConnect
							AccessoryRemoveButtonConnect = Button:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
								if not table.find(PlayerData[SelectPlayer].CatalogRemove, accessory.AssetId) then
									table.insert(PlayerData[SelectPlayer].CatalogRemove, accessory.AssetId)
								end

								Button:Destroy()
								AccessoryRemoveButtonConnect:Disconnect()
							end)

							table.insert(AllConnect, AccessoryRemoveButtonConnect)
						end
					end

				end)
			end

			Function.GUIUpdate()
		end)

		local ShirtConnect = GUIObject.ShirtTextbox:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.ShirtTextbox.Text) then
				PlayerData[SelectPlayer].CatalogClothes.Shirt = GUIObject.ShirtTextbox.Text

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].CatalogClothes.Shirt = ""

				Function.GUIUpdate()
			end
		end)

		local PantsConnect = GUIObject.PantsTextbox:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.PantsTextbox.Text) then
				PlayerData[SelectPlayer].CatalogClothes.Pants = GUIObject.PantsTextbox.Text

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].CatalogClothes.Pants = ""

				Function.GUIUpdate()
			end
		end)

		local ShirtGraphicConnect = GUIObject.ShirtGraphicTextbox:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.ShirtGraphicTextbox.Text) then
				PlayerData[SelectPlayer].CatalogClothes.ShirtGraphic = GUIObject.ShirtGraphicTextbox.Text

				Function.GUIUpdate()
			end
		end)

		local BreastsScaleConnect = GUIObject.BreastsScaleText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.BreastsScaleText.Text) then
				PlayerData[SelectPlayer].BreastsScale = GUIObject.BreastsScaleText.Text

				Function.GUIUpdate()
			end
		end)

		local ButtsScaleConnect = GUIObject.ButtsScaleText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.ButtsScaleText.Text) then
				PlayerData[SelectPlayer].ButtsScale = GUIObject.ButtsScaleText.Text

				Function.GUIUpdate()
			end
		end)

		local LegsScaleConnect = GUIObject.LegsScaleText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.LegsScaleText.Text) then
				PlayerData[SelectPlayer].LegsScale = GUIObject.LegsScaleText.Text

				Function.GUIUpdate()
			end
		end)

		local PositionPhysicsMultiplyConnect = GUIObject.PositionPhysicsMultiplyText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.PositionPhysicsMultiplyText.Text) then
				PositionPhysicsMultiply = GUIObject.PositionPhysicsMultiplyText.Text

				Function.GUIUpdate()
			end
		end)

		local RotationPhysicsMultiplyConnect = GUIObject.RotationPhysicsMultiplyText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.RotationPhysicsMultiplyText.Text) then
				RotationPhysicsMultiply = GUIObject.RotationPhysicsMultiplyText.Text

				Function.GUIUpdate()
			end
		end)

		local BreastsTypeConnect = GUIObject.BreastsTypeButton.MouseButton1Down:Connect(function()
			PlayerData[SelectPlayer].BreastsType += 1

			if PlayerData[SelectPlayer].BreastsType > MaxBreastsType then
				PlayerData[SelectPlayer].BreastsType = 1
			end

			Function.GUIUpdate()
		end)

		local TorsoTypeConnect = GUIObject.TorsoTypeButton.MouseButton1Down:Connect(function()
			PlayerData[SelectPlayer].TorsoType += 1

			if PlayerData[SelectPlayer].TorsoType > MaxTorsoType then
				PlayerData[SelectPlayer].TorsoType = 1
			end

			Function.GUIUpdate()
		end)

		local ArmTypeConnect = GUIObject.ArmTypeButton.MouseButton1Down:Connect(function()
			PlayerData[SelectPlayer].ArmType += 1

			if PlayerData[SelectPlayer].ArmType > MaxArmType then
				PlayerData[SelectPlayer].ArmType = 1
			end

			Function.GUIUpdate()
		end)

		local LegsTypeConnect = GUIObject.LegsTypeButton.MouseButton1Down:Connect(function()
			PlayerData[SelectPlayer].LegsType += 1

			if PlayerData[SelectPlayer].LegsType > MaxLegsType then
				PlayerData[SelectPlayer].LegsType = 1
			end

			Function.GUIUpdate()
		end)

		local LegsTypeConnect = GUIObject.ButtTypeButton.MouseButton1Down:Connect(function()
			PlayerData[SelectPlayer].ButtType += 1

			if PlayerData[SelectPlayer].ButtType > MaxButtType then
				PlayerData[SelectPlayer].ButtType = 1
			end

			Function.GUIUpdate()
		end)

		local BodyTransparencyConnect = GUIObject.BodyTransparencyButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].RealtimeBodyTransparency = not PlayerData[SelectPlayer].RealtimeBodyTransparency

			Function.GUIUpdate()
		end)

		local ClickExecuteConnect = GUIObject.ClickExecuteButton.MouseButton1Click:Connect(function()
			ClickExecute = not ClickExecute

			Function.GUIUpdate()
		end)

		local TCS = game:GetService("TextChatService")
		if TCS:FindFirstChild("TextChatCommands") == nil then
			local newfolder = Instance.new("Folder", TCS)
			newfolder.Name = "TextChatCommands"
		end

		local BBCToggleCommand = Instance.new("TextChatCommand", game:GetService("TextChatService").TextChatCommands)
		BBCToggleCommand.Name = "ToggleCommand"
		BBCToggleCommand.PrimaryAlias = "/e toggle"
		BBCToggleCommand.SecondaryAlias = "/e tg"

		local BBCToggleConnect = BBCToggleCommand.Triggered:Connect(function()
			if PlayerData[SelectPlayer].ToggleBBC == true then
				PlayerData[SelectPlayer].ToggleBBC = false
			else
				PlayerData[SelectPlayer].ToggleBBC = true
			end
			local TextChatService = game:GetService("TextChatService")
			local Channel = TextChatService:WaitForChild("TextChannels"):WaitForChild("RBXGeneral")
			Channel:DisplaySystemMessage(tostring(PlayerData[SelectPlayer].ToggleBBC))
		end)

		local MobileCloseConnect = GUIObject.MobileCloseButton.MouseButton1Click:Connect(function()
			GUIObject.Screen.Enabled = not GUIObject.Screen.Enabled
		end)

		local SkinToneConnect = GUIObject.SkinToneText.FocusLost:Connect(function()
			local Text = GUIObject.SkinToneText.Text

			if Text == "" then
				PlayerData[SelectPlayer].SkinTone = nil
			else
				local Color = Function.StringTo(Text, "RGB")

				PlayerData[SelectPlayer].SkinTone = Color
				GUIObject.SkinToneText.TextColor3 = Color
			end
		end)

		local NippleColorConnect = GUIObject.NippleColorText.FocusLost:Connect(function()
			local Text = GUIObject.NippleColorText.Text

			if Text == "" then
				PlayerData[SelectPlayer].NippleColor = nil
			else
				local Color = Function.StringTo(Text, "RGB")

				PlayerData[SelectPlayer].NippleColor = Color
				GUIObject.NippleColorText.TextColor3 = Color
			end
		end)

		local AccessoryConnect = GUIObject.AccessoryTextbox.FocusLost:Connect(function()
			if tonumber(GUIObject.AccessoryTextbox.Text) then
				table.insert(PlayerData[SelectPlayer].CatalogAccessory, GUIObject.AccessoryTextbox.Text)

				local Button = Function.ButtonCreate(GUIObject.AccessoryTextbox.Text, GUIObject.Catalog_3:FindFirstChild(SelectPlayer))

				local AccessoryButtonConnect
				AccessoryButtonConnect = Button:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
					for i, v in pairs(PlayerData[SelectPlayer].CatalogAccessory) do
						if tonumber(v) == tonumber(Button.Name) then
							table.remove(PlayerData[SelectPlayer].CatalogAccessory, i)
						end
					end

					Button:Destroy()
					AccessoryButtonConnect:Disconnect()
				end)

				table.insert(AllConnect, AccessoryButtonConnect)
			end
		end)

		local OutfitIdConnect = GUIObject.OutfitIdTextbox.FocusLost:Connect(function()
			if tonumber(GUIObject.OutfitIdTextbox.Text) then
				local Text = GUIObject.OutfitIdTextbox.Text

				if Text == "" then
					PlayerData[SelectPlayer].CatalogOutfitId = ""
				else
					PlayerData[SelectPlayer].CatalogOutfitId = Text
				end

				PlayerData[SelectPlayer].CatalogRemove = {}
				if GUIObject.Catalog_3:FindFirstChild(SelectPlayer) then
					for i, v in pairs(GUIObject.Catalog_3:FindFirstChild(SelectPlayer):GetChildren()) do
						if not v:IsA("UIGridLayout") then
							v:Destroy()
						end
					end
				end
				if PlayerData[SelectPlayer].CatalogOutfitId ~= "" then

					pcall(function()
						local HumanoidDescription = game.Players:GetHumanoidDescriptionFromOutfitId(PlayerData[SelectPlayer].CatalogOutfitId)

						for i, accessory in pairs(HumanoidDescription:GetAccessories(true)) do
							if accessory then
								local AccessoryInfo = MPS:GetProductInfo(accessory.AssetId)

								local Button = Function.ButtonCreate(AccessoryInfo.Name, GUIObject.Catalog_3:FindFirstChild(SelectPlayer))

								local AccessoryRemoveButtonConnect
								AccessoryRemoveButtonConnect = Button:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
									if not table.find(PlayerData[SelectPlayer].CatalogRemove, accessory.AssetId) then
										table.insert(PlayerData[SelectPlayer].CatalogRemove, accessory.AssetId)
									end

									Button:Destroy()
									AccessoryRemoveButtonConnect:Disconnect()
								end)

								table.insert(AllConnect, AccessoryRemoveButtonConnect)
							end
						end

					end)
				end

				Function.GUIUpdate()
			end
		end)

		local MeshNameConnect = GUIObject.MeshNameTextbox:GetPropertyChangedSignal("Text"):Connect(function()
			local Text = GUIObject.MeshNameTextbox.Text

			if PartList[Text] then
				GUIObject.MeshNameTextbox.TextColor3 = Color3.new(1,1,1)

				Function.GUIUpdate()
			elseif Text == "DEBUG" then
				GUIObject.MeshNameTextbox.TextColor3 = Color3.new(0,1,0)

				Function.GUIUpdate()
			else
				GUIObject.MeshNameTextbox.TextColor3 = Color3.new(1,0,0)
			end
		end)

		local CharacterPreviewConnect = GUIObject.PreviewButton.MouseButton1Click:Connect(function()
			Function.CharacterPreview(SelectPlayer)
		end)

		local BundleButtons = {}
		local ClothesButtons = {}
		local RecolorButtons = {}

		for i, v in pairs(Bundle) do
			local BButton = Function.ButtonCreate(i, GUIObject.BundlesButtonFrame)
			if v.ClothingBundle and v.ClothingBundle == true then
				BButton.BackgroundColor3 = Color3.fromRGB(90, 38, 0)
			elseif v.IsPreset == true then
				BButton.BackgroundColor3 = Color3.fromRGB(25, 84, 0)
			end

			if i ~= "nil" and i ~= "Bald" then
				table.insert(BundleButtons, BButton)
			else
				if i == "nil" then
					BButton.LayoutOrder = -999999999
				else
					BButton.LayoutOrder = -999999998
				end
			end

			local function checkBundle(v)

				if v.Preset then

					if v.Preset["CatalogUsername"] or v.Preset["CatalogAccessory"] then

						if GUIObject.Catalog_3:FindFirstChild(SelectPlayer) then
							for i, v in pairs(GUIObject.Catalog_3:FindFirstChild(SelectPlayer):GetChildren()) do
								if not v:IsA("UIGridLayout") then
									v:Destroy()
								end
							end
						end

					end

					for setting, value in pairs(v.Preset) do
						if setting ~= "PositionPhysicsMultiply"
							and setting ~= "RotationPhysicsMultiply"
							and setting ~= "Method" then
							if setting == "CurrentBundle" then
								if (not Bundle[value].ClothingBundle or Bundle[value].ClothingBundle == false) and 
									(not Bundle[value].IsPreset or Bundle[value].IsPreset == false) then
									PlayerData[SelectPlayer][setting] = value
								end
								checkBundle(Bundle[value])
							elseif setting == "CatalogUsername" then
								PlayerData[SelectPlayer][setting] = value

								pcall(function()
									local UsernameId = game.Players:GetUserIdFromNameAsync(value)

									local HumanoidDescription = game.Players:GetHumanoidDescriptionFromUserId(UsernameId)

									for i, accessory in pairs(HumanoidDescription:GetAccessories(true)) do
										if accessory and not (v.Preset.CatalogRemove and table.find(v.Preset.CatalogRemove, accessory.AssetId)) then
											local AccessoryInfo = MPS:GetProductInfo(accessory.AssetId)

											local Button = Function.ButtonCreate(AccessoryInfo.Name, GUIObject.Catalog_3:FindFirstChild(SelectPlayer))

											local AccessoryRemoveButtonConnect
											AccessoryRemoveButtonConnect = Button:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
												if not table.find(PlayerData[SelectPlayer].CatalogRemove, accessory.AssetId) then
													table.insert(PlayerData[SelectPlayer].CatalogRemove, accessory.AssetId)
												end

												Button:Destroy()
												AccessoryRemoveButtonConnect:Disconnect()
											end)

											table.insert(AllConnect, AccessoryRemoveButtonConnect)
										end
									end

								end)
							elseif setting == "CatalogAccessory" then
								for i, x in pairs(value) do

									local Button = Function.ButtonCreate(x, GUIObject.Catalog_3:FindFirstChild(SelectPlayer))

									local AccessoryButtonConnect
									AccessoryButtonConnect = Button:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
										for i, v in pairs(PlayerData[SelectPlayer].CatalogAccessory) do
											if tonumber(v) == tonumber(Button.Name) then
												table.remove(PlayerData[SelectPlayer].CatalogAccessory, i)
											end
										end

										Button:Destroy()
										AccessoryButtonConnect:Disconnect()
									end)

									table.insert(AllConnect, AccessoryButtonConnect)
								end
								PlayerData[SelectPlayer][setting] = value
							else
								PlayerData[SelectPlayer][setting] = value
							end
						else
							if setting == "PositionPhysicsMultiply" then
								PositionPhysicsMultiply = value
							elseif setting == "RotationPhysicsMultiply" then
								RotationPhysicsMultiply = value
							elseif setting == "Method" then
								Method = value
							end
						end
					end
				end

				if v.Clothing then
					for i, v in pairs(v.Clothing) do
						if not table.find(PlayerData[SelectPlayer].CurrentClothes, v) then
							table.insert(PlayerData[SelectPlayer].CurrentClothes, v)
						end

						for i, c in pairs(Clothes[v].Weld) do -- CHANGE here
							if PartList[c] and PartList[c].Recolor then
								if not PlayerData[SelectPlayer].ClothesRecolor[v] then
									PlayerData[SelectPlayer].ClothesRecolor[v] = {}
									RecolorButtons[v] = {}
								end
								if PartList[c].Recolor == "Primary" and not PlayerData[SelectPlayer].ClothesRecolor[v]["Primary"] then
									PlayerData[SelectPlayer].ClothesRecolor[v]["Primary"] = "nil"
									local button = Function.ButtonCreate(v, GUIObject.RecolorListFrame, true, {Color = PartList[c].Color.Color, Text = v.. " PrimaryColor"})
									button:FindFirstChildOfClass("UIAspectRatioConstraint"):Destroy()

									button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[c].Color.Color
									button:FindFirstChildOfClass("TextBox").Text = ""
									local primaryChangeConnect = button:FindFirstChildOfClass("TextBox").FocusLost:Connect(function()
										if button:FindFirstChildOfClass("TextBox").Text ~= "" then
											local RGB = Function.StringTo(button:FindFirstChildOfClass("TextBox").Text, "RGB")

											button:FindFirstChildOfClass("TextBox").TextColor3 = RGB
											PlayerData[SelectPlayer].ClothesRecolor[v]["Primary"] = RGB
										else
											PlayerData[SelectPlayer].ClothesRecolor[v]["Primary"] = "nil"
											button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[c].Color.Color
										end
									end)
									table.insert(RecolorButtons[v],primaryChangeConnect)
									table.insert(AllConnect,primaryChangeConnect)
								elseif PartList[c].Recolor == "Secondary" and not PlayerData[SelectPlayer].ClothesRecolor[v]["Secondary"] then
									PlayerData[SelectPlayer].ClothesRecolor[v]["Secondary"] = "nil"
									local button = Function.ButtonCreate(v, GUIObject.RecolorListFrame, true, {Color = PartList[c].Color.Color, Text = v.. " SecondaryColor"})
									button:FindFirstChildOfClass("UIAspectRatioConstraint"):Destroy()

									button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[c].Color.Color
									button:FindFirstChildOfClass("TextBox").Text = ""
									local secondaryChangeConnect = button:FindFirstChildOfClass("TextBox").FocusLost:Connect(function()
										if button:FindFirstChildOfClass("TextBox").Text ~= "" then
											local RGB = Function.StringTo(button:FindFirstChildOfClass("TextBox").Text, "RGB")

											button:FindFirstChildOfClass("TextBox").TextColor3 = RGB
											PlayerData[SelectPlayer].ClothesRecolor[v]["Secondary"] = RGB
										else
											PlayerData[SelectPlayer].ClothesRecolor[v]["Secondary"] = "nil"
											button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[c].Color.Color
										end
									end)
									table.insert(RecolorButtons[v],secondaryChangeConnect)
									table.insert(AllConnect,secondaryChangeConnect)
								elseif PartList[c].Recolor == "Tertiary" and not PlayerData[SelectPlayer].ClothesRecolor[v]["Tertiary"] then
									PlayerData[SelectPlayer].ClothesRecolor[v]["Tertiary"] = "nil"
									local button = Function.ButtonCreate(v, GUIObject.RecolorListFrame, true, {Color = PartList[c].Color.Color, Text = v.. " TertiaryColor"})
									button:FindFirstChildOfClass("UIAspectRatioConstraint"):Destroy()

									button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[c].Color.Color
									button:FindFirstChildOfClass("TextBox").Text = ""
									local tertiaryChangeConnect = button:FindFirstChildOfClass("TextBox").FocusLost:Connect(function()
										if button:FindFirstChildOfClass("TextBox").Text ~= "" then
											local RGB = Function.StringTo(button:FindFirstChildOfClass("TextBox").Text, "RGB")

											button:FindFirstChildOfClass("TextBox").TextColor3 = RGB
											PlayerData[SelectPlayer].ClothesRecolor[v]["Tertiary"] = RGB
										else
											PlayerData[SelectPlayer].ClothesRecolor[v]["Tertiary"] = "nil"
											button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[c].Color.Color
										end
									end)
									table.insert(RecolorButtons[v],tertiaryChangeConnect)
									table.insert(AllConnect,tertiaryChangeConnect)
								end
							end
						end
					end
				end

				if v.Recolor then
					for i, v in pairs(v.Recolor) do
						PlayerData[SelectPlayer].ClothesRecolor[i] = v
						for color, rgb in pairs(v) do
							for z, button in pairs(GUIObject.RecolorListFrame:GetChildren()) do
								if button.Name == i then
									if button:FindFirstChildOfClass("TextBox").PlaceholderText == i.." "..color.."Color" then
										local Split = string.split(tostring(rgb), ",")
										button:FindFirstChildOfClass("TextBox").TextColor3 = rgb
										button:FindFirstChildOfClass("TextBox").Text = math.round(Split[1]*255)..","..math.round(Split[2]*255)..","..math.round(Split[3]*255)
									end
								end
							end
						end
					end
				end

			end

			local BBConnect = BButton:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()
				if (not v.ClothingBundle or v.ClothingBundle == false) and (not v.IsPreset or v.IsPreset == false) then
					PlayerData[SelectPlayer].CurrentBundle = BButton.Name
				end

				checkBundle(v)

				Function.GUIUpdate()
			end)

			table.insert(AllConnect, BBConnect)
		end

		for i, v in pairs(Clothes) do
			local CButton = Function.ButtonCreate(i, GUIObject.ClothesButtonFrame)

			if i ~= "nil" then
				table.insert(ClothesButtons, CButton)
			end

			local CBConnect = CButton:FindFirstChildOfClass("TextButton").MouseButton1Click:Connect(function()

				if not table.find(PlayerData[SelectPlayer].CurrentClothes, CButton.Name) then
					table.insert(PlayerData[SelectPlayer].CurrentClothes, CButton.Name)

					if Clothes[CButton.Name].Weld then

						for i, v in pairs(Clothes[CButton.Name].Weld) do
							if PartList[v] and PartList[v].Recolor then
								if not PlayerData[SelectPlayer].ClothesRecolor[CButton.Name] then
									PlayerData[SelectPlayer].ClothesRecolor[CButton.Name] = {}
									RecolorButtons[CButton.Name] = {}
								end
								if PartList[v].Recolor == "Primary" and not PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Primary"] then
									PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Primary"] = "nil"
									local button = Function.ButtonCreate(CButton.Name, GUIObject.RecolorListFrame, true, {Color = PartList[v].Color.Color, Text = CButton.Name.. " PrimaryColor"})
									button:FindFirstChildOfClass("UIAspectRatioConstraint"):Destroy()

									button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[v].Color.Color
									button:FindFirstChildOfClass("TextBox").Text = ""
									local primaryChangeConnect = button:FindFirstChildOfClass("TextBox").FocusLost:Connect(function()
										if button:FindFirstChildOfClass("TextBox").Text ~= "" then
											local RGB = Function.StringTo(button:FindFirstChildOfClass("TextBox").Text, "RGB")

											button:FindFirstChildOfClass("TextBox").TextColor3 = RGB
											PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Primary"] = RGB
										else
											PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Primary"] = "nil"
											button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[v].Color.Color
										end
									end)
									table.insert(RecolorButtons[CButton.Name],primaryChangeConnect)
									table.insert(AllConnect,primaryChangeConnect)
								elseif PartList[v].Recolor == "Secondary" and not PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Secondary"] then
									PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Secondary"] = "nil"
									local button = Function.ButtonCreate(CButton.Name, GUIObject.RecolorListFrame, true, {Color = PartList[v].Color.Color, Text = CButton.Name.. " SecondaryColor"})
									button:FindFirstChildOfClass("UIAspectRatioConstraint"):Destroy()

									button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[v].Color.Color
									button:FindFirstChildOfClass("TextBox").Text = ""
									local secondaryChangeConnect = button:FindFirstChildOfClass("TextBox").FocusLost:Connect(function()
										if button:FindFirstChildOfClass("TextBox").Text ~= "" then
											local RGB = Function.StringTo(button:FindFirstChildOfClass("TextBox").Text, "RGB")

											button:FindFirstChildOfClass("TextBox").TextColor3 = RGB
											PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Secondary"] = RGB
										else
											PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Secondary"] = "nil"
											button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[v].Color.Color
										end
									end)
									table.insert(RecolorButtons[CButton.Name],secondaryChangeConnect)
									table.insert(AllConnect,secondaryChangeConnect)
								elseif PartList[v].Recolor == "Tertiary" and not PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Tertiary"] then
									PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Tertiary"] = "nil"
									local button = Function.ButtonCreate(CButton.Name, GUIObject.RecolorListFrame, true, {Color = PartList[v].Color.Color, Text = CButton.Name.. " TertiaryColor"})
									button:FindFirstChildOfClass("UIAspectRatioConstraint"):Destroy()

									button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[v].Color.Color
									button:FindFirstChildOfClass("TextBox").Text = ""
									local tertiaryChangeConnect = button:FindFirstChildOfClass("TextBox").FocusLost:Connect(function()
										if button:FindFirstChildOfClass("TextBox").Text ~= "" then
											local RGB = Function.StringTo(button:FindFirstChildOfClass("TextBox").Text, "RGB")

											button:FindFirstChildOfClass("TextBox").TextColor3 = RGB
											PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Tertiary"] = RGB
										else
											PlayerData[SelectPlayer].ClothesRecolor[CButton.Name]["Tertiary"] = "nil"
											button:FindFirstChildOfClass("TextBox").TextColor3 = PartList[v].Color.Color
										end
									end)
									table.insert(RecolorButtons[CButton.Name],tertiaryChangeConnect)
									table.insert(AllConnect,tertiaryChangeConnect)
								end
							end
						end

					end

				else
					for i, v in pairs(PlayerData[SelectPlayer].CurrentClothes) do
						if v == CButton.Name then
							table.remove(PlayerData[SelectPlayer].CurrentClothes, i)

							if PlayerData[SelectPlayer].ClothesRecolor[CButton.Name] then
								PlayerData[SelectPlayer].ClothesRecolor[CButton.Name] = nil
								for i, v in pairs(GUIObject.RecolorListFrame:GetChildren()) do
									if v.Name == CButton.Name then
										v:Destroy()
									end
								end
								for i, v in pairs(RecolorButtons[CButton.Name]) do
									table.remove(AllConnect,table.find(AllConnect,v))
								end
								RecolorButtons[CButton.Name] = nil
							end

						end
					end
				end

				Function.GUIUpdate()
			end)

			table.insert(AllConnect, CBConnect)
		end

		table.sort(BundleButtons, function(a,b)
			return a.Name:lower() < b.Name:lower()
		end)
		table.sort(ClothesButtons, function(a,b)
			return a.Name < b.Name
		end)

		for i, v in pairs(BundleButtons) do
			local extraorder = 0
			if Bundle[v.Name].ClothingBundle and Bundle[v.Name].ClothingBundle == true then
				extraorder = -999
			elseif Bundle[v.Name].IsPreset and Bundle[v.Name].IsPreset == true then
				extraorder = -999999
			end
			v.LayoutOrder = i+extraorder
		end
		for i, v in pairs(ClothesButtons) do
			v.LayoutOrder = i
		end

		for _, Button in pairs(GUIObject.CharacterFrame:GetChildren()) do
			if Button:IsA("ImageButton") then
				local LocalTransparencyConnect = Button.MouseButton1Click:Connect(function()
					PlayerData[SelectPlayer].LocalTransparency[Button.Name] = not PlayerData[SelectPlayer].LocalTransparency[Button.Name]

					Function.GUIUpdate()
				end)

				table.insert(AllConnect, LocalTransparencyConnect)
			end
		end

		local ClothesSearchConnect = GUIObject.ClothesSearch:GetPropertyChangedSignal("Text"):Connect(function()
			Function.GUIUpdate()
		end)

		local BundleSearchConnect = GUIObject.BundleSearch:GetPropertyChangedSignal("Text"):Connect(function()
			Function.GUIUpdate()
		end)

		local FirstPersonConnect = GUIObject.FPExecute.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].FPerson = not PlayerData[SelectPlayer].FPerson

			Function.GUIUpdate()
		end)

		local GravityConnect = GUIObject.GravityButton.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].PhysicsObeyGravity = not PlayerData[SelectPlayer].PhysicsObeyGravity

			Function.GUIUpdate()
		end)

		local ShirtHPConnect = GUIObject.TopHPText.FocusLost:Connect(function()
			if tonumber(GUIObject.TopHPText.Text) then
				PlayerData[SelectPlayer].TopHP = tonumber(GUIObject.TopHPText.Text)

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].TopHP = ""

				Function.GUIUpdate()
			end
		end)

		local PantsHPConnect = GUIObject.BottomHPText.FocusLost:Connect(function()
			if tonumber(GUIObject.BottomHPText.Text) then
				PlayerData[SelectPlayer].BottomHP = tonumber(GUIObject.BottomHPText.Text)

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].BottomHP = ""

				Function.GUIUpdate()
			end
		end)

		local ShirtClothesConnect = GUIObject.TopClothesText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.TopClothesText.Text) then
				PlayerData[SelectPlayer].HPClothes.Shirt = tonumber(GUIObject.TopClothesText.Text)

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].HPClothes.Shirt = ""

				Function.GUIUpdate()
			end
		end)

		local PantsClothesConnect = GUIObject.BottomClothesText:GetPropertyChangedSignal("Text"):Connect(function()
			if tonumber(GUIObject.BottomClothesText.Text) then
				PlayerData[SelectPlayer].HPClothes.Pants = tonumber(GUIObject.BottomClothesText.Text)

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].HPClothes.Pants = ""

				Function.GUIUpdate()
			end
		end)

		local DamageSFXConnect = GUIObject.DamageSFX.FocusLost:Connect(function()
			if tonumber(GUIObject.DamageSFX.Text) then
				PlayerData[SelectPlayer].DamageSFX = tonumber(GUIObject.DamageSFX.Text)

				Function.GUIUpdate()
			else
				PlayerData[SelectPlayer].DamageSFX = ""

				Function.GUIUpdate()
			end
		end)

		local VolumeSFXConnect = GUIObject.VolumeText.FocusLost:Connect(function()
			if tonumber(GUIObject.VolumeText.Text) then
				PlayerData[SelectPlayer].Volume = tonumber(GUIObject.VolumeText.Text)

				Function.GUIUpdate()
			end
		end)

		local TearToggleConnect = GUIObject.TPToggle.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].TearParticles = not PlayerData[SelectPlayer].TearParticles

			Function.GUIUpdate()
		end)

		local HealToggleConnect = GUIObject.PHToggle.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].HealParticles = not PlayerData[SelectPlayer].HealParticles

			Function.GUIUpdate()
		end)

		local HardcoreToggleConnect = GUIObject.HardcoreToggle.MouseButton1Click:Connect(function()
			PlayerData[SelectPlayer].HardcoreHP = not PlayerData[SelectPlayer].HardcoreHP

			Function.GUIUpdate()
		end)

		table.insert(AllConnect, ExecuteConnect)
		table.insert(AllConnect, ResetConnect)
		table.insert(AllConnect, DelayTimeConnect)
		table.insert(AllConnect, DestroyConnect)
		table.insert(AllConnect, BundleBodyColorConnect)
		table.insert(AllConnect, MeshSizeLockConnect)
		table.insert(AllConnect, AccessorySizeLockConnect)
		table.insert(AllConnect, MeshBasePartInvisibleConnect)
		table.insert(AllConnect, BodyPartPhysicsConnect)
		table.insert(AllConnect, UsernameConnect)
		table.insert(AllConnect, MethodConnect)
		table.insert(AllConnect, MethodConnect2)
		table.insert(AllConnect, KeybindConnect)
		table.insert(AllConnect, ToneConnect)
		table.insert(AllConnect, ShirtConnect)
		table.insert(AllConnect, ShirtGraphicConnect)
		table.insert(AllConnect, PantsConnect)
		table.insert(AllConnect, AccessoryConnect)
		table.insert(AllConnect, PositionPhysicsMultiplyConnect)
		table.insert(AllConnect, RotationPhysicsMultiplyConnect)
		table.insert(AllConnect, ClickExecuteConnect)
		table.insert(AllConnect, MobileCloseConnect)
		table.insert(AllConnect, SkinToneConnect)
		table.insert(AllConnect, NippleColorConnect)
		table.insert(AllConnect, BreastsTypeConnect)
		table.insert(AllConnect, OutfitIdConnect)
		table.insert(AllConnect, BBCToggleConnect)
		table.insert(AllConnect, ClothesSearchConnect)
		table.insert(AllConnect, BundleSearchConnect)
		table.insert(AllConnect, TorsoTypeConnect)
		table.insert(AllConnect, LegsTypeConnect)
		table.insert(AllConnect, FirstPersonConnect)
		table.insert(AllConnect, ShirtHPConnect)
		table.insert(AllConnect, PantsHPConnect)
		table.insert(AllConnect, ShirtClothesConnect)
		table.insert(AllConnect, PantsClothesConnect)
		table.insert(AllConnect, DamageSFXConnect)
		table.insert(AllConnect, VolumeSFXConnect)
		table.insert(AllConnect, TearToggleConnect)
		table.insert(AllConnect, HealToggleConnect)
		table.insert(AllConnect, HardcoreToggleConnect)
		table.insert(AllConnect, GravityConnect)
	end

	Function.UIStrokeCreate(GUIObject.PageFrame)
	Function.UIStrokeCreate(GUIObject.ToneFrame)
	Function.UIStrokeCreate(GUIObject.ResetFrame)
	Function.UIStrokeCreate(GUIObject.DelayFrame)
	Function.UIStrokeCreate(GUIObject.BundleFrame)
	Function.UIStrokeCreate(GUIObject.DestroyFrame)
	Function.UIStrokeCreate(GUIObject.PlayerFrame)
	Function.UIStrokeCreate(GUIObject.BreastsTypeFrame)
	Function.UIStrokeCreate(GUIObject.TorsoTypeFrame)
	Function.UIStrokeCreate(GUIObject.ArmTypeFrame)
	Function.UIStrokeCreate(GUIObject.LegsTypeFrame)
	Function.UIStrokeCreate(GUIObject.ButtTypeFrame)
	Function.UIStrokeCreate(GUIObject.AutoExecuteFrame)
	Function.UIStrokeCreate(GUIObject.BundleBodyColorFrame)
	Function.UIStrokeCreate(GUIObject.ExecuteFrame)
	Function.UIStrokeCreate(GUIObject.KeybindFrame)
	Function.UIStrokeCreate(GUIObject.FaceFrame)
	Function.UIStrokeCreate(GUIObject.Bundles_2)
	Function.UIStrokeCreate(GUIObject.Clothes_2)
	Function.UIStrokeCreate(GUIObject.Menu_2)
	Function.UIStrokeCreate(GUIObject.Menu2_2)
	Function.UIStrokeCreate(GUIObject.LocalTransparencyFrame)
	Function.UIStrokeCreate(GUIObject.MeshSizeLockFrame)
	Function.UIStrokeCreate(GUIObject.AccessorySizeLockFrame)
	Function.UIStrokeCreate(GUIObject.MeshBasePartInvisibleFrame)
	Function.UIStrokeCreate(GUIObject.BodyPartPhysicsFrame)
	Function.UIStrokeCreate(GUIObject.MethodFrame)
	Function.UIStrokeCreate(GUIObject.Catalog_2)
	Function.UIStrokeCreate(GUIObject.Edit_2)
	Function.UIStrokeCreate(GUIObject.HP)
	Function.UIStrokeCreate(GUIObject.FPFrame)
	Function.UIStrokeCreate(GUIObject.MeshNameFrame)
	Function.UIStrokeCreate(GUIObject.ShirtFrame)
	Function.UIStrokeCreate(GUIObject.ShirtGraphicFrame)
	Function.UIStrokeCreate(GUIObject.PantsFrame)
	Function.UIStrokeCreate(GUIObject.AccessoryFrame)
	Function.UIStrokeCreate(GUIObject.UsernameFrame)
	Function.UIStrokeCreate(GUIObject.ClickExecuteFrame)
	Function.UIStrokeCreate(GUIObject.PositionPhysicsMultiplyFrame)
	Function.UIStrokeCreate(GUIObject.RotationPhysicsMultiplyFrame)
	Function.UIStrokeCreate(GUIObject.SkinToneFrame)
	Function.UIStrokeCreate(GUIObject.NippleColorFrame)
	Function.UIStrokeCreate(GUIObject.Menu3_3)
	Function.UIStrokeCreate(GUIObject.BreastsScaleFrame)
	Function.UIStrokeCreate(GUIObject.ButtsScaleFrame)
	Function.UIStrokeCreate(GUIObject.LegsScaleFrame)
	Function.UIStrokeCreate(GUIObject.OutfitIdFrame)
	Function.UIStrokeCreate(GUIObject.TopHPFrame)
	Function.UIStrokeCreate(GUIObject.TopClothesFrame)
	Function.UIStrokeCreate(GUIObject.BottomHPFrame)
	Function.UIStrokeCreate(GUIObject.BottomClothesFrame)
	Function.UIStrokeCreate(GUIObject.DamageFrame)
	Function.UIStrokeCreate(GUIObject.VolumeFrame)
	Function.UIStrokeCreate(GUIObject.TPFrame)
	Function.UIStrokeCreate(GUIObject.PHFrame)
	Function.UIStrokeCreate(GUIObject.Recolor)
	Function.UIStrokeCreate(GUIObject.GravityFrame)
	Function.UIStrokeCreate(GUIObject.BodyTransparencyFrame)
	Function.UIStrokeCreate(GUIObject.HardcoreFrame)

	--Properties:

	GUIObject.Screen.Name = "RoClothes"
	GUIObject.Screen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	GUIObject.Screen.ResetOnSpawn = false
	GUIObject.Screen.Enabled = true

	GUIObject.MobileCloseButtonScreen.Name = "RoClothesCloseButton"
	GUIObject.MobileCloseButtonScreen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	GUIObject.MobileCloseButtonScreen.ResetOnSpawn = false
	GUIObject.MobileCloseButtonScreen.Enabled = false

	if RS:IsClient() and not RS:IsStudio() then
		GUIObject.Screen.Parent = game:GetService("CoreGui")
		GUIObject.MobileCloseButtonScreen.Parent = game:GetService("CoreGui")
	else
		GUIObject.Screen.Parent = Player:WaitForChild("PlayerGui")
		GUIObject.MobileCloseButtonScreen.Parent = Player:WaitForChild("PlayerGui")
	end

	GUIObject.MainFrame.Name = "MainFrame"
	GUIObject.MainFrame.Text = ""
	GUIObject.MainFrame.Modal = true
	GUIObject.MainFrame.Parent = GUIObject.Screen
	GUIObject.MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.MainFrame.Position = UDim2.new(0.757, 0, 0.231759638, 0)
	GUIObject.MainFrame.Size = UDim2.new(0.18244803, 0, 0.536480665, 0)
	GUIObject.MainFrame.BackgroundTransparency = 1

	GUIObject.Dragger.Parent = GUIObject.MainFrame

	GUIObject.PageFrame.Name = "PageFrame"
	GUIObject.PageFrame.Parent = GUIObject.MainFrame
	GUIObject.PageFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PageFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.PageFrame.Position = UDim2.new(0,0,0)
	GUIObject.PageFrame.Size = UDim2.new(1,0,1,0)

	GUIObject.UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient.Rotation = -90
	GUIObject.UIGradient.Parent = GUIObject.PageFrame

	GUIObject.UICorner.CornerRadius = UDim.new(0.100000001, 0)
	GUIObject.UICorner.Parent = GUIObject.PageFrame

	GUIObject.Clothes_3.Name = "Clothes"
	GUIObject.Clothes_3.Parent = GUIObject.PageFrame
	GUIObject.Clothes_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Clothes_3.BackgroundTransparency = 1.000
	GUIObject.Clothes_3.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Clothes_3.Visible = false

	GUIObject.ClothesSearch.Name = "ClothesSearch"
	GUIObject.ClothesSearch.Parent = GUIObject.Clothes_3
	GUIObject.ClothesSearch.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ClothesSearch.BackgroundColor3 = Color3.fromRGB(6, 0, 76)
	GUIObject.ClothesSearch.BorderColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClothesSearch.Position = UDim2.new(0.5, 0, 1.02, 0)
	GUIObject.ClothesSearch.Size = UDim2.new(.9, 0, 0.0646399707, 0)

	GUIObject.UIGradient_34.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(48, 48, 48)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
	GUIObject.UIGradient_34.Rotation = -90
	GUIObject.UIGradient_34.Parent = GUIObject.ClothesSearch

	Function.UIStrokeCreate(GUIObject.ClothesSearch).ApplyStrokeMode = Enum.ApplyStrokeMode.Border

	GUIObject.UICorner_35.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_35.Parent = GUIObject.ClothesSearch

	--GUIObject.ClothesSearch.ClearTextOnFocus = false
	GUIObject.ClothesSearch.Font = Enum.Font.Code
	GUIObject.ClothesSearch.Text = ""
	GUIObject.ClothesSearch.PlaceholderText = "Search Clothes"
	GUIObject.ClothesSearch.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClothesSearch.TextScaled = true
	GUIObject.ClothesSearch.TextSize = 14.000
	GUIObject.ClothesSearch.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClothesSearch.TextWrapped = true

	GUIObject.ClothesButtonFrame.Name = "ClothesButtonFrame"
	GUIObject.ClothesButtonFrame.Parent = GUIObject.Clothes_3
	GUIObject.ClothesButtonFrame.Active = true
	GUIObject.ClothesButtonFrame.AnchorPoint = Vector2.new(0.5, 0.5)
	GUIObject.ClothesButtonFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ClothesButtonFrame.BackgroundTransparency = 1.000
	GUIObject.ClothesButtonFrame.BorderSizePixel = 0
	GUIObject.ClothesButtonFrame.ClipsDescendants = true
	GUIObject.ClothesButtonFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
	GUIObject.ClothesButtonFrame.Size = UDim2.new(0.949999988, 0, 0.949999988, 0)
	GUIObject.ClothesButtonFrame.Visible = true
	GUIObject.ClothesButtonFrame.CanvasSize = UDim2.new(0, 0, 0.5, 0)
	GUIObject.ClothesButtonFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
	GUIObject.ClothesButtonFrame.ScrollBarThickness = 0

	GUIObject.UIGridLayout.Parent = GUIObject.ClothesButtonFrame
	GUIObject.UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
	GUIObject.UIGridLayout.CellSize = UDim2.new(0.300000012, 0, 0.174999997, 0)

	GUIObject.Menu.Name = "Menu"
	GUIObject.Menu.Parent = GUIObject.PageFrame
	GUIObject.Menu.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu.BackgroundTransparency = 1.000
	GUIObject.Menu.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.DestroyFrame.Name = "DestroyFrame"
	GUIObject.DestroyFrame.Parent = GUIObject.Menu
	GUIObject.DestroyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DestroyFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.DestroyFrame.Position = UDim2.new(0.784810185, 0, 0.875, 0)
	GUIObject.DestroyFrame.Size = UDim2.new(0.18244803, 0, 0.128480643, 0)

	GUIObject.UIAspectRatioConstraint_2.Parent = GUIObject.DestroyFrame

	GUIObject.UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 0, 0))}
	GUIObject.UIGradient_3.Rotation = -90
	GUIObject.UIGradient_3.Parent = GUIObject.DestroyFrame

	GUIObject.UICorner_3.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_3.Parent = GUIObject.DestroyFrame

	GUIObject.DestroyButton.Name = "DestroyButton"
	GUIObject.DestroyButton.Parent = GUIObject.DestroyFrame
	GUIObject.DestroyButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DestroyButton.BackgroundTransparency = 1.000
	GUIObject.DestroyButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.DestroyButton.Font = Enum.Font.Code
	GUIObject.DestroyButton.Text = "DESTROY"
	GUIObject.DestroyButton.TextColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.DestroyButton.TextScaled = true
	GUIObject.DestroyButton.TextSize = 14.000
	GUIObject.DestroyButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DestroyButton.TextStrokeTransparency = 0.000
	GUIObject.DestroyButton.TextWrapped = true

	GUIObject.PlayerFrame.Name = "PlayerFrame"
	GUIObject.PlayerFrame.Parent = GUIObject.Menu
	GUIObject.PlayerFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.PlayerFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PlayerFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.PlayerFrame.Position = UDim2.new(0.5, 0, 0.025, 0)
	GUIObject.PlayerFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 0, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 0, 100))}
	GUIObject.UIGradient_4.Rotation = -90
	GUIObject.UIGradient_4.Parent = GUIObject.PlayerFrame

	GUIObject.UICorner_4.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_4.Parent = GUIObject.PlayerFrame

	GUIObject.PlayerExecute.Name = "PlayerExecute"
	GUIObject.PlayerExecute.Parent = GUIObject.PlayerFrame
	GUIObject.PlayerExecute.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.PlayerExecute.BackgroundTransparency = 1.000
	GUIObject.PlayerExecute.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.PlayerExecute.ClearTextOnFocus = false
	GUIObject.PlayerExecute.Font = Enum.Font.Code
	GUIObject.PlayerExecute.PlaceholderText = "Player To Execute (Self = Yourself)"
	GUIObject.PlayerExecute.Text = "Self"
	GUIObject.PlayerExecute.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PlayerExecute.TextScaled = true
	GUIObject.PlayerExecute.TextSize = 14.000
	GUIObject.PlayerExecute.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PlayerExecute.TextWrapped = true

	GUIObject.BreastsTypeFrame.Name = "BreastsTypeFrame"
	GUIObject.BreastsTypeFrame.Parent = GUIObject.Menu
	GUIObject.BreastsTypeFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BreastsTypeFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BreastsTypeFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BreastsTypeFrame.Position = UDim2.new(0.5, 0, 0.195, 0)
	GUIObject.BreastsTypeFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_5.Rotation = -90
	GUIObject.UIGradient_5.Parent = GUIObject.BreastsTypeFrame

	GUIObject.UICorner_5.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_5.Parent = GUIObject.BreastsTypeFrame

	GUIObject.BreastsTypeButton.Name = "BreastsTypeButton"
	GUIObject.BreastsTypeButton.Parent = GUIObject.BreastsTypeFrame
	GUIObject.BreastsTypeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BreastsTypeButton.BackgroundTransparency = 1.000
	GUIObject.BreastsTypeButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BreastsTypeButton.ZIndex = 2
	GUIObject.BreastsTypeButton.Font = Enum.Font.Code
	GUIObject.BreastsTypeButton.Text = "Breasts Type: 1"
	GUIObject.BreastsTypeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BreastsTypeButton.TextScaled = true
	GUIObject.BreastsTypeButton.TextSize = 14.000
	GUIObject.BreastsTypeButton.TextWrapped = true

	GUIObject.BundleSearch.Name = "BundleSearch"
	GUIObject.BundleSearch.Parent = GUIObject.Bundles
	GUIObject.BundleSearch.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BundleSearch.BackgroundColor3 = Color3.fromRGB(6, 0, 76)
	GUIObject.BundleSearch.BorderColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleSearch.Position = UDim2.new(0.5, 0, 1.02, 0)
	GUIObject.BundleSearch.Size = UDim2.new(.9, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A17.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(48, 48, 48)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
	GUIObject.UIGradient_A17.Rotation = -90
	GUIObject.UIGradient_A17.Parent = GUIObject.BundleSearch

	Function.UIStrokeCreate(GUIObject.BundleSearch).ApplyStrokeMode = Enum.ApplyStrokeMode.Border

	GUIObject.UICorner_A17.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A17.Parent = GUIObject.BundleSearch

	--GUIObject.ClothesSearch.ClearTextOnFocus = false
	GUIObject.BundleSearch.Font = Enum.Font.Code
	GUIObject.BundleSearch.Text = ""
	GUIObject.BundleSearch.PlaceholderText = "Search Bundles"
	GUIObject.BundleSearch.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleSearch.TextScaled = true
	GUIObject.BundleSearch.TextSize = 14.000
	GUIObject.BundleSearch.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleSearch.TextWrapped = true

	GUIObject.BundleFrame.Name = "BundleFrame"
	GUIObject.BundleFrame.Parent = GUIObject.Menu
	GUIObject.BundleFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BundleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BundleFrame.Position = UDim2.new(0.5, 0, 0.11, 0)
	GUIObject.BundleFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(30, 0, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(55, 0, 100))}
	GUIObject.UIGradient_6.Rotation = -90
	GUIObject.UIGradient_6.Parent = GUIObject.BundleFrame

	GUIObject.UICorner_6.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_6.Parent = GUIObject.BundleFrame

	GUIObject.BundleText.Name = "BundleText"
	GUIObject.BundleText.Parent = GUIObject.BundleFrame
	GUIObject.BundleText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleText.BackgroundTransparency = 1.000
	GUIObject.BundleText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BundleText.ZIndex = 2
	GUIObject.BundleText.Font = Enum.Font.Code
	GUIObject.BundleText.Text = "Bundle: nil"
	GUIObject.BundleText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleText.TextScaled = true
	GUIObject.BundleText.TextSize = 14.000
	GUIObject.BundleText.TextWrapped = true

	GUIObject.DelayFrame.Name = "DelayFrame"
	GUIObject.DelayFrame.Parent = GUIObject.Menu
	GUIObject.DelayFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.DelayFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DelayFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.DelayFrame.Position = UDim2.new(0.5, 0, 0.535, 0)
	GUIObject.DelayFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.UIGradient_7.Rotation = -90
	GUIObject.UIGradient_7.Parent = GUIObject.DelayFrame

	GUIObject.UICorner_7.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_7.Parent = GUIObject.DelayFrame

	GUIObject.DelayTimeText.Name = "DelayTimeText"
	GUIObject.DelayTimeText.Parent = GUIObject.DelayFrame
	GUIObject.DelayTimeText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.DelayTimeText.BackgroundTransparency = 1.000
	GUIObject.DelayTimeText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.DelayTimeText.Font = Enum.Font.Code
	GUIObject.DelayTimeText.PlaceholderText = "Delay Time After Respawn"
	GUIObject.DelayTimeText.Text = "1"
	GUIObject.DelayTimeText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DelayTimeText.TextScaled = true
	GUIObject.DelayTimeText.TextSize = 14.000
	GUIObject.DelayTimeText.TextWrapped = true

	GUIObject.AutoExecuteFrame.Name = "AutoExecuteFrame"
	GUIObject.AutoExecuteFrame.Parent = GUIObject.Menu
	GUIObject.AutoExecuteFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.AutoExecuteFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AutoExecuteFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.AutoExecuteFrame.Position = UDim2.new(0.5, 0, 0.62, 0)
	GUIObject.AutoExecuteFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_8.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_8.Parent = GUIObject.AutoExecuteFrame

	GUIObject.UIGradient_8.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.UIGradient_8.Rotation = -90
	GUIObject.UIGradient_8.Parent = GUIObject.AutoExecuteFrame

	GUIObject.AutoExecuteButton.Name = "AutoExecuteButton"
	GUIObject.AutoExecuteButton.Parent = GUIObject.AutoExecuteFrame
	GUIObject.AutoExecuteButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.AutoExecuteButton.BackgroundTransparency = 1.000
	GUIObject.AutoExecuteButton.BorderSizePixel = 0
	GUIObject.AutoExecuteButton.LayoutOrder = 1
	GUIObject.AutoExecuteButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.AutoExecuteButton.Font = Enum.Font.Code
	GUIObject.AutoExecuteButton.Text = "Auto Execute"
	GUIObject.AutoExecuteButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AutoExecuteButton.TextScaled = true
	GUIObject.AutoExecuteButton.TextSize = 14.000
	GUIObject.AutoExecuteButton.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.AutoExecuteButton.TextStrokeTransparency = 0.000
	GUIObject.AutoExecuteButton.TextWrapped = true

	GUIObject.BundleBodyColorFrame.Name = "BundleBodyColorFrame"
	GUIObject.BundleBodyColorFrame.Parent = GUIObject.Menu
	GUIObject.BundleBodyColorFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BundleBodyColorFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleBodyColorFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BundleBodyColorFrame.Position = UDim2.new(0.5, 0, 0.365, 0)
	GUIObject.BundleBodyColorFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_15.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_15.Rotation = -90
	GUIObject.UIGradient_15.Parent = GUIObject.BundleBodyColorFrame

	GUIObject.UICorner_15.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_15.Parent = GUIObject.BundleBodyColorFrame

	GUIObject.BundleBodyColorButton.Name = "BundleBodyColorButton"
	GUIObject.BundleBodyColorButton.Parent = GUIObject.BundleBodyColorFrame
	GUIObject.BundleBodyColorButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BundleBodyColorButton.BackgroundTransparency = 1.000
	GUIObject.BundleBodyColorButton.BorderSizePixel = 0
	GUIObject.BundleBodyColorButton.LayoutOrder = 1
	GUIObject.BundleBodyColorButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BundleBodyColorButton.Font = Enum.Font.Code
	GUIObject.BundleBodyColorButton.Text = "Bundle Body Color"
	GUIObject.BundleBodyColorButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundleBodyColorButton.TextScaled = true
	GUIObject.BundleBodyColorButton.TextSize = 14.000
	GUIObject.BundleBodyColorButton.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.BundleBodyColorButton.TextStrokeTransparency = 0.000
	GUIObject.BundleBodyColorButton.TextWrapped = true

	GUIObject.ResetFrame.Name = "ResetFrame"
	GUIObject.ResetFrame.Parent = GUIObject.Menu
	GUIObject.ResetFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ResetFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ResetFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ResetFrame.Position = UDim2.new(0.5, 0, 0.705, 0)
	GUIObject.ResetFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_9.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_9.Parent = GUIObject.ResetFrame

	GUIObject.UIGradient_9.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 0, 0))}
	GUIObject.UIGradient_9.Rotation = -90
	GUIObject.UIGradient_9.Parent = GUIObject.ResetFrame

	GUIObject.ResetButton.Name = "ResetButton"
	GUIObject.ResetButton.Parent = GUIObject.ResetFrame
	GUIObject.ResetButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ResetButton.BackgroundTransparency = 1.000
	GUIObject.ResetButton.BorderSizePixel = 0
	GUIObject.ResetButton.LayoutOrder = 1
	GUIObject.ResetButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ResetButton.Font = Enum.Font.Code
	GUIObject.ResetButton.Text = "Reset"
	GUIObject.ResetButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ResetButton.TextScaled = true
	GUIObject.ResetButton.TextSize = 14.000
	GUIObject.ResetButton.TextStrokeColor3 = Color3.fromRGB(99, 0, 0)
	GUIObject.ResetButton.TextWrapped = true

	GUIObject.ExecuteFrame.Name = "ExecuteFrame"
	GUIObject.ExecuteFrame.Parent = GUIObject.Menu
	GUIObject.ExecuteFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ExecuteFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ExecuteFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ExecuteFrame.Position = UDim2.new(0.5, 0, 0.79, 0)
	GUIObject.ExecuteFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_10.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_10.Parent = GUIObject.ExecuteFrame

	GUIObject.UIGradient_10.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 0, 0))}
	GUIObject.UIGradient_10.Rotation = -90
	GUIObject.UIGradient_10.Parent = GUIObject.ExecuteFrame

	GUIObject.ExecuteButton.Name = "ExecuteButton"
	GUIObject.ExecuteButton.Parent = GUIObject.ExecuteFrame
	GUIObject.ExecuteButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ExecuteButton.BackgroundTransparency = 1.000
	GUIObject.ExecuteButton.BorderSizePixel = 0
	GUIObject.ExecuteButton.LayoutOrder = 1
	GUIObject.ExecuteButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ExecuteButton.Font = Enum.Font.Code
	GUIObject.ExecuteButton.Text = "Execute"
	GUIObject.ExecuteButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ExecuteButton.TextScaled = true
	GUIObject.ExecuteButton.TextSize = 14.000
	GUIObject.ExecuteButton.TextStrokeColor3 = Color3.fromRGB(99, 0, 0)
	GUIObject.ExecuteButton.TextWrapped = true

	GUIObject.ToneFrame.Name = "ToneFrame"
	GUIObject.ToneFrame.Parent = GUIObject.Menu
	GUIObject.ToneFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ToneFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ToneFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ToneFrame.Position = UDim2.new(0.5, 0, 0.28, 0)
	GUIObject.ToneFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_11.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_11.Rotation = -90
	GUIObject.UIGradient_11.Parent = GUIObject.ToneFrame

	GUIObject.UICorner_11.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_11.Parent = GUIObject.ToneFrame

	GUIObject.ToneButton.Name = "ToneButton"
	GUIObject.ToneButton.Parent = GUIObject.ToneFrame
	GUIObject.ToneButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ToneButton.BackgroundTransparency = 1.000
	GUIObject.ToneButton.BorderSizePixel = 0
	GUIObject.ToneButton.LayoutOrder = 1
	GUIObject.ToneButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ToneButton.Font = Enum.Font.Code
	GUIObject.ToneButton.Text = "Tone: Base"
	GUIObject.ToneButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ToneButton.TextScaled = true
	GUIObject.ToneButton.TextSize = 14.000
	GUIObject.ToneButton.TextStrokeColor3 = Color3.fromRGB(57, 57, 57)
	GUIObject.ToneButton.TextWrapped = true

	GUIObject.Bundles.Name = "Bundles"
	GUIObject.Bundles.Parent = GUIObject.PageFrame
	GUIObject.Bundles.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Bundles.BackgroundTransparency = 1.000
	GUIObject.Bundles.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Bundles.Visible = false

	GUIObject.BundlesButtonFrame.Name = "BundlesButtonFrame"
	GUIObject.BundlesButtonFrame.Parent = GUIObject.Bundles
	GUIObject.BundlesButtonFrame.Active = true
	GUIObject.BundlesButtonFrame.AnchorPoint = Vector2.new(0.5, 0.5)
	GUIObject.BundlesButtonFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BundlesButtonFrame.BackgroundTransparency = 1.000
	GUIObject.BundlesButtonFrame.BorderSizePixel = 0
	GUIObject.BundlesButtonFrame.ClipsDescendants = true
	GUIObject.BundlesButtonFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
	GUIObject.BundlesButtonFrame.Size = UDim2.new(0.949999988, 0, 0.949999988, 0)
	GUIObject.BundlesButtonFrame.Visible = true
	GUIObject.BundlesButtonFrame.CanvasSize = UDim2.new(0, 0, 0.5, 0)
	GUIObject.BundlesButtonFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
	GUIObject.BundlesButtonFrame.ScrollBarThickness = 0

	GUIObject.UIGridLayout_2.Parent = GUIObject.BundlesButtonFrame
	GUIObject.UIGridLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
	GUIObject.UIGridLayout_2.CellSize = UDim2.new(0.300000012, 0, 0.174999997, 0)

	GUIObject.ButtonFrame.Name = "ButtonFrame"
	GUIObject.ButtonFrame.Parent = GUIObject.MainFrame
	GUIObject.ButtonFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ButtonFrame.BackgroundTransparency = 1.000
	GUIObject.ButtonFrame.Position = UDim2.new(1.055,0,0,0)
	GUIObject.ButtonFrame.Size = UDim2.new(0.15,0,1,0)

	GUIObject.UIListLayout.Parent = GUIObject.ButtonFrame
	GUIObject.UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
	GUIObject.UIListLayout.Padding = UDim.new(0.025, 0)
	GUIObject.UIListLayout.VerticalAlignment = Enum.VerticalAlignment.Center
	GUIObject.UIListLayout.VerticalFlex = Enum.UIFlexAlignment.SpaceEvenly

	GUIObject.Menu_2.Name = "Menu"
	GUIObject.Menu_2.Parent = GUIObject.ButtonFrame
	GUIObject.Menu_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Menu_2.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Menu_2.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_3.Parent = GUIObject.Menu_2

	GUIObject.UICorner_12.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_12.Parent = GUIObject.Menu_2

	GUIObject.MenuButton.Name = "MenuButton"
	GUIObject.MenuButton.Parent = GUIObject.Menu_2
	GUIObject.MenuButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MenuButton.BackgroundTransparency = 1.000
	GUIObject.MenuButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.MenuButton.Font = Enum.Font.Code
	GUIObject.MenuButton.Text = "Menu"
	GUIObject.MenuButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MenuButton.TextScaled = true
	GUIObject.MenuButton.TextSize = 14.000
	GUIObject.MenuButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MenuButton.TextWrapped = true

	GUIObject.UIGradient_12.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_12.Rotation = -90
	GUIObject.UIGradient_12.Parent = GUIObject.Menu_2

	GUIObject.Menu2_2.Name = "Menu2"
	GUIObject.Menu2_2.Parent = GUIObject.ButtonFrame
	GUIObject.Menu2_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu2_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Menu2_2.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Menu2_2.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_7.Parent = GUIObject.Menu2_2

	GUIObject.UICorner_20.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_20.Parent = GUIObject.Menu2_2

	GUIObject.Menu2Button.Name = "Menu2Button"
	GUIObject.Menu2Button.Parent = GUIObject.Menu2_2
	GUIObject.Menu2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu2Button.BackgroundTransparency = 1.000
	GUIObject.Menu2Button.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Menu2Button.Font = Enum.Font.Code
	GUIObject.Menu2Button.Text = "Settings"
	GUIObject.Menu2Button.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu2Button.TextScaled = true
	GUIObject.Menu2Button.TextSize = 14.000
	GUIObject.Menu2Button.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu2Button.TextWrapped = true

	GUIObject.UIGradient_19.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_19.Rotation = -90
	GUIObject.UIGradient_19.Parent = GUIObject.Menu2_2

	GUIObject.Menu3_3.Name = "Menu3"
	GUIObject.Menu3_3.Parent = GUIObject.ButtonFrame
	GUIObject.Menu3_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu3_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Menu3_3.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Menu3_3.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.M3UIAspectRatioConstraint.Parent = GUIObject.Menu3_3

	GUIObject.M3UICorner.CornerRadius = UDim.new(0.25, 0)
	GUIObject.M3UICorner.Parent = GUIObject.Menu3_3

	GUIObject.Menu3Button.Name = "Menu3Button"
	GUIObject.Menu3Button.Parent = GUIObject.Menu3_3
	GUIObject.Menu3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu3Button.BackgroundTransparency = 1.000
	GUIObject.Menu3Button.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Menu3Button.Font = Enum.Font.Code
	GUIObject.Menu3Button.Text = "Body"
	GUIObject.Menu3Button.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu3Button.TextScaled = true
	GUIObject.Menu3Button.TextSize = 14.000
	GUIObject.Menu3Button.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu3Button.TextWrapped = true

	GUIObject.M3UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.M3UIGradient.Rotation = -90
	GUIObject.M3UIGradient.Parent = GUIObject.Menu3_3

	GUIObject.Clothes_2.Name = "Clothes"
	GUIObject.Clothes_2.Parent = GUIObject.ButtonFrame
	GUIObject.Clothes_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Clothes_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Clothes_2.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Clothes_2.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_4.Parent = GUIObject.Clothes_2

	GUIObject.UICorner_13.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_13.Parent = GUIObject.Clothes_2

	GUIObject.ClothesButton.Name = "ClothesButton"
	GUIObject.ClothesButton.Parent = GUIObject.Clothes_2
	GUIObject.ClothesButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClothesButton.BackgroundTransparency = 1.000
	GUIObject.ClothesButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ClothesButton.Font = Enum.Font.Code
	GUIObject.ClothesButton.Text = "Clothes"
	GUIObject.ClothesButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClothesButton.TextScaled = true
	GUIObject.ClothesButton.TextSize = 14.000
	GUIObject.ClothesButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClothesButton.TextWrapped = true

	GUIObject.UIGradient_13.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_13.Rotation = -90
	GUIObject.UIGradient_13.Parent = GUIObject.Clothes_2

	GUIObject.Bundles_2.Name = "Bundles"
	GUIObject.Bundles_2.Parent = GUIObject.ButtonFrame
	GUIObject.Bundles_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Bundles_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Bundles_2.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Bundles_2.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_5.Parent = GUIObject.Bundles_2

	GUIObject.UICorner_14.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_14.Parent = GUIObject.Bundles_2

	GUIObject.BundlesButton.Name = "BundlesButton"
	GUIObject.BundlesButton.Parent = GUIObject.Bundles_2
	GUIObject.BundlesButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundlesButton.BackgroundTransparency = 1.000
	GUIObject.BundlesButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BundlesButton.Font = Enum.Font.Code
	GUIObject.BundlesButton.Text = "Bundles"
	GUIObject.BundlesButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundlesButton.TextScaled = true
	GUIObject.BundlesButton.TextSize = 14.000
	GUIObject.BundlesButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BundlesButton.TextWrapped = true

	GUIObject.UIGradient_14.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_14.Rotation = -90
	GUIObject.UIGradient_14.Parent = GUIObject.Bundles_2

	GUIObject.NameFrame.Name = "NameFrame"
	GUIObject.NameFrame.Parent = GUIObject.MainFrame
	GUIObject.NameFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.NameFrame.BackgroundTransparency = 1.000
	GUIObject.NameFrame.Position = UDim2.new(0, 0, -0.096, 0)
	GUIObject.NameFrame.Size = UDim2.new(0.561, 0, 0.04, 0)

	GUIObject.NameText.Name = "NameText"
	GUIObject.NameText.Parent = GUIObject.NameFrame
	GUIObject.NameText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.NameText.BackgroundTransparency = 1.000
	GUIObject.NameText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.NameText.ZIndex = 2
	GUIObject.NameText.Font = Enum.Font.Code
	GUIObject.NameText.Text = "RoClothes modded"
	GUIObject.NameText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.NameText.TextScaled = true
	GUIObject.NameText.TextSize = 14.000
	GUIObject.NameText.TextWrapped = true
	GUIObject.NameText.TextXAlignment = Enum.TextXAlignment.Left

	GUIObject.VersionText.Name = "VersionText"
	GUIObject.VersionText.Parent = GUIObject.NameFrame
	GUIObject.VersionText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.VersionText.BackgroundTransparency = 1.000
	GUIObject.VersionText.Position = UDim2.new(0, 0, 1.06666636, 0)
	GUIObject.VersionText.Size = UDim2.new(1, 0, 0.799999952, 0)
	GUIObject.VersionText.ZIndex = 2
	GUIObject.VersionText.Font = Enum.Font.Code
	GUIObject.VersionText.Text = "Version - "..CVersion
	GUIObject.VersionText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.VersionText.TextScaled = true
	GUIObject.VersionText.TextSize = 14.000
	GUIObject.VersionText.TextWrapped = true
	GUIObject.VersionText.TextXAlignment = Enum.TextXAlignment.Left

	GUIObject.KeybindFrame.Name = "KeybindFrame"
	GUIObject.KeybindFrame.Parent = GUIObject.Menu
	GUIObject.KeybindFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.KeybindFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.KeybindFrame.Position = UDim2.new(0.0542876273, 0, 0.931, 0)
	GUIObject.KeybindFrame.Size = UDim2.new(0.684944391, 0, 0.0538139641, 0)

	GUIObject.UIGradient_16.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(26, 27, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 47, 0))}
	GUIObject.UIGradient_16.Rotation = -90
	GUIObject.UIGradient_16.Parent = GUIObject.KeybindFrame

	GUIObject.UICorner_16.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_16.Parent = GUIObject.KeybindFrame

	GUIObject.KeybindButton.Name = "KeybindButton"
	GUIObject.KeybindButton.Parent = GUIObject.KeybindFrame
	GUIObject.KeybindButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.KeybindButton.BackgroundTransparency = 1.000
	GUIObject.KeybindButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.KeybindButton.Font = Enum.Font.Code
	GUIObject.KeybindButton.Text = "Insert"
	GUIObject.KeybindButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.KeybindButton.TextScaled = true
	GUIObject.KeybindButton.TextSize = 14.000
	GUIObject.KeybindButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.KeybindButton.TextWrapped = true

	GUIObject.FaceFrame.Name = "FaceFrame"
	GUIObject.FaceFrame.Parent = GUIObject.Menu
	GUIObject.FaceFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.FaceFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.FaceFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.FaceFrame.Position = UDim2.new(0.5, 0, 0.449999988, 0)
	GUIObject.FaceFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_17.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_17.Rotation = -90
	GUIObject.UIGradient_17.Parent = GUIObject.FaceFrame

	GUIObject.UICorner_17.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_17.Parent = GUIObject.FaceFrame

	GUIObject.FaceButton.Name = "FaceButton"
	GUIObject.FaceButton.Parent = GUIObject.FaceFrame
	GUIObject.FaceButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.FaceButton.BackgroundTransparency = 1.000
	GUIObject.FaceButton.BorderSizePixel = 0
	GUIObject.FaceButton.LayoutOrder = 1
	GUIObject.FaceButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.FaceButton.Font = Enum.Font.Code
	GUIObject.FaceButton.Text = "Face"
	GUIObject.FaceButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.FaceButton.TextScaled = true
	GUIObject.FaceButton.TextSize = 14.000
	GUIObject.FaceButton.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.FaceButton.TextStrokeTransparency = 0.000
	GUIObject.FaceButton.TextWrapped = true

	GUIObject.Menu2.Name = "Menu2"
	GUIObject.Menu2.Parent = GUIObject.PageFrame
	GUIObject.Menu2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu2.BackgroundTransparency = 1.000
	GUIObject.Menu2.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Menu2.Visible = false

	GUIObject.LocalTransparencyFrame.Name = "LocalTransparencyFrame"
	GUIObject.LocalTransparencyFrame.Parent = GUIObject.Menu2
	GUIObject.LocalTransparencyFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.LocalTransparencyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LocalTransparencyFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.LocalTransparencyFrame.Position = UDim2.new(0.647907138, 0, 0.0250000004, 0)
	GUIObject.LocalTransparencyFrame.Size = UDim2.new(0.595495105, 0, 0.0646399707, 0)

	GUIObject.UIGradient_18.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 93))}
	GUIObject.UIGradient_18.Rotation = -90
	GUIObject.UIGradient_18.Parent = GUIObject.LocalTransparencyFrame

	GUIObject.UICorner_18.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_18.Parent = GUIObject.LocalTransparencyFrame

	GUIObject.LocalTransparencyButton.Name = "LocalTransparency"
	GUIObject.LocalTransparencyButton.Parent = GUIObject.LocalTransparencyFrame
	GUIObject.LocalTransparencyButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.LocalTransparencyButton.BackgroundTransparency = 1.000
	GUIObject.LocalTransparencyButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.LocalTransparencyButton.ClearTextOnFocus = false
	GUIObject.LocalTransparencyButton.Font = Enum.Font.Code
	GUIObject.LocalTransparencyButton.PlaceholderText = "Player To Execute (Self = Yourself)"
	GUIObject.LocalTransparencyButton.Text = "0"
	GUIObject.LocalTransparencyButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LocalTransparencyButton.TextScaled = true
	GUIObject.LocalTransparencyButton.TextSize = 14.000
	GUIObject.LocalTransparencyButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LocalTransparencyButton.TextWrapped = true

	GUIObject.CharacterFrame.Name = "CharacterFrame"
	GUIObject.CharacterFrame.Parent = GUIObject.Menu2
	GUIObject.CharacterFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.CharacterFrame.BackgroundTransparency = 1.000
	GUIObject.CharacterFrame.Position = UDim2.new(0.0591630787, 0, 0.0266665854, 0)
	GUIObject.CharacterFrame.Size = UDim2.new(0.272571504, 0, 0.218666583, 0)

	GUIObject.UIAspectRatioConstraint_6.Parent = GUIObject.CharacterFrame
	GUIObject.UIAspectRatioConstraint_6.AspectRatio = 0.750

	GUIObject.LeftArmButton.Name = "Left Arm"
	GUIObject.LeftArmButton.Parent = GUIObject.CharacterFrame
	GUIObject.LeftArmButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LeftArmButton.BackgroundTransparency = 0.500
	GUIObject.LeftArmButton.BorderSizePixel = 0
	GUIObject.LeftArmButton.Position = UDim2.new(0, 0, 0.25, 0)
	GUIObject.LeftArmButton.Size = UDim2.new(0.25, 0, 0.449999988, 0)
	GUIObject.LeftArmButton.Image = "rbxasset0"
	GUIObject.LeftArmButton.ImageTransparency = 1.000

	GUIObject.TorsoButton.Name = "Torso"
	GUIObject.TorsoButton.Parent = GUIObject.CharacterFrame
	GUIObject.TorsoButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TorsoButton.BackgroundTransparency = 0.500
	GUIObject.TorsoButton.BorderSizePixel = 0
	GUIObject.TorsoButton.Position = UDim2.new(0.25, 0, 0.25, 0)
	GUIObject.TorsoButton.Size = UDim2.new(0.5, 0, 0.449999988, 0)
	GUIObject.TorsoButton.Image = "rbxasset0"
	GUIObject.TorsoButton.ImageTransparency = 1.000

	GUIObject.RightArmButton.Name = "Right Arm"
	GUIObject.RightArmButton.Parent = GUIObject.CharacterFrame
	GUIObject.RightArmButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RightArmButton.BackgroundTransparency = 0.500
	GUIObject.RightArmButton.BorderSizePixel = 0
	GUIObject.RightArmButton.Position = UDim2.new(0.75, 0, 0.25, 0)
	GUIObject.RightArmButton.Size = UDim2.new(0.25, 0, 0.449999988, 0)
	GUIObject.RightArmButton.Image = "rbxasset0"
	GUIObject.RightArmButton.ImageTransparency = 1.000

	GUIObject.RightLegButton.Name = "Right Leg"
	GUIObject.RightLegButton.Parent = GUIObject.CharacterFrame
	GUIObject.RightLegButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RightLegButton.BackgroundTransparency = 0.500
	GUIObject.RightLegButton.BorderSizePixel = 0
	GUIObject.RightLegButton.Position = UDim2.new(0.5, 0, 0.699999988, 0)
	GUIObject.RightLegButton.Size = UDim2.new(0.25, 0, 0.449999988, 0)
	GUIObject.RightLegButton.Image = "rbxasset0"
	GUIObject.RightLegButton.ImageTransparency = 1.000

	GUIObject.LeftLegButton.Name = "Left Leg"
	GUIObject.LeftLegButton.Parent = GUIObject.CharacterFrame
	GUIObject.LeftLegButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LeftLegButton.BackgroundTransparency = 0.500
	GUIObject.LeftLegButton.BorderSizePixel = 0
	GUIObject.LeftLegButton.Position = UDim2.new(0.25, 0, 0.699999988, 0)
	GUIObject.LeftLegButton.Size = UDim2.new(0.25, 0, 0.449999988, 0)
	GUIObject.LeftLegButton.Image = "rbxasset0"
	GUIObject.LeftLegButton.ImageTransparency = 1.000

	GUIObject.HeadButton.Name = "Head"
	GUIObject.HeadButton.Parent = GUIObject.CharacterFrame
	GUIObject.HeadButton.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.HeadButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HeadButton.BackgroundTransparency = 0.500
	GUIObject.HeadButton.BorderSizePixel = 0
	GUIObject.HeadButton.Position = UDim2.new(0.5, 0, 0, 0)
	GUIObject.HeadButton.Size = UDim2.new(0.349999994, 0, 0.25, 0)
	GUIObject.HeadButton.Image = "rbxasset0"
	GUIObject.HeadButton.ImageTransparency = 1.000

	GUIObject.UICorner_19.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_19.Parent = GUIObject.HeadButton

	GUIObject.HatButton.Name = "Hat"
	GUIObject.HatButton.Parent = GUIObject.CharacterFrame
	GUIObject.HatButton.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.HatButton.BackgroundTransparency = 1
	GUIObject.HatButton.BorderSizePixel = 0
	GUIObject.HatButton.Position = UDim2.new(0.85, 0, -0.05, 0)
	GUIObject.HatButton.Size = UDim2.new(0.35, 0, 0.35, 0)
	GUIObject.HatButton.Image = "rbxassetid://13285138825"
	GUIObject.HatButton.ImageColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HatButton.ScaleType = Enum.ScaleType.Fit

	GUIObject.MeshSizeLockFrame.Name = "MeshSizeLockFrame"
	GUIObject.MeshSizeLockFrame.Parent = GUIObject.Menu2
	GUIObject.MeshSizeLockFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.MeshSizeLockFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshSizeLockFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.MeshSizeLockFrame.Position = UDim2.new(0.5, 0, 0.289999992, 0)
	GUIObject.MeshSizeLockFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_20.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_20.Rotation = -90
	GUIObject.UIGradient_20.Parent = GUIObject.MeshSizeLockFrame

	GUIObject.UICorner_21.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_21.Parent = GUIObject.MeshSizeLockFrame

	GUIObject.MeshSizeLockButton.Name = "MeshSizeLockButton"
	GUIObject.MeshSizeLockButton.Parent = GUIObject.MeshSizeLockFrame
	GUIObject.MeshSizeLockButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.MeshSizeLockButton.BackgroundTransparency = 1.000
	GUIObject.MeshSizeLockButton.BorderSizePixel = 0
	GUIObject.MeshSizeLockButton.LayoutOrder = 1
	GUIObject.MeshSizeLockButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.MeshSizeLockButton.Font = Enum.Font.Code
	GUIObject.MeshSizeLockButton.Text = "Mesh Size Lock"
	GUIObject.MeshSizeLockButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshSizeLockButton.TextScaled = true
	GUIObject.MeshSizeLockButton.TextSize = 14.000
	GUIObject.MeshSizeLockButton.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.MeshSizeLockButton.TextStrokeTransparency = 0.000
	GUIObject.MeshSizeLockButton.TextWrapped = true

	GUIObject.AccessorySizeLockFrame.Name = "AccessorySizeLockFrame"
	GUIObject.AccessorySizeLockFrame.Parent = GUIObject.Menu2
	GUIObject.AccessorySizeLockFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.AccessorySizeLockFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AccessorySizeLockFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.AccessorySizeLockFrame.Position = UDim2.new(0.5, 0, 0.375, 0)
	GUIObject.AccessorySizeLockFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_21.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_21.Rotation = -90
	GUIObject.UIGradient_21.Parent = GUIObject.AccessorySizeLockFrame

	GUIObject.UICorner_22.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_22.Parent = GUIObject.AccessorySizeLockFrame

	GUIObject.AccessorySizeLockButton.Name = "AccessorySizeLockButton"
	GUIObject.AccessorySizeLockButton.Parent = GUIObject.AccessorySizeLockFrame
	GUIObject.AccessorySizeLockButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.AccessorySizeLockButton.BackgroundTransparency = 1.000
	GUIObject.AccessorySizeLockButton.BorderSizePixel = 0
	GUIObject.AccessorySizeLockButton.LayoutOrder = 1
	GUIObject.AccessorySizeLockButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.AccessorySizeLockButton.Font = Enum.Font.Code
	GUIObject.AccessorySizeLockButton.Text = "Accessory Size Lock"
	GUIObject.AccessorySizeLockButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AccessorySizeLockButton.TextScaled = true
	GUIObject.AccessorySizeLockButton.TextSize = 14.000
	GUIObject.AccessorySizeLockButton.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.AccessorySizeLockButton.TextStrokeTransparency = 0.000
	GUIObject.AccessorySizeLockButton.TextWrapped = true

	GUIObject.MeshBasePartInvisibleFrame.Name = "MeshBasePartInvisibleFrame"
	GUIObject.MeshBasePartInvisibleFrame.Parent = GUIObject.Menu2
	GUIObject.MeshBasePartInvisibleFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.MeshBasePartInvisibleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshBasePartInvisibleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.MeshBasePartInvisibleFrame.Position = UDim2.new(0.271, 0, 0.46, 0)
	GUIObject.MeshBasePartInvisibleFrame.Size = UDim2.new(0.425, 0, 0.0646399707, 0)

	GUIObject.UIGradient_22.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_22.Rotation = -90
	GUIObject.UIGradient_22.Parent = GUIObject.MeshBasePartInvisibleFrame

	GUIObject.UICorner_23.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_23.Parent = GUIObject.MeshBasePartInvisibleFrame

	GUIObject.MeshBasePartInvisibleButton.Name = "MeshBasePartInvisibleButton"
	GUIObject.MeshBasePartInvisibleButton.Parent = GUIObject.MeshBasePartInvisibleFrame
	GUIObject.MeshBasePartInvisibleButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.MeshBasePartInvisibleButton.BackgroundTransparency = 1.000
	GUIObject.MeshBasePartInvisibleButton.BorderSizePixel = 0
	GUIObject.MeshBasePartInvisibleButton.LayoutOrder = 1
	GUIObject.MeshBasePartInvisibleButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.MeshBasePartInvisibleButton.Font = Enum.Font.Code
	GUIObject.MeshBasePartInvisibleButton.Text = "Mesh Base Part Invisible"
	GUIObject.MeshBasePartInvisibleButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshBasePartInvisibleButton.TextScaled = true
	GUIObject.MeshBasePartInvisibleButton.TextSize = 14.000
	GUIObject.MeshBasePartInvisibleButton.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.MeshBasePartInvisibleButton.TextStrokeTransparency = 0.000
	GUIObject.MeshBasePartInvisibleButton.TextWrapped = true

	GUIObject.BodyPartPhysicsFrame.Name = "BodyPartPhysicsFrame"
	GUIObject.BodyPartPhysicsFrame.Parent = GUIObject.Menu2
	GUIObject.BodyPartPhysicsFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BodyPartPhysicsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BodyPartPhysicsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BodyPartPhysicsFrame.Position = UDim2.new(0.5, 0, 0.545, 0)
	GUIObject.BodyPartPhysicsFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_23.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_23.Rotation = -90
	GUIObject.UIGradient_23.Parent = GUIObject.BodyPartPhysicsFrame

	GUIObject.UICorner_24.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_24.Parent = GUIObject.BodyPartPhysicsFrame

	GUIObject.BodyPartPhysicsButton.Name = "BodyPartPhysicsButton"
	GUIObject.BodyPartPhysicsButton.Parent = GUIObject.BodyPartPhysicsFrame
	GUIObject.BodyPartPhysicsButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BodyPartPhysicsButton.BackgroundTransparency = 1.000
	GUIObject.BodyPartPhysicsButton.BorderSizePixel = 0
	GUIObject.BodyPartPhysicsButton.LayoutOrder = 1
	GUIObject.BodyPartPhysicsButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BodyPartPhysicsButton.Font = Enum.Font.Code
	GUIObject.BodyPartPhysicsButton.Text = "Body Part Physics"
	GUIObject.BodyPartPhysicsButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BodyPartPhysicsButton.TextScaled = true
	GUIObject.BodyPartPhysicsButton.TextSize = 14.000
	GUIObject.BodyPartPhysicsButton.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BodyPartPhysicsButton.TextStrokeTransparency = 0.000
	GUIObject.BodyPartPhysicsButton.TextWrapped = true

	GUIObject.MethodFrame.Name = "MethodFrame"
	GUIObject.MethodFrame.Parent = GUIObject.Menu
	GUIObject.MethodFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MethodFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.MethodFrame.Position = UDim2.new(0.0542876273, 0, 0.865, 0)
	GUIObject.MethodFrame.Size = UDim2.new(0.684944391, 0, 0.0538139641, 0)

	GUIObject.UIGradient_24.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(26, 27, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 47, 0))}
	GUIObject.UIGradient_24.Rotation = -90
	GUIObject.UIGradient_24.Parent = GUIObject.MethodFrame

	GUIObject.UICorner_25.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_25.Parent = GUIObject.MethodFrame

	GUIObject.MethodButton.Name = "MethodButton"
	GUIObject.MethodButton.Parent = GUIObject.MethodFrame
	GUIObject.MethodButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MethodButton.BackgroundTransparency = 1.000
	GUIObject.MethodButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.MethodButton.Font = Enum.Font.Code
	GUIObject.MethodButton.Text = "Method: 1"
	GUIObject.MethodButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MethodButton.TextScaled = true
	GUIObject.MethodButton.TextSize = 14.000
	GUIObject.MethodButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MethodButton.TextWrapped = true

	GUIObject.Catalog_2.Name = "Catalog"
	GUIObject.Catalog_2.Parent = GUIObject.ButtonFrame
	GUIObject.Catalog_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Catalog_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Catalog_2.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Catalog_2.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_9.Parent = GUIObject.Catalog_2

	GUIObject.UICorner_34.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_34.Parent = GUIObject.Catalog_2

	GUIObject.CatalogButton.Name = "CatalogButton"
	GUIObject.CatalogButton.Parent = GUIObject.Catalog_2
	GUIObject.CatalogButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.CatalogButton.BackgroundTransparency = 1.000
	GUIObject.CatalogButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.CatalogButton.Font = Enum.Font.Code
	GUIObject.CatalogButton.Text = "Catalog"
	GUIObject.CatalogButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.CatalogButton.TextScaled = true
	GUIObject.CatalogButton.TextSize = 14.000
	GUIObject.CatalogButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.CatalogButton.TextWrapped = true

	GUIObject.UIGradient_33.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_33.Rotation = -90
	GUIObject.UIGradient_33.Parent = GUIObject.Catalog_2

	GUIObject.Edit_2.Name = "Edit"
	GUIObject.Edit_2.Parent = GUIObject.ButtonFrame
	GUIObject.Edit_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Edit_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Edit_2.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Edit_2.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_8.Parent = GUIObject.Edit_2

	GUIObject.UICorner_33.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_33.Parent = GUIObject.Edit_2

	GUIObject.EditButton.Name = "EditButton"
	GUIObject.EditButton.Parent = GUIObject.Edit_2
	GUIObject.EditButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.EditButton.BackgroundTransparency = 1.000
	GUIObject.EditButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.EditButton.Font = Enum.Font.Code
	GUIObject.EditButton.Text = "Edit"
	GUIObject.EditButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.EditButton.TextScaled = true
	GUIObject.EditButton.TextSize = 14.000
	GUIObject.EditButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.EditButton.TextWrapped = true

	GUIObject.UIGradient_32.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_32.Rotation = -90
	GUIObject.UIGradient_32.Parent = GUIObject.Edit_2

	GUIObject.Catalog_3.Name = "Catalog"
	GUIObject.Catalog_3.Parent = GUIObject.PageFrame
	GUIObject.Catalog_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Catalog_3.BackgroundTransparency = 1.000
	GUIObject.Catalog_3.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Catalog_3.Visible = false

	GUIObject.UsernameFrame.Name = "UsernameFrame"
	GUIObject.UsernameFrame.Parent = GUIObject.Catalog_3
	GUIObject.UsernameFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.UsernameFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.UsernameFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.UsernameFrame.Position = UDim2.new(0.5, 0, 0.0250000004, 0)
	GUIObject.UsernameFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_27.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_27.Parent = GUIObject.UsernameFrame

	GUIObject.UsernameTextbox.Name = "UsernameTextbox"
	GUIObject.UsernameTextbox.Parent = GUIObject.UsernameFrame
	GUIObject.UsernameTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.UsernameTextbox.BackgroundTransparency = 1.000
	GUIObject.UsernameTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.UsernameTextbox.ClearTextOnFocus = false
	GUIObject.UsernameTextbox.Font = Enum.Font.Code
	GUIObject.UsernameTextbox.PlaceholderText = "Username"
	GUIObject.UsernameTextbox.Text = ""
	GUIObject.UsernameTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.UsernameTextbox.TextScaled = true
	GUIObject.UsernameTextbox.TextSize = 14.000
	GUIObject.UsernameTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.UsernameTextbox.TextWrapped = true

	GUIObject.UIGradient_26.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(22, 45, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(52, 80, 145))}
	GUIObject.UIGradient_26.Rotation = -90
	GUIObject.UIGradient_26.Parent = GUIObject.UsernameFrame

	GUIObject.AccessoryFrame.Name = "AccessoryFrame"
	GUIObject.AccessoryFrame.Parent = GUIObject.Catalog_3
	GUIObject.AccessoryFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.AccessoryFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AccessoryFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.AccessoryFrame.Position = UDim2.new(0.5, 0, 0.109999999, 0)
	GUIObject.AccessoryFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_28.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_28.Parent = GUIObject.AccessoryFrame

	GUIObject.AccessoryTextbox.Name = "AccessoryTextbox"
	GUIObject.AccessoryTextbox.Parent = GUIObject.AccessoryFrame
	GUIObject.AccessoryTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.AccessoryTextbox.BackgroundTransparency = 1.000
	GUIObject.AccessoryTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.AccessoryTextbox.ClearTextOnFocus = false
	GUIObject.AccessoryTextbox.Font = Enum.Font.Code
	GUIObject.AccessoryTextbox.PlaceholderText = "Accessory Id"
	GUIObject.AccessoryTextbox.Text = ""
	GUIObject.AccessoryTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AccessoryTextbox.TextScaled = true
	GUIObject.AccessoryTextbox.TextSize = 14.000
	GUIObject.AccessoryTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.AccessoryTextbox.TextWrapped = true

	GUIObject.UIGradient_27.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(22, 45, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(52, 80, 145))}
	GUIObject.UIGradient_27.Rotation = -90
	GUIObject.UIGradient_27.Parent = GUIObject.AccessoryFrame

	GUIObject.ShirtFrame.Name = "ShirtFrame"
	GUIObject.ShirtFrame.Parent = GUIObject.Catalog_3
	GUIObject.ShirtFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ShirtFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ShirtFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ShirtFrame.Position = UDim2.new(0.5, 0, 0.194999993, 0)
	GUIObject.ShirtFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_29.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_29.Parent = GUIObject.ShirtFrame

	GUIObject.ShirtTextbox.Name = "ShirtTextbox"
	GUIObject.ShirtTextbox.Parent = GUIObject.ShirtFrame
	GUIObject.ShirtTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ShirtTextbox.BackgroundTransparency = 1.000
	GUIObject.ShirtTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ShirtTextbox.ClearTextOnFocus = false
	GUIObject.ShirtTextbox.Font = Enum.Font.Code
	GUIObject.ShirtTextbox.PlaceholderText = "Shirt Id"
	GUIObject.ShirtTextbox.Text = ""
	GUIObject.ShirtTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ShirtTextbox.TextScaled = true
	GUIObject.ShirtTextbox.TextSize = 14.000
	GUIObject.ShirtTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ShirtTextbox.TextWrapped = true

	GUIObject.UIGradient_28.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(22, 45, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(52, 80, 145))}
	GUIObject.UIGradient_28.Rotation = -90
	GUIObject.UIGradient_28.Parent = GUIObject.ShirtFrame

	GUIObject.PantsFrame.Name = "PantsFrame"
	GUIObject.PantsFrame.Parent = GUIObject.Catalog_3
	GUIObject.PantsFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.PantsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PantsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.PantsFrame.Position = UDim2.new(0.5, 0, 0.280000001, 0)
	GUIObject.PantsFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_30.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_30.Parent = GUIObject.PantsFrame

	GUIObject.PantsTextbox.Name = "PantsTextbox"
	GUIObject.PantsTextbox.Parent = GUIObject.PantsFrame
	GUIObject.PantsTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.PantsTextbox.BackgroundTransparency = 1.000
	GUIObject.PantsTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.PantsTextbox.ClearTextOnFocus = false
	GUIObject.PantsTextbox.Font = Enum.Font.Code
	GUIObject.PantsTextbox.PlaceholderText = "Pants Id"
	GUIObject.PantsTextbox.Text = ""
	GUIObject.PantsTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PantsTextbox.TextScaled = true
	GUIObject.PantsTextbox.TextSize = 14.000
	GUIObject.PantsTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PantsTextbox.TextWrapped = true

	GUIObject.UIGradient_29.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(22, 45, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(52, 80, 145))}
	GUIObject.UIGradient_29.Rotation = -90
	GUIObject.UIGradient_29.Parent = GUIObject.PantsFrame

	GUIObject.ShirtGraphicFrame.Name = "ShirtGraphicFrame"
	GUIObject.ShirtGraphicFrame.Parent = GUIObject.Catalog_3
	GUIObject.ShirtGraphicFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ShirtGraphicFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ShirtGraphicFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ShirtGraphicFrame.Position = UDim2.new(0.5, 0, 0.36500001, 0)
	GUIObject.ShirtGraphicFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_31.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_31.Parent = GUIObject.ShirtGraphicFrame

	GUIObject.ShirtGraphicTextbox.Name = "ShirtGraphicTextbox"
	GUIObject.ShirtGraphicTextbox.Parent = GUIObject.ShirtGraphicFrame
	GUIObject.ShirtGraphicTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ShirtGraphicTextbox.BackgroundTransparency = 1.000
	GUIObject.ShirtGraphicTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ShirtGraphicTextbox.ClearTextOnFocus = false
	GUIObject.ShirtGraphicTextbox.Font = Enum.Font.Code
	GUIObject.ShirtGraphicTextbox.PlaceholderText = "Shirt Graphic Id"
	GUIObject.ShirtGraphicTextbox.Text = ""
	GUIObject.ShirtGraphicTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ShirtGraphicTextbox.TextScaled = true
	GUIObject.ShirtGraphicTextbox.TextSize = 14.000
	GUIObject.ShirtGraphicTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ShirtGraphicTextbox.TextWrapped = true

	GUIObject.UIGradient_30.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(22, 45, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(52, 80, 145))}
	GUIObject.UIGradient_30.Rotation = -90
	GUIObject.UIGradient_30.Parent = GUIObject.ShirtGraphicFrame

	GUIObject.Edit.Name = "Edit"
	GUIObject.Edit.Parent = GUIObject.PageFrame
	GUIObject.Edit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Edit.BackgroundTransparency = 1.000
	GUIObject.Edit.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Edit.Visible = false

	GUIObject.MeshNameFrame.Name = "MeshNameFrame"
	GUIObject.MeshNameFrame.Parent = GUIObject.Edit
	GUIObject.MeshNameFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.MeshNameFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshNameFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.MeshNameFrame.Position = UDim2.new(0.5, 0, 0.0250000004, 0)
	GUIObject.MeshNameFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICorner_32.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_32.Parent = GUIObject.MeshNameFrame

	GUIObject.MeshNameTextbox.Name = "MeshNameTextbox"
	GUIObject.MeshNameTextbox.Parent = GUIObject.MeshNameFrame
	GUIObject.MeshNameTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.MeshNameTextbox.BackgroundTransparency = 1.000
	GUIObject.MeshNameTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.MeshNameTextbox.ClearTextOnFocus = false
	GUIObject.MeshNameTextbox.Font = Enum.Font.Code
	GUIObject.MeshNameTextbox.PlaceholderText = "Mesh Name"
	GUIObject.MeshNameTextbox.Text = ""
	GUIObject.MeshNameTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshNameTextbox.TextScaled = true
	GUIObject.MeshNameTextbox.TextSize = 14.000
	GUIObject.MeshNameTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MeshNameTextbox.TextWrapped = true

	GUIObject.UIGradient_31.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(76, 6, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(126, 17, 145))}
	GUIObject.UIGradient_31.Rotation = -90
	GUIObject.UIGradient_31.Parent = GUIObject.MeshNameFrame

	GUIObject.PropertyListFrame.Name = "PropertyListFrame"
	GUIObject.PropertyListFrame.Parent = GUIObject.Edit
	GUIObject.PropertyListFrame.Active = true
	GUIObject.PropertyListFrame.AnchorPoint = Vector2.new(0.5, 0.5)
	GUIObject.PropertyListFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.PropertyListFrame.BackgroundTransparency = 1.000
	GUIObject.PropertyListFrame.BorderSizePixel = 0
	GUIObject.PropertyListFrame.Position = UDim2.new(0.499999911, 0, 0.605427802, 0)
	GUIObject.PropertyListFrame.Size = UDim2.new(0.949999988, 0, 0.74982059, 0)
	GUIObject.PropertyListFrame.BottomImage = "rbxassetid://5946093983"
	GUIObject.PropertyListFrame.CanvasSize = UDim2.new(0, 0, 0.5, 0)
	GUIObject.PropertyListFrame.MidImage = ""
	GUIObject.PropertyListFrame.ScrollBarThickness = 0
	GUIObject.PropertyListFrame.CanvasSize = UDim2.new(0, 0, 0.5, 0)
	GUIObject.PropertyListFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
	GUIObject.PropertyListFrame.TopImage = "rbxassetid://5946093983"

	GUIObject.UIGridLayout_4.Parent = GUIObject.PropertyListFrame
	GUIObject.UIGridLayout_4.SortOrder = Enum.SortOrder.LayoutOrder
	GUIObject.UIGridLayout_4.CellPadding = UDim2.new(0,0,0,0)
	GUIObject.UIGridLayout_4.CellSize = UDim2.new(0.300000012*3.5, 0, 0.174999997*3.5, 0)

	GUIObject.EditNote.Parent = GUIObject.Edit
	GUIObject.EditNote.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.EditNote.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.EditNote.BackgroundTransparency = 1.000
	GUIObject.EditNote.Position = UDim2.new(0.50000006, 0, 0.110409796, 0)
	GUIObject.EditNote.Size = UDim2.new(0.890999973, 0, 0.1, 0)
	GUIObject.EditNote.Font = Enum.Font.Code
	GUIObject.EditNote.Text = "Self = Change Default Mesh Part\\n--------------------------------------\\nPlayer Name = Change Personal Mesh Part"
	GUIObject.EditNote.TextColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.EditNote.TextScaled = true
	GUIObject.EditNote.TextSize = 14.000
	GUIObject.EditNote.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.EditNote.TextStrokeTransparency = 0.000
	GUIObject.EditNote.TextWrapped = true
	GUIObject.EditNote.TextXAlignment = Enum.TextXAlignment.Left
	GUIObject.EditNote.Visible = false

	GUIObject.CharacterPreviewFrame.Name = "CharacterPreviewFrame"
	GUIObject.CharacterPreviewFrame.Parent = GUIObject.MainFrame
	GUIObject.CharacterPreviewFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.CharacterPreviewFrame.BackgroundTransparency = 1.000
	GUIObject.CharacterPreviewFrame.Position = UDim2.new(-0.458589792, 0, 0, 0)
	GUIObject.CharacterPreviewFrame.Size = UDim2.new(0.468550086, 0, 0.378379911, 0)

	GUIObject.ViewportFrame.BackgroundTransparency = 1.000
	GUIObject.ViewportFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ViewportFrame.Size = UDim2.new(1,0,1,0)
	GUIObject.ViewportFrame.CurrentCamera = GUIObject.ViewportCamera
	GUIObject.ViewportFrame.Parent = GUIObject.CharacterPreviewFrame

	GUIObject.ViewportCamera.CFrame = CFrame.new(4, 0.300000012, -4, -0.819152057, 0, 0.57357645, 0, 1, 0, -0.57357645, 0, -0.819152057)
	GUIObject.ViewportCamera.Parent = GUIObject.CharacterPreviewFrame

	GUIObject.PreviewUIAspectRatioConstraint.Parent = GUIObject.CharacterPreviewFrame
	GUIObject.PreviewUIAspectRatioConstraint.AspectRatio = 0.750
	GUIObject.PreviewUIAspectRatioConstraint.DominantAxis = Enum.DominantAxis.Height

	GUIObject.PreviewButton.Parent = GUIObject.CharacterPreviewFrame
	GUIObject.PreviewButton.Name = "PreviewButton"
	GUIObject.PreviewButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PreviewButton.BackgroundTransparency = 1.000
	GUIObject.PreviewButton.Position = UDim2.new(0, 0, 1.00000012, 0)
	GUIObject.PreviewButton.Size = UDim2.new(1, 0, 0.153530627, 0)
	GUIObject.PreviewButton.Font = Enum.Font.Code
	GUIObject.PreviewButton.Text = "Preview"
	GUIObject.PreviewButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PreviewButton.TextScaled = true
	GUIObject.PreviewButton.TextSize = 14.000
	GUIObject.PreviewButton.TextStrokeTransparency = 0.000
	GUIObject.PreviewButton.TextWrapped = true

	GUIObject.ClickExecuteFrame.Name = "ClickExecuteFrame"
	GUIObject.ClickExecuteFrame.Parent = GUIObject.Menu2
	GUIObject.ClickExecuteFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ClickExecuteFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClickExecuteFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ClickExecuteFrame.Position = UDim2.new(0.5, 0, 0.629999995, 0)
	GUIObject.ClickExecuteFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradientCE.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradientCE.Rotation = -90
	GUIObject.UIGradientCE.Parent = GUIObject.ClickExecuteFrame

	GUIObject.UICornerCE.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICornerCE.Parent = GUIObject.ClickExecuteFrame

	GUIObject.ClickExecuteButton.Name = "ClickExecuteButton"
	GUIObject.ClickExecuteButton.Parent = GUIObject.ClickExecuteFrame
	GUIObject.ClickExecuteButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ClickExecuteButton.BackgroundTransparency = 1.000
	GUIObject.ClickExecuteButton.BorderSizePixel = 0
	GUIObject.ClickExecuteButton.LayoutOrder = 1
	GUIObject.ClickExecuteButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ClickExecuteButton.Font = Enum.Font.Code
	GUIObject.ClickExecuteButton.Text = "Click Execute"
	GUIObject.ClickExecuteButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ClickExecuteButton.TextScaled = true
	GUIObject.ClickExecuteButton.TextSize = 14.000
	GUIObject.ClickExecuteButton.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ClickExecuteButton.TextStrokeTransparency = 0.000
	GUIObject.ClickExecuteButton.TextWrapped = true

	GUIObject.PositionPhysicsMultiplyFrame.Name = "PositionPhysicsMultiplyFrame"
	GUIObject.PositionPhysicsMultiplyFrame.Parent = GUIObject.Menu2
	GUIObject.PositionPhysicsMultiplyFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.PositionPhysicsMultiplyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PositionPhysicsMultiplyFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.PositionPhysicsMultiplyFrame.Position = UDim2.new(0.5, 0, 0.714999974, 0)
	GUIObject.PositionPhysicsMultiplyFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICornerPPM.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICornerPPM.Parent = GUIObject.PositionPhysicsMultiplyFrame

	GUIObject.PositionPhysicsMultiplyText.Name = "PositionPhysicsMultiplyText"
	GUIObject.PositionPhysicsMultiplyText.Parent = GUIObject.PositionPhysicsMultiplyFrame
	GUIObject.PositionPhysicsMultiplyText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.PositionPhysicsMultiplyText.BackgroundTransparency = 1.000
	GUIObject.PositionPhysicsMultiplyText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.PositionPhysicsMultiplyText.Font = Enum.Font.Code
	GUIObject.PositionPhysicsMultiplyText.PlaceholderText = "Position Physics Multiply"
	GUIObject.PositionPhysicsMultiplyText.Text = "1"
	GUIObject.PositionPhysicsMultiplyText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PositionPhysicsMultiplyText.TextScaled = true
	GUIObject.PositionPhysicsMultiplyText.TextSize = 14.000
	GUIObject.PositionPhysicsMultiplyText.TextWrapped = true

	GUIObject.UIGradientPPM.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.UIGradientPPM.Rotation = -90
	GUIObject.UIGradientPPM.Parent = GUIObject.PositionPhysicsMultiplyFrame

	GUIObject.RotationPhysicsMultiplyFrame.Name = "RotationPhysicsMultiplyFrame"
	GUIObject.RotationPhysicsMultiplyFrame.Parent = GUIObject.Menu2
	GUIObject.RotationPhysicsMultiplyFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.RotationPhysicsMultiplyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RotationPhysicsMultiplyFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.RotationPhysicsMultiplyFrame.Position = UDim2.new(0.5, 0, 0.800000012, 0)
	GUIObject.RotationPhysicsMultiplyFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICornerRPM.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICornerRPM.Parent = GUIObject.RotationPhysicsMultiplyFrame

	GUIObject.RotationPhysicsMultiplyText.Name = "RotationPhysicsMultiplyText"
	GUIObject.RotationPhysicsMultiplyText.Parent = GUIObject.RotationPhysicsMultiplyFrame
	GUIObject.RotationPhysicsMultiplyText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.RotationPhysicsMultiplyText.BackgroundTransparency = 1.000
	GUIObject.RotationPhysicsMultiplyText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.RotationPhysicsMultiplyText.Font = Enum.Font.Code
	GUIObject.RotationPhysicsMultiplyText.PlaceholderText = "Rotation Physics Multiply"
	GUIObject.RotationPhysicsMultiplyText.Text = "4"
	GUIObject.RotationPhysicsMultiplyText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RotationPhysicsMultiplyText.TextScaled = true
	GUIObject.RotationPhysicsMultiplyText.TextSize = 14.000
	GUIObject.RotationPhysicsMultiplyText.TextWrapped = true

	GUIObject.UIGradientRPM.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.UIGradientRPM.Rotation = -90
	GUIObject.UIGradientRPM.Parent = GUIObject.RotationPhysicsMultiplyFrame

	GUIObject.MobileCloseButton.Name = "MobileCloseButton"
	GUIObject.MobileCloseButton.Parent = GUIObject.MobileCloseButtonScreen
	GUIObject.MobileCloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.MobileCloseButton.BackgroundTransparency = 1.000
	GUIObject.MobileCloseButton.Position = UDim2.new(0.969957054, 0, 0.955650926, 0)
	GUIObject.MobileCloseButton.Size = UDim2.new(0.0300429184, 0, 0.0443490706, 0)
	GUIObject.MobileCloseButton.Image = "rbxassetid://264596039"

	GUIObject.MCBUIAspectRatioConstraint.Parent = GUIObject.MobileCloseButton

	GUIObject.SkinToneFrame.Name = "SkinToneFrame"
	GUIObject.SkinToneFrame.Parent = GUIObject.Menu2
	GUIObject.SkinToneFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.SkinToneFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.SkinToneFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.SkinToneFrame.Position = UDim2.new(0.271, 0, 0.88499999, 0)
	GUIObject.SkinToneFrame.Size = UDim2.new(0.425, 0, 0.0646399707, 0)

	GUIObject.STUICorner.CornerRadius = UDim.new(0.25, 0)
	GUIObject.STUICorner.Parent = GUIObject.SkinToneFrame

	GUIObject.SkinToneText.Name = "SkinToneText"
	GUIObject.SkinToneText.Parent = GUIObject.SkinToneFrame
	GUIObject.SkinToneText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.SkinToneText.BackgroundTransparency = 1.000
	GUIObject.SkinToneText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.SkinToneText.Font = Enum.Font.Code
	GUIObject.SkinToneText.PlaceholderText = "Skin Tone [RGB] (Empty=Disable)"
	GUIObject.SkinToneText.Text = ""
	GUIObject.SkinToneText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.SkinToneText.TextScaled = true
	GUIObject.SkinToneText.TextSize = 14.000
	GUIObject.SkinToneText.TextWrapped = true

	GUIObject.STUIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.STUIGradient.Rotation = -90
	GUIObject.STUIGradient.Parent = GUIObject.SkinToneFrame

	GUIObject.NippleColorFrame.Name = "NippleColorFrame"
	GUIObject.NippleColorFrame.Parent = GUIObject.Menu2
	GUIObject.NippleColorFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.NippleColorFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.NippleColorFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.NippleColorFrame.Position = UDim2.new(0.731, 0, 0.88499999, 0)
	GUIObject.NippleColorFrame.Size = UDim2.new(0.425, 0, 0.0646399707, 0)

	GUIObject.NTUICorner.CornerRadius = UDim.new(0.25, 0)
	GUIObject.NTUICorner.Parent = GUIObject.NippleColorFrame

	GUIObject.NippleColorText.Name = "NippleColorText"
	GUIObject.NippleColorText.Parent = GUIObject.NippleColorFrame
	GUIObject.NippleColorText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.NippleColorText.BackgroundTransparency = 1.000
	GUIObject.NippleColorText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.NippleColorText.Font = Enum.Font.Code
	GUIObject.NippleColorText.PlaceholderText = "Nipple Color [RGB] (Empty=Disable)"
	GUIObject.NippleColorText.Text = ""
	GUIObject.NippleColorText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.NippleColorText.TextScaled = true
	GUIObject.NippleColorText.TextSize = 14.000
	GUIObject.NippleColorText.TextWrapped = true

	GUIObject.NTUIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.NTUIGradient.Rotation = -90
	GUIObject.NTUIGradient.Parent = GUIObject.NippleColorFrame

	GUIObject.Menu3.Name = "Menu3"
	GUIObject.Menu3.Parent = GUIObject.PageFrame
	GUIObject.Menu3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Menu3.BackgroundTransparency = 1.000
	GUIObject.Menu3.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.Menu3.Visible = false

	GUIObject.BreastsScaleFrame.Name = "BreastsScaleFrame"
	GUIObject.BreastsScaleFrame.Parent = GUIObject.Menu3
	GUIObject.BreastsScaleFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BreastsScaleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BreastsScaleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BreastsScaleFrame.Position = UDim2.new(0.5, 0, 0.0250000004, 0)
	GUIObject.BreastsScaleFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.BS1UICorner.CornerRadius = UDim.new(0.25, 0)
	GUIObject.BS1UICorner.Parent = GUIObject.BreastsScaleFrame

	GUIObject.BreastsScaleText.Name = "BreastsScaleText"
	GUIObject.BreastsScaleText.Parent = GUIObject.BreastsScaleFrame
	GUIObject.BreastsScaleText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BreastsScaleText.BackgroundTransparency = 1.000
	GUIObject.BreastsScaleText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BreastsScaleText.ClearTextOnFocus = false
	GUIObject.BreastsScaleText.Font = Enum.Font.Code
	GUIObject.BreastsScaleText.PlaceholderText = "Breasts Scale"
	GUIObject.BreastsScaleText.Text = "1"
	GUIObject.BreastsScaleText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BreastsScaleText.TextScaled = true
	GUIObject.BreastsScaleText.TextSize = 14.000
	GUIObject.BreastsScaleText.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BreastsScaleText.TextWrapped = true

	GUIObject.BS1UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.BS1UIGradient.Rotation = -90
	GUIObject.BS1UIGradient.Parent = GUIObject.BreastsScaleFrame

	GUIObject.ButtsScaleFrame.Name = "ButtsScaleFrame"
	GUIObject.ButtsScaleFrame.Parent = GUIObject.Menu3
	GUIObject.ButtsScaleFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ButtsScaleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ButtsScaleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ButtsScaleFrame.Position = UDim2.new(0.5, 0, 0.109999999, 0)
	GUIObject.ButtsScaleFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.BS2UICorner.CornerRadius = UDim.new(0.25, 0)
	GUIObject.BS2UICorner.Parent = GUIObject.ButtsScaleFrame

	GUIObject.BS2UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.BS2UIGradient.Rotation = -90
	GUIObject.BS2UIGradient.Parent = GUIObject.ButtsScaleFrame

	GUIObject.ButtsScaleText.Name = "ButtsScaleText"
	GUIObject.ButtsScaleText.Parent = GUIObject.ButtsScaleFrame
	GUIObject.ButtsScaleText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.ButtsScaleText.BackgroundTransparency = 1.000
	GUIObject.ButtsScaleText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ButtsScaleText.ClearTextOnFocus = false
	GUIObject.ButtsScaleText.Font = Enum.Font.Code
	GUIObject.ButtsScaleText.PlaceholderText = "Butts Scale"
	GUIObject.ButtsScaleText.Text = "1"
	GUIObject.ButtsScaleText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ButtsScaleText.TextScaled = true
	GUIObject.ButtsScaleText.TextSize = 14.000
	GUIObject.ButtsScaleText.TextWrapped = true

	GUIObject.LegsScaleFrame.Name = "LegsScaleFrame"
	GUIObject.LegsScaleFrame.Parent = GUIObject.Menu3
	GUIObject.LegsScaleFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.LegsScaleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LegsScaleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.LegsScaleFrame.Position = UDim2.new(0.5, 0, 0.195, 0)
	GUIObject.LegsScaleFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.BS3UICorner.CornerRadius = UDim.new(0.25, 0)
	GUIObject.BS3UICorner.Parent = GUIObject.LegsScaleFrame

	GUIObject.BS3UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.BS3UIGradient.Rotation = -90
	GUIObject.BS3UIGradient.Parent = GUIObject.LegsScaleFrame

	GUIObject.LegsScaleText.Name = "LegsScaleText"
	GUIObject.LegsScaleText.Parent = GUIObject.LegsScaleFrame
	GUIObject.LegsScaleText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.LegsScaleText.BackgroundTransparency = 1.000
	GUIObject.LegsScaleText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.LegsScaleText.ClearTextOnFocus = false
	GUIObject.LegsScaleText.Font = Enum.Font.Code
	GUIObject.LegsScaleText.PlaceholderText = "Legs Scale"
	GUIObject.LegsScaleText.Text = "1"
	GUIObject.LegsScaleText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LegsScaleText.TextScaled = true
	GUIObject.LegsScaleText.TextSize = 14.000
	GUIObject.LegsScaleText.TextWrapped = true

	GUIObject.OutfitIdFrame.Name = "Outfit Id"
	GUIObject.OutfitIdFrame.Parent = GUIObject.Catalog_3
	GUIObject.OutfitIdFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.OutfitIdFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.OutfitIdFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.OutfitIdFrame.Position = UDim2.new(0.5, 0, 0.449999988, 0)
	GUIObject.OutfitIdFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UICornerUI.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICornerUI.Parent = GUIObject.OutfitIdFrame

	GUIObject.OutfitIdTextbox.Name = "OutfitIdTextbox"
	GUIObject.OutfitIdTextbox.Parent = GUIObject.OutfitIdFrame
	GUIObject.OutfitIdTextbox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.OutfitIdTextbox.BackgroundTransparency = 1.000
	GUIObject.OutfitIdTextbox.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.OutfitIdTextbox.ClearTextOnFocus = false
	GUIObject.OutfitIdTextbox.Font = Enum.Font.Code
	GUIObject.OutfitIdTextbox.PlaceholderText = "Outfit Id"
	GUIObject.OutfitIdTextbox.Text = ""
	GUIObject.OutfitIdTextbox.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.OutfitIdTextbox.TextScaled = true
	GUIObject.OutfitIdTextbox.TextSize = 14.000
	GUIObject.OutfitIdTextbox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.OutfitIdTextbox.TextWrapped = true

	GUIObject.UIGradientUI.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(22, 45, 94)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(52, 80, 145))}
	GUIObject.UIGradientUI.Rotation = -90
	GUIObject.UIGradientUI.Parent = GUIObject.OutfitIdFrame

	GUIObject.TorsoTypeFrame.Name = "TorsoTypeFrame"
	GUIObject.TorsoTypeFrame.Parent = GUIObject.Menu3
	GUIObject.TorsoTypeFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.TorsoTypeFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TorsoTypeFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.TorsoTypeFrame.Position = UDim2.new(0.5, 0, 0.28, 0)
	GUIObject.TorsoTypeFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A1.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_A1.Rotation = -90
	GUIObject.UIGradient_A1.Parent = GUIObject.TorsoTypeFrame

	GUIObject.UICorner_A1.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A1.Parent = GUIObject.TorsoTypeFrame

	GUIObject.TorsoTypeButton.Name = "TorsoTypeButton"
	GUIObject.TorsoTypeButton.Parent = GUIObject.TorsoTypeFrame
	GUIObject.TorsoTypeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TorsoTypeButton.BackgroundTransparency = 1.000
	GUIObject.TorsoTypeButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.TorsoTypeButton.ZIndex = 2
	GUIObject.TorsoTypeButton.Font = Enum.Font.Code
	GUIObject.TorsoTypeButton.Text = "Torso Type: 1"
	GUIObject.TorsoTypeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TorsoTypeButton.TextScaled = true
	GUIObject.TorsoTypeButton.TextSize = 14.000
	GUIObject.TorsoTypeButton.TextWrapped = true

	GUIObject.LegsTypeFrame.Name = "LegsTypeFrame"
	GUIObject.LegsTypeFrame.Parent = GUIObject.Menu3
	GUIObject.LegsTypeFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.LegsTypeFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LegsTypeFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.LegsTypeFrame.Position = UDim2.new(0.5, 0, 0.45, 0)
	GUIObject.LegsTypeFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_A2.Rotation = -90
	GUIObject.UIGradient_A2.Parent = GUIObject.LegsTypeFrame

	GUIObject.UICorner_A2.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A2.Parent = GUIObject.LegsTypeFrame

	GUIObject.LegsTypeButton.Name = "LegsTypeButton"
	GUIObject.LegsTypeButton.Parent = GUIObject.LegsTypeFrame
	GUIObject.LegsTypeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LegsTypeButton.BackgroundTransparency = 1.000
	GUIObject.LegsTypeButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.LegsTypeButton.ZIndex = 2
	GUIObject.LegsTypeButton.Font = Enum.Font.Code
	GUIObject.LegsTypeButton.Text = "Legs Type: 1"
	GUIObject.LegsTypeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.LegsTypeButton.TextScaled = true
	GUIObject.LegsTypeButton.TextSize = 14.000
	GUIObject.LegsTypeButton.TextWrapped = true

	GUIObject.ArmTypeFrame.Name = "ArmTypeFrame"
	GUIObject.ArmTypeFrame.Parent = GUIObject.Menu3
	GUIObject.ArmTypeFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ArmTypeFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ArmTypeFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ArmTypeFrame.Position = UDim2.new(0.5, 0, 0.365, 0)
	GUIObject.ArmTypeFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A11.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_A11.Rotation = -90
	GUIObject.UIGradient_A11.Parent = GUIObject.ArmTypeFrame

	GUIObject.UICorner_A11.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A11.Parent = GUIObject.ArmTypeFrame

	GUIObject.ArmTypeButton.Name = "ArmTypeButton"
	GUIObject.ArmTypeButton.Parent = GUIObject.ArmTypeFrame
	GUIObject.ArmTypeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ArmTypeButton.BackgroundTransparency = 1.000
	GUIObject.ArmTypeButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ArmTypeButton.ZIndex = 2
	GUIObject.ArmTypeButton.Font = Enum.Font.Code
	GUIObject.ArmTypeButton.Text = "Arm Type: 1"
	GUIObject.ArmTypeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ArmTypeButton.TextScaled = true
	GUIObject.ArmTypeButton.TextSize = 14.000
	GUIObject.ArmTypeButton.TextWrapped = true

	GUIObject.ButtTypeFrame.Name = "ButtTypeFrame"
	GUIObject.ButtTypeFrame.Parent = GUIObject.Menu3
	GUIObject.ButtTypeFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.ButtTypeFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ButtTypeFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.ButtTypeFrame.Position = UDim2.new(0.5, 0, 0.535, 0)
	GUIObject.ButtTypeFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A16.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_A16.Rotation = -90
	GUIObject.UIGradient_A16.Parent = GUIObject.ButtTypeFrame

	GUIObject.UICorner_A16.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A16.Parent = GUIObject.ButtTypeFrame

	GUIObject.ButtTypeButton.Name = "ButtTypeButton"
	GUIObject.ButtTypeButton.Parent = GUIObject.ButtTypeFrame
	GUIObject.ButtTypeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ButtTypeButton.BackgroundTransparency = 1.000
	GUIObject.ButtTypeButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.ButtTypeButton.ZIndex = 2
	GUIObject.ButtTypeButton.Font = Enum.Font.Code
	GUIObject.ButtTypeButton.Text = "Butt Type: 1"
	GUIObject.ButtTypeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.ButtTypeButton.TextScaled = true
	GUIObject.ButtTypeButton.TextSize = 14.000
	GUIObject.ButtTypeButton.TextWrapped = true

	GUIObject.FPFrame.Name = "FirstPersonFrame"
	GUIObject.FPFrame.Parent = GUIObject.Menu2
	GUIObject.FPFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.FPFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.FPFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.FPFrame.Position = UDim2.new(0.647907138, 0, 0.11, 0)
	GUIObject.FPFrame.Size = UDim2.new(0.595495105, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 93))}
	GUIObject.UIGradient_A4.Rotation = -90
	GUIObject.UIGradient_A4.Parent = GUIObject.FPFrame

	GUIObject.UICorner_A4.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A4.Parent = GUIObject.FPFrame

	GUIObject.FPExecute.Name = "FirstPerson"
	GUIObject.FPExecute.Parent = GUIObject.FPFrame
	GUIObject.FPExecute.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.FPExecute.BackgroundTransparency = 1.000
	GUIObject.FPExecute.BorderSizePixel = 0
	GUIObject.FPExecute.LayoutOrder = 1
	GUIObject.FPExecute.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.FPExecute.Font = Enum.Font.Code
	GUIObject.FPExecute.Text = "First Person POV"
	GUIObject.FPExecute.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.FPExecute.TextScaled = true
	GUIObject.FPExecute.TextSize = 14.000
	GUIObject.FPExecute.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.FPExecute.TextStrokeTransparency = 0.000
	GUIObject.FPExecute.TextWrapped = true

	GUIObject.GravityFrame.Name = "GravityFrame"
	GUIObject.GravityFrame.Parent = GUIObject.Menu2
	GUIObject.GravityFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.GravityFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.GravityFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.GravityFrame.Position = UDim2.new(0.647907138, 0, 0.195, 0)
	GUIObject.GravityFrame.Size = UDim2.new(0.595495105, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A15.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 93))}
	GUIObject.UIGradient_A15.Rotation = -90
	GUIObject.UIGradient_A15.Parent = GUIObject.GravityFrame

	GUIObject.UICorner_A15.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A15.Parent = GUIObject.GravityFrame

	GUIObject.GravityButton.Name = "GravityButton"
	GUIObject.GravityButton.Parent = GUIObject.GravityFrame
	GUIObject.GravityButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.GravityButton.BackgroundTransparency = 1.000
	GUIObject.GravityButton.BorderSizePixel = 0
	GUIObject.GravityButton.LayoutOrder = 1
	GUIObject.GravityButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.GravityButton.Font = Enum.Font.Code
	GUIObject.GravityButton.Text = "Physics Obey Gravity"
	GUIObject.GravityButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.GravityButton.TextScaled = true
	GUIObject.GravityButton.TextSize = 14.000
	GUIObject.GravityButton.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.GravityButton.TextStrokeTransparency = 0.000
	GUIObject.GravityButton.TextWrapped = true

	GUIObject.HP.Name = "HP"
	GUIObject.HP.Parent = GUIObject.ButtonFrame
	GUIObject.HP.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HP.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.HP.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.HP.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_A1.Parent = GUIObject.HP

	GUIObject.UICorner_A3.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A3.Parent = GUIObject.HP

	GUIObject.HPButton.Name = "HPButton"
	GUIObject.HPButton.Parent = GUIObject.HP
	GUIObject.HPButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HPButton.BackgroundTransparency = 1.000
	GUIObject.HPButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.HPButton.Font = Enum.Font.Code
	GUIObject.HPButton.Text = "HP"
	GUIObject.HPButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HPButton.TextScaled = true
	GUIObject.HPButton.TextSize = 14.000
	GUIObject.HPButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HPButton.TextWrapped = true

	GUIObject.UIGradient_A3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_A3.Rotation = -90
	GUIObject.UIGradient_A3.Parent = GUIObject.HP

	GUIObject.HPFrame.Name = "HP"
	GUIObject.HPFrame.Parent = GUIObject.PageFrame
	GUIObject.HPFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HPFrame.BackgroundTransparency = 1.000
	GUIObject.HPFrame.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.HPFrame.Visible = false

	GUIObject.TopHPFrame.Name = "TopHPFrame"
	GUIObject.TopHPFrame.Parent = GUIObject.HPFrame
	GUIObject.TopHPFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.TopHPFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TopHPFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.TopHPFrame.Position = UDim2.new(0.5, 0, 0.025, 0)
	GUIObject.TopHPFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.UIGradient_A5.Rotation = -90
	GUIObject.UIGradient_A5.Parent = GUIObject.TopHPFrame

	GUIObject.UICorner_A5.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A5.Parent = GUIObject.TopHPFrame

	GUIObject.TopHPText.Name = "TopHPText"
	GUIObject.TopHPText.ClearTextOnFocus = false
	GUIObject.TopHPText.Parent = GUIObject.TopHPFrame
	GUIObject.TopHPText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.TopHPText.BackgroundTransparency = 1.000
	GUIObject.TopHPText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.TopHPText.Font = Enum.Font.Code
	GUIObject.TopHPText.PlaceholderText = "Shirt Health"
	GUIObject.TopHPText.Text = ""
	GUIObject.TopHPText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TopHPText.TextScaled = true
	GUIObject.TopHPText.TextSize = 14.000
	GUIObject.TopHPText.TextWrapped = true

	GUIObject.TopClothesFrame.Name = "TopClothesFrame"
	GUIObject.TopClothesFrame.Parent = GUIObject.HPFrame
	GUIObject.TopClothesFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.TopClothesFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TopClothesFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.TopClothesFrame.Position = UDim2.new(0.5, 0, 0.11, 0)
	GUIObject.TopClothesFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 54, 45)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 100, 67))}
	GUIObject.UIGradient_A6.Rotation = -90
	GUIObject.UIGradient_A6.Parent = GUIObject.TopClothesFrame

	GUIObject.UICorner_A6.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A6.Parent = GUIObject.TopClothesFrame

	GUIObject.TopClothesText.Name = "TopClothesText"
	GUIObject.TopClothesText.ClearTextOnFocus = false
	GUIObject.TopClothesText.Parent = GUIObject.TopClothesFrame
	GUIObject.TopClothesText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.TopClothesText.BackgroundTransparency = 1.000
	GUIObject.TopClothesText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.TopClothesText.Font = Enum.Font.Code
	GUIObject.TopClothesText.PlaceholderText = "Ripped Shirt Id"
	GUIObject.TopClothesText.Text = ""
	GUIObject.TopClothesText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TopClothesText.TextScaled = true
	GUIObject.TopClothesText.TextSize = 14.000
	GUIObject.TopClothesText.TextWrapped = true

	GUIObject.BottomHPFrame.Name = "BottomHPFrame"
	GUIObject.BottomHPFrame.Parent = GUIObject.HPFrame
	GUIObject.BottomHPFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BottomHPFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BottomHPFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BottomHPFrame.Position = UDim2.new(0.5, 0, 0.195, 0)
	GUIObject.BottomHPFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A7.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(38, 0, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(70, 0, 100))}
	GUIObject.UIGradient_A7.Rotation = -90
	GUIObject.UIGradient_A7.Parent = GUIObject.BottomHPFrame

	GUIObject.UICorner_A7.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A7.Parent = GUIObject.BottomHPFrame

	GUIObject.BottomHPText.Name = "BottomHPText"
	GUIObject.BottomHPText.ClearTextOnFocus = false
	GUIObject.BottomHPText.Parent = GUIObject.BottomHPFrame
	GUIObject.BottomHPText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BottomHPText.BackgroundTransparency = 1.000
	GUIObject.BottomHPText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BottomHPText.Font = Enum.Font.Code
	GUIObject.BottomHPText.PlaceholderText = "Pants Health"
	GUIObject.BottomHPText.Text = ""
	GUIObject.BottomHPText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BottomHPText.TextScaled = true
	GUIObject.BottomHPText.TextSize = 14.000
	GUIObject.BottomHPText.TextWrapped = true

	GUIObject.BottomClothesFrame.Name = "BottomClothesFrame"
	GUIObject.BottomClothesFrame.Parent = GUIObject.HPFrame
	GUIObject.BottomClothesFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BottomClothesFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BottomClothesFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BottomClothesFrame.Position = UDim2.new(0.5, 0, 0.28, 0)
	GUIObject.BottomClothesFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A8.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(38, 0, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(70, 0, 100))}
	GUIObject.UIGradient_A8.Rotation = -90
	GUIObject.UIGradient_A8.Parent = GUIObject.BottomClothesFrame

	GUIObject.UICorner_A8.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A8.Parent = GUIObject.BottomClothesFrame

	GUIObject.BottomClothesText.Name = "BottomClothesText"
	GUIObject.BottomClothesText.ClearTextOnFocus = false
	GUIObject.BottomClothesText.Parent = GUIObject.BottomClothesFrame
	GUIObject.BottomClothesText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BottomClothesText.BackgroundTransparency = 1.000
	GUIObject.BottomClothesText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BottomClothesText.Font = Enum.Font.Code
	GUIObject.BottomClothesText.PlaceholderText = "Ripped Pants Id"
	GUIObject.BottomClothesText.Text = ""
	GUIObject.BottomClothesText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BottomClothesText.TextScaled = true
	GUIObject.BottomClothesText.TextSize = 14.000
	GUIObject.BottomClothesText.TextWrapped = true

	GUIObject.DamageFrame.Name = "DamageFrame"
	GUIObject.DamageFrame.Parent = GUIObject.HPFrame
	GUIObject.DamageFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.DamageFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DamageFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.DamageFrame.Position = UDim2.new(0.5, 0, 0.365, 0)
	GUIObject.DamageFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A9.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 0, 0))}
	GUIObject.UIGradient_A9.Rotation = -90
	GUIObject.UIGradient_A9.Parent = GUIObject.DamageFrame

	GUIObject.UICorner_A9.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A9.Parent = GUIObject.DamageFrame

	GUIObject.DamageSFX.Name = "DamageSFX"
	GUIObject.DamageSFX.ClearTextOnFocus = false
	GUIObject.DamageSFX.Parent = GUIObject.DamageFrame
	GUIObject.DamageSFX.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.DamageSFX.BackgroundTransparency = 1.000
	GUIObject.DamageSFX.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.DamageSFX.Font = Enum.Font.Code
	GUIObject.DamageSFX.PlaceholderText = "Damage SFX Minimum (leave blank to disable)"
	GUIObject.DamageSFX.Text = ""
	GUIObject.DamageSFX.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.DamageSFX.TextScaled = true
	GUIObject.DamageSFX.TextSize = 14.000
	GUIObject.DamageSFX.TextWrapped = true

	GUIObject.VolumeFrame.Name = "VolumeFrame"
	GUIObject.VolumeFrame.Parent = GUIObject.HPFrame
	GUIObject.VolumeFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.VolumeFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.VolumeFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.VolumeFrame.Position = UDim2.new(0.5, 0, 0.45, 0)
	GUIObject.VolumeFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A10.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 0, 0))}
	GUIObject.UIGradient_A10.Rotation = -90
	GUIObject.UIGradient_A10.Parent = GUIObject.VolumeFrame

	GUIObject.UICorner_A10.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A10.Parent = GUIObject.VolumeFrame

	GUIObject.VolumeText.Name = "VolumeText"
	GUIObject.VolumeText.ClearTextOnFocus = false
	GUIObject.VolumeText.Parent = GUIObject.VolumeFrame
	GUIObject.VolumeText.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.VolumeText.BackgroundTransparency = 1.000
	GUIObject.VolumeText.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.VolumeText.Font = Enum.Font.Code
	GUIObject.VolumeText.PlaceholderText = "Volume"
	GUIObject.VolumeText.Text = "1"
	GUIObject.VolumeText.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.VolumeText.TextScaled = true
	GUIObject.VolumeText.TextSize = 14.000
	GUIObject.VolumeText.TextWrapped = true

	GUIObject.TPFrame.Name = "TearFrame"
	GUIObject.TPFrame.Parent = GUIObject.HPFrame
	GUIObject.TPFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.TPFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TPFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.TPFrame.Position = UDim2.new(0.5, 0, 0.535, 0)
	GUIObject.TPFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A12.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 36, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 70, 0))}
	GUIObject.UIGradient_A12.Rotation = -90
	GUIObject.UIGradient_A12.Parent = GUIObject.TPFrame

	GUIObject.UICorner_A12.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A12.Parent = GUIObject.TPFrame

	GUIObject.TPToggle.Name = "TearToggle"
	GUIObject.TPToggle.Parent = GUIObject.TPFrame
	GUIObject.TPToggle.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.TPToggle.BackgroundTransparency = 1.000
	GUIObject.TPToggle.BorderSizePixel = 0
	GUIObject.TPToggle.LayoutOrder = 1
	GUIObject.TPToggle.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.TPToggle.Font = Enum.Font.Code
	GUIObject.TPToggle.Text = "Toggle Tear Particles"
	GUIObject.TPToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.TPToggle.TextScaled = true
	GUIObject.TPToggle.TextSize = 14.000
	GUIObject.TPToggle.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.TPToggle.TextStrokeTransparency = 0.000
	GUIObject.TPToggle.TextWrapped = true

	GUIObject.PHFrame.Name = "HealFrame"
	GUIObject.PHFrame.Parent = GUIObject.HPFrame
	GUIObject.PHFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.PHFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PHFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.PHFrame.Position = UDim2.new(0.5, 0, 0.62, 0)
	GUIObject.PHFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A13.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(54, 36, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(100, 70, 0))}
	GUIObject.UIGradient_A13.Rotation = -90
	GUIObject.UIGradient_A13.Parent = GUIObject.PHFrame

	GUIObject.UICorner_A13.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A13.Parent = GUIObject.PHFrame

	GUIObject.PHToggle.Name = "HealToggle"
	GUIObject.PHToggle.Parent = GUIObject.PHFrame
	GUIObject.PHToggle.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.PHToggle.BackgroundTransparency = 1.000
	GUIObject.PHToggle.BorderSizePixel = 0
	GUIObject.PHToggle.LayoutOrder = 1
	GUIObject.PHToggle.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.PHToggle.Font = Enum.Font.Code
	GUIObject.PHToggle.Text = "Toggle Heal Particles"
	GUIObject.PHToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.PHToggle.TextScaled = true
	GUIObject.PHToggle.TextSize = 14.000
	GUIObject.PHToggle.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.PHToggle.TextStrokeTransparency = 0.000
	GUIObject.PHToggle.TextWrapped = true

	GUIObject.Recolor.Name = "Recolor"
	GUIObject.Recolor.Parent = GUIObject.ButtonFrame
	GUIObject.Recolor.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.Recolor.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.Recolor.Position = UDim2.new(0.784810185, 0, 0.866666734, 0)
	GUIObject.Recolor.Size = UDim2.new(1, 0, 1, 0)

	GUIObject.UIAspectRatioConstraint_A2.Parent = GUIObject.Recolor

	GUIObject.UICorner_A14.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A14.Parent = GUIObject.Recolor

	GUIObject.RecolorButton.Name = "RecolorButton"
	GUIObject.RecolorButton.Parent = GUIObject.Recolor
	GUIObject.RecolorButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RecolorButton.BackgroundTransparency = 1.000
	GUIObject.RecolorButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.RecolorButton.Font = Enum.Font.Code
	GUIObject.RecolorButton.Text = "Recolor"
	GUIObject.RecolorButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RecolorButton.TextScaled = true
	GUIObject.RecolorButton.TextSize = 14.000
	GUIObject.RecolorButton.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RecolorButton.TextWrapped = true

	GUIObject.UIGradient_A14.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(27, 27, 27)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(50, 50, 50))}
	GUIObject.UIGradient_A14.Rotation = -90
	GUIObject.UIGradient_A14.Parent = GUIObject.Recolor

	GUIObject.RecolorFrame.Name = "Recolor"
	GUIObject.RecolorFrame.Parent = GUIObject.PageFrame
	GUIObject.RecolorFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.RecolorFrame.BackgroundTransparency = 1.000
	GUIObject.RecolorFrame.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.RecolorFrame.Visible = false

	GUIObject.RecolorListFrame.Name = "RecolorListFrame"
	GUIObject.RecolorListFrame.Parent = GUIObject.RecolorFrame
	GUIObject.RecolorListFrame.Active = true
	GUIObject.RecolorListFrame.AnchorPoint = Vector2.new(0.5, 0.5)
	GUIObject.RecolorListFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.RecolorListFrame.BackgroundTransparency = 1.000
	GUIObject.RecolorListFrame.BorderSizePixel = 0
	GUIObject.RecolorListFrame.Position = UDim2.new(0.5, 0, 0.5, 0)
	GUIObject.RecolorListFrame.Size = UDim2.new(0.95, 0, 0.95, 0)
	GUIObject.RecolorListFrame.BottomImage = "rbxassetid://5946093983"
	GUIObject.RecolorListFrame.CanvasSize = UDim2.new(0, 0, 0.5, 0)
	GUIObject.RecolorListFrame.MidImage = ""
	GUIObject.RecolorListFrame.ScrollBarThickness = 0
	GUIObject.RecolorListFrame.CanvasSize = UDim2.new(0, 0, 0.5, 0)
	GUIObject.RecolorListFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
	GUIObject.RecolorListFrame.TopImage = "rbxassetid://5946093983"

	GUIObject.UIGridLayout_A1.Parent = GUIObject.RecolorListFrame
	GUIObject.UIGridLayout_A1.SortOrder = Enum.SortOrder.LayoutOrder
	GUIObject.UIGridLayout_A1.HorizontalAlignment = Enum.HorizontalAlignment.Center
	GUIObject.UIGridLayout_A1.CellPadding = UDim2.new(0,0,.02,0)
	GUIObject.UIGridLayout_A1.CellSize = UDim2.new(.98, 0, 0.1, 0)

	GUIObject.BodyTransparencyFrame.Name = "BodyTransparencyFrame"
	GUIObject.BodyTransparencyFrame.Parent = GUIObject.Menu2
	GUIObject.BodyTransparencyFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.BodyTransparencyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BodyTransparencyFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.BodyTransparencyFrame.Position = UDim2.new(0.731, 0, 0.46, 0)
	GUIObject.BodyTransparencyFrame.Size = UDim2.new(0.425, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A18.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 49, 54)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 83, 100))}
	GUIObject.UIGradient_A18.Rotation = -90
	GUIObject.UIGradient_A18.Parent = GUIObject.BodyTransparencyFrame

	GUIObject.UICorner_A18.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A18.Parent = GUIObject.BodyTransparencyFrame

	GUIObject.BodyTransparencyButton.Name = "BodyTransparencyButton"
	GUIObject.BodyTransparencyButton.Parent = GUIObject.BodyTransparencyFrame
	GUIObject.BodyTransparencyButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.BodyTransparencyButton.BackgroundTransparency = 1.000
	GUIObject.BodyTransparencyButton.BorderSizePixel = 0
	GUIObject.BodyTransparencyButton.LayoutOrder = 1
	GUIObject.BodyTransparencyButton.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.BodyTransparencyButton.Font = Enum.Font.Code
	GUIObject.BodyTransparencyButton.Text = "Realtime Body Transparency"
	GUIObject.BodyTransparencyButton.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.BodyTransparencyButton.TextScaled = true
	GUIObject.BodyTransparencyButton.TextSize = 14.000
	GUIObject.BodyTransparencyButton.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.BodyTransparencyButton.TextStrokeTransparency = 0.000
	GUIObject.BodyTransparencyButton.TextWrapped = true

	GUIObject.HardcoreFrame.Name = "HardcoreFrame"
	GUIObject.HardcoreFrame.Parent = GUIObject.HPFrame
	GUIObject.HardcoreFrame.AnchorPoint = Vector2.new(0.5, 0)
	GUIObject.HardcoreFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HardcoreFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
	GUIObject.HardcoreFrame.Position = UDim2.new(0.5, 0, 0.705, 0)
	GUIObject.HardcoreFrame.Size = UDim2.new(0.891309202, 0, 0.0646399707, 0)

	GUIObject.UIGradient_A19.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(38, 10, 10)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(63, 19, 19))}
	GUIObject.UIGradient_A19.Rotation = -90
	GUIObject.UIGradient_A19.Parent = GUIObject.HardcoreFrame

	GUIObject.UICorner_A19.CornerRadius = UDim.new(0.25, 0)
	GUIObject.UICorner_A19.Parent = GUIObject.HardcoreFrame

	GUIObject.HardcoreToggle.Name = "HardcoreToggle"
	GUIObject.HardcoreToggle.Parent = GUIObject.HardcoreFrame
	GUIObject.HardcoreToggle.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
	GUIObject.HardcoreToggle.BackgroundTransparency = 1.000
	GUIObject.HardcoreToggle.BorderSizePixel = 0
	GUIObject.HardcoreToggle.LayoutOrder = 1
	GUIObject.HardcoreToggle.Size = UDim2.new(1, 0, 1, 0)
	GUIObject.HardcoreToggle.Font = Enum.Font.Code
	GUIObject.HardcoreToggle.Text = "Clothing Hardcore HP"
	GUIObject.HardcoreToggle.TextColor3 = Color3.fromRGB(255, 255, 255)
	GUIObject.HardcoreToggle.TextScaled = true
	GUIObject.HardcoreToggle.TextSize = 14.000
	GUIObject.HardcoreToggle.TextStrokeColor3 = Color3.fromRGB(0, 255, 0)
	GUIObject.HardcoreToggle.TextStrokeTransparency = 0.000
	GUIObject.HardcoreToggle.TextWrapped = true

	if not UIS.KeyboardEnabled then
		GUIObject.MobileCloseButtonScreen.Enabled = true
		--Method = 2
	end

	Function.CatalogAccessoryFrameAdd(SelectPlayer)
	Function.GUIFunc()
	Function.GUIUpdate()

	--[[
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	
                               ██████╗░██████╗░███████╗░█████╗░██╗░░██╗███████╗██████╗░
                               ██╔══██╗██╔══██╗██╔════╝██╔══██╗██║░██╔╝██╔════╝██╔══██╗
                               ██████╦╝██████╔╝█████╗░░███████║█████═╝░█████╗░░██████╔╝
                               ██╔══██╗██╔══██╗██╔══╝░░██╔══██║██╔═██╗░██╔══╝░░██╔══██╗
                               ██████╦╝██║░░██║███████╗██║░░██║██║░╚██╗███████╗██║░░██║
                               ╚═════╝░╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝
                                  
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	--------------------------------------------------------------------------------------------------------------
	]]

	for i, v in pairs(game:GetService("CollectionService"):GetTagged("RoClothes")) do
		v:Destroy()
	end

	local BREAKER = Instance.new("BoolValue")
	BREAKER.Name = "RoClothesBreaker"
	BREAKER.Parent = game.workspace

	GUIObject.Screen.Enabled = false
	local loadui = Instance.new("ScreenGui",game:GetService("CoreGui"))
	loadui.Enabled = true
	local oload = Instance.new("ImageLabel",loadui)
	oload.Image = "rbxasset://RClothesContent/load.png"
	oload.Size = UDim2.new(1,0,1,0)
	oload.Transparency = 1
	oload.ImageTransparency = .999
	local load = Instance.new("ImageLabel",loadui)
	load.Image = "rbxasset://RClothesContent/loadv7.png"
	load.Size = UDim2.new(1,0,1,0)
	load.Transparency = 1
	load.ImageTransparency = .999
	local debounce = 0
	local loadtxt
	repeat
		task.wait(.1)
		if loadtxt then
			loadtxt:Destroy()
		end
		loadtxt = Instance.new("TextLabel",loadui)
		loadtxt.BackgroundTransparency = 1
		loadtxt.TextColor3 = Color3.new(1,1,1)
		loadtxt.TextScaled = true
		loadtxt.Size = UDim2.new(1,0,1,0)
		loadtxt.Text = "loading"
		debounce += 1
	until debounce >= 50 or load.IsLoaded == true
	if loadtxt then
		loadtxt:Destroy()
	end
	if load.IsLoaded == false then
		GUIObject.Screen.Enabled = false
		local BREAKER = Instance.new("BoolValue")
		BREAKER.Name = "RoClothesBreaker"
		BREAKER.Parent = game.workspace
		if oload.IsLoaded == true then
			local txt = Instance.new("TextLabel",loadui)
			txt.BackgroundTransparency = 1
			txt.TextColor3 = Color3.new(1,1,1)
			txt.TextScaled = true
			txt.Size = UDim2.new(1,0,1,0)
			txt.Text = "WRONG VERSION FILES ARE LOADED"
			game:GetService("Debris"):AddItem(loadui,2)
			warn("WRONG VERSION FILES ARE LOADED")
		else
			local txt = Instance.new("TextLabel",loadui)
			txt.BackgroundTransparency = 1
			txt.TextColor3 = Color3.new(1,1,1)
			txt.TextScaled = true
			txt.Size = UDim2.new(1,0,1,0)
			txt.Text = "FILES ARE NOT LOADED CORRECTLY"
			game:GetService("Debris"):AddItem(loadui,2)
			warn("FILES ARE NOT LOADED CORRECTLY")
		end
	else
		GUIObject.Screen.Enabled = true
		loadui:Destroy()
	end
	task.wait(2)

	if BREAKER.Parent ~= nil then
		BREAKER:Destroy()
	end

	task.spawn(function()
		while task.wait(0.5) do
			local BreakerObject = game.Workspace:FindFirstChild("RoClothesBreaker")

			if BreakerObject then
				for _, Connect in pairs(AllConnect) do
					Connect:Disconnect()
				end

				GUIObject.Screen:Destroy()
				GUIObject.MobileCloseButtonScreen:Destroy()
				BreakerObject:Destroy()
				warn("RoClothes Disconnected")
				break
			end
		end
	end)
end

if RS:IsStudio() then
	RoClothes(game.Players.LocalPlayer)
else
	if RS:IsClient() then
		RoClothes(game.Players.LocalPlayer)
	elseif RS:IsServer() then
		RoClothes(game.Players:WaitForChild("lerp()"))
	end
end
return nil