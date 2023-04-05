
# Table of Contents

1.  [About](#org97dc785)
2.  [Installation](#org636804b)
3.  [Usage](#orgb33c8b4)
    1.  [Usage: salah [OPTIONS] [PRAYER]](#orgbeded5c)
    2.  [Options: [-f] [&#x2013;format]](#org822af3c)



<a id="org97dc785"></a>

# About

Get Salah timings from salah.com right in the terminal!


<a id="org636804b"></a>

# Installation

-   Linux

    curl https://raw.githubusercontent.com/AfzGit/salah-cli/main/salah-cli --output salah
    chmod a+x salah
    sudo mv salah /usr/bin/ # or anywhere in PATH


<a id="orgb33c8b4"></a>

# Usage


<a id="orgbeded5c"></a>

## Usage: salah [OPTIONS] [PRAYER]

-   -> salah fajr/f
-   -> salah sunrise/s
-   -> salah dhuhr/d
-   -> salah asr/a
-   -> salah magribh/m
-   -> salah isha/i
-   -> salah qiyam/q
-   -> salah all
-   -> Get all times


<a id="org822af3c"></a>

## Options: [-f] [&#x2013;format]

-   -> salah -f fajr
-   -> To format and get only hour and minute numbers (like 4 55 instead of 4:55PM)

