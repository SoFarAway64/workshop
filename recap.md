RECAP CI/CD, Github Actions & Dependabot
========================================

## 🔗 CI/CD – Was ist das & warum ist es wichtig?

CI = Continuous Integration
➡️ Ziel: Sicherstellen, dass neuer Code sofort automatisch getestet wird.

👉 Jeder Push/Commit triggert automatisierte Abläufe:

Build (wird der Code überhaupt kompiliert?)
Tests (laufen alle Unit- oder Integrationstests?)
Linting (ist der Code sauber formatiert?)
Security-Checks (hat der Code bekannte Schwachstellen?)
✅ Vorteil: Fehler im Code werden früh entdeckt – bevor sie sich anhäufen.

CD = Continuous Delivery / Deployment
➡️ Ziel: Den geprüften Code automatisch ausliefern – bis in Produktion.

Continuous Delivery: Code wird automatisch in eine Staging-/Test-Umgebung deployed.
Continuous Deployment: Code wird direkt in Produktion gebracht (ohne manuelle Freigabe).
✅ Vorteil: Änderungen kommen schneller live – keine manuellen Release-Prozesse mehr.

------------------------------------------------
## GitHub Actions – Was ist das?

CI/CD-Plattform von GitHub direkt integriert im Repo.

Anwendung/Vorteile:
-> Automatisch Builds, Tests und Deployments auslösen.
-> Beliebige Skripte oder Tools ausführen.
-> Andere Dienste anbinden (Slack, Discord, AWS, Docker Hub, etc.).

✅ Vorteil: Keine extra CI/CD-Software nötig – alles direkt in GitHub.

------------------------------------------------
## Dependabot – Warum und wofür?

Dependabot scannt deine Projektabhängigkeiten (z. B. package.json, Dockerfile oder requirements.txt).
Wenn es Updates gibt (z. B. Sicherheitsfixes oder neue Versionen), erstellt Dependabot automatisch Pull Requests.
Du kannst die Updates prüfen, mergen und bleibst immer auf aktuellem Stand.
