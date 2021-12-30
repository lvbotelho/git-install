# git-install

#Instalar o Pacote usethis
install.packages("usethis")
library(usethis)

#se apresentar ao git
usethis::use_git_config(# Seu nome
  user.name = "Lais Botelho", 
  # Seu email
  user.email = "lvbotelho12@gmail.com")

#Abra o arquivo .Renviron usando a seguinte função:
usethis::edit_r_environ()
# * Edit 'C:/Users/beatr/Documents/.Renviron'
# * Restart R for changes to take effect

#Criar um novo token no GitHub:
usethis::create_github_token()

#escreve para usar o git
usethis::use_git()

#escreve para usar o github
usethis::use_github()
