# BUS-446
Tennis analytics
A <- c(96.27, 91.76, 95.37)
B <- c("Clay", "Grass", "Hard")
ggplot(WomanGS_df, aes(x=surface, y=minutes)) + stat_summary(fun.data=mean_sdl, geom="bar", fill="blue")

Our project is about different variables in tennis and analyzing them. We saw many of things like how height plays a role in the number of aces you hit and how types of surface does not affect how long the matches go on for. The goals for this porject was just to see some interesting stats about tennis and compare this to what we would think would happen as we are both tennis players and know a lot about the sport. 
That is the code for the bar chart and my other graphs were made in excel
