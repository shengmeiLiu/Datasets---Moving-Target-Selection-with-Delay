# README

## PuckHunt

v1.4

This directory contains the data from studies on the effects of
latency on the action of selecting a target moving with kinematics.

Directories are:

+ *mouse* - studies done with the mouse.
+ *thumbstick* - studies done with the thumbstick.

The mouse studies have sub-directories for WPI (data gathered at
Worcester Polytechnic Institute) and Oslo (data gathered at Westerdals
School of Arts, Communication and Technology).  Each directory also
contains a "qualtrics" sub-directory with demographic information.

Files ending in `*.txt` have tab-delimited columns and files ending in
`*.csv` are comma-delimited.

For the game data, the fields are:

+ *Time* - when data was gathered
+ *Delay* - added delay (note - does *not* include local delay)
+ *Impulse* - force added to target (achieves a certain speed)
+ *Response* - the player's QoE rating (1-5 on screen, encoded as 0.0-1.0)
+ *Elapsed* -  elapsed time (time to select the target, in seconds)
+ *Clicks* - number of clicks taken to select target
+ *Mouse* - total mouse movement (pixels squared)

Note 1: the same Impulse values for the Oslo data had very different
target speeds than the WPI data.  We attribute this to the difference
in the game engine implementation on a Mac versus Windows.  See
[CER17] file for the actual target speeds.

Note 2: as specified above, the delays reported in the data files do
*not* include the local delays. The local delays were as follows:

    WPI mouse: 100 milliseconds  
    WPI thumbstick: 50 milliseconds  
    Oslo: 20 milliseconds

Note 3: For the Oslo dataset, the data for user41 was corrupted and
has been removed from the dataset.  User42 was ambidexstrous and has
two data files - a left and a right hand.

Note 4: For the Thumbstick dataset, the data for user49 was corrupted and
has been removed from the dataset.

Note 5: The "Response" column only contains real data once for every
combination of conditions. The other instances have a dummy value -1.


## References

[Clay18] Mark Claypool. "Game Input with Delay - Moving Target
Selection with a Game Controller Thumbstick", *ACM Transactions on
Multimedia Computing, Communications, and Applications (TOMM)*,
Special Issue on Delay-Sensitive Video Computing in the Cloud, Volume
14, Number 3, Article 57, <https://doi.org/10.1145/3187288>, June
2018. Online at: <http://www.cs.wpi.edu/~claypool/papers/delay-action-thumbstick/>

[CER17] Mark Claypool, Ragnhild Eg and Kjetil Raaen. "Modeling User
Performance for Moving Target Selection with a Delayed Mouse", In
*Proceedings of the 23rd International Conference on MultiMedia
Modeling (MMM)*, Reykjavik, Iceland, January 4-6, 2017. Online at:
<http://www.cs.wpi.edu/~claypool/papers/delay-action-mmm/>
