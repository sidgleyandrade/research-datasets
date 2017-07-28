# AGILE 2017 dataset

The AGILE 2017 is a raw dataset of rainfall gauges and rainfall-related tweets that are openly available in CSV format. This dataset was published at the [20th AGILE Conference](https://agile-online.org/index.php/conference/conference-2017) through the paper `Mining Rainfall Spatio-Temporal Patterns in Twitter: A Temporal Approach`. See [DOI:10.1007/978-3-319-56759-4_2](http://dx.doi.org/10.1007/978-3-319-56759-4_2)

The dataset contains:

- `rainfall_gauges.csv`: The rainfall data collected from the [National Center for Monitoring and Early Warning of Natural Disasters CEMADEN](http://www.cemaden.gov.br/mapainterativo/) referring to the city of Sao Paulo, Brazil. The rainfall measurements were provided in linear depth (millimeters) and with two sizes of temporal window: 10 minutes when it was raining and 60 minutes otherwise.
- `rainfall_gagues_removed.csv`: The rainfall gauges removed due the lack of reliability.
- `tweets.csv`: The georeferenced tweets retrieved by Twitter Streaming API for the same period and administrative boundaries of rainfall data.
- `tweets.ts.csv`: The frequency of rainfall-related tweets and all tweets.

## Citation

Please, cite the conference paper or dataset below if you use this data in your research:

    Andrade, S. C. De, Restrepo-Estrada, Camilo, Mendiondo, E. M. and de Albuquerque, J.P. (2017) 
    Dataset to support: 'Mining rainfall spatio-temporal patterns in Twitter: a temporal approach'.

BibTex

    @misc{wrap87173,
        month = {March},
        title = {Dataset to support: 'Mining rainfall spatio-temporal patterns in Twitter: 
                 a temporal approach'},
        author = {S. C. De Andrade and Camilo Restrepo-Estrada and A. C. B. Delbem and E. M. Mendiondo 
                  and J.P. de Albuquerque},
        publisher = {Centre for Interdisciplinary Methodologies},
        year = {2017},
        keywords = {Social network, Twitter, Rainfall, Temporal analysis, Time-series correlation},
        url = {http://wrap.warwick.ac.uk/87173/}
    }

**Corresponding Author**:  Sidgley Camargo de Andrade (sidgleyandrade [at] utfpr.edu.br [dot] br)

## License

AGILE 2017 dataset is published under the Creative Commons License <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/80x15.png" /></a><br/>
