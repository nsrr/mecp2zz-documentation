## About

Mutations in the methyl-CpG-binding protein 2 (MeCP2) gene are the primary cause of Rett syndrome (RTT), a rare neurodevelopmental disorder that manifests early in childhood. This study used a Rett syndrome mouse model, Mecp2-/y, to study sleep architecture and the homeostatic response to sleep deprivation using polysomnography. Polysomnography recordings were collected over a 48-hour period from 20 male mice, aged 5 to 6 weeks. The first 24 hours comprised baseline recordings, followed by five hours of sleep deprivation and 19 hours of recovery sleep. 

## Methods

A total of 20 animals were used for surgical procedures. Males (5-6 weeks old) (n = 10 per genotype) were anesthetized and stereotaxically implanted with four electroencephalographic (EEG) and two electromyographic (EMG) electrodes for assessment of sleep-wake behavior as previously described (Medina et al., 2022). Animals were subcutaneously given dexamethasone (1 mg/kg), enrofloxacin (5 mg/kg) and carprofen (5 mg/kg) prior to surgical procedure and for an additional 2 days after surgical procedures for a total of 72 hours. Buprenorphine (0.1/mg/kg) was given following righting after surgical procedures. Briefly, four stainless steel screws (BC‐002MP188, Bellcan International Corp, Hialeah, FL) were placed bilaterally over frontal (two) and parietal (two) cortices, and EMG electrodes were inserted bilaterally into the nuchal muscles. EEG electrode placement was secured with dental cement, the mice were individually housed and allowed a minimum of 5 days of recovery from surgery prior to habituation to the recording environment. Animals were connected to a lightweight, flexible tether and allowed five days to habituate to the tether and recording environment. After habituation, mice underwent 24 hours of undisturbed baseline recordings. Recordings started at lights on (hour 1) and ended at lights on after a total of 48 hours of recordings. The first 24 hours consisted of baseline recording, followed by five hours of sleep deprivation at the beginning of lights on (ZT=0 hour 1, day 2). Sleep deprivation was followed by 19 hours of undisturbed recovery sleep. Sleep deprivation was conducted manually via gently handing, when necessary, animals were gently stroked with a soft brush to ensure animals remained awake. 

## Data overview

The RHD2000 amplifier Intan system recorded the raw EEG and EMG data in (.rhd) format. Data was then converted to [European Data Format (.edf) files](:files_path:/EDF_files) using custom software digitalized at 250 Hz. Initially, files were scored using deep-neuronal network algorithm SPINDLE (Miladinović et al., 2019) and then collected in CSV format for manual verification using SleepSign software (Kissei Comtec America, INC). EEG and EMG data were high and low band pass filtered at 0.05 and 50 Hz and 15 and 30 Hz, respectively with a Notch filter set to 60 Hz. EEG power analysis was conducted from EEG spectra analysis of 0.5- 50 Hz. The [CSV files](:files_path:/CSV_files) provided contain every scored epoch along with spectral information for the entire 48 hours.

The [Mecp2ZZ_Annotated_DataCollectionForm (XLSX) file](:files_path:/) provides contextual information about the mice and EDF/CSV filenames.

## Access and usage restrictions

The Mecp2ZZ dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

>[Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

Users must include the following text in any Acknowledgements:

> The Mecp2ZZ work was supported by the National Institutes of Health (1F99NS135815-01). The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*August 2024*

- Make Mecp2ZZ dataset available for data requests

## References

- Mecp2ZZ GitHub Documentation: https://github.com/nsrr/mecp2zz-documentation
- [Ingiosi AM, Schoch H, Wintler T, Singletary KG, Righelli D, Roser LG, Medina E, Risso D, Frank MG, Peixoto L. Shank3 modulates sleep and expression of circadian transcription factors. Elife. 2019 Apr 11;8:e42819. doi: 10.7554/eLife.42819. PMID: 30973326; PMCID: PMC6488297.](https://pubmed.ncbi.nlm.nih.gov/30973326/)
- [Medina E, Peterson S, Ford K, Singletary K, Peixoto L. Critical periods and Autism Spectrum Disorders, a role for sleep. Neurobiol Sleep Circadian Rhythms. 2022 Dec 20;14:100088. doi: 10.1016/j.nbscr.2022.100088. PMID: 36632570; PMCID: PMC9826922.](https://pubmed.ncbi.nlm.nih.gov/36632570/)
- [Miladinović Đ, Muheim C, Bauer S, Spinnler A, Noain D, Bandarabadi M, Gallusser B, Krummenacher G, Baumann C, Adamantidis A, Brown SA, Buhmann JM. SPINDLE: End-to-end learning from EEG/EMG to extrapolate animal sleep scoring across experimental settings, labs and species. PLoS Comput Biol. 2019 Apr 18;15(4):e1006968. doi: 10.1371/journal.pcbi.1006968. PMID: 30998681; PMCID: PMC6490936.](https://pubmed.ncbi.nlm.nih.gov/30998681/)

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
