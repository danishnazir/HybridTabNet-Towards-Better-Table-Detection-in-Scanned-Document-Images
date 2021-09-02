# HybridTabNet-Towards-Better-Table-Detection-in-Scanned-Document-Images
Tables in the document image are one of the most important entities since they contain crucial information.~Therefore, accurate table detection can significantly improve information extraction from tables.~In this work, we present a novel end-to-end trainable pipeline, HybridTabNet, for table detection in scanned document images.~Our two-stage table detector uses the ResNeXt-101 backbone for feature extraction and Hybrid Task Cascade (HTC) to localize the tables in scanned document images. Moreover, we replace conventional convolutions with deformable convolutions in the backbone network. This enables our network to detect tables of arbitrary layouts precisely. We evaluate our approach comprehensively on ICDAR-13, ICDAR-17 POD, ICDAR-19, TableBank, Marmot, and UNLV. Apart from the ICDAR-17 POD dataset, our proposed HybridTabNet outperforms earlier state-of-the-art results without depending on pre and post-processing steps. Furthermore, to investigate how the proposed method generalizes unseen data, we conduct an exhaustive leave-one-out-evaluation. In comparison to prior state-of-the-art results, our method reduces the relative error by 27.57% on ICDAR-2019-TrackA-Modern, 42.64% on TableBank (Latex), $41.33\%$ on TableBank (Word), 55.73% on TableBank (Latex + Word), 10% on Marmot, and 9.67% on UNLV dataset. The achieved results reflect the superior performance of the proposed method.
