# Blood-West-VR
VR Mod for Blood West


BLOOD WEST VR  -  VR mod for "Blood West" (Unity 2022.3, Mono x64, BepInEx 5)
==========================================================================
Version 0.1.12 (test build)

INSTALL
  1. zip into the game folder (merge). 
  2. Start your OpenXR runtime (SteamVR / Oculus / Virtual Desktop), then the game.
  
CONTROLS (the VR controllers are an Xbox gamepad - menus work with them as with a gamepad, no laser pointer)
-
    Right trigger = RT (attack / shoot)
  
    Left trigger = LT (aim / block)
  
    Right grip    = laser (in menus: RB) 
  
    Left grip    = LB (weapon wheel)
  
    Right stick down = RB (switch ammo type)
  
    Hold X 0.6 s = Start (inventory open / close); 
  
    tap X = X (use)
  
    A + B together = Back / View (pause menu)
  
  Use / pick up: point with the right controller (VR menu - Controls - "Use / pick up by pointing with")
  
  Right stick left / right = turn (snap\smooth)
  
  Menus / inventory: left stick = gamepad left stick, right stick = D-pad, the other buttons as on a gamepad
  
  Weapon wheel (hold LB = left grip): the right stick works as the game's own right stick (no turning)
  
  Both stick clicks: tap = re-centre view, 
  
  Both stick hold 1.2 s = VR settings menu

  Live adjust
  -
  Hold L3 (left stick click) and press (live adjusts; A = save, B = back to default when done):
    Y = this weapon
    
    X = weapon hand / arm
    
    B = free hand / arm
    
  Hold R3 (right stick click) and press Y = the laser of this weapon

  Swap option (VR menu - Controls - "Swap LT and the right grip

VR SETTINGS MENU (hold both stick clicks 1.2 s)
  Right stick up / down = choose, left / right = change, A = toggle / select, B = close. Saved at once.

6DOF WEAPON
  The weapon with the game's hands follows your controller and shoots where it points (bullets, bows, throws).
  Laser sight on guns / bows / throwables (rock, dynamite...): hold RB (LaserMode HoldRB / Always / Off).
  Melee weapons: a short laser along the blade, as long as the swing hits reach (MeleeLaser).
  The game's throw arc (dots + landing mark) is hidden (HideThrowArc).
  
  Adjust live - each one on its own (the weapon does not move with the arm, the arms not with the weapon):
  -
    hold L3 + press Y   - this weapon only (saved per weapon)
    
    hold L3 + press X   - your weapon hand / arm (saved for this weapon)
    
    hold L3 + press B   - your other (free) hand / arm (saved for this weapon)
    
    **[a weapon you have not adjusted yet starts with the hands you saved last]**
    
    Hold the OTHER controller's grip to grab it and move / turn it, A = save, B = back to default.
  Laser: hold R3 + press Y. Left stick = move the laser start left / right / up / down, right grip + left stick
  up / down = forward / back, right stick = aim it left / right / up / down. A = save (this weapon), B = default.
  Laser adjust live, per weapon: VR menu - "Laser of this weapon": aim up/down, left/right, start height / forward
  (saved for the weapon in your hand). Thickness, length, colour are for all weapons. The shots follow the laser.
  Hide the arms: VR menu - Weapon / hands - "hide the arms / hands".

MELEE
  Swing the controller: the blade hits what it touches (the game's own hit / damage / blood). The trigger still does
  the game's animated attack. VR menu - Melee: swing speed, blade length, time between swings.


