# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Gaussian Process regression for Empirical Dynamic Modeling Use fitGP (GPEDM) With (In) R Software
install.packages("remotes")
remotes::install_github("tanyalrogers/GPEDM")
library("GPEDM")
# Estimate Gaussian Process regression for Empirical Dynamic Modeling Use fitGP (GPEDM) With (In) R Software
fitGP = read.csv("https://raw.githubusercontent.com/timbulwidodostp/fitGP/main/fitGP/fitGP.csv",sep = ";")
fitGP = fitGP(data = fitGP, y = "Abundance", pop = "Population", E = 3, tau = 1, scaling = "local", predictmethod = "loo")
summary(fitGP)
# Gaussian Process regression for Empirical Dynamic Modeling Use fitGP (GPEDM) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished