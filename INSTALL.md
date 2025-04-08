## 🧰 Build Instructions

<!--<img src="https://www.retrobat.ovh/img/under-construction.png" width="240" alt="under-construction" class="center">-->

The batch script `build.bat` will download all the softwares required, set the config files and build the RetroBat Setup from `setup.nsi` sources script.

- Download and install [Git for Windows](https://gitforwindows.org/) (follow default setup settings).
  
- Download and install [Innosetup](https://jrsoftware.org/isdl.php) (follow default setup settings).

- Open CMD Windows Terminal and run the following commands to clone recursively the RetroBat git with its submodules and run build.bat to launch the build:
```
git clone --recursive https://github.com/RetroBat-Official/retrobat-setup.git
```
```
cd RetroBat
build.bat
```
- Once the build process is done, you will find the RetroBat Setup in the build directory.
