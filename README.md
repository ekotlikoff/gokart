It would be great fun to make an online mario kart clone, lag compensation seems quite involved though. To do this right you need a simulation not only on the server, but also on the client, see the below (if you only simulate server side, clients are going to get input lag = latency to the server, e.g. easily 50ms and unacceptable).

Since I would want to make this a browser game that would mean running the client simulation in javascript, which raises the question of whether you run the server simulation in javascript as well or perform a lot of duplicate effort simulating both in javascript and your server language.

- https://www.reddit.com/r/gamedev/comments/1qyh87/physics_and_networking_how_best_to_avoid_utter/
- https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking
- http://web.cs.wpi.edu/~claypool/courses/4513-B03/papers/games/bernier.pdf
- https://gafferongames.com/post/networked_physics_2004/
