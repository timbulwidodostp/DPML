# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Dynamic panel model with fixed effects Use DPML (DPTM) With (In) R Software
install.packages("DPTM")
library("DPTM")
DPML = read.csv("https://raw.githubusercontent.com/timbulwidodostp/DPML/main/DPML/DPML.csv",sep = ";")
# Estimation Dynamic panel model with fixed effects Use DPML (DPTM) With (In) R Software
# No time fixed effects
DPML_1 <- DPML(DPML ~ DPML_1 + DPML_2, data = DPML, index = c('DPML_3','DPML_4'))
DPML_1
# With time fixed effects
DPML_2 <- DPML(DPML ~ DPML_1 + DPML_2, data = DPML, index = c('DPML_3','DPML_4'), timeFE = TRUE)
DPML_2
# Dynamic panel model with fixed effects Use DPML (DPTM) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished