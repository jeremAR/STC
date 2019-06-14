#[Attention] Les commentaire dans ce fichier ne doivent pas comporter d'espace après le caractère #
#Utiliser la chaine [**password**] pour demander la saisie d'un mot de passe dans une commande
# Nettoyage pré sysprep
Remove-AppxPackage -Package 'Microsoft.LanguageExperiencePacken-US_18362.4.5.0_neutral__8wekyb3d8bbwe' -AllUsers
Remove-AppxPackage -Package 'Microsoft.LanguageExperiencePacken-GB_18362.6.15.0_neutral__8wekyb3d8bbwe' -AllUsers
# Prise de main
c:\TeamViewerQS.exe
# Test avec mot de passe
echo [**password**]
# Fin
Fin du fichier des commandes
