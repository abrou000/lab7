# lab7

Show in New WindowClear OutputExpand/Collapse Output

Call:
glm(formula = NOTCOV ~ AGE_P + I(AGE_P^2) + female + I(female * 
    AfAm) + AfAm + Asian + RaceOther + Hispanic + educ_hs + educ_smcoll + 
    educ_as + educ_bach + educ_adv + married + widowed + divorc_sep + 
    veteran_stat + REGION + region_born, family = binomial, data = data_now)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-1.9153  -0.6468  -0.4511  -0.2505   3.0100  

Coefficients:
                                Estimate Std. Error z value Pr(>|z|)    
(Intercept)                   -3.7999888  0.1496801 -25.387  < 2e-16 ***
AGE_P                          0.1672872  0.0085757  19.507  < 2e-16 ***
I(AGE_P^2)                    -0.0023891  0.0001161 -20.577  < 2e-16 ***
female                        -0.2370174  0.0258184  -9.180  < 2e-16 ***
I(female * AfAm)              -0.2855779  0.0648674  -4.402 1.07e-05 ***
AfAm                           0.0051600  0.0475354   0.109 0.913559    
Asian                         -0.2192390  0.0793556  -2.763 0.005732 ** 
RaceOther                      0.4505916  0.0722408   6.237 4.45e-10 ***
Hispanic                       0.3364628  0.0362447   9.283  < 2e-16 ***
educ_hs                       -0.2298569  0.0323491  -7.106 1.20e-12 ***
educ_smcoll                   -0.6721174  0.0372211 -18.057  < 2e-16 ***
educ_as                       -0.7771953  0.0460378 -16.882  < 2e-16 ***
educ_bach                     -1.5252846  0.0476983 -31.978  < 2e-16 ***
educ_adv                      -2.1619735  0.0785345 -27.529  < 2e-16 ***
married                       -0.6739778  0.0293591 -22.956  < 2e-16 ***
widowed                        0.0444429  0.1339570   0.332 0.740063    
divorc_sep                    -0.0697274  0.0435541  -1.601 0.109390    
veteran_stat                  -0.4937172  0.0670163  -7.367 1.74e-13 ***
REGIONMidwest                  0.3144762  0.0439397   7.157 8.25e-13 ***
REGIONSouth                    0.7273660  0.0381832  19.049  < 2e-16 ***
REGIONWest                     0.2801357  0.0402981   6.952 3.61e-12 ***
region_bornMex Cent Am Caribb  1.1036708  0.0407761  27.067  < 2e-16 ***
region_bornS Am                0.8900031  0.0936321   9.505  < 2e-16 ***
region_bornEur                 0.3671289  0.1125440   3.262 0.001106 ** 
region_bornformer USSR         0.8896666  0.2236605   3.978 6.96e-05 ***
region_bornAfrica              0.7724510  0.1167299   6.617 3.66e-11 ***
region_bornMidE                0.5049012  0.1839923   2.744 0.006067 ** 
region_bornIndia subc          0.9189978  0.1276025   7.202 5.93e-13 ***
region_bornAsia                0.9179534  0.1222180   7.511 5.88e-14 ***
region_bornSE Asia             0.4053055  0.1130062   3.587 0.000335 ***
region_bornElsewhere           0.1708926  0.1833610   0.932 0.351336    
region_bornunknown            -0.1395570  0.2068602  -0.675 0.499902    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for binomial family taken to be 1)

    Null deviance: 54744  on 56069  degrees of freedom
Residual deviance: 46600  on 56038  degrees of freedom
AIC: 46664

Number of Fisher Scoring iterations: 5

Show in New WindowClear OutputExpand/Collapse Output
   Mode   FALSE    TRUE 
logical   50413    5657 
        Age.V1        female    I_female.t.AfAm AfAm      Asian     RaceOther
 Min.   :-1.7029972   1:26028   1: 4103         1: 7361   1: 3901   1: 1019  
 1st Qu.:-0.8901584   0:24385   0:46310         0:43052   0:46512   0:49394  
 Median : 0.0129957                                                          
 Mean   :-0.0053816                                                          
 3rd Qu.: 0.8258344                                                          
 Max.   : 1.6386732                                                          
 Hispanic  educ_hs   educ_smcoll educ_as   educ_bach educ_adv  married  
 1:11940   1:13210   1:10231     1: 5468   1: 8990   1: 4589   1:25522  
 0:38473   0:37203   0:40182     0:44945   0:41423   0:45824   0:24891  
                                                                        
                                                                        
                                                                        
                                                                        
 widowed   divorc_sep Region.Midwest Region.South Region.West
 1:  368   1: 4587    1: 9933        1:17488      1:14908    
 0:50045   0:45826    0:40480        0:32925      0:35505    
                                                             
                                                             
                                                             
                                                             
 born.Mex.CentAm.Carib born.S.Am born.Eur  born.f.USSR born.Africa born.MidE
 1: 6614               1:  623   1:  665   1:  140     1:  455     1:  240  
 0:43799               0:49790   0:49748   0:50273     0:49958     0:50173  
                                                                            
                                                                            
                                                                            
                                                                            
 born.India.subc born.Asia born.SE.Asia born.elsewhere born.unknown
 1:  797         1:  737   1: 1172      1:  251        1:  157     
 0:49616         0:49676   0:49241      0:50162        0:50256     
                                                                   
                                                                   
                                                                   
                                                                   
Show in New WindowClear OutputExpand/Collapse Output
The following objects are masked from data_now (pos = 3):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following objects are masked from data_now (pos = 4):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following object is masked from asecpub20sas (pos = 11):

    NOTCOV

The following object is masked from asecpub20sas (pos = 12):

    NOTCOV

The following objects are masked from data_now (pos = 3):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following objects are masked from data_now (pos = 4):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following object is masked from asecpub20sas (pos = 11):

    NOTCOV

The following object is masked from asecpub20sas (pos = 12):

    NOTCOV

Show in New WindowClear OutputExpand/Collapse Output

Call:
lm(formula = sobj$formula, data = sobj$data)

Residuals:
     Min       1Q   Median       3Q      Max 
-0.63862 -0.20360 -0.11142 -0.00868  1.04431 

Coefficients:
                        Estimate Std. Error t value Pr(>|t|)    
(Intercept)             0.472978   0.111028   4.260 2.08e-05 ***
Age                    -0.015694   0.005750  -2.730 0.006362 ** 
female1                -0.017065   0.005255  -3.247 0.001171 ** 
I_female.t.AfAm1        0.007405   0.014289   0.518 0.604337    
AfAm1                  -0.020919   0.011289  -1.853 0.063918 .  
Asian1                 -0.014532   0.015185  -0.957 0.338610    
RaceOther1              0.026978   0.017561   1.536 0.124550    
Hispanic1               0.010063   0.008236   1.222 0.221803    
educ_hs1               -0.034208   0.008036  -4.257 2.11e-05 ***
educ_smcoll1           -0.073263   0.008700  -8.421  < 2e-16 ***
educ_as1               -0.078265   0.010042  -7.794 7.70e-15 ***
educ_bach1             -0.098531   0.009087 -10.843  < 2e-16 ***
educ_adv1              -0.102580   0.011160  -9.192  < 2e-16 ***
married1               -0.034739   0.006029  -5.762 8.77e-09 ***
widowed1                0.006918   0.026520   0.261 0.794221    
divorc_sep1             0.008717   0.009771   0.892 0.372366    
Region.Midwest1         0.021773   0.008221   2.648 0.008108 ** 
Region.South1           0.046509   0.007413   6.274 3.79e-10 ***
Region.West1            0.029581   0.007751   3.816 0.000137 ***
born.Mex.CentAm.Carib1  0.124822   0.010056  12.413  < 2e-16 ***
born.S.Am1              0.053109   0.021972   2.417 0.015675 *  
born.Eur1               0.032000   0.022380   1.430 0.152815    
born.f.USSR1            0.117525   0.045699   2.572 0.010145 *  
born.Africa1            0.033527   0.022743   1.474 0.140489    
born.MidE1              0.041920   0.036576   1.146 0.251801    
born.India.subc1        0.062325   0.025185   2.475 0.013364 *  
born.Asia1              0.049888   0.023724   2.103 0.035523 *  
born.SE.Asia1           0.053692   0.021104   2.544 0.010982 *  
born.elsewhere1        -0.023603   0.033850  -0.697 0.485655    
born.unknown1          -0.014666   0.039205  -0.374 0.708351    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.3642 on 5627 degrees of freedom
Multiple R-squared:  0.1387,	Adjusted R-squared:  0.1342 
F-statistic: 31.24 on 29 and 5627 DF,  p-value: < 2.2e-16

contrasts dropped from factor femalecontrasts dropped from factor I_female.t.AfAmcontrasts dropped from factor AfAmcontrasts dropped from factor Asiancontrasts dropped from factor RaceOthercontrasts dropped from factor Hispaniccontrasts dropped from factor educ_hscontrasts dropped from factor educ_smcollcontrasts dropped from factor educ_ascontrasts dropped from factor educ_bachcontrasts dropped from factor educ_advcontrasts dropped from factor marriedcontrasts dropped from factor widowedcontrasts dropped from factor divorc_sepcontrasts dropped from factor Region.Midwestcontrasts dropped from factor Region.Southcontrasts dropped from factor Region.Westcontrasts dropped from factor born.Mex.CentAm.Caribcontrasts dropped from factor born.S.Amcontrasts dropped from factor born.Eurcontrasts dropped from factor born.f.USSRcontrasts dropped from factor born.Africacontrasts dropped from factor born.MidEcontrasts dropped from factor born.India.subccontrasts dropped from factor born.Asiacontrasts dropped from factor born.SE.Asiacontrasts dropped from factor born.elsewherecontrasts dropped from factor born.unknown       true
pred        0     1
  FALSE 39698  7990
  TRUE   1054  1671
Show in New WindowClear OutputExpand/Collapse Output

Call:
glm(formula = sobj$formula, family = binomial, data = sobj$data)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-1.6381  -0.6460  -0.4547  -0.2823   2.6780  

Coefficients:
                       Estimate Std. Error z value Pr(>|z|)    
(Intercept)             0.57379    0.81929   0.700  0.48371    
Age                    -0.11297    0.04319  -2.616  0.00891 ** 
female1                -0.12766    0.04006  -3.187  0.00144 ** 
I_female.t.AfAm1        0.05734    0.10668   0.538  0.59091    
AfAm1                  -0.12091    0.08271  -1.462  0.14375    
Asian1                 -0.09499    0.12506  -0.760  0.44751    
RaceOther1              0.16418    0.11453   1.433  0.15172    
Hispanic1               0.06525    0.05955   1.096  0.27318    
educ_hs1               -0.15409    0.05013  -3.074  0.00212 ** 
educ_smcoll1           -0.42143    0.05894  -7.151 8.64e-13 ***
educ_as1               -0.47618    0.07463  -6.381 1.76e-10 ***
educ_bach1             -0.74718    0.07435 -10.049  < 2e-16 ***
educ_adv1              -0.90171    0.11728  -7.688 1.49e-14 ***
married1               -0.27331    0.04589  -5.955 2.60e-09 ***
widowed1                0.07639    0.18510   0.413  0.67983    
divorc_sep1             0.06716    0.06925   0.970  0.33213    
Region.Midwest1         0.19621    0.07060   2.779  0.00545 ** 
Region.South1           0.38652    0.06153   6.282 3.35e-10 ***
Region.West1            0.26886    0.06454   4.165 3.11e-05 ***
born.Mex.CentAm.Carib1  0.65820    0.06589   9.990  < 2e-16 ***
born.S.Am1              0.43594    0.15392   2.832  0.00462 ** 
born.Eur1               0.27188    0.16790   1.619  0.10539    
born.f.USSR1            0.86023    0.28871   2.980  0.00289 ** 
born.Africa1            0.25805    0.17171   1.503  0.13289    
born.MidE1              0.35021    0.26159   1.339  0.18066    
born.India.subc1        0.53806    0.19431   2.769  0.00562 ** 
born.Asia1              0.42481    0.18681   2.274  0.02297 *  
born.SE.Asia1           0.40989    0.16199   2.530  0.01139 *  
born.elsewhere1        -0.24261    0.32209  -0.753  0.45130    
born.unknown1          -0.04107    0.28563  -0.144  0.88566    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for binomial family taken to be 1)

    Null deviance: 5481.3  on 5656  degrees of freedom
Residual deviance: 4721.3  on 5627  degrees of freedom
AIC: 4781.3

Number of Fisher Scoring iterations: 5

contrasts dropped from factor femalecontrasts dropped from factor I_female.t.AfAmcontrasts dropped from factor AfAmcontrasts dropped from factor Asiancontrasts dropped from factor RaceOthercontrasts dropped from factor Hispaniccontrasts dropped from factor educ_hscontrasts dropped from factor educ_smcollcontrasts dropped from factor educ_ascontrasts dropped from factor educ_bachcontrasts dropped from factor educ_advcontrasts dropped from factor marriedcontrasts dropped from factor widowedcontrasts dropped from factor divorc_sepcontrasts dropped from factor Region.Midwestcontrasts dropped from factor Region.Southcontrasts dropped from factor Region.Westcontrasts dropped from factor born.Mex.CentAm.Caribcontrasts dropped from factor born.S.Amcontrasts dropped from factor born.Eurcontrasts dropped from factor born.f.USSRcontrasts dropped from factor born.Africacontrasts dropped from factor born.MidEcontrasts dropped from factor born.India.subccontrasts dropped from factor born.Asiacontrasts dropped from factor born.SE.Asiacontrasts dropped from factor born.elsewherecontrasts dropped from factor born.unknown       true
pred        0     1
  FALSE 39576  7859
  TRUE   1176  1802
Show in New WindowClear OutputExpand/Collapse Output

Call:
 randomForest(formula = as.factor(NOTCOV) ~ ., data = sobj$data,      importance = TRUE, proximity = TRUE) 
               Type of random forest: classification
                     Number of trees: 500
No. of variables tried at each split: 5

        OOB estimate of  error rate: 16.86%
Confusion matrix:
     0   1 class.error
0 4490  99  0.02157333
1  855 213  0.80056180
                          0     1 MeanDecreaseAccuracy MeanDecreaseGini
Age                   32.45  1.44                31.17           136.90
female                 5.32 11.89                10.65            23.13
I_female.t.AfAm        2.60  6.49                 6.42             7.44
AfAm                   1.51  7.39                 6.21            12.16
Asian                  7.16 -0.39                 6.99            10.42
RaceOther             -1.08  3.32                 0.91             9.95
Hispanic              -6.15 22.88                24.22            49.93
educ_hs               19.58 -9.84                16.49            18.73
educ_smcoll           16.29  9.67                22.25            18.08
educ_as               16.53 12.15                21.40            15.55
educ_bach             20.38 23.43                28.73            27.07
educ_adv              17.70 13.83                22.14            15.39
married               22.19 -3.09                22.00            26.48
widowed               -2.19  2.50                -0.89             3.92
divorc_sep             3.41 -1.59                 2.49            12.57
Region.Midwest        -3.04  6.58                 1.13            12.11
Region.South           2.93 22.05                18.38            23.28
Region.West            3.28  5.39                 7.77            17.16
born.Mex.CentAm.Carib  9.28 58.64                44.21            94.50
born.S.Am              4.67  4.24                 6.36             6.82
born.Eur              -1.02  5.27                 1.62             5.97
born.f.USSR           -1.50  4.62                 1.11             4.13
born.Africa           -6.80  2.05                -5.47             4.36
born.MidE             -3.85  0.03                -3.41             3.49
born.India.subc        6.72  3.68                 7.61             6.02
born.Asia              7.36  0.48                 7.29             5.47
born.SE.Asia          -0.97  4.85                 1.25             7.06
born.elsewhere         7.68 -1.97                 6.20             2.84
born.unknown          -6.15  0.45                -5.60             2.14
    true
pred     0     1
   0 39766  7943
   1   986  1718
R Console


Show in New WindowClear OutputExpand/Collapse Output
Error: attempt to use zero-length variable name
Show in New WindowClear OutputExpand/Collapse Output




Call:  glmnet(x = as.matrix(sobj$data[, -1]), y = sobj$data$NOTCOV) 

   Df  %Dev   Lambda
1   0  0.00 0.109700
2   1  1.33 0.099940
3   1  2.44 0.091060
4   1  3.36 0.082970
5   1  4.12 0.075600
6   1  4.76 0.068880
7   1  5.28 0.062760
8   1  5.72 0.057190
9   1  6.08 0.052110
10  2  6.38 0.047480
11  4  6.83 0.043260
12  4  7.43 0.039420
13  4  7.92 0.035920
14  5  8.36 0.032730
15  5  8.80 0.029820
16  5  9.16 0.027170
17  7  9.48 0.024760
18  7  9.81 0.022560
19  7 10.08 0.020550
20  9 10.34 0.018730
21 11 10.68 0.017060
22 10 11.06 0.015550
23 10 11.34 0.014170
24 10 11.58 0.012910
25 11 11.77 0.011760
26 13 11.96 0.010720
27 13 12.13 0.009764
28 16 12.29 0.008897
29 17 12.45 0.008106
30 18 12.59 0.007386
31 19 12.72 0.006730
32 18 12.83 0.006132
33 18 12.92 0.005587
34 20 12.99 0.005091
35 23 13.09 0.004639
36 23 13.20 0.004227
37 23 13.29 0.003851
38 25 13.38 0.003509
39 25 13.46 0.003197
40 25 13.52 0.002913
41 25 13.58 0.002654
42 25 13.62 0.002419
43 25 13.66 0.002204
44 25 13.69 0.002008
45 25 13.72 0.001830
46 25 13.74 0.001667
47 26 13.76 0.001519
48 26 13.77 0.001384
49 26 13.78 0.001261
50 26 13.79 0.001149
51 28 13.81 0.001047
52 28 13.81 0.000954
53 28 13.82 0.000869
54 28 13.83 0.000792
55 29 13.84 0.000722
56 29 13.84 0.000658
57 29 13.84 0.000599
58 29 13.85 0.000546
59 29 13.85 0.000497
60 29 13.85 0.000453
61 29 13.86 0.000413
62 29 13.86 0.000376
63 29 13.86 0.000343
64 29 13.86 0.000312
65 29 13.86 0.000285
66 29 13.86 0.000259
67 29 13.86 0.000236
68 29 13.86 0.000215
69 29 13.86 0.000196
70 29 13.86 0.000179
71 29 13.86 0.000163
72 29 13.86 0.000148
73 29 13.87 0.000135
74 29 13.87 0.000123
75 29 13.87 0.000112
76 29 13.87 0.000102
77 29 13.87 0.000093
[1] 0.0007919987
[1] -7.140951
30 x 1 sparse Matrix of class "dgCMatrix"
                                 1
(Intercept)            0.962236620
Age                   -0.014360333
female                 0.030732172
I_female.t.AfAm        .          
AfAm                   0.029408067
Asian                  0.008161881
RaceOther             -0.051689594
Hispanic              -0.022094952
educ_hs                0.056522128
educ_smcoll            0.133746345
educ_as                0.143537268
educ_bach              0.184653208
educ_adv               0.192192429
married                0.069028258
widowed               -0.004091736
divorc_sep            -0.014534740
Region.Midwest        -0.034436677
Region.South          -0.084621169
Region.West           -0.050123348
born.Mex.CentAm.Carib -0.250444170
born.S.Am             -0.093460250
born.Eur              -0.054321554
born.f.USSR           -0.217571792
born.Africa           -0.056747498
born.MidE             -0.069790919
born.India.subc       -0.097171798
born.Asia             -0.072562250
born.SE.Asia          -0.082339636
born.elsewhere         0.038303204
born.unknown           0.015103430
       true
pred        0     1
  FALSE 27074  3090
  TRUE  13678  6571
R Console

Call:  glmnet(x = as.matrix(sobj$data[, -1]), y = sobj$data$NOTCOV) 

   Df  %Dev   Lambda
1   0  0.00 0.109700
2   1  1.33 0.099940
3   1  2.44 0.091060
4   1  3.36 0.082970
5   1  4.12 0.075600
6   1  4.76 0.068880
7   1  5.28 0.062760
8   1  5.72 0.057190
9   1  6.08 0.052110
10  2  6.38 0.047480
11  4  6.83 0.043260
12  4  7.43 0.039420
13  4  7.92 0.035920
14  5  8.36 0.032730
15  5  8.80 0.029820
16  5  9.16 0.027170
17  7  9.48 0.024760
18  7  9.81 0.022560
19  7 10.08 0.020550
20  9 10.34 0.018730
21 11 10.68 0.017060
22 10 11.06 0.015550
23 10 11.34 0.014170
24 10 11.58 0.012910
25 11 11.77 0.011760
26 13 11.96 0.010720
27 13 12.13 0.009764
28 16 12.29 0.008897
29 17 12.45 0.008106
30 18 12.59 0.007386
31 19 12.72 0.006730
32 18 12.83 0.006132
33 18 12.92 0.005587
34 20 12.99 0.005091
35 23 13.09 0.004639
36 23 13.20 0.004227
37 23 13.29 0.003851
38 25 13.38 0.003509
39 25 13.46 0.003197
40 25 13.52 0.002913
41 25 13.58 0.002654
42 25 13.62 0.002419
43 25 13.66 0.002204
44 25 13.69 0.002008
45 25 13.72 0.001830
46 25 13.74 0.001667
47 26 13.76 0.001519
48 26 13.77 0.001384
49 26 13.78 0.001261
50 26 13.79 0.001149
51 28 13.81 0.001047
52 28 13.81 0.000954
53 28 13.82 0.000869
54 28 13.83 0.000792
55 29 13.84 0.000722
56 29 13.84 0.000658
57 29 13.84 0.000599
58 29 13.85 0.000546
59 29 13.85 0.000497
60 29 13.85 0.000453
61 29 13.86 0.000413
62 29 13.86 0.000376
63 29 13.86 0.000343
64 29 13.86 0.000312
65 29 13.86 0.000285
66 29 13.86 0.000259
67 29 13.86 0.000236
68 29 13.86 0.000215
69 29 13.86 0.000196
70 29 13.86 0.000179
71 29 13.86 0.000163
72 29 13.86 0.000148
73 29 13.87 0.000135
74 29 13.87 0.000123
75 29 13.87 0.000112
76 29 13.87 0.000102
77 29 13.87 0.000093
[1] 0.0007919987
[1] -7.140951
30 x 1 sparse Matrix of class "dgCMatrix"
                                 1
(Intercept)            0.962236620
Age                   -0.014360333
female                 0.030732172
I_female.t.AfAm        .          
AfAm                   0.029408067
Asian                  0.008161881
RaceOther             -0.051689594
Hispanic              -0.022094952
educ_hs                0.056522128
educ_smcoll            0.133746345
educ_as                0.143537268
educ_bach              0.184653208
educ_adv               0.192192429
married                0.069028258
widowed               -0.004091736
divorc_sep            -0.014534740
Region.Midwest        -0.034436677
Region.South          -0.084621169
Region.West           -0.050123348
born.Mex.CentAm.Carib -0.250444170
born.S.Am             -0.093460250
born.Eur              -0.054321554
born.f.USSR           -0.217571792
born.Africa           -0.056747498
born.MidE             -0.069790919
born.India.subc       -0.097171798
born.Asia             -0.072562250
born.SE.Asia          -0.082339636
born.elsewhere         0.038303204
born.unknown           0.015103430
       true
pred        0     1
  FALSE 27074  3090
  TRUE  13678  6571
Show in New WindowClear OutputExpand/Collapse Output
[1] 0.03314621
[1] 0.03574475
[1] 0.03407851
[1] 0.04282626
> attach(data_use1)
The following objects are masked from data_now (pos = 3):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following objects are masked from data_now (pos = 4):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following object is masked from asecpub20sas (pos = 11):

    NOTCOV

The following object is masked from asecpub20sas (pos = 12):

    NOTCOV

> usevarb<- (AGE_P>= 18) & (AGE_P <= 55)
> data_now<-subset(data_use1,usevarb)
> detach()
> attach(data_now)
The following objects are masked from data_now (pos = 3):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following objects are masked from data_now (pos = 4):

    AfAm, AGE_P, Asian, borninUSA, disabl_limit, divorc_sep,
    earn_lastyr, educ_adv, educ_as, educ_bach, educ_hs, educ_nohs,
    educ_smcoll, ERNYR_P, female, FMX, FPX, HHX, Hispan_DR,
    Hispan_Mex, Hispan_PR, Hispanic, inworkforce, married, MEDICAID,
    MEDICARE, NOTCOV, person_healthstatus, private_ins, RaceOther,
    REGION, region_born, RRP, SCHIP, sptn_medical, veteran_stat,
    widowed

The following object is masked from asecpub20sas (pos = 11):

    NOTCOV

The following object is masked from asecpub20sas (pos = 12):

    NOTCOV

> data_now$earn_lastyr <- as.factor(data_now$ERNYR_P)
> levels(data_now$earn_lastyr) <- c("0","$01-$4999","$5000-$9999","$10000-$14999","$15000-$19999","$20000-$24999","$25000-$34999","$35000-$44999","$45000-$54999","$55000-$64999","$65000-$74999","$75000 and over",NA,NA,NA)
> 
> # the purpose of this subset is to limit the interval of Age for better understnading
> # i also tried to include new variables such as personal_health status but it has not been excellent when running on the test data, so i dropped it 
> model_logit1 <- glm(NOTCOV ~ AGE_P + I(AGE_P^2) + female+ I(female*AfAm) + AfAm + Asian + RaceOther  
+                     + Hispanic + educ_hs + educ_smcoll + educ_as + educ_bach + educ_adv 
+                     + married + widowed + divorc_sep + veteran_stat + REGION + region_born,
+                     family = binomial, data = data_now)
> summary(model_logit1)

Call:
glm(formula = NOTCOV ~ AGE_P + I(AGE_P^2) + female + I(female * 
    AfAm) + AfAm + Asian + RaceOther + Hispanic + educ_hs + educ_smcoll + 
    educ_as + educ_bach + educ_adv + married + widowed + divorc_sep + 
    veteran_stat + REGION + region_born, family = binomial, data = data_now)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-1.9153  -0.6468  -0.4511  -0.2505   3.0100  

Coefficients:
                                Estimate Std. Error z value Pr(>|z|)    
