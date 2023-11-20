# Oefening

**Doelstelling**:
Deelnemen aan een samenwerkingsproject waarbij teamleden hun persoonlijke informatie toevoegen aan een notebook binnen een Databricks-omgeving, geïntegreerd met een GitHub-repository voor versiebeheer en samenwerking.

**Projectcasus**:
Elk teamlid voegt zijn of haar naam, GitHub-gebruikersnaam en afdeling (PNL) toe aan een gezamenlijk notebook in Databricks.

**Voorbereiding**:
Verdeel in teams van 3-4 personen. Wijs rollen toe:

**Release Managers (Martijn/Sussanne/Jasper)**:

- Maak een nieuwe openbare GitHub-repository aan, genaamd "TeamInfoProject".
- Voeg een README.md-bestand toe met een deze tekst.
- Maak een nieuw notebook in Databricks binnen de "TeamInfoProject" repository.
- Deel de URL van de repository met het team.
  
**Specialist 1, 2 en 3**:

- Accepteer de uitnodiging voor samenwerking aan de repository.
- Kloon de "TeamInfoProject" repository in hun Databricks-werkruimte.
- Voeg hun naam, GitHub-gebruikersnaam en afdeling toe aan hetzelfde notebook, onder de gegevens van de Release Manager.
- Commit en push de wijzigingen naar de GitHub-repository.

**Gebruik deze format om de informatie toe te voegen aan de notebooks**:
    name: "NAME_HERE" 
    github username: "USERNAME_HERE"
    email: "MAIL_HERE" 
    department: "DEPARTMENT_HERE" 

-------------------------------------------------------------------------------------------------------------------------------------------------
# Stappen van de Oefening

**1. Release Managers (Martijn/Susanna/Jasper):**
   - Voeg alle teamleden toe als medewerkers aan de GitHub-repository.
   - Link in Databricks de werkruimte aan de aangemaakte repository (via Repos).
   - Deel de URL van de repository met je groep.

**2. Alle Specialisten:**
   - Accepteer de uitnodiging voor samenwerking aan de repository.
   - Kloon de repository in hun Databricks-werkruimte via Repos.

**3. Specialist 1 (Persoonlijke Informatie Toevoegen):**
   - Maak in Databricks een nieuwe branch aan, genaamd 'personal-info-1'.
   - Maak een nieuw notebook in deze branch, voeg je naam, GitHub-gebruikersnaam en afdeling (PNL) toe.
   - Commit en push het notebook naar de 'personal-info-1' branch met behulp van Databricks' Git-functies.
   - Gebruik Databricks om een pull request te initiëren voor het mergen van 'personal-info-1' naar de hoofdbranch.

**4. Specialist 2 (Persoonlijke Informatie Toevoegen):**
   - Wacht tot 'personal-info-1' is gemerged.
   - Maak een nieuwe branch 'personal-info-2', voeg je informatie toe aan het notebook.
   - Commit en push naar 'personal-info-2'.
   - Initieer via Databricks een pull request voor het mergen naar de hoofdbranch.

**5. Specialist 3 (Persoonlijke Informatie Toevoegen):**
   - Wacht tot 'personal-info-2' is gemerged.
   - Maak een nieuwe branch 'personal-info-3', voeg je informatie toe.
   - Commit en push naar 'personal-info-3'.
   - Initieer een pull request via Databricks.

**6. Release Manager:**
   - Review en merge pull requests sequentieel in Databricks: 'personal-info-1', 'personal-info-2', 'personal-info-3'.
   - Zorg voor correcte integratie en los merge-conflicten op.

**Belangrijke Opmerkingen:**
   - Communicatie en coördinatie zijn essentieel.
   - Wacht op de merge van voorgaande branches voordat je verdergaat met afhankelijke taken om conflicten te voorkomen en consistentie te   garanderen.



