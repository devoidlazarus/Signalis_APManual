# Rotfront Flesh Walls

Whenever tarot card Items are picked up within the Rotfront level, upon exiting the room, the room will eventually be closed off by a wall of flesh and unable to be reentered. This can prevent certain locations from being accessed if they are not checked before the wall of flesh forms.

Fortunately, through the debug console, the `goto` command can be used to teleport between rooms, bypassing the flesh walls. Below is the list of tarot cards Items that trigger walls of flesh, the rooms they are located in, and the commands needed to get in/out of the room:

| Item | Rooms Blocked Off | Entry Command | Exit Command |
| --- | --- | --- | --- |
| Lovers | Dormitory | goto Student Dorms | goto Blockwart Corridor |
| Star | Hospital Room, Hospital Hallway, Apartment | goto Hospital Hallway | goto Atrium; goto Clothesline Hallway; goto Apartment Corridor |
| Sun | Packstation, Photo Store | goto Packstation; goto Photostore | goto Metro Station; goto Cables Corridor |
| Death | Commercial Corridor, Backyard, Backroom, Bookstore | goto Commercial Corridor; goto Backyard; goto Backroom; goto Book Store | goto Lobby; goto Space Between Walls |
| Moon | Butterfly Room | goto Butterfly Apartment | goto Clothesline Hallway |
| Tower |  |  |  |
