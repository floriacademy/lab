# Comment contribuer

## Etape 1 : Forkez

Cliquez sur le bouton "Fork" en haut a droite de cette page.

## Etape 2 : Clonez votre fork

```bash
git clone https://github.com/<votre-username>/lab.git
cd lab
```

## Etape 3 : Creez votre projet

```bash
mkdir -p talents/<votre-username>/<nom-projet>/src
cp -r templates/starter-project/* talents/<votre-username>/<nom-projet>/
```

## Etape 4 : Developpez

- Ecrivez votre code dans `src/`
- Ajoutez des tests dans `tests/`
- Completez le `README.md` avec :
  - Description du projet
  - Comment l'installer et le lancer
  - Technologies utilisees
  - Ce que vous avez appris

## Etape 5 : Commitez et pushez

```bash
git add .
git commit -m "feat: <nom-projet> - <description courte>"
git push origin main
```

## Etape 6 : Ouvrez une Pull Request

1. Allez sur votre fork sur GitHub
2. Cliquez "Contribute" > "Open pull request"
3. Decrivez votre projet dans la PR
4. L'IA mentor evaluera votre code automatiquement

## Regles

- Un seul projet par Pull Request
- Votre code doit builder sans erreur
- Pas de secrets, cles API ou mots de passe dans le code
- README obligatoire
- Respect du Code de Conduite
