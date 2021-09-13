# tar
From https://linuxize.com/post/how-to-extract-unzip-tar-gz-file/ <https://linuxize.com/post/how-to-extract-unzip-tar-gz-file/>

To extract a tar.gz file, use the ```--extract (-x)``` option and specify the archive file name after the f option:

```tar -xf archive.tar.gz```

The tar command will auto-detect compression type and will extract the archive. The same command can be used to extract tar archives compressed with other algorithms such as .tar.bz2 .

The ```-v``` option will make the tar command more visible and print the names of the files being extracted on the terminal.

```tar -xvf archive.tar.gz```

By default, tar will extract the archive contents in the current working directory . Use the ```--directory (-C)``` to extract archive files in a specific directory:

```tar -xf archive.tar.gz -C /home/linuxize/files```
