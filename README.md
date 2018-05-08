# rename_aclewid

rename all the files in a folder with their corresponding ACLEW id.

### dependencies:

pandas

can install with:

```
$ pip install -U pandas
```

### usage

```
$ python rename_aclewid.py ACLEW_listofcorpora.csv input_dir
```

After it is done running, the script will output a file named ```renamed_files.csv```, which is a spreadsheet of all the files with before/after names