
# tradelog 

## School project (Operating systems, BASH)
Evaluation 15/15


# CZ
Skript pro analýzu záznamu systému pro obchodování na burze cenných papírů.
Může filtrovat záznamy a poskytovat statistiky podle vstupu uživatele.
## Použití:     tradelog [FILTR] [PŘÍKAZ] [LOG [LOG2 [...]]

| Příkaz | Popis |
| --- | --- |
| `list-tick`  | Výpis seznamu vyskytujících se burzovních symbolů, tzv. 'tickerů. |
| `profit`     | Výpis celkového zisku z uzavřených pozic. |
| `pos`        | Výpis hodnot aktuálně držených pozic seřazených sestupně dle hodnoty. |
| `last-price` | Výpis poslední známé ceny pro každý ticker. |
| `hist-ord`   | Výpis histogramu počtu transakcí dle tickeru. |
| `graph-pos`  | Výpis grafu hodnot držených pozic dle tickeru. |

| Filter | Popis |
| --- | --- |
| `-a DATETIME` | Jsou uvažovány pouze záznamy PO tomto datu (bez tohoto data).* |
| `-b DATETIME` | Jsou uvažovány pouze záznamy PŘED tímto datem (bez tohoto data). |
| `-t TICKER`   | Jsou uvažovány pouze záznamy odpovídající danému tickeru. |
| `-w WIDTH`    | U výpisu grafů nastavuje jejich šířku, tedy délku nejdelšího řádku na WIDTH. |

*DATETIME je formátu YYYY-MM-DD HH:MM:SS

# EN
A script for analyzing the record of the system for trading on the stock exchange. 
The script will filter records and provide statistics according to user input.
## Usage:     tradelog [FILTER] [COMMAND] [LOG [LOG2 [...]]
| Command | Description |
| --- | --- |
| `list-tick`  | Listing the list of stock symbols, the so-called “tickers" |
| `profit`     | An extract of the total profit from closed positions. |
| `pos`        | List of values of currently held positions sorted in descending order of value. |
| `last-price` | Listing the last known price for each ticker. |
| `hist-ord`   | Extract the histogram of the number of transactions according to the ticker. |
| `graph–pos`  | Print the chart of the values of the held positions according to the ticker. |

| Filter | Description |
| --- | --- |
| `-a DATETIME` | Only records after this date (without this date) are considered.* |
| `-b DATETIME` | Only records before this date (without this date) are considered. |
| `-t TICKER`   | Only entries corresponding to a given ticker are considered. |
| `-w WIDTH`    | For listing graphs, it sets their width, that is, the length of the longest line to width. |

*DATETIME is in format of YYYY-MM-DD HH:MM:SS
