# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a binomial linear regression model Use blm With (In) R Software
install.packages("blm")
library("blm")
# Estimate Fit a binomial linear regression model Use blm With (In) R Software
blm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/blm/main/blm/blm.csv",sep = ";")
blm <- blm(blm ~ blm_1 + blm_2 + blm_3, data = blm)
logLik(blm)
summary(blm)
confint(blm)
# Fit a binomial linear regression model Use blm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished