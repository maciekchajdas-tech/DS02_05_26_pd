# DS02_05_26_pd
Kurs Data Science LearnIT - DS02-05-26
# 📚 Instrukcja oddawania prac domowych

## Struktura folderów

Każda praca domowa trafia do odpowiedniego folderu lekcji, w podfolderze nazwanym według schematu:

```
literaimienia_nazwisko_pd
```

**Przykład:** Anna Kowalska → `akowalska_pd`, Jan Nowak → `jnowak_pd`

```
prace_domowe/
└── lekcja_05/
    ├── akowalska_pd/
    │   └── praca_domowa.ipynb   # lub .py / .md
    └── jnowak_pd/
        └── praca_domowa.md
```

---

## Jak wrzucić pracę? (krok po kroku)

### 1. Zrób fork repozytorium

Wejdź na stronę repo i kliknij przycisk **Fork** (prawy górny róg).

```
https://github.com/michalszlapa/DS02_05_26_pd
```

---

### 2. Sklonuj swojego forka na komputer

```bash
git clone https://github.com/TWOJA_NAZWA/DS02_05_26_pd.git
cd DS02_05_26_pd
```

> Zamień `TWOJA_NAZWA` na swoją nazwę użytkownika GitHub.

---

### 3. Stwórz swój folder i wrzuć plik

Utwórz folder według schematu `literaimienia_nazwisko_pd` w folderze odpowiedniej lekcji, np.:

```
prace_domowe/lekcja_05/j_nowak_pd/
```

Wrzuć tam swój plik z rozwiązaniem (`.ipynb`, `.py` lub `.md`).

---

### 4. Zapisz zmiany (commit i push)

```bash
git add .
git commit -m "lekcja_05 - Jan Nowak"
git push
```

---

### 5. Otwórz Pull Request

1. Wejdź na GitHuba na swoje repozytorium (fork)
2. Kliknij **"Compare & pull request"**
3. Sprawdź, czy zmiany wyglądają poprawnie
4. Kliknij **"Create pull request"**

---

## ✅ Checklist przed wysłaniem

- [ ] Folder nazwany poprawnie: `literaimienia_nazwisko_pd` (małe litery, bez polskich znaków)
- [ ] Plik z rozwiązaniem jest w środku folderu
- [ ] Pull Request otwarty do głównego repo

---

## ❓ Pytania?

Zgłoś się do prowadzącego lub napisz na kanale kursu.
