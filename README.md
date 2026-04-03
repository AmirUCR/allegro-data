# ALLEGRO Jumpstart
This repository serves as a starting point for ALLEGRO. Included are 50 fungal species with orthologous genes for _LYS2_, _MET17_, _TRP1_, _URA3_, _FCY1_, _GAP1_, and _CAN1_ in _S. cerevisiae_ S288C.

You would clone this repo as a starting point after you install ALLEGRO via `pip install allegro-bio`. Then, cd into this repo folder, and run `allegro` to use the default configurations.

Additionally, we provide all 2,263 species and their CDS orthologous to the genes above under `data/input/cds/compressed_ortho_from_gff.zip`, and their manifest file at `data/input/fourdbs_input_species.csv`. To replicate the results in the paper, unzip the CDS files and configure ALLEGRO to use that directory and manifest accordingly. In `config.yaml`, set the `input_species_path_column` to `ortho_file_name`.

There is also a `config.yml` which you can use as a starting point. ALLEGRO also supports CLI options as described in its [Wiki](https://github.com/ucrbioinfo/allegro/wiki/2.-Tutorial-(Basic-Settings)).