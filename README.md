# hello-world
My first Repository. Just to learn


#
#
#

cat("\014")   #Limpa o console
rm(list=ls()) #Limpa a memória

x2 <- seq(from = 6.5, to = 7.5, by = 1.0e-3)

#
# Plotagem da Funcao Acumulada
#

result2 <- pnorm(x2, mean = 6.957755, sd = 0.075)

plot(x2,result2)
grid()

result3 <- pnorm(6.897705, mean = 6.957755, sd = 0.075)

# It's a little better to use cat() instead of print(), as the latter can print
# only one expression and its output is numbered, which may be a nuisance.

cat("\n")
cat("Resposta em % = ", result3*100, "\n")
cat("\n")


