In superconducting magnets, the irreversible transition of a portion of the coils to the resistive state is called “quench.” Having large stored energy, quenches can lead to damage of magnet components due to localized heating, high voltage, or large mechanical forces. Unfortunately, current quench protection systems can only detect the quench after it happens, giving magnet operators very short response time (a few ms). In this study, we propose a quench prediction system using an auto-encoder fully-connected deep neural network. When incrementally trained with expert features extracted from acoustic data in sensors around the magnet, the system can potentially forecast the quench seconds before it happens. This leads to better diagnostics and detection of magnet quenches, which eventually speed up magnet testing processes and prevent expensive parts from being damaged.