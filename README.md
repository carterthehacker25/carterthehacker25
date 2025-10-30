let x2 = 0
player.onChat("give", function () {
    
})
player.onItemInteracted(FISHING_ROD, function () {
    if (x2 == 0) {
        mobs.applyEffect(FIRE_RESISTANCE, mobs.target(NEAREST_PLAYER), 10, 1)
        x2 = 1
    } else {
        x2 = 0
        blocks.fill(
        TNT,
        pos(-2, -4, -2),
        pos(2, -4, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -7, -2),
        pos(2, -7, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -10, -2),
        pos(2, -10, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -13, -2),
        pos(2, -13, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -16, -2),
        pos(2, -16, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -19, -2),
        pos(2, -19, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -25, -2),
        pos(2, -25, 2),
        FillOperation.Replace
        )
        blocks.fill(
        TNT,
        pos(-2, -22, -2),
        pos(2, -22, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -24, -2),
        pos(2, -24, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -21, -2),
        pos(2, -21, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -18, -2),
        pos(2, -18, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -15, -2),
        pos(2, -15, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -12, -2),
        pos(2, -12, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -9, -2),
        pos(2, -9, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -6, -2),
        pos(2, -6, 2),
        FillOperation.Replace
        )
        blocks.fill(
        REDSTONE_BLOCK,
        pos(-2, -3, -2),
        pos(2, -3, 2),
        FillOperation.Replace
        )
        loops.pause(5)
        blocks.fill(
        AIR,
        pos(-2, -3, -2),
        pos(2, -3, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-2, -6, -2),
        pos(2, -6, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-2, -9, -2),
        pos(2, -9, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-2, -12, -2),
        pos(2, -12, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-2, -15, -2),
        pos(2, -15, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-5, -18, -5),
        pos(2, -18, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-2, -21, -2),
        pos(2, -21, 2),
        FillOperation.Replace
        )
        blocks.fill(
        AIR,
        pos(-2, -24, -2),
        pos(2, -24, 2),
        FillOperation.Replace
        )
    }
})
