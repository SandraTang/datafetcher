### Dependencies
Install the tar ball in the repo, the cleaning script requires it!
```
tar xfvz wfdb.tar.gz
cd wfdb-10.6.2
./configure
sudo make install
```
Then, get a virtual environment if possible, install on bs4, requests, wget, progressbar2

Run `python3 ./get_hea_files`
and
`bash ./rr_generator.sh`

Tweak the file last_record to indicate your starting subject id and the python file to indicate your stopping 
