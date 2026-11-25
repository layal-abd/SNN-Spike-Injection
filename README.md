# Spike-injection attacks and threshold-guarding defense for SNN keyword spotting

COMP 500 project, Beirut Arab University.

## What this is
A spiking neural network (SNN) classifies one-second clips of "yes" vs "no" from the Google Speech Commands dataset. We attack it by injecting fake spikes into the hidden layer and test a threshold-guarding training defense.

## How to run
1. Open `snn_experiments.ipynb` in Google Colab (File > Upload notebook).
2. Set Runtime > Change runtime type > T4 GPU.
3. Run the cells in order. Results are saved to Google Drive in a folder called `snn_project`.

## Files
- `snn_experiments.ipynb`: all code
- `final_asr_curves.csv`, `final_summary.csv`: final results (5 seeds)
- `fig_*.pdf`: figures used in the report

## Team
Layal Abdulwahab, Samir Misto, Hiba Hweidi, Reem Saad. Supervisor: Dr. Mustapha Bizri