(Intercept)                   -3.7999888  0.1496801 -25.387  < 2e-16 ***
AGE_P                          0.1672872  0.0085757  19.507  < 2e-16 ***
I(AGE_P^2)                    -0.0023891  0.0001161 -20.577  < 2e-16 ***
female                        -0.2370174  0.0258184  -9.180  < 2e-16 ***
I(female * AfAm)              -0.2855779  0.0648674  -4.402 1.07e-05 ***
AfAm                           0.0051600  0.0475354   0.109 0.913559    
Asian                         -0.2192390  0.0793556  -2.763 0.005732 ** 
RaceOther                      0.4505916  0.0722408   6.237 4.45e-10 ***
Hispanic                       0.3364628  0.0362447   9.283  < 2e-16 ***
educ_hs                       -0.2298569  0.0323491  -7.106 1.20e-12 ***
educ_smcoll                   -0.6721174  0.0372211 -18.057  < 2e-16 ***
educ_as                       -0.7771953  0.0460378 -16.882  < 2e-16 ***
educ_bach                     -1.5252846  0.0476983 -31.978  < 2e-16 ***
educ_adv                      -2.1619735  0.0785345 -27.529  < 2e-16 ***
married                       -0.6739778  0.0293591 -22.956  < 2e-16 ***
widowed                        0.0444429  0.1339570   0.332 0.740063    
divorc_sep                    -0.0697274  0.0435541  -1.601 0.109390    
veteran_stat                  -0.4937172  0.0670163  -7.367 1.74e-13 ***
REGIONMidwest                  0.3144762  0.0439397   7.157 8.25e-13 ***
REGIONSouth                    0.7273660  0.0381832  19.049  < 2e-16 ***
REGIONWest                     0.2801357  0.0402981   6.952 3.61e-12 ***
region_bornMex Cent Am Caribb  1.1036708  0.0407761  27.067  < 2e-16 ***
region_bornS Am                0.8900031  0.0936321   9.505  < 2e-16 ***
region_bornEur                 0.3671289  0.1125440   3.262 0.001106 ** 
region_bornformer USSR         0.8896666  0.2236605   3.978 6.96e-05 ***
region_bornAfrica              0.7724510  0.1167299   6.617 3.66e-11 ***
region_bornMidE                0.5049012  0.1839923   2.744 0.006067 ** 
region_bornIndia subc          0.9189978  0.1276025   7.202 5.93e-13 ***
region_bornAsia                0.9179534  0.1222180   7.511 5.88e-14 ***
region_bornSE Asia             0.4053055  0.1130062   3.587 0.000335 ***
region_bornElsewhere           0.1708926  0.1833610   0.932 0.351336    
region_bornunknown            -0.1395570  0.2068602  -0.675 0.499902    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for binomial family taken to be 1)

    Null deviance: 54744  on 56069  degrees of freedom
Residual deviance: 46600  on 56038  degrees of freedom
AIC: 46664

Number of Fisher Scoring iterations: 5

