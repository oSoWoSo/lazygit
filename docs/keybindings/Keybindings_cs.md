_This file is auto-generated. To update, make the changes in the pkg/i18n directory and then run `go generate ./...` from the project root._

# Lazygit Klávesové zkratky

_Legenda: `<c-b>` znamená ctrl+b, `<a-b>` znamená alt+b, `B` znamená Shift+b_

## Globální klávesové zkratky

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-r> `` | Přepnout na poslední úložiště |  |
| `` <pgup> (fn+up/shift+k) `` | Posuňte hlavní okno nahoru |  |
| `` <pgdown> (fn+down/shift+j) `` | Přejděte dolů v hlavním okně |  |
| `` @ `` | Zobrazit možnosti protokolu příkazů | Zobrazit možnosti pro protokol příkazů, např. zobrazit/skrýt protokol příkazů a zaměřit se na protokol příkazů. |
| `` P `` | Vystrčit | Přesuňte aktuální větev do její nadřazené větve. Pokud není nakonfigurována žádná nadřazená větev, budete vyzváni ke konfiguraci nadřazené větve. |
| `` p `` | SEM | Vytáhněte změny ze vzdáleného pro aktuální větev. Pokud není nakonfigurována žádná nadřazená větev, budete vyzváni ke konfiguraci nadřazené větve. |
| `` ) `` | Increase rename similarity threshold | Increase the similarity threshold for a deletion and addition pair to be treated as a rename. |
| `` ( `` | Decrease rename similarity threshold | Decrease the similarity threshold for a deletion and addition pair to be treated as a rename. |
| `` } `` | Zvětšete velikost kontextu v zobrazení rozdílu | Zvyšte množství kontextu zobrazeného kolem změn v zobrazení rozdílu. |
| `` { `` | Zmenšete velikost kontextu v zobrazení rozdílu | Snižte množství kontextu zobrazeného kolem změn v pohledu rozdílu. |
| `` : `` | Execute shell command | Bring up a prompt where you can enter a shell command to execute. |
| `` <c-p> `` | Zobrazit možnosti vlastní opravy |  |
| `` m `` | Zobrazit možnosti sloučení/rebase | Zobrazit možnosti pro přerušení/pokračování/přeskočení aktuálního sloučení/rebase. |
| `` R `` | Obnovit | Obnovte stav git (tj. spusťte `git status`, `git branch` atd. na pozadí, abyste aktualizovali obsah panelů). Toto nespustí `git fetch`. |
| `` + `` | Režim další obrazovky (normální/polovina plná/celá obrazovka) |  |
| `` _ `` | Předchozí režim obrazovky |  |
| `` ? `` | Otevřete nabídku klávesových zkratek |  |
| `` <c-s> `` | Zobrazit možnosti filtru | Zobrazit možnosti filtrování protokolu potvrzení pro zobrazení pouze potvrzení, která odpovídají filtru. |
| `` W `` | Zobrazit možnosti diferenciace | Zobrazit možnosti pro odlišení dvou odkazů, např. diferencování od vybrané reference, zavedení reference do diferencování a obrácení směru rozdílů. |
| `` <c-e> `` | Zobrazit možnosti diferenciace | Zobrazit možnosti pro odlišení dvou odkazů, např. diferencování od vybrané reference, zavedení reference do diferencování a obrácení směru rozdílů. |
| `` q `` | Výstup |  |
| `` <esc> `` | Zrušit |  |
| `` <c-w> `` | Přepnout mezery | Přepněte, zda se změny mezer zobrazí v rozdílovém zobrazení. |
| `` z `` | Vrátit zpět | Reflog se použije k určení, jaký příkaz git spustit, aby se vrátil poslední příkaz git. To nezahrnuje změny pracovního stromu; berou se v úvahu pouze závazky. |
| `` <c-z> `` | Předělat | Reflog se použije k určení, jaký příkaz git spustit, aby se opakoval poslední příkaz git. To nezahrnuje změny pracovního stromu; berou se v úvahu pouze závazky. |

## Navigace v panelu seznamu

| Key | Action | Info |
|-----|--------|-------------|
| `` , `` | Předchozí stránka |  |
| `` . `` | Další stránka |  |
| `` < (<home>) `` | Přejděte nahoru |  |
| `` > (<end>) `` | Přejděte dolů |  |
| `` v `` | Přepnout výběr rozsahu |  |
| `` <s-down> `` | Vyberte rozsah dolů |  |
| `` <s-up> `` | Vyberte rozsah nahoru |  |
| `` / `` | Hledat aktuální zobrazení podle textu |  |
| `` H `` | Přejděte doleva |  |
| `` L `` | Přejděte doprava |  |
| `` ] `` | Další karta |  |
| `` [ `` | Předchozí karta |  |

## Commit Summary

| Key | Action | Info |
|-----|--------|-------------|
| `` <enter> `` | Potvrdit |  |
| `` <esc> `` | Blízko |  |

## Hlavní panel (normální)

| Key | Action | Info |
|-----|--------|-------------|
| `` mouse wheel down (fn+up) `` | Přejděte dolů |  |
| `` mouse wheel up (fn+down) `` | Přejděte nahoru |  |

## Hlavní panel (schválení)

| Key | Action | Info |
|-----|--------|-------------|
| `` <left> `` | Přejít na předchozí fragment |  |
| `` <right> `` | Přejít na další fragment |  |
| `` v `` | Přepnout výběr rozsahu |  |
| `` a `` | Zvýrazněte fragment | Přepnout režim výběru fragmentu. |
| `` <c-o> `` | Zkopírovat vybraný text do schránky |  |
| `` <space> `` | Potvrdit | Přepnout schválený/neschválený výběr. |
| `` d `` | Odmítnout | Když je vybrána nepotvrzená změna, zrušte ji pomocí `git reset`. Když je vybrána potvrzená změna, zrušte potvrzení. |
| `` o `` | Otevřít soubor | Otevřete soubor ve výchozí aplikaci. |
| `` e `` | Upravit soubor | Otevřete soubor v externím editoru. |
| `` <esc> `` | Návrat na panel souborů |  |
| `` <tab> `` | Přepnout zobrazení | Přepnout do jiného zobrazení (potvrzené/nepotvrzené změny). |
| `` E `` | Upravit fragment | Upravte vybraný fragment v externím editoru. |
| `` c `` | Commit | Potvrdit změny schváleny. |
| `` w `` | Potvrdit změny bez háčku předběžného potvrzení |  |
| `` C `` | Potvrďte změny pomocí editoru git |  |
| `` <c-f> `` | Najděte základní odevzdaný k opravě | Najděte potvrzení, na kterém jsou založeny vaše aktuální změny, abyste opravili/změnili odevzdání. To vám ušetří nutnost procházet potvrzení ve vaší větvi jeden po druhém, abyste viděli, které potvrzení je třeba opravit/změnit. Viz dokumentaci: <https://github.com/jesseduffield/lazygit/tree/master/docs/Fixup_Commits.md> |
| `` / `` | Hledat aktuální zobrazení podle textu |  |

## Hlavní panel (sloučení)

| Key | Action | Info |
|-----|--------|-------------|
| `` <space> `` | Vyberte fragment |  |
| `` b `` | Vyberte všechny fragmenty |  |
| `` <up> `` | Předchozí fragment |  |
| `` <down> `` | Další Fragment |  |
| `` <left> `` | Předchozí konflikt |  |
| `` <right> `` | Další konflikt |  |
| `` z `` | Vrátit zpět | Vraťte zpět poslední řešení konfliktu sloučení. |
| `` e `` | Upravit soubor | Otevřete soubor v externím editoru. |
| `` o `` | Otevřít soubor | Otevřete soubor ve výchozí aplikaci. |
| `` M `` | Otevřete nástroj pro externí sloučení | Spusťte `git mergetool`. |
| `` <esc> `` | Návrat na panel souborů |  |

## Hlavní panel (vytvoření opravy)

| Key | Action | Info |
|-----|--------|-------------|
| `` <left> `` | Přejít na předchozí fragment |  |
| `` <right> `` | Přejít na další fragment |  |
| `` v `` | Přepnout výběr rozsahu |  |
| `` a `` | Zvýrazněte fragment | Přepnout režim výběru fragmentu. |
| `` <c-o> `` | Zkopírovat vybraný text do schránky |  |
| `` o `` | Otevřít soubor | Otevřete soubor ve výchozí aplikaci. |
| `` e `` | Upravit soubor | Otevřete soubor v externím editoru. |
| `` <space> `` | Přepnout čáry v patchi |  |
| `` <esc> `` | Ukončete vlastní nástroj pro tvorbu oprav |  |
| `` / `` | Hledat aktuální zobrazení podle textu |  |

## Menu

| Key | Action | Info |
|-----|--------|-------------|
| `` <enter> `` | Udělej to |  |
| `` <esc> `` | Blízko |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Místní

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat název pobočky do schránky |  |
| `` i `` | Zobrazit možnosti git-flow |  |
| `` <space> `` | Přepínač | Přepnout vybranou položku. |
| `` n `` | Nová pobočka |  |
| `` o `` | Vytvořte požadavek na stažení |  |
| `` O `` | Viz možnosti pro vytvoření požadavku na stažení |  |
| `` <c-y> `` | Zkopírovat adresu URL žádosti o stažení do schránky |  |
| `` c `` | Přepnout podle jména | Přepnout podle jména. Do vstupního pole můžete zadat '-' pro přepnutí na poslední větev. |
| `` F `` | Vypínač síly | Vynutit přepnutí vybrané větve. Tím se před přepnutím na vybranou větev zruší všechny Místní změny v pracovním stromu. |
| `` d `` | Vymazat | Zobrazit možnosti odstranění Místní/vzdálené větve. |
| `` r `` | Přemístit | Založte přepínanou větev na vybrané větvi. |
| `` M `` | Spojit | Sloučit vybranou větev s aktuálně rezervovanou větví. |
| `` f `` | Rychle vpřed | Rychle vpřed vybranou větev z jejího zdroje. |
| `` T `` | Nová značka |  |
| `` s `` | Pořadí řazení |  |
| `` g `` | Reset |  |
| `` R `` | Změňte název pobočky |  |
| `` u `` | Zobrazit možnosti pro upstream | Zobrazit možnosti pro větve proti proudu, např. nastavit/odebrat upstream a resetovat na upstream. |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <enter> `` | Zobrazit závazky |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Odevzdané

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat hash odevzdání do schránky |  |
| `` <c-r> `` | Resetovat vybrané závazky |  |
| `` b `` | Zobrazit možnosti půlení |  |
| `` s `` | Spojit | Sloučit vybrané potvrzení s potvrzeními pod ním. Zpráva vybraného odevzdání bude připojena k odevzdání pod ním. |
| `` f `` | Pozměňovací návrh | Zahrňte vybrané potvrzení do níže uvedeného potvrzení. Podobné jako fixup, ale zpráva vybraného odevzdání bude zahozena. |
| `` r `` | Přeformulovat | Přeformulovat zprávu vybraného odevzdání. |
| `` R `` | Přeformulovat s editorem |  |
| `` d `` | Vymazat | Smazat vybrané potvrzení. Toto odebere odevzdání z větve prostřednictvím rebasingu. Pokud odevzdání zavádí změny, na kterých závisí pozdější odevzdání, možná budete muset vyřešit konflikty sloučení. |
| `` e `` | Upravit (Zahájit interaktivní přepracování) | Upravit vybrané potvrzení. Použijte toto ke spuštění interaktivní rebase z vybraného odevzdání. Zatímco probíhá rebasování, označí se tím vybraný reviz k úpravám, což znamená, že pokud budete pokračovat v rebasování, rebasování se na vybraném revizi pozastaví, aby bylo možné provést změny. |
| `` i `` | Spusťte interaktivní rebase | Spusťte interaktivní rebase commitů na vaší větvi. To bude obsahovat všechny odevzdání od HEAD po první sloučení sloučení nebo potvrzení hlavní větve.
Chcete-li místo toho zahájit interaktivní rebase z vybraného odevzdání, stiskněte `e`. |
| `` p `` | Vybrat | Označit vybrané odevzdání k výběru (při rebasingu). To znamená, že potvrzení bude zachováno i po pokračování v rebasování. |
| `` F `` | Vytvořte opravu potvrzení | Vytvořte commit 'fixup!' pro vybraný commit. Později můžete stisknout `S` na stejném odevzdání pro použití všech výše uvedených opravných odevzdání. |
| `` S `` | Použít potvrzení opravy | Sloučit všechny 'fixup!' commity, buď nad vybraným commitem, nebo všechny v aktuální větvi (autosquash). |
| `` <c-j> `` | Posuňte odevzdání dolů |  |
| `` <c-k> `` | Posunout závazek nahoru |  |
| `` V `` | Pasta (třešeň) |  |
| `` B `` | Označit jako základní potvrzení pro rebase | Vyberte základní potvrzení pro další rebase. Když znovu založíte větev, budou přeneseny pouze odevzdání nad základním odevzdáním. K tomu se používá příkaz `git rebase --onto`. |
| `` A `` | Opravit | Opravte odevzdání pomocí potvrzených změn. Pokud je vybraný odevzdání HEAD, provede se `git commit --amend`. V opačném případě bude commit opraven pomocí rebasingu. |
| `` a `` | Opravte atribut odevzdání | Nastavit/Resetovat autora odevzdání nebo nastavit spoluautora. |
| `` t `` | Vrátit zpět | Vytvořte revertovat odevzdání pro vybrané odevzdání, které použije změny vybraného odevzdání v opačném pořadí. |
| `` T `` | Potvrzení značky | Vytvořte nový tag ukazující na vybraný odevzdání. Budete požádáni o zadání názvu značky a volitelného popisu. |
| `` <c-l> `` | Zobrazit možnosti protokolu | Zobrazit možnosti pro protokoly odevzdání, např. změna pořadí řazení, skrytí git grafu, zobrazení celého git grafu. |
| `` <space> `` | Přepínač | Přepnout vybrané potvrzení jako oddělenou HEAD. |
| `` y `` | Zkopírovat atribut odevzdání do schránky | Zkopírovat atribut odevzdání do schránky (např. hash, URL, diff, zpráva, autor). |
| `` o `` | Otevřete commit v prohlížeči |  |
| `` n `` | Vytvořte novou větev z potvrzení |  |
| `` g `` | Reset | Zobrazení možností resetování (měkké/smíšené/tvrdé) pro vybranou položku. |
| `` C `` | Kopírovat (třešeň výběr) | Označit odevzdání jako zkopírované. Poté můžete v zobrazení lokálních odevzdání stisknout `V` a vybrat zkopírované odevzdání do vyhrazené větve. Výběr můžete kdykoli zrušit stisknutím `<esc>`. |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <enter> `` | Zobrazit soubory |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Hledat aktuální zobrazení podle textu |  |

## Podvýbor

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat hash odevzdání do schránky |  |
| `` <space> `` | Přepínač | Přepnout vybrané potvrzení jako oddělenou HEAD. |
| `` y `` | Zkopírovat atribut odevzdání do schránky | Zkopírovat atribut odevzdání do schránky (např. hash, URL, diff, zpráva, autor). |
| `` o `` | Otevřete commit v prohlížeči |  |
| `` n `` | Vytvořte novou větev z potvrzení |  |
| `` g `` | Reset | Zobrazení možností resetování (měkké/smíšené/tvrdé) pro vybranou položku. |
| `` C `` | Kopírovat (třešeň výběr) | Označit odevzdání jako zkopírované. Poté můžete v zobrazení lokálních odevzdání stisknout `V` a vybrat zkopírované odevzdání do vyhrazené větve. Výběr můžete kdykoli zrušit stisknutím `<esc>`. |
| `` <c-r> `` | Resetovat vybrané závazky |  |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <enter> `` | Zobrazit soubory |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Hledat aktuální zobrazení podle textu |  |

## Potvrdit soubory

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat cestu do schránky |  |
| `` y `` | Kopírovat do schránky |  |
| `` c `` | Přepínač | Přepnout soubor. Nahradí soubor ve vašem pracovním stromu verzí z vybraného odevzdání. |
| `` d `` | Vymazat | Zahoďte změny tohoto souboru z tohoto odevzdání. Spouští interaktivní rebase na pozadí, takže pokud pozdější odevzdání změní i tento soubor, může dojít ke konfliktu sloučení. |
| `` o `` | Otevřít soubor | Otevřete soubor ve výchozí aplikaci. |
| `` e `` | Upravit | Otevřete soubor v externím editoru. |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <space> `` | Přepnout soubor s povolenou opravou | Přepněte, zda je soubor součástí vlastní opravy. Viz https://github.com/jesseduffield/lazygit#rebase-magic-custom-patches. |
| `` a `` | Přepnout všechny soubory | Přidat/odebrat všechny soubory odevzdání do vlastní opravy. Viz https://github.com/jesseduffield/lazygit#rebase-magic-custom-patches. |
| `` <enter> `` | Přejít do souboru / Přepnout adresář sbalení | Pokud je vybrán soubor, přejděte do souboru, abyste mohli přidat/odebrat jednotlivé řádky do vlastní opravy. Pokud je vybrán adresář, přepněte adresář. |
| `` ` `` | Přepnout zobrazení stromu souborů | Přepínání zobrazení souboru mezi plochým a stromovým. Ploché rozvržení zobrazuje všechny cesty k souborům v jednom seznamu, stromové rozvržení seskupuje soubory podle adresářů. |
| `` - `` | Collapse all files | Collapse all directories in the files tree |
| `` = `` | Expand all files | Expand all directories in the file tree |
| `` / `` | Hledat aktuální zobrazení podle textu |  |

## Potvrzovací panel

| Key | Action | Info |
|-----|--------|-------------|
| `` <enter> `` | Potvrdit |  |
| `` <esc> `` | Zavřít/Zrušit |  |

## Pracovní stromy

| Key | Action | Info |
|-----|--------|-------------|
| `` n `` | Nový pracovní strom |  |
| `` <space> `` | Přepínač | Přepněte na vybraný pracovní strom. |
| `` o `` | Otevřít v editoru |  |
| `` d `` | Vymazat | Smazat vybraný pracovní strom. Tím se odstraní jak adresář pracovního stromu, tak metadata pracovního stromu v adresáři .git. |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Reflog

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat hash odevzdání do schránky |  |
| `` <space> `` | Přepínač | Přepnout vybrané potvrzení jako oddělenou HEAD. |
| `` y `` | Zkopírovat atribut odevzdání do schránky | Zkopírovat atribut odevzdání do schránky (např. hash, URL, diff, zpráva, autor). |
| `` o `` | Otevřete commit v prohlížeči |  |
| `` n `` | Vytvořte novou větev z potvrzení |  |
| `` g `` | Reset | Zobrazení možností resetování (měkké/smíšené/tvrdé) pro vybranou položku. |
| `` C `` | Kopírovat (třešeň výběr) | Označit odevzdání jako zkopírované. Poté můžete v zobrazení lokálních odevzdání stisknout `V` a vybrat zkopírované odevzdání do vyhrazené větve. Výběr můžete kdykoli zrušit stisknutím `<esc>`. |
| `` <c-r> `` | Resetovat vybrané závazky |  |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <enter> `` | Zobrazit závazky |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Soubory

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat cestu do schránky |  |
| `` <space> `` | Potvrdit | Přepnout schválení pro vybraný soubor. |
| `` <c-b> `` | Filtrovat soubory podle stavu |  |
| `` y `` | Kopírovat do schránky |  |
| `` c `` | Commit | Potvrdit změny schváleny. |
| `` w `` | Potvrdit změny bez háčku předběžného potvrzení |  |
| `` A `` | Opravit poslední odevzdané |  |
| `` C `` | Potvrďte změny pomocí editoru git |  |
| `` <c-f> `` | Najděte základní odevzdaný k opravě | Najděte potvrzení, na kterém jsou založeny vaše aktuální změny, abyste opravili/změnili odevzdání. To vám ušetří nutnost procházet potvrzení ve vaší větvi jeden po druhém, abyste viděli, které potvrzení je třeba opravit/změnit. Viz dokumentaci: <https://github.com/jesseduffield/lazygit/tree/master/docs/Fixup_Commits.md> |
| `` e `` | Upravit | Otevřete soubor v externím editoru. |
| `` o `` | Otevřít soubor | Otevřete soubor ve výchozí aplikaci. |
| `` i `` | Ignorovat nebo vyloučit soubor |  |
| `` r `` | Obnovit soubory |  |
| `` s `` | Skrýt | Skrýt všechny změny. Pro další možnosti skrytí použijte klávesu zobrazení možností schránky. |
| `` S `` | Zobrazit možnosti schránky | Zobrazit možnosti schránky (např. skrýt vše, skrýt schválené, skrýt neschválené). |
| `` a `` | Potvrďte vše | Přepnout potvrzení/zrušení pro všechny soubory v pracovním stromu. |
| `` <enter> `` | Potvrdit řádky / Sbalit adresář | Pokud je vybranou položkou soubor, zaměřte se na zobrazení schválení, abyste mohli schválit jednotlivé fragmenty/řádky. Pokud je vybranou položkou adresář, sbalte jej/rozbalte jej. |
| `` d `` | Odmítnout | Zobrazit možnosti pro zrušení změn ve vybraném souboru. |
| `` g `` | Zobrazit možnosti obnovení upstreamu |  |
| `` D `` | Reset | Zobrazit možnosti resetování pro pracovní strom (např. zničit pracovní strom). |
| `` ` `` | Přepnout zobrazení stromu souborů | Přepínání zobrazení souboru mezi plochým a stromovým. Ploché rozvržení zobrazuje všechny cesty k souborům v jednom seznamu, stromové rozvržení seskupuje soubory podle adresářů. |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` M `` | Otevřete nástroj pro externí sloučení | Spusťte `git mergetool`. |
| `` f `` | Stáhnout | Stáhnout změny ze vzdáleného serveru. |
| `` - `` | Collapse all files | Collapse all directories in the files tree |
| `` = `` | Expand all files | Expand all directories in the file tree |
| `` / `` | Hledat aktuální zobrazení podle textu |  |

## Status

| Key | Action | Info |
|-----|--------|-------------|
| `` o `` | Otevřete konfigurační soubor | Otevřete soubor ve výchozí aplikaci. |
| `` e `` | Upravit konfigurační soubor | Otevřete soubor v externím editoru. |
| `` u `` | Zkontrolovat aktualizace |  |
| `` <enter> `` | Přepnout na poslední úložiště |  |
| `` a `` | Zobrazit všechny pobočky v protokolech |  |

## Submoduly

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat název submodulu do schránky |  |
| `` <enter> `` | Pojďte dál | Zadejte submodul. Jakmile jste uvnitř submodulu, můžete se stisknutím `<esc>` vrátit do nadřazeného úložiště. |
| `` d `` | Vymazat | Smažte vybraný submodul a jeho odpovídající adresář. |
| `` u `` | Aktualizovat | Aktualizovat vybraný submodul. |
| `` n `` | Nový submodul |  |
| `` e `` | Aktualizovat adresu URL submodulu |  |
| `` i `` | Zahájit | Inicializovat vybraný submodul pro přípravu ke stažení. Pravděpodobně budete chtít na to navázat voláním akce 'update' pro stažení submodulu. |
| `` b `` | Zobrazit možnosti hromadných operací podmodulu |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Tagy

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Copy tag to clipboard |  |
| `` <space> `` | Přepínač | Přepnout vybranou značku jako oddělenou HEAD. |
| `` n `` | Nová značka | Vytvořte nový tag z aktuálního odevzdání. Budete požádáni o zadání názvu značky a volitelného popisu. |
| `` d `` | Vymazat | Zobrazit možnosti Místního/vzdáleného odstranění štítků. |
| `` P `` | Odeslat značku | Odeslat vybraný štítek na dálkové ovládání. Budete požádáni o výběr dálkového ovládání. |
| `` g `` | Reset | Zobrazení možností resetování (měkké/smíšené/tvrdé) pro vybranou položku. |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <enter> `` | Zobrazit závazky |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Vzdálené

| Key | Action | Info |
|-----|--------|-------------|
| `` <enter> `` | Zobrazit větve |  |
| `` n `` | Nový dálkový ovladač |  |
| `` d `` | Vymazat | Smazat vybrané dálkové ovládání. Žádné Místní sledující vzdálenou z tohoto vzdáleného nebudou ovlivněny. |
| `` e `` | Upravit | Upravte název nebo adresu URL vybraného dálkového ovládání. |
| `` f `` | Stáhnout | Stáhněte si aktualizace ze vzdáleného úložiště. Načítá nové odevzdání a větve bez jejich slučování s Místními větvemi. |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Vzdálené pobočky

| Key | Action | Info |
|-----|--------|-------------|
| `` <c-o> `` | Zkopírovat název pobočky do schránky |  |
| `` <space> `` | Přepínač | Přepněte na novou Místní na základě vybrané vzdálené pobočky. Nová pobočka bude sledovat vzdálenou. |
| `` n `` | Nová pobočka |  |
| `` M `` | Spojit | Sloučit vybranou větev s aktuálně rezervovanou větví. |
| `` r `` | Přemístit | Založte přepínanou větev na vybrané větvi. |
| `` d `` | Vymazat | Smazat vzdálenou větev ze vzdáleného. |
| `` u `` | Nastavit jako upstream | Nastavte vybranou vzdálenou větev jako předřazenou od rezervované větve. |
| `` s `` | Pořadí řazení |  |
| `` g `` | Reset | Zobrazení možností resetování (měkké/smíšené/tvrdé) pro vybranou položku. |
| `` <c-t> `` | Otevřít externí nástroj pro porovnání (git difftool) |  |
| `` <enter> `` | Zobrazit závazky |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |

## Úložný prostor

| Key | Action | Info |
|-----|--------|-------------|
| `` <space> `` | Použít | Použijte záznam ze schránky na pracovní adresář. |
| `` g `` | Vytáhnout | Použijte záznam ze schránky na pracovní adresář a odeberte záznam ze schránky. |
| `` d `` | Vymazat | Odeberte položku schránky ze seznamu schránky. |
| `` n `` | Nová pobočka | Vytvořte novou větev z vybrané položky schránky. Funguje to tak, že se git přepne na odevzdání, na kterém byl záznam pro skrýš vytvořen, vytvoří z tohoto odevzdání novou větev a poté použije záznam skrýše na novou větev jako další odevzdání. |
| `` r `` | Změnit název schránky |  |
| `` <enter> `` | Zobrazit soubory |  |
| `` w `` | Zobrazit možnosti pracovního stromu |  |
| `` / `` | Filtrovat aktuální zobrazení podle textu |  |
