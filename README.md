#!/bin/bash
#test

date=`date "+%Y%m%d"`
dir="./work_${date}"

if [ -e $dir ]; then
    echo "$dir found."
else
    echo "$dir NOT found."
    mkdir work_${date}
fi