> d_region <- data.frame(model.matrix(~ data_now$REGION))
> d_region_born <- data.frame(model.matrix(~ factor(data_now$region_born)))  # snips any with zero in the subgroup
> dat_for_analysis_sub <- data.frame(
+   data_now$NOTCOV,
+   data_now$AGE_P,
+   data_now$female,
+   data_now$AfAm,
+   data_now$Asian,
+   data_now$RaceOther,
+   data_now$Hispanic,
+   data_now$educ_hs,
+   data_now$educ_smcoll,
+   data_now$educ_as,
+   data_now$educ_bach,
+   data_now$educ_adv,
+   data_now$married,
+   data_now$widowed,
+   data_now$divorc_sep,
+   d_region[,2:4],
+   d_region_born[,2:12]) # need [] since model.matrix includes intercept term
> 
> names(dat_for_analysis_sub) <- c("NOTCOV",
+                                  "Age",
+                                  "female",
+                                  "AfAm",
+                                  "Asian",
+                                  "RaceOther",
+                                  "Hispanic",
+                                  "educ_hs",
+                                  "educ_smcoll",
+                                  "educ_as",
+                                  "educ_bach",
+                                  "educ_adv",
+                                  "married",
+                                  "widowed",
+                                  "divorc_sep",
+                                  "Region.Midwest",
+                                  "Region.South",
+                                  "Region.West",
+                                  "born.Mex.CentAm.Carib",
+                                  "born.S.Am",
+                                  "born.Eur",
+                                  "born.f.USSR",
+                                  "born.Africa",
+                                  "born.MidE",
+                                  "born.India.subc",
+                                  "born.Asia",
+                                  "born.SE.Asia",
+                                  "born.elsewhere",
+                                  "born.unknown")
> #the principle of standardization is to get all the values under a normal curve. this will help  minimze the value of predictor
> ```{r}
Error: attempt to use zero-length variable name
> require("standardize")
> set.seed(654321)
> NN <- length(dat_for_analysis_sub$NOTCOV)
> #restrict_1 <- as.logical(round(runif(NN,min=0,max=0.55))) # use fraction as training data
> restrict_1<-(runif(NN)<0.1) # we use 10% as train data and 70% as test data
> summary(restrict_1)
   Mode   FALSE    TRUE 
logical   50413    5657 
> dat_train <- subset(dat_for_analysis_sub, restrict_1)
> dat_test <- subset(dat_for_analysis_sub, !restrict_1)
> sobj <- standardize(NOTCOV ~ Age + female + I(female*AfAm) +AfAm + Asian + RaceOther + Hispanic + 
+                       educ_hs + educ_smcoll + educ_as + educ_bach + educ_adv + 
+                       married + widowed + divorc_sep +
+                       Region.Midwest + Region.South + Region.West + 
+                       born.Mex.CentAm.Carib + born.S.Am + born.Eur + born.f.USSR + 
+                       born.Africa + born.MidE + born.India.subc + born.Asia + 
+                       born.SE.Asia + born.elsewhere + born.unknown, dat_train, family = binomial)
> s_dat_test <- predict(sobj, dat_test)
> require("standardize")
> set.seed(654321)
> NN <- length(dat_for_analysis_sub$NOTCOV)
> #restrict_1 <- as.logical(round(runif(NN,min=0,max=0.55))) # use fraction as training data
> restrict_1<-(runif(NN)<0.1) # we use 10% as train data and 70% as test data
> summary(restrict_1)
   Mode   FALSE    TRUE 
logical   50413    5657 
> dat_train <- subset(dat_for_analysis_sub, restrict_1)
> dat_test <- subset(dat_for_analysis_sub, !restrict_1)
> sobj <- standardize(NOTCOV ~ Age + female + I(female*AfAm) +AfAm + Asian + RaceOther + Hispanic + 
+                       educ_hs + educ_smcoll + educ_as + educ_bach + educ_adv + 
+                       married + widowed + divorc_sep +
+                       Region.Midwest + Region.South + Region.West + 
+                       born.Mex.CentAm.Carib + born.S.Am + born.Eur + born.f.USSR + 
+                       born.Africa + born.MidE + born.India.subc + born.Asia + 
+                       born.SE.Asia + born.elsewhere + born.unknown, dat_train, family = binomial)
> 
> s_dat_test <- predict(sobj, dat_test)
> summary(s_dat_test)
        Age.V1        female    I_female.t.AfAm AfAm      Asian     RaceOther
 Min.   :-1.7029972   1:26028   1: 4103         1: 7361   1: 3901   1: 1019  
 1st Qu.:-0.8901584   0:24385   0:46310         0:43052   0:46512   0:49394  
 Median : 0.0129957                                                          
 Mean   :-0.0053816                                                          
 3rd Qu.: 0.8258344                                                          
 Max.   : 1.6386732                                                          
 Hispanic  educ_hs   educ_smcoll educ_as   educ_bach educ_adv  married  
 1:11940   1:13210   1:10231     1: 5468   1: 8990   1: 4589   1:25522  
 0:38473   0:37203   0:40182     0:44945   0:41423   0:45824   0:24891  
                                                                        
                                                                        
                                                                        
                                                                        
 widowed   divorc_sep Region.Midwest Region.South Region.West
 1:  368   1: 4587    1: 9933        1:17488      1:14908    
 0:50045   0:45826    0:40480        0:32925      0:35505    
                                                             
                                                             
                                                             
                                                             
 born.Mex.CentAm.Carib born.S.Am born.Eur  born.f.USSR born.Africa born.MidE
 1: 6614               1:  623   1:  665   1:  140     1:  455     1:  240  
 0:43799               0:49790   0:49748   0:50273     0:49958     0:50173  
                                                                            
                                                                            
                                                                            
                                                                            
 born.India.subc born.Asia born.SE.Asia born.elsewhere born.unknown
 1:  797         1:  737   1: 1172      1:  251        1:  157     
 0:49616         0:49676   0:49241      0:50162        0:50256     
                                                                   
                                                                   
                                                                   
                                                                   
> 
> #the prediction base is effectively 90% of data , 10.1% is considered as train data covered.
> # we also see the predict of not covered in born Mexico and central America is high. this could be analyzed through the migration and the crossing of the borders. many who come in united states might be entered through illegal ways  which restarined them to be enrolled in any coverage. this also explain the high rate of hidpanics not covered 23% amomg this race and 14% among African American
> # now let'see what the linear probability model gives. this model helps to call the standardized regression SOBJ. then after we see what the Logit prediction gives
> # LPM
> model_lpm1 <- lm(sobj$formula, data = sobj$data)
> summary(model_lpm1)

Call:
lm(formula = sobj$formula, data = sobj$data)

Residuals:
     Min       1Q   Median       3Q      Max 
-0.63862 -0.20360 -0.11142 -0.00868  1.04431 

Coefficients:
                        Estimate Std. Error t value Pr(>|t|)    
(Intercept)             0.472978   0.111028   4.260 2.08e-05 ***
Age                    -0.015694   0.005750  -2.730 0.006362 ** 
female1                -0.017065   0.005255  -3.247 0.001171 ** 
I_female.t.AfAm1        0.007405   0.014289   0.518 0.604337    
AfAm1                  -0.020919   0.011289  -1.853 0.063918 .  
Asian1                 -0.014532   0.015185  -0.957 0.338610    
RaceOther1              0.026978   0.017561   1.536 0.124550    
Hispanic1               0.010063   0.008236   1.222 0.221803    
educ_hs1               -0.034208   0.008036  -4.257 2.11e-05 ***
educ_smcoll1           -0.073263   0.008700  -8.421  < 2e-16 ***
educ_as1               -0.078265   0.010042  -7.794 7.70e-15 ***
educ_bach1             -0.098531   0.009087 -10.843  < 2e-16 ***
educ_adv1              -0.102580   0.011160  -9.192  < 2e-16 ***
married1               -0.034739   0.006029  -5.762 8.77e-09 ***
widowed1                0.006918   0.026520   0.261 0.794221    
divorc_sep1             0.008717   0.009771   0.892 0.372366    
Region.Midwest1         0.021773   0.008221   2.648 0.008108 ** 
Region.South1           0.046509   0.007413   6.274 3.79e-10 ***
Region.West1            0.029581   0.007751   3.816 0.000137 ***
born.Mex.CentAm.Carib1  0.124822   0.010056  12.413  < 2e-16 ***
born.S.Am1              0.053109   0.021972   2.417 0.015675 *  
born.Eur1               0.032000   0.022380   1.430 0.152815    
born.f.USSR1            0.117525   0.045699   2.572 0.010145 *  
born.Africa1            0.033527   0.022743   1.474 0.140489    
born.MidE1              0.041920   0.036576   1.146 0.251801    
born.India.subc1        0.062325   0.025185   2.475 0.013364 *  
born.Asia1              0.049888   0.023724   2.103 0.035523 *  
born.SE.Asia1           0.053692   0.021104   2.544 0.010982 *  
born.elsewhere1        -0.023603   0.033850  -0.697 0.485655    
born.unknown1          -0.014666   0.039205  -0.374 0.708351    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.3642 on 5627 degrees of freedom
Multiple R-squared:  0.1387,	Adjusted R-squared:  0.1342 
F-statistic: 31.24 on 29 and 5627 DF,  p-value: < 2.2e-16

> pred_vals_lpm <- predict(model_lpm1, s_dat_test)
contrasts dropped from factor femalecontrasts dropped from factor I_female.t.AfAmcontrasts dropped from factor AfAmcontrasts dropped from factor Asiancontrasts dropped from factor RaceOthercontrasts dropped from factor Hispaniccontrasts dropped from factor educ_hscontrasts dropped from factor educ_smcollcontrasts dropped from factor educ_ascontrasts dropped from factor educ_bachcontrasts dropped from factor educ_advcontrasts dropped from factor marriedcontrasts dropped from factor widowedcontrasts dropped from factor divorc_sepcontrasts dropped from factor Region.Midwestcontrasts dropped from factor Region.Southcontrasts dropped from factor Region.Westcontrasts dropped from factor born.Mex.CentAm.Caribcontrasts dropped from factor born.S.Amcontrasts dropped from factor born.Eurcontrasts dropped from factor born.f.USSRcontrasts dropped from factor born.Africacontrasts dropped from factor born.MidEcontrasts dropped from factor born.India.subccontrasts dropped from factor born.Asiacontrasts dropped from factor born.SE.Asiacontrasts dropped from factor born.elsewherecontrasts dropped from factor born.unknown
> pred_model_lpm1 <- (pred_vals_lpm > 0.5)
> table(pred = pred_model_lpm1, true = dat_test$NOTCOV)
       true
pred        0     1
  FALSE 39698  7990
  TRUE   1054  1671
> # the predict probality linear model give 1671 not covered 
> # logit 
> model_logit1 <- glm(sobj$formula, family = binomial, data = sobj$data)
> summary(model_logit1)

Call:
glm(formula = sobj$formula, family = binomial, data = sobj$data)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-1.6381  -0.6460  -0.4547  -0.2823   2.6780  

Coefficients:
                       Estimate Std. Error z value Pr(>|z|)    
(Intercept)             0.57379    0.81929   0.700  0.48371    
Age                    -0.11297    0.04319  -2.616  0.00891 ** 
female1                -0.12766    0.04006  -3.187  0.00144 ** 
I_female.t.AfAm1        0.05734    0.10668   0.538  0.59091    
AfAm1                  -0.12091    0.08271  -1.462  0.14375    
Asian1                 -0.09499    0.12506  -0.760  0.44751    
RaceOther1              0.16418    0.11453   1.433  0.15172    
Hispanic1               0.06525    0.05955   1.096  0.27318    
educ_hs1               -0.15409    0.05013  -3.074  0.00212 ** 
educ_smcoll1           -0.42143    0.05894  -7.151 8.64e-13 ***
educ_as1               -0.47618    0.07463  -6.381 1.76e-10 ***
educ_bach1             -0.74718    0.07435 -10.049  < 2e-16 ***
educ_adv1              -0.90171    0.11728  -7.688 1.49e-14 ***
married1               -0.27331    0.04589  -5.955 2.60e-09 ***
widowed1                0.07639    0.18510   0.413  0.67983    
divorc_sep1             0.06716    0.06925   0.970  0.33213    
Region.Midwest1         0.19621    0.07060   2.779  0.00545 ** 
Region.South1           0.38652    0.06153   6.282 3.35e-10 ***
Region.West1            0.26886    0.06454   4.165 3.11e-05 ***
born.Mex.CentAm.Carib1  0.65820    0.06589   9.990  < 2e-16 ***
born.S.Am1              0.43594    0.15392   2.832  0.00462 ** 
born.Eur1               0.27188    0.16790   1.619  0.10539    
born.f.USSR1            0.86023    0.28871   2.980  0.00289 ** 
born.Africa1            0.25805    0.17171   1.503  0.13289    
born.MidE1              0.35021    0.26159   1.339  0.18066    
born.India.subc1        0.53806    0.19431   2.769  0.00562 ** 
born.Asia1              0.42481    0.18681   2.274  0.02297 *  
born.SE.Asia1           0.40989    0.16199   2.530  0.01139 *  
born.elsewhere1        -0.24261    0.32209  -0.753  0.45130    
born.unknown1          -0.04107    0.28563  -0.144  0.88566    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for binomial family taken to be 1)

    Null deviance: 5481.3  on 5656  degrees of freedom
Residual deviance: 4721.3  on 5627  degrees of freedom
AIC: 4781.3

Number of Fisher Scoring iterations: 5

> pred_vals <- predict(model_logit1, s_dat_test, type = "response")
contrasts dropped from factor femalecontrasts dropped from factor I_female.t.AfAmcontrasts dropped from factor AfAmcontrasts dropped from factor Asiancontrasts dropped from factor RaceOthercontrasts dropped from factor Hispaniccontrasts dropped from factor educ_hscontrasts dropped from factor educ_smcollcontrasts dropped from factor educ_ascontrasts dropped from factor educ_bachcontrasts dropped from factor educ_advcontrasts dropped from factor marriedcontrasts dropped from factor widowedcontrasts dropped from factor divorc_sepcontrasts dropped from factor Region.Midwestcontrasts dropped from factor Region.Southcontrasts dropped from factor Region.Westcontrasts dropped from factor born.Mex.CentAm.Caribcontrasts dropped from factor born.S.Amcontrasts dropped from factor born.Eurcontrasts dropped from factor born.f.USSRcontrasts dropped from factor born.Africacontrasts dropped from factor born.MidEcontrasts dropped from factor born.India.subccontrasts dropped from factor born.Asiacontrasts dropped from factor born.SE.Asiacontrasts dropped from factor born.elsewherecontrasts dropped from factor born.unknown
> pred_model_logit1 <- (pred_vals > 0.5)
> table(pred = pred_model_logit1, true = dat_test$NOTCOV)
       true
pred        0     1
  FALSE 39576  7859
  TRUE   1176  1802
> #the logit model gives 1802 uncovered
> require('randomForest')
> set.seed(54321)
> model_randFor <- randomForest(as.factor(NOTCOV) ~ ., data = sobj$data, importance=TRUE, proximity=TRUE)
> print(model_randFor)

Call:
 randomForest(formula = as.factor(NOTCOV) ~ ., data = sobj$data,      importance = TRUE, proximity = TRUE) 
               Type of random forest: classification
                     Number of trees: 500
No. of variables tried at each split: 5

        OOB estimate of  error rate: 16.86%
Confusion matrix:
     0   1 class.error
0 4490  99  0.02157333
1  855 213  0.80056180
> round(importance(model_randFor),2)
                          0     1 MeanDecreaseAccuracy MeanDecreaseGini
Age                   32.45  1.44                31.17           136.90
female                 5.32 11.89                10.65            23.13
I_female.t.AfAm        2.60  6.49                 6.42             7.44
AfAm                   1.51  7.39                 6.21            12.16
Asian                  7.16 -0.39                 6.99            10.42
RaceOther             -1.08  3.32                 0.91             9.95
Hispanic              -6.15 22.88                24.22            49.93
educ_hs               19.58 -9.84                16.49            18.73
educ_smcoll           16.29  9.67                22.25            18.08
educ_as               16.53 12.15                21.40            15.55
educ_bach             20.38 23.43                28.73            27.07
educ_adv              17.70 13.83                22.14            15.39
married               22.19 -3.09                22.00            26.48
widowed               -2.19  2.50                -0.89             3.92
divorc_sep             3.41 -1.59                 2.49            12.57
Region.Midwest        -3.04  6.58                 1.13            12.11
Region.South           2.93 22.05                18.38            23.28
Region.West            3.28  5.39                 7.77            17.16
born.Mex.CentAm.Carib  9.28 58.64                44.21            94.50
born.S.Am              4.67  4.24                 6.36             6.82
born.Eur              -1.02  5.27                 1.62             5.97
born.f.USSR           -1.50  4.62                 1.11             4.13
born.Africa           -6.80  2.05                -5.47             4.36
born.MidE             -3.85  0.03                -3.41             3.49
born.India.subc        6.72  3.68                 7.61             6.02
born.Asia              7.36  0.48                 7.29             5.47
born.SE.Asia          -0.97  4.85                 1.25             7.06
born.elsewhere         7.68 -1.97                 6.20             2.84
born.unknown          -6.15  0.45                -5.60             2.14
> varImpPlot(model_randFor)
> # look at confusion matrix for this too
> pred_model1 <- predict(model_randFor,  s_dat_test)
> table(pred = pred_model1, true = dat_test$NOTCOV)
    true
pred     0     1
   0 39766  7943
   1   986  1718
> # the Random Forest prediction is 1718 not covered 
> require(e1071)
> # tuned_parameters <- tune.svm(as.factor(NOTCOV) ~ ., data = sobj$data, gamma = 10^(-3:0), cost = 10^(-2:1)) 
> # summary(tuned_parameters)
> # figure best parameters and input into next
> svm.model <- svm(as.factor(NOTCOV) ~ ., data = sobj$data, cost = 10, gamma = 0.1)
> svm.pred <- predict(svm.model, s_dat_test)
> table(pred = svm.pred, true = dat_test$NOTCOV)
    true
pred     0     1
   0 38662  7502
   1  2090  2159
> ```{r}
Error: attempt to use zero-length variable name
> # Elastic Net
> require(glmnet)
> model1_elasticnet <-  glmnet(as.matrix(sobj$data[,-1]),sobj$data$NOTCOV) 
> # default is alpha = 1, lasso
> 
> par(mar=c(4.5,4.5,1,4))
> plot(model1_elasticnet)
> vnat=coef(model1_elasticnet)
> vnat=vnat[-1,ncol(vnat)] # remove the intercept, and get the coefficients at the end of the path
> axis(4, at=vnat,line=-.5,label=names(sobj$data[,-1]),las=1,tick=FALSE, cex.axis=0.5) 
> 
> plot(model1_elasticnet, xvar = "lambda")
> plot(model1_elasticnet, xvar = "dev", label = TRUE)
> print(model1_elasticnet)

