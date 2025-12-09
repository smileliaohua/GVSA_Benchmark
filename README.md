# GVSA_Benchmark
Can AI Observe Geographical Space? Evaluating Geo-Visuospatial Ability of Large Multimodal Models

The 'Dataset' folder contains all the test images.
This 'Test_results_20251209.xlsx' file contains the performance records of eight state-of-the-art multimodal large language models (MLLMs): Hunyuan-Vision, QWEN-VL-Plus, GLM-4V-Plus, Gemini-2.0, Claude-3.5-Sonnet, GPT-4o and DeepSeek-VL2, under zero-shot, zero-CoT, and one-shot prompting strategies; GPT-5 under zero-shot and complex COT.

# 1. Model

1. Hunyuan-Vision
2. QWEN-VL-Plus
3.  GLM-4V-Plus
4. Gemini-2.0
5. Claude-3.5-Sonnet
6. DeepSeek-VL2
7. GPT-4o
8. GPT-5

# 2. Category

1. G-IS: Geographic Intrinsic-static (IS)
2. G-ID: Geographic Intrinsic-dynamic (ID)
3. G-ES: Geographic Extrinsic-static (ES)
4. G-ED: Geographic Extrinsic-dynamic (ED)
5. NG-IS: Non-geographic Intrinsic-static (IS)
6. NG-ID: Non-geographic Intrinsic-dynamic (ID)
7. NG-ES: Non-geographic Extrinsic-static (ES)
8. NG-ED: Non-geographic Extrinsic-dynamic (ED)

# 3. Prompt Strategy

1. zero shot
2. zero CoT：simple COT and complex COT
3. one shot

# 4. Tests

1. Map Overlay (Robert Bednarz & Lee, 2012)
2. Spatial Positioning and Orientation(Robert Bednarz & Lee, 2012; Newcombe et al., 2015)
3. Intersection Decision
4. Spatial Relation (Robert Bednarz & Lee, 2012; Jiang, 2018)
5. Best Location Selection (Robert Bednarz & Lee, 2012; Jiang, 2018)
6. Spatial Localization
7. Water Level (Brase & Hill, 2017)
8. Spatial Construction (Robert Bednarz & Lee, 2012; Jiang, 2018)
9. Spatial Deconstruction (Robert Bednarz & Lee, 2012; Jiang, 2018)
10. Cube Comparison (CP) (Ekstrom et al., 1976)
11. Card Rotation Test (CRT) (Ekstrom et al., 1976)
12. Cross Section Test (CST) (Cohen & Hegarty, 2012)
13. Mental Rotation Test (MRT) (Vandenberg & Kuse, 1978)
14. Purdue Spatial Visualization Test-Rotation (PD-R) (Bodner & Guay, 1997)
15. Purdue Spatial Visualization Test-Development (PD-D) (Bodner & Guay, 1997)
16. Purdue Spatial Visualization Test-View (PD-V) (Bodner & Guay, 1997)
17. Paper Folding Test (PFT) (Ekstrom et al., 1976)
18. Interpreting Contour Maps (Newcombe et al., 2015)
19. Comprehending Geographic Feature (Robert Bednarz & Lee, 2012)
20. Hidden Figures Test (HFT) (Ekstrom et al., 1976)
21. Hidden Patterns Test (HPT) (Ekstrom et al., 1976)
22. Perspective Taking/Spatial Orientation Test (PTSOT) (Hegarty, 2004; Friedman et al., 2020)

Note: Items whose question number ends with the letter “A” were generated with AI assistance. “CGFA” in Comprehending Geographic Features, “SDA” in Spatial Deconstruction, “LCA” in Spatial Localization, and “IDA” in Intersection Decision.

# 5. Language

Each item was tested in Chinese and English.

# 6. Test rounds

Each item was tested and re-tested under zero shot (two rounds).

# References

Bodner, G. M., & Guay, R. B. (1997). The Purdue Visualization of Rotations Test. _The Chemical Educator_, _2_(4), 1–17. https://doi.org/10.1007/s00897970138a

Brase, G. L., & Hill, W. T. (2017). Adding up to good Bayesian reasoning: Problem format manipulations and individual skill differences. _Journal of Experimental Psychology: General_, _146_(4), 577–591. https://doi.org/10.1037/xge0000280

Cohen, C. A., & Hegarty, M. (2012). Inferring cross sections of 3D objects: A new spatial thinking test. _Learning and Individual Differences_, _22_(6), 868–874. https://doi.org/10.1016/j.lindif.2012.05.007

Ekstrom, R. B., French, J. W., & Harman, H. H. (1976). _Kit of Factor-Referenced Cognitive Tests_.

Friedman, A., Kohler, B., Gunalp, P., Boone, A. P., & Hegarty, M. (2020). A computerized spatial orientation test. _Behavior Research Methods_, _52_(2), 799–812. https://doi.org/10.3758/s13428-019-01277-3

Hegarty, M. (2004). A dissociation between mental rotation and perspective-taking spatial abilities. _Intelligence_, _32_(2), 175–191. https://doi.org/10.1016/j.intell.2003.12.001

Newcombe, N. S., Weisberg, S. M., Atit, K., Jacovina, M. E., Ormand, C. J., & Shipley, T. F. (2015). The Lay of the Land: Sensing and Representing Topography. _Baltic International Yearbook of Cognition, Logic and Communication_, _10_(1). https://doi.org/10.4148/1944-3676.1099

Robert Bednarz, & Lee, J. (2012). Components of Spatial Thinking: Evidence from a Spatial Thinking Ability Test. _Journal of Geography_, _111_(1), 15–26. https://doi.org/10.1080/00221341.2011.583262

Vandenberg, S. G., & Kuse, A. R. (1978). Mental Rotations, a Group Test of Three-Dimensional Spatial Visualization. _Perceptual and Motor Skills_, _47_(2), 599–604. https://doi.org/10.2466/pms.1978.47.2.599

Jiang Lianfei. (2018). A Research on Geospatial Thinking of Pre-service Geography Teacher. [PhD Thesis] East China Normal University.
