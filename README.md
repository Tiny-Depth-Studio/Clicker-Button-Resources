# Clicker Button Resources

Public images for Clicker Button that Steam has to fetch from a URL, mainly the Steam
Inventory item icons of the in-app purchases. Same layout as `Clicker-Ore-Resources`.

Files are served from
`https://raw.githubusercontent.com/Tiny-Depth-Studio/Clicker-Button-Resources/main/<path>`,
which is the value to put in the item definition's `icon_url` / `icon_url_large`.

## Expected files

| Path | Steam item def | Product | Grants |
| --- | --- | --- | --- |
| `InAppPurchase/Currency/StoreDiamonds_1.png` | 1 | `diamonds_100` | 100 diamonds |
| `InAppPurchase/Currency/StoreDiamonds_2.png` | 2 | `diamonds_550` | 550 diamonds |
| `InAppPurchase/Currency/StoreDiamonds_3.png` | 3 | `diamonds_1200` | 1,200 diamonds |
| `InAppPurchase/Currency/StoreDiamonds_4.png` | 4 | `diamonds_2600` | 2,600 diamonds |
| `InAppPurchase/Currency/StoreDiamonds_5.png` | 5 | `diamonds_7000` | 7,000 diamonds |

PNG, square, 1024 x 1024 with transparency (the Clicker Ore icons use the same size).
Item def ids and grants must match the game's store catalog and the game server's product catalog.

The diamond pack icons are the studio's own art: Clicker Ore's `StoreDiamonds_1, 2, 3, 4, 6` with the
blue gems recoloured pink, the same images the game's store cards use. Only art the studio owns goes
here; Unity Asset Store GUI pack art must not be committed to this public repository.
