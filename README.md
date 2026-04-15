# Blanking Circuit for Synchronizing a Projector DLP471TPEVM with Mini2P Scanning
**Overview**
This repository presents the design, implementation, and validation of a blanking circuit used to synchronize a DLP projector with a Mini2P scanning system.

The projector displays visual stimuli in an area where a mouse can freely move. Depending on the task and experimental conditions, the mouse interacts with the presented visual scene by adjusting its movement relative to the projected image.

**Motivation**
In two-photon imaging, it is essential to suppress external light sources during data acquisition. The projector is used for visual stimulation but introduces optical artifacts if active during scanning.

The blanking circuit ensures precise temporal control of the projection, activating it only during appropriate phases.

**System Description**