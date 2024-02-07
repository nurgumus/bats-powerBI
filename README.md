This one is the main page that give general info about species,families, generational length, what type of food they consume and their population status.
Has one info button about generational length because people can get confused. back button refreshes and hides the info. Done with bookmarks.

![Ekran görüntüsü 2024-02-07 142344](https://github.com/nurgumus/bats-powerBI/assets/108015878/af7ea1f4-3526-4413-911d-118b6d497177)

This one is the second slide and it's about environmental threats, the score is calculated by:

[Threat Level ] = [Mining & quarrying] + [Sacred activities] + [Tourism and caving activities] + [Guano extraction] + [Vandalism] + [Nest harvesting] + [Bushmeat hunting & medicine] + [Gating] + [Scientific research] + [Agriculture] + [Urbanisation] + [Deforestation] + [Pollution] + [Road Kills] + [Diseases and parasitism] + [Invasive species, predation] + [Intensional killings/Misguided killings] + [Fire] + [Drought]+ [Heatwaves]+ [Extreme cold]+ [Storm]

So higher the score is, the environment they live in is much more dangerous.

![Ekran görüntüsü 2024-02-07 142359](https://github.com/nurgumus/bats-powerBI/assets/108015878/60ff142f-8996-473d-a876-c8cfc261b9e0)

This slide is about parasites, has a map, slicer and parasite species distrubution.

![Ekran görüntüsü 2024-02-07 142539](https://github.com/nurgumus/bats-powerBI/assets/108015878/65e3d370-f574-4330-bbc6-87b5dd4b2b74)

Fourth and last slide is about their ecosystem. Natural range means "A species range is the area where a particular species can be found during its lifetime."
Target is the natural range and value is the current range of the species. Top left card shows are they in the area as expected.

And the red bars you see on the table are concantrated according to environment level score. I calculated that column with:

Env Score = [Canopy.cov]+ [Tree.dens] + [Freshwater.dist] -[Bareground.change] - [Shortveg.change] + [Talltree.change] - [Urban.dist] - [Road.dist] - [Mine.dens]- [Nighlight]- [Pesticide.exp]-[Pop.dens]

The score itself doesn't particularly mean anything but it being higher or lower indicates ideas about environment quality.

![Ekran görüntüsü 2024-02-07 154701](https://github.com/nurgumus/bats-powerBI/assets/108015878/95b4ee74-06e8-43ab-8334-b14bdd06c8a6)

This is the data model. One-to-many or Many-to-many relations sadly. 

![Ekran görüntüsü 2024-02-07 154820](https://github.com/nurgumus/bats-powerBI/assets/108015878/c7641b62-86b0-4d74-8cee-b6863b29eaf1)
