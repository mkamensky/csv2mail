# csv2mail
Mass email based on csv file

##Usage

`csv2mail <template> [<csv>...]`

Where `<template>` is a Mustache mail template file (including the header), 
and any further arguments are csv files. CSV data is also read from STDIN.

    -h, --help                       Prints this help
    -d, --delivery STRING            Delivery method ("logger" for STDOUT)
