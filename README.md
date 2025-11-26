# KYPO Cyber Range Platform Demo Training

Linear game for [KYPO CRP](https://docs.crp.kypo.muni.cz/).

Follow [general instructions](https://docs.crp.kypo.muni.cz/basic-concepts/typical-training-workflow/training-workflow-cloud/) to set up the game.

This game uses `kali` image from [MUNI-KYPO-IMAGES](https://gitlab.ics.muni.cz/muni-kypo-images), which needs to be available in OpenStack. To get and upload the image, see [this guide](https://gitlab.ics.muni.cz/muni-kypo-images/muni-kypo-images-wiki/-/wikis/How-to-get-image-for-OpenStack).

## Game Levels Summary
- `nmap` port scanning
- `hydra` password guessing at `telnet` 
- privilege escalation using misconfigured `sudo`

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|server|ubuntu-focal-x86_64|standard.small|
|client|kali|standard.small|
|router|debian-9-x86_64|standard.small|

## License and Credits
[MIT License](./LICENSE)

**Leading author:** Zdeněk Vydra

**Contributors:** Jakub Čegan, Tomáš Sapák, Kamil Andoniadis, Igor Ignác, Juraj Paluba, Dominik Pilár, Michal Urban, Tomáš Kacvinský

# fork_demo_KYPO
