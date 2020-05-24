# OSX CPU Temp

Outputs current CPU temperature for OSX.

## Usage 

### Compiling

```bash
make
```

### Running

```bash
./osx-cpu-temp
```

or

```bash
sudo make install # installs to /usr/local/bin
osx-cpu-temp
```

### Using clib

```bash
clib install lavoiesl/osx-cpu-temp
```

### Output example

```
99.7 °F
```

### Options

 * `-C` Output temperature in Celsius.
 * `-F` Output temperature in Fahrenheit (default).
 * `-f` Output fan speed.
 * `-g` Output gpu temperature.

## Maintainer 

Sébastien Lavoie <github@lavoie.sl>

### Source 

Apple System Management Control (SMC) Tool 
Copyright (C) 2006

### Inspiration 

 * https://www.eidac.de/smcfancontrol/
 * https://github.com/hholtmann/smcFanControl/tree/master/smc-command
