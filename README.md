HeroesHUD
=========

Just a tweaked stock HUD specifically targeted at the MLP Heroes mod for TF2

Pick your game's aspect ratio and throw the entire folder into your /tf/custom folder

If you want to use the HUD crosshairs, open /scripts/hudlayout.res with a text editor and change "visible" for CrossHairKonrWingsOutline OR OtherCrossHairs to "1".
In OtherCrossHairs, changing the labelText will change the crosshair. Look at the image in /resource/fonts for a guide.
After that, you may have to mess with the xpos and ypos to get it centered. crosshair 0 in your console/autoexec.cfg should remove the default crosshair from the game.
Animations are set up for the crosshairs, just open /scripts/hudanimations_tf.txt and search for damagedplayer and remove the // from the crosshair you're using.
Crosshair color can be chaged in /resource/clientscheme.res. Just look for crosshaircolor and change to the desired RGBA value.