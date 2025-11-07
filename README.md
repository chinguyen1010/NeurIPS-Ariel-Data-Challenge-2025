# NeurIPS: Ariel Data Challenge 2025 (sponsor by UCL)
Derive exoplanet signals from Ariel's optical instruments. Create models that clean up messy telescope data in order to see the faint chemical traces in exoplanet atmospheres
<img width="560" height="280" alt="image" src="https://github.com/user-attachments/assets/437b5052-71b5-4862-9835-0c7138d61e3b" />

Description
When an exoplanet passes in front of its host star, a small amount of starlight filters through the planet's atmosphere. This technique, known as transit spectroscopy, enables researchers to analyze atmospheric composition. However, these signals are incredibly faint, often hidden by complex, time-dependent noise from both the instruments and the stars themselves.

In this competition, you'll work with simulated data from ESA's Ariel mission, which aims to characterize 1,000 exoplanets after its 2029 launch. Your goal is to recover the true exoplanet spectrum from these noisy observations.

This year's competition builds off of the 2024 competition of a similar nature, with a dataset that has been updated to be more realistic, incorporating effects such as stellar limb darkening, validated star-planet pairs, more diverse atmospheric models, and Ariel's actual observation cadence. This introduces new challenges related to generalization, data efficiency, and integrating observations from multiple visits.

Your work could help accelerate the field of exoplanet research, directly support scientists preparing for the European Space Agency's (ESA) upcoming Ariel mission and deepen our understanding of these distant worlds, and ultimately contribute to answering one of astronomy's most profound questions: Are we alone in the universe?

Evaluation:


<img width="754" height="624" alt="Screenshot 2025-11-06 at 10 58 04 PM" src="https://github.com/user-attachments/assets/6c713a36-f652-4824-903b-372dd9863e19" />


Submission File:

You must predict a mean and uncertainty for each planet_id. An example submission file is included in the Data Files. Each submission row must include 567 columns, so we will not attempt to provide an example here. The leftmost column must be the planet_id, the next 283 columns must be the spectra, and the remaining columns the uncertainties.

