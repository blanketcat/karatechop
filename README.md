# Karate-Chop

### Installation

Clone the repo into your ```/home/$USER/bin``` folder or somewhere else in your ```$PATH```.

```
~$ git clone THIS_REPO 
```

If I get time to add the features I want to add to this, I'll package it up for apt, rpm, and yum.

### Chop Large Files Into Smaller Ones

```
~$ karatechop -c -i <INPUT_FILE> -o <OUTPUT_DIR>
```

### Reassemble Resulting Files Into Original

```
~$ karatechop -r -d <INPUT_DIR>
```


