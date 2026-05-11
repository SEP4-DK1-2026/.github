# Git standarder for SEP4

## Branches & commit beskeder

* **Alle branch-navne og commit-beskeder skal skrives på engelsk.**

---

## Repository struktur

* Hver hovedapplikation har sit eget repository:

  * `IoT`
  * `MAL`
  * `WEB`

* Ekstra utility applikationer, microservices mm. har også deres egne repositories (f.eks. `WEB-microservice`)
---

## Pull requests & reviews

* Når et medlem af en subgruppe opretter en pull request:

  * Skal **et andet medlem af samme subgruppe** reviewe den.

---

## Branch navngivning

* Alle branches skal starte med en kategori:

### Tilladte kategorier:

* `feature` – tilføjelse, refactoring eller fjernelse af funktionalitet
* `bugfix` – fejlrettelser
* `test` – tilføjelse eller ændring af tests (unit tests, integration tests osv.)

### Format:

```
<kategori>/<kort-beskrivelse>
```

### Eksempler:

```
feature/add-home-button
bugfix/broken-home-button
test/add-login-tests
```

---

## Commit beskeder

* Følg standarderne beskrevet i denne guide:

[https://cbea.ms/git-commit/](https://cbea.ms/git-commit/)

---
