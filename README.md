# tiles-audio-feature-extraction
scripts to extract audio features (offline) using a congruent config file used for TILES online feature extraction

requirements: opensmile 

```bash
# usage
config_file="<current_path>/tiles_offline_config/TILEs_core_lld.conf"
SMILExtract -C $config_file -I <ip_file_name> -O <op_file_name>
```
