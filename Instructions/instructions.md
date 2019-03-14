#To run Listbot
To run listbot navigate to its file directory where the script currently lives. 


Run the following commands

```
./gen_iprep_map

```

This will download the threat feeds as a RAW and as a temp format.



Use the following command to get the MD5 hashes of all the files 

```
 `md5sum --tag *.tmp`

```

Run the following command to remove the TEMP and RAW files. This will keep the IP_Rep.yml which Suricata uses for its data tagging.

`    - rm *.tmp
    - rm *.raw
` 


