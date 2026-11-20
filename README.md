# Jestřáb

Český Agent Skill pro stručnou, hravou řeč inspirovanou postavami Jaroslava Foglara. Název odkazuje na Foglarovu skautskou přezdívku. [Životopis Jaroslava Foglara](https://www.spjf.cz/jaroslav-foglar)

> Ježkovy oči! Oba exporty končí ve stejném souboru. Druhý přepíše první.

## Instalace

V projektu, kde chceš Jestřába používat, spusť s Node.js a npm jeden z těchto příkazů. Po úspěšné instalaci se v terminálu rovnou vypíše vlajka.

**Codex**

```sh
npx skills add Alcariss/jestrab@v0.1.0 --skill jestrab -a codex -y &&
  cat .agents/skills/jestrab/assets/vlajka.txt
```

**Claude Code**

```sh
npx skills add Alcariss/jestrab@v0.1.0 --skill jestrab -a claude-code -y &&
  cat .claude/skills/jestrab/assets/vlajka.txt
```

Při ruční instalaci zkopíruj celou složku [skills/jestrab](skills/jestrab) do `.agents/skills/` pro Codex nebo `.claude/skills/` pro Claude Code.

## Použití

Otevři novou relaci. V Codexu použij `$jestrab`, v Claude Code `/jestrab`, případně napiš „Zapni režim Jestřáb.“

- **Blesk** — jedna až dvě krátké věty.
- **Komiks** — výchozí režim pro běžnou práci.
- **Klubovna** — krátké odstavce pro vysvětlení souvislostí.

Napiš třeba „Přepni na blesk“ nebo „Ukaž vlajku Rychlých šípů“. Po ověřeném milníku se terminálová vlajka může objevit i sama. „Stop Jestřáb“ vrátí běžný styl.

## Licence

Vlastní text skillu a jeho příklady jsou pod [licencí MIT](LICENSE). Původ obratů uvádí [jazykový tahák](skills/jestrab/references/obraty.md).
