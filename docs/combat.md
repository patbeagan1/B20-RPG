

### Combat
Combat in this game is interactive on both the attacker's and the Defender's part. Both the Attacker and the Defender will have to roll to see if they have succeeded in what they are trying to do. The basics of combat can be summed up by the following two stages:

### Attack
Both the Attacker and Defender roll d20, and add their dex mod to the result.
The players compare their final scores. If the Attacker has a higher score, the attack has succeeded, and damage must be calculated. If the Defender has a higher score, the attack is over.
### Damage
If the Attacker has succeeded, add together the following:
The Attacker's primary weapon damage
Half of the Attacker's secondary weapon damage, rounded down  
Half of the character's strength stat, rounded down
Subtract the Defender's shield
Subtract the final number from the Defender's health points. 0 is the lowest that their health is able to go.
Before combat starts, take a moment to add up the character’s damage value, and the defender’s shield. It will save time during the actual gameplay. 
Show me the code (Python)
    def combat(attacker, defender):
 
        # Both the Attacker and defender roll d20 and add their dex mod.
        atk_roll = roll(20) + attacker.get_dex_mod()
        def_roll = roll(20) + defender.get_dex_mod()
 
        # If the attacker's dice beat the defender's, the attack succeeds.
        if atk_roll > def_roll:
 
            # Damage dealt is determined by the held weapons,
            # the character's strength and the defender's shield bonus.
            weapon_bonus = attacker.atk1 + attacker.atk2 // 2
            strength_bonus = attacker.get_str() // 2
            defender_resist = defender.shield
            damage = weapon_bonus + strength_bonus - defender_resist
 
            # You can't deal less than 0 damage.
            defender.health -= max(0, damage)
 