Call:  glmnet(x = as.matrix(sobj$data[, -1]), y = sobj$data$NOTCOV) 

   Df  %Dev   Lambda
1   0  0.00 0.109700
2   1  1.33 0.099940
3   1  2.44 0.091060
4   1  3.36 0.082970
5   1  4.12 0.075600
6   1  4.76 0.068880
7   1  5.28 0.062760
8   1  5.72 0.057190
9   1  6.08 0.052110
10  2  6.38 0.047480
11  4  6.83 0.043260
12  4  7.43 0.039420
13  4  7.92 0.035920
14  5  8.36 0.032730
15  5  8.80 0.029820
16  5  9.16 0.027170
17  7  9.48 0.024760
18  7  9.81 0.022560
19  7 10.08 0.020550
20  9 10.34 0.018730
21 11 10.68 0.017060
22 10 11.06 0.015550
23 10 11.34 0.014170
24 10 11.58 0.012910
25 11 11.77 0.011760
26 13 11.96 0.010720
27 13 12.13 0.009764
28 16 12.29 0.008897
29 17 12.45 0.008106
30 18 12.59 0.007386
31 19 12.72 0.006730
32 18 12.83 0.006132
33 18 12.92 0.005587
34 20 12.99 0.005091
35 23 13.09 0.004639
36 23 13.20 0.004227
37 23 13.29 0.003851
38 25 13.38 0.003509
39 25 13.46 0.003197
40 25 13.52 0.002913
41 25 13.58 0.002654
42 25 13.62 0.002419
43 25 13.66 0.002204
44 25 13.69 0.002008
45 25 13.72 0.001830
46 25 13.74 0.001667
47 26 13.76 0.001519
48 26 13.77 0.001384
49 26 13.78 0.001261
50 26 13.79 0.001149
51 28 13.81 0.001047
52 28 13.81 0.000954
53 28 13.82 0.000869
54 28 13.83 0.000792
55 29 13.84 0.000722
56 29 13.84 0.000658
57 29 13.84 0.000599
58 29 13.85 0.000546
59 29 13.85 0.000497
60 29 13.85 0.000453
61 29 13.86 0.000413
62 29 13.86 0.000376
63 29 13.86 0.000343
64 29 13.86 0.000312
65 29 13.86 0.000285
66 29 13.86 0.000259
67 29 13.86 0.000236
68 29 13.86 0.000215
69 29 13.86 0.000196
70 29 13.86 0.000179
71 29 13.86 0.000163
72 29 13.86 0.000148
73 29 13.87 0.000135
74 29 13.87 0.000123
75 29 13.87 0.000112
76 29 13.87 0.000102
77 29 13.87 0.000093
> 
> cvmodel1_elasticnet = cv.glmnet(data.matrix(sobj$data[,-1]),data.matrix(sobj$data$NOTCOV)) 
> cvmodel1_elasticnet$lambda.min
[1] 0.0007919987
> log(cvmodel1_elasticnet$lambda.min)
[1] -7.140951
> coef(cvmodel1_elasticnet, s = "lambda.min")
30 x 1 sparse Matrix of class "dgCMatrix"
                                 1
