# ALLEGRO Jumpstart
This repository serves as a starting point for ALLEGRO. Included are 50 fungal species with orthologous genes for __LYS2__, __MET17__, __TRP1__, __URA3__, __FCY1__, __GAP1__, and __CAN1__ in __S. cerevisiae__ S288C.\

Additionally, we provide all 2,263 species and their CDS orthologous to the genes above under `data/input/cds/compressed_ortho_from_gff.zip`, and their manifest file at `data/input/fourdbs_input_species.csv`. To replicate the results in the paper, unzip the CDS files and configure ALLEGRO to use that directory and manifest accordingly. In `config.yaml`, set the `input_species_path_column` to `ortho_file_name`.

There is also a `config.yml` which you can use as a starting point. ALLEGRO also supports CLI options as described in its [Wiki](https://github.com/ucrbioinfo/allegro/wiki/2.-Tutorial-(Basic-Settings)).