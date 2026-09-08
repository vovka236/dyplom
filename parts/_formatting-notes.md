# Metadane formatowania oryginału (dyplom.docx)

Zapisane po to, żeby przy składaniu finalnego .docx odtworzyć wygląd 1:1.

## Strona
- Rozmiar: 7560945 x 10692765 EMU (≈ 19.999 cm x 28.283 cm — zbliżone do A4, prawdopodobnie z niestandardowym marginesem)
- Marginesy (EMU): lewy 1259840 (~3.5 cm), prawy 539750 (~1.5 cm), górny 899795 (~2.5 cm), dolny 899795 (~2.5 cm)
- Jedna sekcja w całym dokumencie (brak podziałów sekcji)

## Style akapitów użyte w treści
- `Normal` — podstawowy tekst akapitów
- `No Spacing` — część akapitów (bez odstępu przed/po)
- `Heading 1` — tytuły rozdziałów (WSTĘP, ROZDZIAŁ 1/2/3, ZAKOŃCZENIE)
- `Heading 2` — tytuły podrozdziałów (np. 1.1, 2.3...)

## Czcionka
- Domyślna (styl Normal): Times New Roman

## Przypisy
- 118 przypisów dolnych (footnotes), oryginalnie numerowane 1–118 w kolejności występowania w tekście
- Wyodrębnione do plików .md razem z odpowiadającym im rozdziałem/podrozdziałem (sekcja pod `---` na końcu pliku)
- Zawierają cytowania w stylu przypisów (autor, tytuł kursywą, wydawnictwo, rok, strony, URL, [dostęp: data])

## Obrazy
- 4 obrazy (image1–4.png) + 1 dodatkowy (hash-named .png) w treści rozdziału 2, wyodrębnione do `parts/media/`
- Podpisy typu "Rysunek N. ..." zachowane w tekście nad/przy obrazkiem

## Uwagi do naprawy przy poprawkach (nie ruszane na tym etapie)
- W oryginale w tytułach ROZDZIAŁ 2 i ROZDZIAŁ 3 oraz w wielu miejscach w treści (głównie te dwa rozdziały) występowały litery cyrylicy wizualnie
  identyczne z łacińskimi: cyrylicka 'о' (U+043E), 'О' (U+041E), 'і' (U+0456), 'І' (U+0406).
  Zamienione na łacińskie odpowiedniki (o, O, i, I) we wszystkich plikach w `parts/`.
- Pozostałe znaki specjalne w tekście (np. „ ” cudzysłowy, °, ₂, non-breaking space, é, minus typograficzny) zostawione bez zmian — to
  poprawne znaki, nie cyrylica.