(Intercept)            0.962236620
Age                   -0.014360333
female                 0.030732172
I_female.t.AfAm        .          
AfAm                   0.029408067
Asian                  0.008161881
RaceOther             -0.051689594
Hispanic              -0.022094952
educ_hs                0.056522128
educ_smcoll            0.133746345
educ_as                0.143537268
educ_bach              0.184653208
educ_adv               0.192192429
married                0.069028258
widowed               -0.004091736
divorc_sep            -0.014534740
Region.Midwest        -0.034436677
Region.South          -0.084621169
Region.West           -0.050123348
born.Mex.CentAm.Carib -0.250444170
born.S.Am             -0.093460250
born.Eur              -0.054321554
born.f.USSR           -0.217571792
born.Africa           -0.056747498
born.MidE             -0.069790919
born.India.subc       -0.097171798
born.Asia             -0.072562250
born.SE.Asia          -0.082339636
born.elsewhere         0.038303204
born.unknown           0.015103430
> 
> pred1_elasnet <- predict(model1_elasticnet, newx = data.matrix(s_dat_test), s = cvmodel1_elasticnet$lambda.min)
> pred_model1_elasnet <- (pred1_elasnet < mean(pred1_elasnet)) 
> table(pred = pred_model1_elasnet, true = dat_test$NOTCOV)
       true
pred        0     1
  FALSE 27074  3090
  TRUE  13678  6571
> 
> model2_elasticnet <-  glmnet(as.matrix(sobj$data[,-1]),sobj$data$NOTCOV, alpha = 0)

> # or try different alpha values to see if you can improve

 # Linear model Prediction
Linear model Prediction
    true
pred        0     1
  FALSE 39698  7990
  TRUE   1054  1671
  
Logit Model Prediction
    true
pred        0     1
  FALSE 39576  7859
  TRUE   1176  1802
  
Random Foreest model prediction
    true
pred     0     1
   0 39766  7943
   1   986  1718
  
  
svm model prediction
   true
pred     0     1
   0 38662  7502
   1  2090  2159
  
  
glmnet model pred
pred        0     1
  FALSE 27074  3090
  TRUE  13678  6571
> "
> lmaccuracy = ( 1671/(39698+ 7990+1054+ 1671))
> glmaccuracy = (1802/(39576+ 7859 + 1176 + 1802))
> rmaccuracy = (1718/(39766+ 7943 + 986+ 1718))
> svmaccuracy = (2159/(2159+7502+38662+2090))
> 
> lmaccuracy
[1] 0.03314621
> glmaccuracy
[1] 0.03574475
> rmaccuracy
[1] 0.03407851
> svmaccuracy
[1] 0.04282626
> 

#the highest accuracy in the prediction values is from the Support vector machine with 0.0428. Then SVM predicted better under the varibales used to address the question.
