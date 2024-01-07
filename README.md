# lang-mode
Class repo for D2M

##Assignment 2
#Install

install.packages("tidyverse")
install.packages("papaja")

require("tidyverse")
require("papaja")

#Load

library(tidyverse)
library(papaja)

#Require

require(readr)

#Assign

x <- 2
y = "hello world"

#Dataframe

Data_Frame <- data.frame(
    Column_1 = c("a", "b", "c"),
    Column_2 = c("d", "e", "f")
)

print(Data_Frame)

#papaja

if(!"tinytex" %in% rownames(installed.packages())) install.packages("tinytex")

tinytex::install_tinytex()


