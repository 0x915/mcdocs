## 配置文件 config/mca.json  
```json
// 覆盖新生成的村民和僵尸村民
"overwriteOriginalVillagers": true,
"overwriteOriginalZombieVillagers": true,

// 使用僵尸村民代替僵尸生成，实验性社区要求。
"overwriteAllZombiesWithZombieVillagers": false,

// Add Modded Villagers to be converted into MCA villagers, if they are not converted already. Same for modded Zombie Villagers
"moddedVillagerWhitelist": [],
"moddedZombieVillagerWhitelist": [],

// 小僵尸生成概率
"babyZombieChance": 0.25,

// 询问村民是否是某个标签
"villagerTagsHacks": true,

// 允许死神生成
"allowGrimReaper": true,

// 村民聊天信息使用的前缀
"villagerChatPrefix": "",

// 玩家能对婴儿造成伤害
"canHurtBabies": true,

// 切换进入时的村庄名称通知、结婚通知、出生通知、村民进货通知、有人到达旅馆时通知以及通知是否应显示在聊天中而不是显示在热键栏上方
"enterVillageNotification": true,
"villagerMarriageNotification": true,
"villagerBirthNotification": true,
"innArrivalNotification": true,
"villagerRestockNotification": true,
"showNotificationsAsChat": false,

// 被视为好友的红心数量
"heartsToBeConsideredAsFriend": 40,

// 启用村民感染、感染机会、交易级别阻力以及村民在感染蜱后多久变成僵尸
"enableInfection": true,
"infectionChance": 5,
"infectionChanceDecreasePerLevel": 0.25,
"infectionTime": 72000

// 双胞胎婴儿的比例
"twinBabyChance": 0.02f,

// 结婚、订婚、花束所需的红心数量
"marriageHeartsRequirement": 100.0,
"engagementHeartsRequirement": 50.0,
"bouquetHeartsRequirement": 10.0,

// 村民成长世界和最大年龄，时间通常以刻度为单位，每秒20个刻度，Minecraft 一天为 24000 个刻度
"babyItemGrowUpTime": 24000,
"villagerMaxAgeTime": 192000,

// 村民的最大生命值
"villagerMaxHealth": 20,

// 每当村民被困时，他们就可以传送。 禁用，因为可能会导致村民失踪
"allowVillagerTeleporting": false,
"villagerMinTeleportationDistance": 144.0,

// 您将获得孩子的初始红心数量
"childInitialHearts": 100,

//IMPORTANT: Only full numbers allowed for greetAfterDays, otherwise your game will crash
// 村民向你打招呼需要多少颗心以及距离村民向你打招呼的天数间隔，天数只允许使用整数
"greetHeartsThreshold": 75,
"greetAfterDays": 1,

// 肤色与生物群落无关的村民比例
"geneticImmigrantChance": 20,

// 村民拥有一种特征的概率与被继承几率，拥有更多特征的几率呈指数级下降
"traitChance": 0.25,
"traitInheritChance": 0.5,

// 允许玩家添加被阻止的特征，这些特征是：左撇子、乳糜泻、糖尿病、素食者、带电者和 Sirben
// 这些特征默认被阻止，因为它们不会对玩家的游戏玩法做任何事情
"bypassTraitRestrictions": false,

// 村民成为夜猫子的概率，这意味着如果村民被允许成为夜猫子，他们会在晚上醒来并在白天睡觉。
// 默认设置为 false，因为尚未对生存进行测试，请谨慎操作，如果启用，请进行备份
"nightOwlChance": 0.5,
"allowAnyNightOwl": false,

// 每N颗心，你可以在没有守卫攻击你的情况下击中一个村民
"heartsForPardonHit": 30,
"pardonPlayerTicks": 1200,

// 守卫是否应该攻击所有怪物。在改装环境中很有帮助，也可以导致守卫攻击被动怪物。使用优先级列表进行微调。
"guardsTargetMonsters": false,

// 村民身高肥胖系数（男性村民比女性村民稍大、稍宽）
"maleVillagerHeightFactor": 0.9,
"femaleVillagerHeightFactor": 0.85,
"maleVillagerWidthFactor": 1.0,
"femaleVillagerWidthFactor": 0.95,

// 在村民上方显示姓名标签
"showNameTags": true,

// 使用MCA语音或原板语音
"useMCAVoices": true,
"useVanillaVoices": false,

// 每N次交互都会增加一种疲劳，疲劳冷却世界
"interactionChanceFatigue": 1,
"interactionFatigueCooldown": 3000,

// 交易等级增加最大生命值
"villagerHealthBonusPerLevel": 5,

// 使用原板模型
"useSquidwardModels": false,

// 启用女性乳房
"enableBoobs": true,

// 烧焦衣服的刻度
"burnedClothingTickLength": 3600,

// 村民有染发的概率
"coloredHairChance": 0.02,

// 村民出现在墓碑上所需的红心数量。不适用于家庭成员，因为他们会自动添加
"heartsRequiredToAutoSpawnGravestone": 10,

// 更智能的门AI可以开门
"useSmarterDoorAI": false,

// 担任守卫的村民比例
"guardSpawnFraction = 0.175f,

// 控制村民提供的税款金额以及征收税款的时间间隔。
"taxesFactor": 1.5,

// 每N个刻度就是一个纳税季节
"taxSeason": 168000,

// 村庄每分钟更新一次。 每次更新都有 5% 发生婚姻、冒险、出生。
"marriageChancePerMinute": 0.05,
"adventurerAtInnChancePerMinute": 0.05,
"villagerProcreationChancePerMinute": 0.05,

// 如果你名声不好，赏金猎人的攻击间隔
"bountyHunterInterval": 24000,
"bountyHunterHeartsInterval": -150,

// 旅馆是否会生成冒险家、邪教徒、流浪商人
"innSpawnsAdventurers": true,
"innSpawnsCultists": true,
"innSpawnsWanderingTraders": true,

// 原板村民的比例。0意味着所有村民都将转换为 MCA 村民，0.5将导致公平混合。
"fractionOfVanillaVillages": 0,

// 原板僵尸村民的比例
"fractionOfVanillaZombies": 0,

// 被视为村庄的最小建筑数量。低于该值的村庄被视为定居点，不会打印欢迎来到村庄的消息
"minimumBuildingsToBeConsideredAVillage": 3,

// 保存原板村民生成的维度
"villagerDimensionBlacklist": [],

// 控制村民可以转化的地方。 默认值是自然生成并在结构中
// List of all allowed, case-insensitive terms: Natural, Chunk_generation, Spawner, Structure, Breeding, Mob_summoned, Jockey, Event, Conversion, Reinforcement, Triggered, Bucket, Spawn_egg, Command, Dispenser, Patrol
"allowedSpawnReasons": [
  "natural",
  "structure"
],

// 村民可互动项目的列表
"villagerInteractionItemBlacklist": [
  "minecraft:bucket"
],

// 村民会记住他们的最后一份礼物，并且会对重复的反应不太高兴。
// 公式为 出现次数*giftDesaturationFactor*max(satisfaction,0)^giftDesaturationExponent
// 也就是说，每次出现都会使满意度降低0.5，但礼物越贵，这种影响就越小（因为指数小于1）
// giftSatisfactionFactor 乘以满意度以获得实际的心灵影响
"giftDesaturationQueueLength": 16,
"giftDesaturationFactor": 0.5,
"giftDesaturationExponent": 0.85,
"giftSatisfactionFactor": 0.33,

// 一份礼物对心情的影响有多大
"giftMoodEffect": 0.5,
"baseGiftMoodEffect": 2.0,
"giftDesaturationReset": 24000,

// 是否允许玩家互相结婚
"allowPlayerMarriage": true,

// 最小和最大建筑物尺寸以及最大建筑物半径。较大的建筑物可能会导致重新扫描时出现小滞后
"minBuildingSize": 32,
"maxBuildingSize": 8192,
"maxBuildingRadius": 320,

// 死神祭坛最小柱子尺寸
"minPillarHeight": 2,

// 砍伐最大树高、有效原木和有效树底块
"maxTreeHeight": 8,
"maxTreeTicks": {
  "#minecraft:logs": 60
},
"validTreeSources": [
  "minecraft:grass_block",
  "minecraft:dirt"
],

// 新玩家加入时进入命运启动画面
"launchIntoDestiny": true,

// 允许一次通过命令重设你的命运
"allowDestinyCommandOnce": true,

// 允许多次通过命令重设你的命运
"allowDestinyCommandMoreThanOnce": false,

// 允许命运出生点传送
"allowDestinyTeleportation": true,

// 允许玩家看起来像村民
"enableVillagerPlayerModel": true,

// 允许 shaderLocationsMap 选项起作用
"enablePlayerShaders": true,

// 强迫玩家看起来像村民（玩家按钮不可用）
"forceVillagerPlayerModel": false,

// 允许重新打开编辑器（仅显示姓名、性别等，因为衣服和头发可以通过项目更改）
"allowPlayerEditor": true,

// 允许每个人访问完整的玩家编辑器
"allowFullPlayerEditor": true,

// 使用 7.3.2 之前的名称代替国际名称
"useModernUSANamesOnly" = false,

// 守卫将攻击的目标的详细优先级列表
// 负数表示忽略，越高越危险，优先级越高
"guardsTargetEntities": {
  "minecraft:creeper": -1,
  "minecraft:drowned": 2,
  "minecraft:evoker": 3,
  "minecraft:husk": 2,
  "minecraft:illusioner": 3,
  "minecraft:pillager": 3,
  "minecraft:ravager": 3,
  "minecraft:vex": 0,
  "minecraft:vindicator": 4,
  "minecraft:zoglin": 2,
  "minecraft:zombie": 4,
  "minecraft:zombie_villager": 3,
  "minecraft:spider": 0,
  "minecraft:skeleton": 0,
  "minecraft:slime": 0,
  "mcafemale_zombie_villager": 3,
  "mcamale_zombie_villager": 3
},

// 村民寻路黑名单，当前仅用于定义传送的有效位置
"villagerPathfindingBlacklist": [
  "#minecraft:climbable",
  "#minecraft:fence_gates",
  "#minecraft:fences",
  "#minecraft:fire",
  "#minecraft:portals",
  "#minecraft:slabs",
  "#minecraft:stairs",
  "#minecraft:trapdoors",
  "#minecraft:walls"
]

// 谣言对话选项中可以提及的结构
"structuresInRumors": [
    "igloo",
    "pyramid",
    "ruined_portal_desert",
    "ruined_portal_swamp",
    "ruined_portal",
    "ruined_portal_mountain",
    "mansion",
    "monument",
    "shipwreck",
    "shipwreck_beached",
    "village_desert",
    "village_taiga",
    "village_snowy",
    "village_plains",
    "village_savanna",
    "swamp_hut",
    "mineshaft",
    "jungle_pyramid",
    "pillager_outpost"
],

// 命运传送的地点
"destinyLocations": [
    "somewhere",
    "shipwreck_beached",
    "village_desert",
    "village_taiga",
    "village_snowy",
    "village_plains",
    "village_savanna"
],

// 用于指定结构是否有任何附加翻译
"destinyLocationsToTranslationMap": {
    "shipwreck_beached": "destiny.story.sailing",
    "default": "destiny.story.travelling"
},

// professionConversionsMap 和 shaderLocationsMap 的选项
// 设计为能够使用其他职业的服装，如果您的模组不向我们提供任何服装
// 这里仅使用成人服装，婴儿和儿童服装保持不变。
"professionConversionsMap": {
    "your_mod:your_profession": "mca:guard",
    "default": "minecraft:blacksmith"
},

// 如果相机实体具有指定的特征，它将应用着色器，并在当前相机实体没有时将其删除。
// 需要 `enablePlayerShaders` 为 true 才能使用此功能
"shaderLocationsMap": {
    "color_blind": "minecraft:shaders/post/desaturate.json"
},

// playerRendererBlacklist 选项
// 如果存在某些模组，允许您禁用玩家模型的某些渲染元素
// 支持的值：arms、left_arm、right_arm、all、block_player、block_villager
"playerRendererBlacklist": {
    "firstperson": "arms",
    "epicfight": "all",
    "firstpersonmod": "arms"
}

// 所有可能税项的项目及其价值单位。
// 每个物品都有相同的机会被挑选，直到税款全部付清。
// 如果该物品太贵（价值大于可用的税收预算），它可能会随机不被挑选。
"taxesMap": {
  "minecraft:emerald": 1.0
}
```
