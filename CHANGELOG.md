Change Log
==========
Versioned according to [Semantic Versioning](http://semver.org/).

## Unreleased

Fixed:

  * repaired `operation_level=region` (typo)

Changed:

  * Trained models loadable and registered in SavedModel format
  * Test both models, deployed normally (not in CWD)
  * Test input with actual regions in `operation_level=region`

## [0.0.11] - 2022-10-24

Added:

  * Trained models listed in ocrd-tool.json for download with OCR-D resource manager, #53

## [0.0.10] - 2022-07-21

Fixed:

  * Use correct import, `s/click/types`, #40

## [0.0.9] - 2022-04-26

Changed:

  * Factor setup by @bertsky in #31
  * use TF2 (with TF1.compat mode) by @cneud in #35

## [0.0.8] - 2021-02-02

Fixed:

  * handle image smaller than patch size
  * fix unbound variable error, #27

## [0.0.7] - 2021-02-02

Changed:

  * Use OCR-D/core resource resolving, #25

## [0.0.6] - 2020-11-23

Fixed:

  * Require h5py < 3, qurator-spk/sbb_textline_detection#50, #18
  * Require `tensorflow-gpu` (CPU+GPU), not `tensorflow` (CPU only), #20

## [0.0.5] - 2020-11-02

Fixed:

  * Memory leak, start tf session only once, #17 ht @sulzbals

## [0.0.4] - 2020-10-27

Changed:

  * Env var `SBB_BINARIZE_DATA` is combined with `model` param now, #9

## [0.0.3]

Fixed:

  * typo broke `sbb_binarize` CLI, #13

## [0.0.2]

Changed:

  * `SBB_BINARIZE_DATA` can replace `model` parameter, #6

Fixed:

  * AlternativeImage/comments now set on page level, #8, #11
  * Only try to load `*.h5` model files, #7, #10

## [0.0.1]

Initial release

<!-- link-labels -->
[0.0.11]: ../../compare/v0.0.11...v0.0.10
[0.0.10]: ../../compare/v0.0.10...v0.0.9
[0.0.9]: ../../compare/v0.0.9...v0.0.8
[0.0.8]: ../../compare/v0.0.8...v0.0.7
[0.0.7]: ../../compare/v0.0.7...v0.0.6
[0.0.6]: ../../compare/v0.0.6...v0.0.5
[0.0.5]: ../../compare/v0.0.6...v0.0.4
[0.0.4]: ../../compare/v0.0.4...v0.0.3
[0.0.3]: ../../compare/v0.0.3...v0.0.2
[0.0.2]: ../../compare/v0.0.1...v0.0.2
