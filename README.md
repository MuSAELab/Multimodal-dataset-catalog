# Multimodal dataset catalog
This repository lists publicly available datasets encompassing the following modalities:
 - Visual-audio
 - Audio and speech
 - Biomedical signals (e.g., EEG, ECG, etc.)

Though we updated it on a regular basis, we may miss some most recent ones. Feel free to let us know by creating a new issue :)
## Visual-audio (updated 07-24-2024)
### Deepfakes
[**Kaggle The Global Multimedia Deepfake Detection**](https://www.kaggle.com/competitions/multi-ffdv/data): The total amount of the training set is about 250,000 videos (with audio), and the ratio of Deepfake audio-video files to real face audio-video files is about 3:1. For Deepfake audio-video files, it can be subdivided into three subcategories: fake_audio_fake_visual, real_audio_fake_visual, and fake_audio_real_visual, and the ratio is about 1:1:1. All the audio-video files in the competition have been preprocessed uniformly with the same frame size, frame rate and audio sampling frequency.

[**FaceForensics**](https://github.com/ondyari/FaceForensics): 5k+ videos; face-swapping; majority is non-EN audios.

[**Deepfake Detection Challenge Dataset (DFDC)**](https://ai.meta.com/datasets/dfdc/): 10k+ videos; face-swapping; EN.

[**DF-TIMIT**](https://www.idiap.ch/en/scientific-research/data/deepfaketimit): 600+ videos; faceswapping; EN.

[**Celeb-DF**](https://github.com/yuezunli/celeb-deepfakeforensics): 6k+ videos; face swapping; EN;

[**FakeAVCeleb**](https://sites.google.com/view/fakeavcelebdash-lab/): 20k+ videos; fake audio and face; EN.

[**WildDeepfake**](https://github.com/deepfakeinthewild/deepfake-in-the-wild): 7k+ videos; from Internet.

## Speech-datasets (updated 07-24-2024)
### Deepfakes
[**ASVspoof 5**](https://www.asvspoof.org/): (Ongoing challenge) Audio deepfake dataset with ~160K samples in training and similar size for validation, and ~680K samples in the evaluation set. Since the challenge is ongoing, registration is required to obtain access to all data.

[**MLAAD**](https://deepfake-total.com/mlaad): Multi-lingual deepfake audios generated by 23 types of TTS and VC systems.

[**ASVspoof 2021**](https://www.asvspoof.org/index2021.html): the commonly used deepfake dataset from the ASVspoof challenge series. This is the 2021 version which includes a deepfake track, with 600K utterances from a variety of generation algorithms and codecs. See also the [2019 version](https://datashare.ed.ac.uk/handle/10283/3336), which also has some DFs in the LA track.

[**WaveFake**](https://github.com/RUB-SysSec/WaveFake): include only crafted speech based on the data from LJ speech corpus. For each genuine utterance, it comes with more than 10 different DF versions.

[**In-the-wild**](https://deepfake-demo.aisec.fraunhofer.de/in_the_wild): in-the-wild deepfakes, including genuine and crafted ones from celebrity voices.

[**ADD**](): mandarin deepfake detection challenge databases. Link to be updated.

[**Half-truth audio detection (HAD)**](): partial-deepfake and fully-deepfake utterances. Link to be updated.

[**Partial Spoof**](https://zenodo.org/record/4817532): partially-spoofed utterances contain a mix of both spoofed and bona fide segments.

[**SceneFake**](https://zenodo.org/record/7663324): acoustic scene is crafted while voice itself remains unchanged. Detailed generation pipeline can be found in the [paper](https://arxiv.org/pdf/2211.06073.pdf).

[**Singfake**](https://singfake.org/): In-the-wild dataset consisting of 28.93 hours of bonafide and 29.40 hours of deepfake song clips in five languages from 40 singers. Train/valid/test splits were provided with the data.


### Healthcare
[**The UK COVID-19 Vocal Audio Dataset**](https://zenodo.org/records/10043978): Audio recordings of volitional coughs, exhalations, and speech alongside demographic, self-reported symptom and respiratory condition data, and linked to SARS-CoV-2 PCR test results. A total of 72,999 participants (25,776 tested positive). This dataset has additional potential uses for bioacoustics research, with 11.30% participants reporting asthma, and 27.20% with linked influenza PCR test results.

[**Cambridge COVID Sound**](https://openreview.net/pdf?id=9KArJb4r5ZQ): (obtained upon requests) includes ~300H of voice, cough, and breathing data collected remotely from healthy and COVID individuals. It comes with rich metadata, such as COVID-status, gender, age, symptom, pre-existing medical conditions. However, the COVID labels are self-reproted not PCR-validated.

[**Coswara**](https://github.com/iiscleap/Coswara-Data): COVID-19 sounds (voice, cough, breathing) collected in India. See also the related [DiCOVA 1&2 challenge datasets](https://dicova2021.github.io/). The challenge ones are obtained upon requests.

[**ComParE 2021 COVID Detection Dataset**](http://www.compare.openaudio.eu/now/): (obtained upon requests) includes ~3K audio samples (speech, cough, and breathing) from COVID and healthy individuals. This is an INTERSPEECH challenge dataset.

[**TORGO**](http://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html): in-lab voice recordings from individuals with dysarthria. It also provides the text groudtruth and articulatory traces.

[**Nemours**](): (link to be updated) ~800 sentence utterances collected in-lab from individuals with different degrees of dysarthria. Labels are intelligibility.

[**NCSC**](): (link to be updated) sentence utterances from individuals who received a cervical tumor surgery, with binary labels (low- / high-intelligibility)

[**KSoF-C**](https://zenodo.org/record/6460102): (obtained upon request) Original version contains 5K 3-sec speech segments from 37 German speakers. The segments contain speech of persons who stutter. The one used in the INTERSPEECH 2022 ComParE challenge (KSOF-C) only features 4601 non-ambiguously labeled segments, where segments are classified as one of the 8 classes - the seven stuttering-related classes and an eighth “garbage” class, denoting unintelligible segments, segments containing no speech, or segments that are negatively affected by loud background noise.

[**Sep-28k**](https://github.com/apple/ml-stuttering-events-dataset/): A Dataset for Stuttering Event Detection from Podcasts with People Who Stutter. It contains stuttering event annotations for approximately 28,000 3-second clips (English). In addition they include stutter event annotations for about 4,000 3-second clips from the FluencyBank dataset.

[**DAIC-WOZ**](https://dcapswoz.ict.usc.edu/): (obtained upon request) this dataset includes audio-visual interviews of 189 participants, male and female, who underwent evaluation of psychological distress. Each participant was assigned a self-assessed depression score through the patient health questionnaire (PHQ-8) method. A total of ~58H of audio data.

[**MDVR-KCL**](https://zenodo.org/records/2867216): scripted and spontaneous speech recordings from healthy and individuals with Parkinson's disease. Labels are binary PD/Healthy. Other rating labels are available as well.

## Biosignal-datasets
TBD



# Contribute & Author
For contribution or questions, please contact at [Yi.Zhu@inrs.ca].



