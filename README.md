# Speech-datasets (updated Sep 16th 2023)
This repository lists publicly available speech datasets mainly in the cybersecurity and healthcare domain, and is updated on a regular basis.
## Deepfakes
[**ASVspoof 2021**](https://www.asvspoof.org/index2021.html): the commonly used deepfake dataset from the ASVspoof challenge series. This is the 2021 version which includes a deepfake track, with 600K utterances from a variety of generation algorithms and codecs. See also the [2019 version](https://datashare.ed.ac.uk/handle/10283/3336), which also has some DFs in the LA track.

[**WaveFake**](https://github.com/RUB-SysSec/WaveFake): include only crafted speech based on the data from LJ speech corpus. For each genuine utterance, it comes with more than 10 different DF versions.

[**In-the-wild**](https://deepfake-demo.aisec.fraunhofer.de/in_the_wild): in-the-wild deepfakes, including genuine and crafted ones from celebrity voices.

[**ADD**](): mandarin deepfake detection challenge databases. Link to be updated.

[**Half-truth audio detection (HAD)**](): partial-deepfake and fully-deepfake utterances. Link to be updated.

[**Partial Spoof**](https://zenodo.org/record/4817532): partially-spoofed utterances contain a mix of both spoofed and bona fide segments.

[**SceneFake**](https://zenodo.org/record/7663324): acoustic scene is crafted while voice itself remains unchanged. Detailed generation pipeline can be found in the [paper](https://arxiv.org/pdf/2211.06073.pdf).



## Healthcare
[**Cambridge COVID Sound**](https://openreview.net/pdf?id=9KArJb4r5ZQ): (obtained upon requests) includes ~300H of voice, cough, and breathing data collected remotely from healthy and COVID individuals. It comes with rich metadata, such as COVID-status, gender, age, symptom, pre-existing medical conditions. However, the COVID labels are self-reproted not PCR-validated.

[**Coswara**](https://github.com/iiscleap/Coswara-Data): COVID-19 sounds (voice, cough, breathing) collected in India. See also the related [DiCOVA 1&2 challenge datasets](https://dicova2021.github.io/). The challenge ones are obtained upon requests.

[**ComParE 2021 COVID Detection Dataset**](http://www.compare.openaudio.eu/now/): (obtained upon requests) includes ~3K audio samples (speech, cough, and breathing) from COVID and healthy individuals. This is an INTERSPEECH challenge dataset.

[**TORGO**](http://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html): in-lab voice recordings from individuals with dysarthria. It also provides the text groudtruth and articulatory traces.

[**Nemours**](): (link to be updated) ~800 sentence utterances collected in-lab from individuals with different degrees of dysarthria. Labels are intelligibility.

[**NCSC**](): (link to be updated) sentence utterances from individuals who received a cervical tumor surgery, with binary labels (low- / high-intelligibility)

[**KSoF-C**](https://zenodo.org/record/6460102): (obtained upon request) Original version contains 5K 3-sec speech segments from 37 German speakers. The segments contain speech of persons who stutter. The one used in the INTERSPEECH 2022 ComParE challenge (KSOF-C) only features 4601 non-ambiguously labeled segments, where segments are classified as one of the 8 classes - the seven stuttering-related classes and an eighth “garbage” class, denoting unintelligible segments, segments containing no speech, or segments that are negatively affected by loud background noise.

# Contribute & Author
If you wish to contribute or simply offer some comments, contact me at [Yi.Zhu@inrs.ca].



