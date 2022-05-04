# Schéma des données d’impact d’un service numérique public

Ce schéma a été créé pour la publication de statistiques d'impact et/ou d'usage des services numériques publics, Startups d'Etat et des Territoires. 

## Documentation

- [Obligatoire] nom_service_numerique : Nom de la startup (String) : validateur de l’identifiant sur beta.gouv.fr (implémenter custom check sur Validata)
- [Obigatoire] objectif : objectif que cherche à mesurer l’indicateur

## Description de l’indicateur

- [Obligatoire] indicateur : Intitulé de l’indicateur
- [Obligatoire] unite_mesure : %, jours, ….
- [Obligatoire] periodicite : Fréquence de calcul, de collecte ou de parution de l’indicateur - Liste : Annuel, Semestriel, Trimestriel, Mensuel, Hebodmadaire, Quotidien
- [Obligatoire] periode : periode se réfère la mesure (YYYY-MM-DD), pour annuel indiquer 2020-12-31, mois le dernier jour du mois.
- mode_collecte: Automatisé ; comptages manuels, enquêtes, etc. (préciser les modalités)
- mode_calcul: Façon dont est calculé ou agrégé l’indicateur à partir des données de base (ex : formule paramétrique ou pondération des données locales), en distinguant dans le cas d’un ratio, le numérateur et le dénominateur. Si nécessaire, fournir un exemple de calcul.

## Modalités d’interprétation de l’indicateur

- limites: Préciser les limites et biais connus et justifier le choix de l’indicateur malgré ses limites
- modalites_interpretation: Si nécessaire, préciser la signification, les modalités de lecture et de compréhension de l’indicateur
- sens_evolution : Sens d’évolution souhaité (A la hausse / à la baisse)

