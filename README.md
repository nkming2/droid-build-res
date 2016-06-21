# droid-build-res
Bash script to build Android drawable resources in multiple screen DPIs, needs imagemagick

# Usage
droid-build-res SIZE FILE...  
* SIZE The image size under 160DPI

*To mantain good quality, the files should be at least 4x the stated size

# Example
droid-build-res 24 ic_pony_white_24dp.png
