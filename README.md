# Signal Modulation 

This repository contains solution to assignment for Principal of Communications Systems course at VJTI, Mumbai

# Generate sample data

* To generate a sample signal as the input signal, run the following command:

  ```bash
  python3 generate_signal.py
  ```

  Output of the file, enter the number of data points to generate, we take 1000 data points for this example

  ```bash
  Press 1 for sin wave
  Press 2 for cosine wave
  Press 3 for using custom audio file (wav format)
  Enter option: 2
  Enter number of elements: 1000
    ```
    
* To use custom audio file as input
  ```bash
  Press 1 for sin wave
  Press 2 for cosine wave
  Press 3 for using custom audio file (wav format)
  Enter option: 3
  Enter audio file name: custom.wav
    ```

  This will generate a file called `data.txt` with float values on each line.

# Amplitude Modulation

> Write a program in MATLAB/Python/Scilab (any) to generate an AM wave for a given modulation index and modulating signal. The modulation index, carrier frequency and modulating signal must be taken as input from user.

> Plot one signal below the other in a single figure as subparts, for convenient visualization.

To generate AM output signal, run the following command:
    
```bash
python3 amplitude_modulation.py
```

#### Sin signal as input

Output of python file

```bash
Enter File Name: data.txt
Enter value of modulation index (0-1): 0.9
Enter value of carrier frequency: 10000
```

![](AM_sin.png)

#### Cosine signal as input

Output of python file

```bash
Enter File Name: data.txt
Enter value of modulation index (0-1): 0.4
Enter value of carrier frequency: 100000
```

![](AM_cos.png)

#### Custom Audio file as input

Output of python file

```bash
Enter File Name: data.txt
Enter value of modulation index (0-1): 0.6
Enter value of carrier frequency: 1000
```

![](AM_custom.png)

# Frequency Modulation

> Write a program in MATLAB/Python/Scilab (any) to generate an FM wave for a given deviation ratio and modulating signal. The deviation ratio, carrier frequency and modulating signal must be taken as input from user.

> Plot one signal below the other in a single figure as subparts, for convenient visualization.

To generate FM output signal, run the following command:

```bash
python3 frequency_modulation.py
```

#### Sin signal as input


Output of the python file

```bash
Enter File Name: data.txt
Enter value of deviation ratio: 10
Enter value of carrier frequency: 1000
```

![](FM_sin.png)


#### Cosine signal as input


Output of the python file

```bash
Enter File Name: data.txt
Enter value of deviation ratio: 10
Enter value of carrier frequency: 1000000
```

![](FM_cos.png)


#### Custom audio file as input

Output of the python file

```bash
Enter File Name: data.txt
Enter value of deviation ratio: 10
Enter value of carrier frequency: 10000
```

![](FM_custom.png)
