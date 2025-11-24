# Procédure : Création d’un utilisateur Active Directory

## Objectif
Créer un nouvel utilisateur dans Active Directory et préparer son compte pour l’intégration au poste de travail.

## Pré-requis
- Rôle AD DS installé  
- Droits helpdesk ou admin délégués  

## Étapes
1. Ouvrir **Active Directory Users and Computers (ADUC)**  
2. Aller dans l’OU : `LAB_Users`  
3. Clic droit → **New → User**  
4. Renseigner :
   - Prénom  
   - Nom  
   - SamAccountName  
5. Définir le mot de passe temporaire  
6. Cocher **User must change password at next logon**  
7. Valider  
8. Ajouter l’utilisateur dans les groupes nécessaires (ex : `GG_LAB_Users`)

## Vérifications
- L’utilisateur apparaît dans l’OU  
- Le compte est activé  
- Les bons groupes sont appliqués
