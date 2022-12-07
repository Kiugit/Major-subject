# Major-subject in R
Major subject in university


  
  student %>% ggplot(aes(x=`50m달리기(초)`, y=`멀리뛰기(CM)`)) +
  geom_point(shape=21, color="black", fill="#69b3a2", size=10) +
  geom_smooth(method = lm, formula = y ~ x, se=F) +
  theme_ipsum() +
  ggtitle("멀리뛰기와 50m달리기")
