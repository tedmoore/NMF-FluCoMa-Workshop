# NMF-FluCoMa-Workshop
Materials for the Music Hackspace workshop on NMF via FluCoMa

# De-Mix Audio using FluCoMa in Max

Non-negative matrix factorization, or "NMF", is an unsupervised machine learning algorithm that can de-mix an audio recording into separate sound objects (such as snare hits, horn timbres, or vowel sounds). The sound objects it finds often correspond to how we perceive different sound objects in audio, making it very useful for creative de-mixing and re-mixing of sound materials. In this workshop we'll look at how to use NMF to (1) de-mix recorded audio into sound objects, (2) deconstruct real-time audio streams, (3) identify important sounds in real-time audio, and (4) seed this process to help the algorithm find the sound objects we're interested in.

## Outline

* What is Non-negative Matrix Factorization (NMF)?
* NMF for spectral-temporal decomposition
    - fluid.bufnmf~
* Real-time spectral decomposition
    - fluid.nmffilter~
* Real-time sound object identification
    - fluid.nmfmatch~
* Seeding NMF
    - seeding bases to focus on certain templates
    - seeding activations to focus on certain moments in time
* Over-separating and recombining bases
* BufNMFCross