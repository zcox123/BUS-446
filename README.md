# BUS-446
Tennis analytics
A <- c(96.27, 91.76, 95.37)
B <- c("Clay", "Grass", "Hard")
ggplot(WomanGS_df, aes(x=surface, y=minutes)) + stat_summary(fun.data=mean_sdl, geom="bar", fill="blue")
