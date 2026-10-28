# Prvi koraci u terminalu

<!-- Ovo je početna verzija (v0) za projekt P1.
     Sve što je u [uglatim zagradama] zamijenite svojim tekstom.
     Očekivane rezultate prepišite sa SVOJEG zaslona, ne izmišljajte ih.
     Kad završite, ovaj komentar izbrišite. -->

Ovaj tutorial objašnjava osnovne naredbe terminala za pregled mapa, stvaranje datoteka i upravljanje njima. Za prolazak kroz upute potrebno je oko 10 minuta.
## Prije početka

- Radim na operacijskom sustavu Windows i koristim terminal u Visual Studio Codeu.
- Radim na operacijskom sustavu Windows i koristim terminal u Visual Studio Codeu.

## 1. Otvorite terminal

U izborniku **Terminal** odaberite **New Terminal**.

**Očekivani rezultat:** [Kako izgleda redak u kojem treperi pokazivač? Prepišite ga sa svojeg zaslona.]

## 2. Provjerite gdje se nalazite

```bash
pwd
```

**Očekivani rezultat:** [Prepišite ispis sa svojeg računala.]

## 3. Napravite mapu i uđite u nju

```bash
mkdir proba-terminala
cd proba-terminala
pwd
```

**Očekivani rezultat:** [Čime sada završava putanja?]

## 4. Napravite datoteku i upišite u nju tekst

```bash
echo "# Moje bilješke" > biljeske.md
cat biljeske.md
```

**Očekivani rezultat:** [Prepišite ispis.]

## 5. Dodajte još jedan redak

```bash
echo "- Naredba pwd ispisuje gdje se nalazim." >> biljeske.md
cat biljeske.md
```

**Očekivani rezultat:** [Prepišite ispis.]

Operator > zapisuje tekst u datoteku i pritom briše njezin prethodni sadržaj. Operator >> dodaje novi tekst na kraj datoteke, a postojeći sadržaj ostaje sačuvan.

## 6. Kopirajte, preimenujte i izbrišite datoteku

```bash
cp biljeske.md kopija.md
mv kopija.md stara.md
rm stara.md
ls
```

**Očekivani rezultat:** [Što ispiše `ls`?]

Prije korištenja naredbe rm provjerite naziv datoteke i jeste li u pravoj mapi jer se obrisana datoteka ne premješta u koš za smeće.

## Ako ne radi

| Poruka | Što znači | Što učiniti |
|---|---|---|
| `No such file or directory` | [Objasnite.] | [Objasnite.] |
| [Druga poruka koju ste vidjeli na vježbama] | [Objasnite.] | [Objasnite.] |

## Što dalje

Za dodatno učenje preporučujem službenu dokumentaciju za Git, u kojoj se mogu pronaći objašnjenja naredbi i primjeri rada s repozitorijima. Dostupna je na https://git-scm.com/doc.
