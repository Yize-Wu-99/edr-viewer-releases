# WinEDR, pCLAMP and Clampfit files on Mac

[EDR Viewer for Mac](README.md) opens electrophysiology recordings on Apple Silicon Macs running macOS 14 or later. This guide explains which workflows it can help with before you download.

## WinEDR for Mac: opening EDR recordings

If you have a WinEDR .edr recording and want to inspect it on a Mac, open the file in EDR Viewer. Viewer Mode provides trace inspection and A/B region measurements without activation. Check the displayed sampling rate, channel units and signal before interpreting a recording.

EDR Viewer reads recording files; it does not run WinEDR or control recording hardware.

## pCLAMP for Mac: viewing ABF and ATF files

For recordings made with pCLAMP / Axon software, EDR Viewer supports ABF and ATF imports. Multi-sweep ABF recordings are opened one selected sweep at a time. Compatibility depends on the file variant; support for these formats does not guarantee every file or acquisition configuration.

If you searched for “pcamp for Mac”, the electrophysiology software name is **pCLAMP**.

## Clampfit for Mac: choosing a recording viewer

If your goal is to view an ABF trace or make A/B measurements on macOS, try the free Viewer Mode with your own recording. Optional Full Access adds processing, FFT/PSD, exports and Analysis.

EDR Viewer is a separate application, not an official Mac version of Clampfit or pCLAMP. It does not promise complete feature or numerical equivalence with Clampfit, and does not provide acquisition or instrument control. Choose software according to the analysis and validation your experiment requires.

## EDR, ABF, ATF and numerical text files

| File | Typical use | Import consideration |
| --- | --- | --- |
| EDR | WinEDR recordings | Check channels, sampling rate and units. |
| ABF | Axon / pCLAMP recordings | Select one sweep at a time for multi-sweep recordings. |
| ATF | Axon Text Format | Check the imported signal and metadata. |
| TXT, CSV, TSV | Numerical time-series data | Requires regularly sampled numerical data; confirm columns, sampling rate and units. |

## Download and installation

[Download EDR Viewer for Mac](DOWNLOAD.md) · [Installation help](INSTALL.md) · [Activation](ACTIVATION.md)

The current release is **2.18**, for **Apple Silicon (M1 or later), macOS 14+**. Download the **DMG** application installer. This release is not Apple notarized. GitHub's automatic source ZIP/TAR archives contain this distribution repository's documents and images, not the application.

Viewer Mode is free. Optional Full Access costs **£7.99 once for up to 2 Macs**; version 2.18 requires a Live key.

For a file that fails to open, [report a problem](https://github.com/Yize-Wu-99/edr-viewer-releases/issues/new) with the format, app version and error message. Do not post private experimental data or license keys publicly.
