## What I learned
- GPR B-scans: buried utilities appear as hyperbolas, and I learned to
  inspect and preprocess them before training.
- Extending a simple binary CNN to a 3-class classifier, and evaluating it
  with a confusion matrix and per-class recall.

## Limitations
- Single public dataset; the split was [by image / by survey], so test
  performance may be optimistic.
- No depth information, since PNG images carry no metadata.

## Next steps
- Compare with a pretrained ResNet, and try YOLO detection on a
  hyperbola dataset.

  ## Dataset

This project uses the public GPR dataset from Mendeley Data:
- **Title:** Intelligent recognition of subsurface utilities and voids: A Ground Penetrating Radar dataset for Deep Learning applications
- **Link:** https://doi.org/10.17632/ww7fd9t325.1
- **Licence:** CC by 4.0
