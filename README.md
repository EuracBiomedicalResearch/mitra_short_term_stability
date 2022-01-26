# Short-term stability of Neoteryx Mitra blood microsamples

In this project the short-term stability of Neoteryx Mitra blood microsamples is
evaluated using an untargeted metabolomics setup for polar metabolites. The
impact of different storage conditions on metabolite concentrations is
investigated.

The data analysis files defining this analysis are:

- [sts_preprocessing_neg.Rmd](sts_preprocessing_neg.Rmd): pre-processing of the
  negative polarity data.
- [sts_preprocessing_pos.Rmd](sts_preprocessing_pos.Rmd): pre-processing of the
  positive polarity data.
- [sts_normalization_neg.Rmd](sts_normalization_neg.Rmd): data normalization
  (negative polarity).
- [sts_normalization_pos.Rmd](sts_normalization_pos.Rmd): data normalization
  (positive polarity).
- [sts_targeted_neg.Rmd](sts_targeted_neg.Rmd): differential abundance analysis
  for the semi-targeted data, negative polarity.
- [sts_targeted_pos.Rmd](sts_targeted_pos.Rmd): differential abundance analysis
  for the semi-targeted data, positive polarity.
- [sts_untargeted_neg.Rmd](sts_untargeted_neg.Rmd): differential abundance
  analysis for the untargeted data, negative polarity.
- [sts_untargeted_pos.Rmd](sts_untargeted_pos.Rmd): differential abundance
  analysis for the untargeted data, positive polarity.

Analysis files need to be processed in the above order.
