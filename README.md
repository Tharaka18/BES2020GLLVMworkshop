# Analysing multivariate ecological data with Generalized Linear Latent Variable Models
Thanks for participating, and welcome to this BES workshop on the <tt>gllvm</tt> R-package.

Before continuing further to the exercise material, please make sure you have installed the following, required, R-packages:
```r
install.packages("corrplot")
install.packages("dplyr")
install.packages("mvabund")
install.packages("gllvm")
```

If you encounter any problems when using the <tt>gllvm</tt> R-package, please explore [existing issues in the github repository of the package](https://github.com/JenniNiku/gllvm/issues). If your problem has not already been explored by someone else, feel free to post a new issue or use the [discussion board](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/discussions) in this repository.

# Workshop material
All workshop material can be found in this repository, listed below.

## Day 1 - With focus on model-based ordination
1) [Background on Generalized Linear Latent Variable Models](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%201/BESWorkshopSlides_Day1_BertvV.pdf)
2) [<tt>gllvm</tt> R-package](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%201/BESWorkshopSlides_Day1_JN.pdf)
   - [Exercise in R](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Exercise/day%201/ExercisesPart1.R)
3) [Ecological interpretation of GLLVM results](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%201/BESWorkshopSlides_Day1_SamP.pdf)
   - [Exercise in R](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Exercise/day%201/Session3.R)

## Day 2 - With focus on Joint Species Distribution Models
1) [Background on Generalized Linear Latent Variable Models](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%202/BESWorkshopSlides_Day2_BertvV.pdf)
2) [<tt>gllvm</tt> R-package](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%202/BESWorkshopSlides_Day2_JN.pdf)
   - [Exercise in R](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Exercise/day%202/ExercisesPart2.R)
3) [Ecological interpretation of GLLVM results](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%202/BESWorkshopSlides_Day2_SamP.pdf)
   - [Exercise in R](https://github.com/BertvanderVeen/BES2020GLLVMworkshop/blob/main/Slides/day%202/BESWorkshopSlides_Day2_SamP.pdf)

Further example material on using the <tt>gllvm</tt> R-package is available in the vignettes, and the [reference manual](https://cran.r-project.org/web/packages/gllvm/gllvm.pdf), of the package:<br>
https://cran.r-project.org/web/packages/gllvm/vignettes/vignette1.html <br>
https://cran.r-project.org/web/packages/gllvm/vignettes/vignette2.html <br>
https://cran.r-project.org/web/packages/gllvm/vignettes/vignette3.html <br>
https://cran.r-project.org/web/packages/gllvm/vignettes/vignette4.html <br>

# Questions
Any questions regarding the exercise material can be posted on the discussion board, or communicated over twitter using the #GLLVMs hashtag, directed [@vdVeenB](https://twitter.com/vdVeenB), [@J__Niku](https://twitter.com/J__Niku), [@samperrinNTNU](https://twitter.com/samperrinNTNU), or [@BobOHara](https://twitter.com/bobohara).

# Some recommended reading
Blanchet, F., Cazelles, K., & Gravel, D. (2020). Co-occurrence is not evidence of ecological interactions. Ecology Letters, 23(7), 1050-1063.

Clark, J., Gelfand, A., Woodall, C., & Zhu, K. (2014). More than the sum of the parts: forest climate response from joint species distribution models. Ecological Applications, 24(5), 990-999.

D'Amen, M., Mod, H., Gotelli, N., & Guisan, A. (2018). Disentangling biotic interactions, environmental filters, and dispersal limitation as drivers of species co-occurrence. Ecography, 41(8), 1233-1244.

[Halvorsen, R. (2012). A gradient analytic perspective on distribution modelling. Sommerfeltia, 35(1), 1–165.](http://nhm2.uio.no/botanisk/nbf/temp/Sommerfeltia_35_20121206_PRESS.pdf)

Hui, F., Taskinen, S., Pledger, S., Foster, S., & Warton, D. (2015). Model-based approaches to unconstrained ordination. Methods in Ecology and Evolution, 6(4), 399-411.
Hui, F., Warton, D., Ormerod, J., Haapaniemi, V., & Taskinen, S. (2017). Variational approximations for generalized linear latent variable models. Journal of Computational and Graphical Statistics, 26(1), 35–43.

Niku, J., Warton, D., Hui, F., & Taskinen, S. (2017). Generalized linear latent variable models for multivariate count and biomass data in ecology. Journal of Agricultural, Biological and Environmental Statistics, 22(4), 498–522.

Niku, J., Hui, F., Taskinen, S., & Warton, D. (2019). gllvm: Fast analysis of multivariate abundance data with generalized linear latent variable models in r. Methods in Ecology and Evolution, 10(12), 2173–2182.

Niku, J., Brooks, W., Herliansyah, R., Hui, F., Taskinen, S., & Warton, D. (2019). Efficient estimation of generalized linear latent variable models. PloS one, 14(5), e0216129.

Pollock, L., Tingley, R., Morris, W., Golding, N., O'Hara, R., Parris, K., Vesk, P., & McCarthy, M. (2014). Understanding co-occurrence by modelling species simultaneously with a Joint Species Distribution Model (JSDM)Methods in Ecology and Evolution, 5(5), 397-406.

Wang, Y., Naumann, U., Wright, S., & Warton, D. (2012). mvabund– an R package for model-based analysis of multivariate abundance data. Methods in Ecology and Evolution, 3(3), 471-474.

Warton, D., Wright, S., & Wang, Y. (2012). Distance-based multivariate analyses confound location and dispersion effects. Methods in Ecology and Evolution, 3(1), 89–101.

Warton, D., Blanchet, F., O’Hara, R., Ovaskainen, O., Taskinen, S., Walker, S., & Hui, F. (2015). So many variables: joint modeling in community ecology. Trends in Ecology & Evolution, 30(12), 766–779.
Warton, D., Foster, S., De’ath, G., Stoklosa, J., & Dunstan, P. (2015). Model-based thinking for community ecology. Plant Ecology, 216(5), 669–682.

Warton, D., & Hui, F. (2017). The central role of mean-variance relationships in the analysis of multivariate abundance data: a response to Roberts (2017). Methods in Ecology and Evolution, 8(11), 1408-1414.

Zurell, D., Zimmermann, N., Gross, H., Baltensweiler, A., Sattler, T., & Wüest, R. (2020). Testing species assemblage predictions from stacked and joint species distribution models. Journal of Biogeography, 47(1), 101-113.

