# Roid Macros

### Customized for Weird Vibes:  
* Uses SuperWoW (if available) to avoid target swaps
* Empowers `/starattack` to avoid delaying OH swings when dual weilding
* Allows item id's to be used in macros instead of names, to shorted them
* Allows limited nesting of macros:
```
/run -- CastSpellByName("Taunt")
/cast [stance:2] {"/run if not UnitIsUnit("targettarget","player") then CastSpellByName("Taunt","target") end"}
```
* Expanded the power of the `equipped` conditional:
```
/cast [equipped:Bows] Shoot Bow; [equipped:Crossbows] Shoot Crossbow; [equipped:Guns] Shoot Gun; [equipped:Thrown] Throw
/cast [equipped:Heartstriker/22811] Shoot Bow
/cast [equipped:Badge_Of_The_Swarm_Guard nocooldown:Death_Wish] Death Wish;Bloodthirst
```

---

This addon allows you to use a small subset of the macro conditions, first introduced in the TBC expansion, in your 1.12.1 Vanilla client.

Demo videos:

[![Example Video](https://i9.ytimg.com/vi/xHTe4Df77MY/mq2.jpg?sqp=CJjhi5kG&rs=AOn4CLA0OYCKrr3Cj2p_ccYLYfUA_i9MOQ)](https://www.youtube.com/watch?v=xHTe4Df77MY)
[![Example Video2](https://i9.ytimg.com/vi/0w5nePeJlPU/mq2.jpg?sqp=CJjhi5kG&rs=AOn4CLBzPjcmu5zGYpT3vR5ieDvVyuE-iw)](https://www.youtube.com/watch?v=0w5nePeJlPU)

### Installation

- Make sure ClassicMouseover is not installed or disable it in the character select screen!
- [Download](https://github.com/DennisWG/Roid-Macros/archive/master.zip) the latest version of Roid Macros directly from the repository and extract it into your `WoW/Interface/AddOns/` folder.
- Rename `Roid-Macros-master` to `Roid-Macros`
- Run World of Warcraft and make sure to enable this addon in the character select screen

### Explanations and more information

For an in-depth explanation please visit [the documentation](https://denniswg.github.io/Roid-Macros/).

License
----

MIT
