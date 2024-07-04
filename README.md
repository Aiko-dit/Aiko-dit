print(string.format("Final player state: isActive=%s, position=(x=%.2f, y=%.2f)", tostring(player.isActive), player.position.x, player.position.y))local function aim(angle)
    player.angle = angle
    print(string.format("Player aimed at angle %.2f degrees", angle))
}
end
end
