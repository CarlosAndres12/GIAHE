
# Getting Started with R and RStudio

This guide provides step-by-step instructions on how to install R and RStudio.

**Important:** You must install **R** _before_ you install **RStudio**. Think of R as the engine of a car, and RStudio as the dashboard and steering wheel. RStudio needs R to run!

## Step 1: Install R

R is the underlying statistical programming language. You will download it from CRAN (The Comprehensive R Archive Network).

### Windows

1.  Go to the CRAN website: [https://cran.r-project.org/](https://cran.r-project.org/ "null")
    
2.  Click on **"Download R for Windows"**.
    
3.  Click on **"base"** (or click on "install R for the first time").
    
4.  Click on **"Download R [version number] for Windows"** to download the `.exe` file.
    
5.  Open the downloaded file and follow the installation wizard. You can leave all the default settings as they are.
    

### macOS

1.  Go to the CRAN website: [https://cran.r-project.org/](https://cran.r-project.org/ "null")
    
2.  Click on **"Download R for macOS"**.
    
3.  Download the relevant `.pkg` file for your Mac:
    
    -   **Apple Silicon (M1/M2/M3 Macs):** Download the `R-[version]-arm64.pkg` file.
        
    -   **Intel Macs:** Download the `R-[version]-x86_64.pkg` file.
        
4.  Open the downloaded `.pkg` file and follow the standard installation prompts.
    

### Linux (Ubuntu/Debian)

Open your terminal and run the following commands to update your package index and install R:

```
sudo apt update
sudo apt install r-base

```

_Note: For other Linux distributions (Fedora, Arch, etc.), refer to the specific instructions on the_ [_CRAN Linux page_](https://cran.r-project.org/bin/linux/ "null")_._

## Step 2: Install RStudio

RStudio is an Integrated Development Environment (IDE) that makes working with R much easier and more user-friendly.

1.  Go to the Posit (formerly RStudio) download page: [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/ "null")
    
2.  Scroll down to the **"Install RStudio"** section. The website should automatically detect your operating system and offer the correct download button.
    
    -   _If it doesn't, scroll down further to "All Installers" and select the appropriate file for your OS (.exe for Windows, .dmg for Mac, .deb/.rpm for Linux)._
        
3.  Download the installer file.
    
4.  Run the installer:
    
    -   **Windows:** Open the `.exe` file and follow the setup wizard.
        
    -   **macOS:** Open the `.dmg` file and drag the RStudio icon into your Applications folder.
        
    -   **Linux:** Use your package manager to install the downloaded file (e.g., `sudo dpkg -i rstudio-[version]-amd64.deb`).
        

## Step 3: Verify Your Installation

1.  Open **RStudio** from your Start Menu (Windows) or Applications folder (Mac).
    
    -   _Do not open the basic "R" application by mistake._
        
2.  Once RStudio opens, look at the **Console** pane (usually the bottom-left or the entire left side of the screen).
    
3.  Type the following command and press `Enter`:
    

```
print("Hello, R!")

```

4.  If you see `[1] "Hello, R!"` printed right below it, congratulations! Your installation was successful.
    


