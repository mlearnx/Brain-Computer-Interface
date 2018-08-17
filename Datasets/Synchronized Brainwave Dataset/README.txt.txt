Source: https://www.kaggle.com/berkeley-biosense/synchronized-brainwave-dataset

Desctiption:
- File eeg_data (electroencephalography data)
  - id: Integer value in the range of 1 to 30 representing the subject. You can cross-reference these with subject-metadata.csv to learn more about each (anonymized) subject.
  - indra_time: The synchronized timing of the reading. See browser_latency below. Use this for most analyses. 
  - browser_latency: The difference between the time on the subject's computer, and the time of our server. 
  - reading_time: The time at which the Neurosky sensor data passed through the bluetooth connection onto the subject's computer.
  - attention_esense: Neurosky's eSense meters for Attention level, in integer values in the range of 0 to 100. 
  - meditation_esense: Neurosky's eSense meters for Meditation level, in integer values in the range of 0 to 100. 
  - eeg_power: Represents the magnitude of 8 commonly-recognized types of EEG frequency bands -- delta (0.5 - 2.75Hz), theta (3.5 - 6.75Hz), low-alpha (7.5 - 9.25Hz), high-alpha (10 - 11.75Hz), low-beta (13 - 16.75Hz), high-beta (18 - 29.75Hz), low-gamma (31 - 39.75Hz), and mid-gamma (41 - 49.75Hz). These values have no units and are only meaningful for comparison to the values for the other frequency bands within a sample.
  - raw_values: Tuple containing raw sample values acquired by the sensor, at a sampling rate of 512Hz.
  - signal_quality: 
  - createdAt:
  - updatedAt:
  - label: The task that the subject was doing at the time of the recording. See stimulus_times.csv.
- File stimulus_times.csv
- subject-metadata.csv
