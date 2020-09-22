# The Encephalophone

The encephalophone is based on brain-computer interfaces using an old method, called electroencephalography, which measures electrical signals in the brain.

The instrument collects brain signals through a cap that transforms specific signals into musical notes.
The invention is coupled with a synthesizer, allowing the user to create music using a wide variety of instrumental sounds.

**“The encephalophone may have potential applications both as a novel musical instrument without requiring movement, as well as a potential therapeutic biofeedback device for patients suffering from motor deficits (e.g., amyotrophic lateral sclerosis, brainstem stroke, traumatic amputation),”** the scientists said.

## Project in Progress
1. - [ ] Reading Raw EEG signals with MATLAB.
2. - [ ] Filtering the signals through 4th order Buttorworth Filter
3. - [ ] Saving the filtered EEG signals as a CSV file.
4. - [x] Reading the filtered signals and creating dataframe of Alpha/Theta waves.
5. - [x] Reranging the EEG signals to the audible range.
6. - [x] Converting the signals to Musical Notes and playing them
7. - [ ] Feeding the Musical notes to CNN.
8. - [ ] Training the CNN to generate further music.
9. - [ ] (Optional) Decipher the music notes by music fingerprinting to find the similiar song.
10. - [ ] (Optional) Streamlining the processes.

## Research paper references
1. [The Encephalophone: A Novel Musical Biofeedback Device using Conscious Control of Electroencephalogram (EEG)](https://doi.org/10.3389/fnhum.2017.00213)
2. [Encephalophone - Google Patents](https://patents.google.com/patent/US20160027423A1/en)
3. [A closed-loop, music-based brain-computer interface for emotion mediation](https://doi.org/10.1371/journal.pone.0213516)
4. [A Simplified Encephalophone](https://psycnet.apa.org/doi/10.1126/science.105.2721.216)

## Project Structure

 File/Directory      | Details        
  ------------------ | ----------------------------------------------- 
 csv_files           | Simplified and generated EEG signal datasets   
 preprocessing.ipynb | Preprocessing Notebook(*in progress*)                  
 sound.ipynb         | Converted Alpha/Theta signal data to musical notes     

