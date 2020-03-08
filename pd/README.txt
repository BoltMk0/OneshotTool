ONESHOT TOOL;;

TO CREATE A NEW OBJECT;
Make sure you're in edit mode "Edit -> Edit mode".;
click "Put -> Object" (Ctl + 1) and place it anywhere in the window. Then type the object parameters using the convention:;

"<objtype> <objid>";

Where <objid> is an integer identifier unique to the object group (i.e. you can have "bgm 1" and "sfx 1" but not two "bgm 1"s).;
And<objtype> is one of the following:;

1) "bgm";
Made for background music. bgm sounds will loop continuously until told to stop and do not have FX sends.;

2) "sfx";
Sound effects component. One-shot player with 3 voices and FX sends.;

3) "env";
Accoustic environment. FX sends go to these, and only one is active at a time (will fade between).;

To edit parameters either hold down ctl (to bring out of edit mode) or toggle edit mode off by going to "Edit -> edit mode".
 