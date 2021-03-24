# Cricket-analysis
 Looking at data from cricket matches using Python.
 
 ## Twenty20 cricket
 ### Do teams end up with double the runs that they have after 12 overs?
 
It's a common rule of thumb that teams tend to double their total score in the final eight overs of a 20-over game. This is because teams are likely to play more aggressively towards the end of their innings. To verify this, I found a [dataset](https://github.com/Chitaranjanpradhan/IPLIndian-Premier-League-Cricket-Ball-By-Ball-Cricket-Data) containing ball-by-ball data for every match of the first nine seasons of the Indian Premier League (IPL). I then looked at all the innings that lasted 20 overs and kept track of the point at which they reached half the final total. I then plotted out the results with a histogram showing the various points at which teams reached half their final score. The data seems to match the rule of thumb well: we can see a Gaussian centred near 12 or 13 overs with some finite distribution around it!
![](https://github.com/arnavprasad7/Cricket-analysis/blob/main/halfway_pts.jpg)

