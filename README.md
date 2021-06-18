# Summer-Research-Academy

In preparation for the summer research academy, I'd like to ask you to install some software so that we can get jump in right away once the class starts.

For our course, we will use the statistical programming language R to run empirical analyses. The best way to run R is within a so-called integrated development environment or IDE, which expands the functionality of R. You can read more about the difference between R and RStudio [here!] (https://bookdown.org/kdonovan125/ibis_data_analysis_r4/introducing-r-and-rstudio.html). To make sure everything is set up correctly, we will do the following three things:

1. Install R.
2. Install RStudio.
3. Install a package. We will install a package called ```tidyverse``` but it could be any other package because we just want to make sure that R is installed correctly.

Depending on what computer you have you will either install the software for Windows, for Mac OS with an Intel chip, or for Mac OS with an Apple Silicon chip. I outline what to do in each of the scenarios. You probably know if you have Windows or Mac but how do you know if you have an Intel or an Apple Silicon chip? Just go [here!] (https://www.howtogeek.com/706226/how-to-check-if-your-mac-is-using-an-intel-or-apple-silicon-processor/) and follow the instructions to find out.

## Step 1: Download and Install R

Choose **one** of the following:

* If you have **Windows**, go [here!] (https://mirror.las.iastate.edu/CRAN/bin/windows/base/) 
* If you have a **Mac** with an **Intel** chip, go [here!] (https://mirror.las.iastate.edu/CRAN/bin/macosx/) and download R-4.1.0.pkg 
* If you have a **Mac** with an **Apple Silicon** chip, go [here!] (https://mirror.las.iastate.edu/CRAN/bin/macosx/) and download R-4.1.0-arm64.pkg

Open the file and follow the instructions to install R.

## Step 2: Download and Install RStudio

Go [here!] (https://www.rstudio.com/products/rstudio/download/#download) and click on the button that says "Download RStudio for [Mac/Windows]" (depending on your OS).

Open the file and follow the instructions to install RStudio.

## Step 3: Start RStudio and Install the Tidyverse Package

You will learn all about what packages are and what they do during our course. For now, just follow these instructions so we can see whether the software works as planned.

1. Open RStudio.
2. Click on the console window.
3. Type ```install.packages("tidyverse")```

You should see on the screen how the package is being installed. It may (or may not) be that you are asked questions about how to install it along the lines of "are you sure you want to install this?" (say yes), "do you want to install the following dependencies?" (say yes).

Once you see the curso blinking idly again, type in ```library(tidyverse)```. We use this to load a package. Look if there are any lines that say ```Error```. If not, you are done.

If so, there was a problem with the installation.  In that case, close RStudio and repeat Step 3.

Once the ```tidyverse``` is installed correctly, you are done. Congratulations! If you keep receiving an error messsage even after trying several times, please get in touch with the SRA staff.
