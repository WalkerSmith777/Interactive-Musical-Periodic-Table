# Interactive-Musical-Periodic-Table

Welcome to the interactive musical periodic table! This is a program in Max/MSP that sonifies the visible spectra of chemical elements.
The original project was documented in an SMC 2024 paper: https://smcnetwork.org/smc2024/papers/SMC2024_paper_id192.pdf
However, this is the first time the code is being released. This release features new design additions documented in a paper submitted to the 2025 AudioMostly Conference.

A short video guide to the Max patch (accompanying the original SMC 2024 paper) can be found here: https://drive.google.com/file/d/1Vip9FK3LUlwAOh74fPBf_WBMF14fMBTZ/view

Using the patch should be pretty plug-and-play. If you click on an element and don't hear any sound, it is likely because Max cannot find the TSV files containing the element data. In Max, go to Options->File Preferences, and clikc the "+" icon at the bottom left. Then, click the "choose" button that pops up, and select the folder that the Max patch is in (the folder you just unzipped), and click the box under "Subfolders" on the far right. You may need to quit and restart Max to get it to work.

This was made in Max 8.6.3. I haven't tested it in Max 9. If you find it does not work in Max 9, please let me know :)

Enjoy!

