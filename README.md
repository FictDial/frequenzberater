# FrequenzBerater
created by Károly Füzessi and Lilla Magyari

Get lemma frequencies from the [NoWaC frequency list](https://www.hf.uio.no/iln/english/about/organization/text-laboratory/services/nowac-frequency.html) and append it your file. Dictionary cleaned and licensed under [CC BY-NC-SA 2.0](https://creativecommons.org/licenses/by-nc-sa/2.0/).

Usage:
```
py -3 freq.py input.tsv output.tsv
```

Input file is a tab-separated values file with the following columns: frekvens, lemma, ordklasse. 
To create the input file, you can use the Oslo-Bergen Tagger (https://tekstlab.uio.no/obt-ny/english/index.html).

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant agreement No. 845343.
Project's website: https://www.uis.no/nb/lesesenteret/fictdial

