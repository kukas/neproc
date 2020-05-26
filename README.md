# Cvičení z neprocedurálního programování

Paralelka v úterý ve 12:20 v SW2, vede Jirka Balhar, email balhar.j@gmail.com

## Požadavky na zápočet

1. Domácí úkoly
    - měly by být spíš snazší, celkem 6, pro zápočet minimálně 2 z Prologu a 2 z Haskellu.
    - zadání budou na ReCodexu, přihlaste se a přidejte se do skupiny.
2. Aktivita v hodině
    - programování na projektor (za každou aktivitu bod, celkem byste měli nasbírat 5 bodů, 2 z Prologu, 2 z Haskellu)
    - pokud nechcete chodit na cviko, můžeme se domluvit na zkoušce nanečisto + trochu složitější zápočťák.
    - do ReCodexu přidám nějaké nepovinné domácí úkoly za body navíc.
3. Zápočťák
    - v Prologu nebo v Haskellu
    - zadání přibližně v polovině semestru, takže někdy v průběhu března. Domluvte se se mnou po mailu nebo po cvičení.
    - pro inspiraci na téma zápočťáku je seznam zadání na stránkách [Jana Hrice](http://kti.mff.cuni.cz/~hric/vyuka/pl_prikl_win.pdf) nebo [Tomáše Dvořáka](https://ksvi.mff.cuni.cz/~dvorak/vyuka/14/NPRG005x01/programy.html).
    - s programem je potřeba odevzdat i dokumentaci a testovací data spolu s příkazy/dotazy pro spuštění.
    - **na zkoušku je potřeba zápočet!**, nejlepší je tedy mít zápočet už na konci května.

## Materiály

- [Learn Prolog Now!](http://www.learnprolognow.org/) [LPN], zejména podle této učebnice budu učit první polovinu semestru. Jde najít i PDF verze.
- [Learn You a Haskell for Great Good](http://learnyouahaskell.com/)
- [Cvičení Martina Piláta](https://martinpilat.com/cs/neproceduralni-programovani) pro další příklady a pěkně sepsané základy.
- [Cvičení Adama Dingle](https://ksvi.mff.cuni.cz/~dingle/2019-20/npp/npp.html) anglická paralelka
- [Moodle předmětu](https://dl1.cuni.cz/course/view.php?id=5223), klíč dostanete na první přednášce. V informacích o předmětu je uvedená další literatura.
    - **zkouška bude zadávána přes Moodle**, takže je lepší se jako student zapsat do kurzu předmětu co nejdříve. Nebo alespoň před samotnou zkouškou.
## Nástroje

Jak si spustit Prolog/Haskell doma? Je tu víc možností:

- Nainstalovat: [SWI Prolog](https://www.swi-prolog.org/), [Haskell Platform](https://www.haskell.org/platform/)
- Spustit online: [online Prolog](https://swish.swi-prolog.org/), [Haskell](https://repl.it/languages/haskell)
- Můžete se taky připojit [SSHčkem k počítači v labu](https://kam.mff.cuni.cz/~stinovlas/unix/navody/pripojeni-do-labu) a pracovat vzdáleně.

K editaci souborů lze použít [Visual Studio Code](https://code.visualstudio.com/) s pluginy VSC-Prolog, Haskell Syntax Highlighting a Simple GHC (Haskell) Integration.

## Cvičení

- 18.2.: organizační info, základy Prologu na vztazích - viz LPN kapitola 1, vyhodocovač logických formulí.
- 25.2.: zopakování unifikace a hledání důkazů, Peanova aritmetika, cvičení rekurze - viz LPN kapitoly 2, 3.
- 3.3.: seznamy, akumulátor - viz LPN 4, 6.
- 10.3.: aritmetika, procvičování akumulátoru, operátor řezu, predikáty vyššího řádu (call)
- 24.3.: [zadání](./cvika/cv5_zadani.pl) - řez, rozdílové seznamy, stromy, dfs
- 31.3.: [zadání](./cvika/cv6_zadani.pl) - nedeterminismus, dfs, bfs, procházení stavového prostoru
- 7.4.: úvod do Haskellu, práce se seznamy a jednoduchými typy - viz LYAH kapitoly Introduction, Baby's first functions, An intro to lists, Tuples, Types and Typeclasses, Pattern matching, Guards, guards!
- 14.4.: [zadání](./cvika/cv8_zadani.hs) - procvičování rekurze a funkcí vyššího řádu, rozsahy a nekonečné seznamy. Viz LYAH Texas ranges, Recursion, Higher Order Functions. [Informace k debuggingu](https://downloads.haskell.org/~ghc/7.6.3/docs/html/users_guide/ghci-debugger.html)
- 21.4.: [zadání](./cvika/cv9_zadani.hs) - list comprehensions, nekonečné seznamy, vlastní typy. Viz LYAH Making Our Own Types and Typeclasses podkapitoly až po Recursive data structures.
- 28.4.: [zadání](./cvika/cv10_zadani.hs) - $, ., vlastní typy dokončení, stromy. Viz LYAH Making Our Own Types and Typeclasses podkapitoly až po Recursive data structures.
- 5.5.: [zadání](./cvika/cv11_zadani.hs) - typeclasses. Viz LYAH Making Our Own Types and Typeclasses: Typeclasses 102, A yes-no typeclass, The Functor typeclass, Kinds and some type-foo
- 15.5.: [zadání](./cvika/cv12_zadani.hs) - Kinds, Foldable, Functor znovu, začátek Applicative. Viz LYAH Kinds and some type-foo, Functors redux, Applicative functors
- 19.5.: [zadání](./cvika/cv13_zadani.hs) - Applicative Functor, Monády, IO. Viz LYAH Applicative functors, A Fistful of Monads
- 26.5.: [zadání](./cvika/cv14_zadani.hs) - Monády - Maybe, Either, IO, List, (v plánu bylo i State). Viz LYAH A Fistful of Monads, For a Few Monads More

## Body za aktivitu
| iniciály | 18.2. | 25.2. | 3.3. | 10.3. | DÚ 1 | bonus 1 | bonus 2 | DÚ 2 | DÚ 3 | **PROLOG** | 14.4. | bonus 1 | 21.4. | 28.4. | 5.5.  | 15.5. | 19.5. | 26.5. | bonus 2 | DÚ 1  | DÚ 2  | DÚ 3  | **HASKELL** | iniciály |
| -------- | ----- | ----- | ---- | ----- | ---- | ------- | ------- | ---- | ---- | ---------- | ----- | ------- | ----- | ----- | ----- | ----- | ----- | ----- | ------- | ----- | ----- | ----- | ----------- | -------- |
| LB       |       |       |      | *     | OK   | *       |         | OK   | OK   | **hotovo** |       | *       |       |       |       |       |       |       |         | OK*   | OK    |       | **hotovo**  | LB       |
| M.Bo.    |       |       | *    |       | OK   | *       | **      | OK   |      | **hotovo** |       | *       |       |       |       |       |       |       |         | OK    | OK    |       |             | M.Bo.    |
| M.Br     |       |       |      | *     | OK   |         | *       | 1/2  |      |            |       | *       |       |       |       |       |       |       |         | OK*   | OK    |       | **hotovo**  | M.Br     |
| MC       |       |       | *    | *     | OK   | *       | **      | OK   | OK   | **hotovo** |       |         | **    |       |       |       |       |       |         | OK*   | OK    |       | **hotovo**  | MC       |
| NG       | *     |       |      |       | OK   | *       | **      | OK   |      | **hotovo** | *     | *       | **    | *     | *     |       | *     | *     |         | OK*   | OK    |       | **hotovo**  | NG       |
| TGJ      |       |       | *    |       | OK   | *       |         | OK   |      | **hotovo** |       |         |       |       |       |       |       |       |         | OK*   | OK    |       |             | TGJ      |
| ZK       |       |       |      |       | OK   | *       |         |      | OK*  | **hotovo** |       | *       | *     |       |       |       |       |       |         |       |       |       |             | ZK       |
| SK       |       | *     |      |       |      |         |         |      |      |            |       |         |       |       |       |       |       |       |         |       |       |       |             | SK       |
| PM       |       |       | *    |       | OK   | *       |         | OK   | OK   | **hotovo** |       |         |       |       |       |       |       |       |         | OK    | OK    |       |             | PM       |
| VM       |       |       |      |       | OK   | *       |         |      |      |            |       |         |       |       |       |       |       |       |         |       |       |       |             | VM       |
| TLN      |       |       |      |       | OK   | *       |         | OK   | OK*  | **hotovo** |       |         |       |       |       |       |       |       |         | OK*   |       |       |             | TLN      |
| KN       | *     |       | *    | *     | OK   | *       | **      | OK   |      | **hotovo** | *     | *       |       | *     |       |       |       |       |         | OK    | OK    |       | **hotovo**  | KN       |
| JP       | *     |       |      | *     | OK   | **      |         | OK   |      | **hotovo** |       |         | **    | *     | *     | *     | *     |       |         | OK*   |       |       |             | JP       |
| DP       |       | *     | *    |       | OK   | *       | **      | OK   |      | **hotovo** |       | *       | *     |       |       |       |       |       |         | OK*   | OK    |       | **hotovo**  | DP       |
| KP       |       |       |      | *     | OK   | *       | **      | OK   | OK   | **hotovo** |       | *       | *     | **    | **    | **    | *     |       |         | OK*   | OK    |       | **hotovo**  | KP       |
| DR       |       |       |      |       | OK   | *       | *       |      |      |            |       |         |       |       |       |       |       |       |         |       |       |       |             | DR       |
| JŠ       |       |       |      |       | OK   | *       | **      | OK   |      | **hotovo** |       | *       |       |       |       |       |       |       |         | OK*   | OK    |       | **hotovo**  | JŠ       |
| SU       | *     | *     |      | *     | OK   |         |         |      | OK   | **hotovo** |       |         |       | **    |       |       |       |       |         | OK    |       |       |             | SU       |
| JU       |       |       |      |       | OK   | *       | *       |      | OK*  | **hotovo** |       |         |       |       |       |       |       |       |         | OK*   | OK    |       |             | JU       |
| MV       | *     |       |      |       | OK   | *       | **      | OK   | OK   | **hotovo** |       |         |       |       |       |       |       |       |         | OK*   | OK    |       |             | MV       |
| KŽ       | *     | *     |      |       | OK   | *       |         |      |      |            |       | *       |       |       |       |       |       |       |         |       |       |       |             | KŽ       |
