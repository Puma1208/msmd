# Changelog

## v1.1-thesis (fork)

* Fix remaining Python 3 issues and support NumPy 2
* Handle file paths that contain spaces
* Fix the double dot in rendered MIDI file names
* Thesis settings: system detection thresholds, one upright piano sound font at tempo 1.0

## v1.1

* All note events are set to a velocity of `64` by default
* Note-audio alignment is saved in the respective mung file for all performances
* `environment.yaml` file includes only versions, no build numbers
* Data moved to Zenodo
* `all_split.yaml` cleaned from problematic pieces (repetition mistakes through Lilypond->MIDI conversion)
* `msmd_manager_app` ported to Qt5
* Package ported to Python 3

## v1.0

* Initial version