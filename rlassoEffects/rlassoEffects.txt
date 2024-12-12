# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Rigorous Lasso for Linear Models: Inference Use rlassoEffects (hdm) With (In) R Software
install.packages("hdm")
install.packages("ggplot2")
library("hdm")
library("ggplot2")
rlassoEffects = read.csv("https://raw.githubusercontent.com/timbulwidodostp/rlassoEffects/main/rlassoEffects/rlassoEffects.csv",sep = ";")
# Estimation Rigorous Lasso for Linear Models: Inference Use rlassoEffects (hdm) With (In) R Software
lasso.effect = rlassoEffects(I = ~ X1 + X2 + X3, data=rlassoEffects)
print(lasso.effect)
summary(lasso.effect)
confint(lasso.effect)
# Rigorous Lasso for Linear Models: Inference Use rlassoEffects (hdm) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished