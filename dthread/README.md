this tool use to kill thread in uninterruptible sleep, we change thread status then exit

useage:
    make
    insmod ./killd.ko pid=1234
    rmmod killd