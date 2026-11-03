# Pokémon Co-op

Un lanceur pour jouer à Pokémon à deux, chacun sur sa propre copie du jeu : on se voit sur la carte,
on avance ensemble, on échange et on combat en ligne. Jeux DS (melonDS), 3DS (Azahar) et Game Boy
Advance (mGBA), avec rééquilibrage, randomisation et patchs dans l'application.

Aucun jeu n'est fourni : chacun ajoute sa propre ROM.

## Télécharger

| Système | Fichier | Où le trouver |
|---|---|---|
| Windows 10 et 11 | `Pokemon.Coop.zip` | [dernière version Windows](https://github.com/coaxel2/pokemon-coop-releases/releases/latest) |
| macOS (Apple Silicon) | `Pokemon-Coop-Mac.zip` | [versions `mac-…`](https://github.com/coaxel2/pokemon-coop-releases/releases?q=mac-&expanded=true) |
| Linux (x86_64) | `Pokemon-Coop-Linux.tar.gz` | [versions `linux-…`](https://github.com/coaxel2/pokemon-coop-releases/releases?q=linux-&expanded=true) |

Prends la version la plus récente de ton système. Une fois installé, le lanceur se met à jour tout seul.

### Installer

- **Windows** : décompresse le zip où tu veux, puis double-clic sur `Pokemon Coop.exe`.
- **macOS** : décompresse, glisse `Pokemon Coop.app` dans Applications. Au premier lancement : clic droit, Ouvrir.
- **Linux** : `tar -xzf Pokemon-Coop-Linux.tar.gz`, puis double-clic sur `Pokemon Coop` dans le dossier
  (ou `./"Pokemon Coop"` dans un terminal). Le lanceur s'ajoute ensuite au menu des applications.
  Il marche sur Ubuntu 22.04 et toute distribution plus récente (Debian 12, Fedora, Mint, Arch...).

## Comment les versions sont faites

Chaque version Windows est publiée depuis le PC de développement. Les versions Mac et Linux du même
numéro sont ensuite compilées ici même par GitHub Actions ([`mac-linux.yml`](.github/workflows/mac-linux.yml)),
depuis les mêmes sources.

## Licences

Les émulateurs modifiés sont des logiciels libres : melonDS (GPL v3), Azahar (GPL v2), mGBA (MPL 2.0).
Leurs sources modifiées sont jointes à chaque version Windows (`sources-mods-…zip`, `melonds-coop-…zip`),
et les licences sont dans le dossier `licences` de chaque paquet.
