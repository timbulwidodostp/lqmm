# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Linear Quantile Mixed Models Use lqmm With (In) R Software
# Mixed-effects Quantile regression Use lqmm With (In) R Software
install.packages("lqmm")
library("lqmm")
lqmm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/lqmm/main/lqmm/lqmm.csv",sep = ";")
# Estimation 
# Linear Quantile Mixed Models Use lqmm With (In) R Software
# Mixed-effects Quantile regression Use lqmm With (In) R Software
lqmm <- lqmm(y ~ prog + month + inter, random = ~ 1, group = month, tau = c(0.1, 0.5, 0.9), data = lqmm)
summary(lqmm)
# Linear Quantile Mixed Models Use lqmm With (In) R Software
# Mixed-effects Quantile regression Use lqmm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished