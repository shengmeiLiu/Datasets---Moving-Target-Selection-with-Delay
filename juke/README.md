# README

## Motion 

v1.3

This directory contains the data from studies on the effects of
latency on the action of selecting a target moving with force-based
physics.  It uses a game called "Juke!".

The directories are:

+ *game* - the objective game data.
+ *qoe* - the subjective QoE data.
+ *qualtrics* - the demographic data.

For the game data, the fields are:

+ *user_id* - user id
+ *turn* - game round	
+ *x_curs* - mouse x location (pixels)
+ *y_cursl* - mouse y location (pixels)
+ *x_targ*n - target x location (pixels)
+ *y_targ* - target y location (pixels)
+ *angle* - angle range when turning (in degrees)
+ *min_tim* - minimum time between turns (in milliseconds)
+ *lag* - amount of added delay (in milliseconds)
+ *dist* - pixel distance of target from mouse when clicked
+ *elapsed* - elapsed time (time to select the target, in milliseconds)
+ *targ_dist_trvl* - total pixel distance target traveled
+ *mouse_dist_trvl* - total pixel distance mouse traveled

Note: the delays reported in the data files ("lag" above) do *not*
include the local delays. The local delays were 50 milliseconds.

## References

[CCG20] Mark Claypool, Andy Cockburn and Carl Gutwin. "The Impact of
Motion and Delay on Selecting Game Targets with a Mouse", *ACM
Transactions on Multimedia, Computing, Communinication and
Applications (TOMM)*, Volume 16, Number 2s, Article 73,
<https://doi.org/10.1145/3390464> May 2020. Online at:
<http://www.cs.wpi.edu/~claypool/papers/delay-motion-tomm/>

[CCG19] Mark Claypool, Andy Cockburn and Carl Gutwin. "Game Input with
Delay - Moving Target Selection Parameters", In *Proceedings of the
10th ACM Multimedia Systems Conference (MMSys)*, Amherst, MA, USA,
June 18-21, 2019. Online at:
<http://www.cs.wpi.edu/~claypool/papers/delay-motion/>

