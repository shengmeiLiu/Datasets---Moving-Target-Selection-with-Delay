# README

## Motion 

v1.0

The directories are:

+ *game* - the objective game data.
+ *qoe* - the subjective QoE data.
+ *qualtrics* - the demographic data.

For the game data, the fields are:

+ *user_id*	- user id
+ *turn* - round	
+ *x_curs* - mouse x location (pixels)
+ *y_cursl*	- mouse y location (pixels)
+ *x_targ*n	- target x location (pixels)
+ *y_targ* - target y location (pixels)
+ *angle* - angle range when turning (in degrees)
+ *min_tim* - minimum time between turns (in milliseconds)
+ *lag* - amount of added delay (in milliseconds)
+ *dist* - pixel distance of target from mouse when clicked
+ *elapsed* - elapsed time (time to select the target, in milliseconds)
+ *targ_dist_trvl* - total pixel distance target traveled
+ *mouse_dist_trvl* - total pixel distance mouse traveled

## References

[CCG19] Mark Claypool, Andy Cockburn and Carl Gutwin. "Game Input with
Delay - Moving Target Selection Parameters", In *Proceedings of the
10th ACM Multimedia Systems Conference (MMSys)*, Amherst, MA, USA,
June 18-21, 2019. Online at:
http://www.cs.wpi.edu/~claypool/papers/delay-motion/

