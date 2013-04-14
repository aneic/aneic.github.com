### Ancient Near-East Ivory Clustering

This code identifies stylistically similar groups in a corpus of Levantine ivory statuettes using maximum likelihood and maximum posterior clustering. 

![Example Objects](https://raw.github.com/aneic/aneic.github.com/non-auto/images/sample_objects.png)

While this code has been written with the application to art historical data in mind, it may be used generally to perform clustering data with a combination of categorical and real-valued features, where some data may be missing. 

Data may be read from a CSV file. Each row is interpreted as a separate observation. Numerical columns are assumed to be real-valued, string-valued columns are assumed to be categorical.


### Read the Code

The repository [aneic-core](https://github.com/aneic/aneic-core) contains the sources for the statistical algorithm, as well as the levantine corpus dataset.

The repository [aneic-scripts](https://github.com/aneic/aneic-scripts) contains support code needed in order to perform analysis of the Levantine corpus. 


### Example Usage

        git clone https://github.com/aneic/aneic-scripts.git
        cd aneic-scripts/130317_01_mfm_sigma_1.0_a_2.0
        git clone https://github.com/aneic/aneic-core.git
        python run_mfm.py


### License

This project is both open data and open source. 

The [levantine corpus](https://github.com/aneic/aneic-core/tree/master/data) dataset is copyright 2013 Amy Gansell (@amygansell). It is distributed under the [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/us/). 

The source code is copyright 2013 Jan-Willem van de Meent (@jwvdm) and Sakellarios Zairis (@szairis). It is distributed under [MIT license](https://github.com/aneic/aneic-core/blob/master/src/mit-license.txt). 