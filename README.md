

## Meta

Hvala [ul-fmf/mathematics-in-ljubljana](https://github.com/ul-fmf/mathematics-in-ljubljana/).

## Format spletne strani

Uporabljamo [Jekyll](https://jekyllrb.com) za generiranje spletnih strain iz `Markdown` datotek.
To je format, v katerem je napisano tudi to besedilo, ki ga berete.
Več informacij: [tukaj]((https://guides.github.com/features/mastering-markdown/)).

Uporabljamo [YAMT theme](http://jekyllthemes.org/themes/jekyll-yamt/) kot šminko (ang. _lipstick_).
Kot strežnik uporabljamo [GitHub pages](https://guides.github.com/features/pages/).

Povezava do spletne strani: [https://ul-fmf.github.io/olmu/](https://ul-fmf.github.io/olmu/).

## Dodajanje in urejanje vsebine

Lahko to naredite tu (na githubu) ali pa lokalno. V mapi `_posts` dodajte novo datoteko ali pa uredite obstoječo.

Datoteke morajo biti oblike `yyyy-mm-dd-naslov.md`, kjer je `y` števka v letu, `m` števka v mesecu in `d` števka v dnevu.
Primeri datotek (tudi z večbesednimi naslovi) so že v mapi.

Datoteke uredite v skladu s navodili v testnih datotekah (npr. testnim člankom, testnim sodelovanjem ...).


## Lokalno razvijanje

Razvijanje poteka na osebnem računalniku (namesto na githubu) precej hitreje in skrito pred očmi javnosti.
Ko klonirate repozitorij in namestite [Jekyll](https://jekyllrb.com) (navodila spodaj), postopate tako v ukazni vrstici:

```
> bundle istall
> bundle exec jekyll build
> bundle exec jekyll serve
```

Pojdite na naslov, ki vam ga sporoči Jekyll - verjetno bo to [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

## Namestitev Jekylla

Uradna navodila se nehajajo [tukaj](https://jekyllrb.com/docs/installation/).
Če ne uporabljate Windowsov, jim sledite.

Če jih, je najlažje 
- namestiti [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install)
oz. [virtualko](https://www.virtualbox.org/), s čimer na računalnik dobite Linux (v neki obliki)
- slediti uradnim navodilom za namestitev Jekylla za Linux

Če tega ne morete, poskusite slediti navodilom za Windows.
