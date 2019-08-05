
Visual-dstat tools

### Requires

- [dstat](http://dag.wiee.rs/home-made/dstat/)
- [python](https://www.python.org/)

Also uses [Dygraphs](http://dygraphs.com/) for javascript charts (included)

### Visualize existing file

```
$ dstat --time -v --net --output dstat.csv 1 10
$ ./visual_dstat.sh dstat.csv

```

### Execute and visualize

```
$ ./visual_dstat.sh

```

Then point your browser to http://localhost:2221


### Other command

``` shell
iostat -kx sda3 sdb3 sdq3 sdr3 sda sdb sdc sdd sde sdf sdg sdh sdi sdj sdk sdl sdn sdm sdo sdp sdq sdr sds sdt sdu sdv sdw sdx sdy sdz sdaa sdab sdac nvme0n1 nvme1n1 nvme2n1 nvme3n1 nvme4n1 nvme5n1 nvme6n1 nvme7n1 3

dstat -C 0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104,105,106,107,108,109,110,111,112,113,114,115,116,117,118,119,120,121,122,123,124,125,126,127,128,total -D sda3,sdb3,sdc,sdd,sde,sdf,sdg,sdh,sdi,sdj,sdk,sdl,sdn,sdm,sdo,sdp,sdq,sdr,sds,sdt,sdu,sdv,sdw,sdx,sdy,sdz,sdaa,sdab,sdac,nvme0n1,nvme1n1,nvme2n1,nvme3n1,nvme4n1,nvme5n1,nvme6n1,nvme7n1,sda,sdb,total --nocolor

dstat --time --vmstat 3
```

### License

The MIT License (MIT)

Copyright (c) 2019 BigdataLyn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.