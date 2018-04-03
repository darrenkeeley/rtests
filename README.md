# rtests
These are all the statistical tests/models we did in SAS class, 6304 and 6305.

A link to the markdown-rendered version: https://rpubs.com/DarrenKeeley/rtests

A couple notes:
+ The way I was able to replicate the F tests for Random/Mixed Effect models is not ideal. It involves calculating the F tests by manually dividing the mean square by the interaction term. So you'll have to look up the calculation of the model's MS's in the textbook (or SAS!). It's not great, but it'll have to do for now!
+ I haven't explored the HOV test completely. The only example is with a simple Fixed Effect model. However, I asked Prof Zhou about it, and she said when model complexity increases, the HOV is not worth calculating and that a residual plot will suffice in ensuring our assumptions are met.
