import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
df = pd.read_excel('SampleDataFile.xlsx')
Mean = df.mean()
STD = df.std()
FFT = np.fft.fft(df)
freq = np.fft.fftfreq(len(df))
function = input('What function would you like to be computed? Type Mean, STD, or FFT \n')
if function == "Mean":
    print(Mean)
elif function =="STD":
    print(STD)
elif function == "FFT":
    plt.plot(freq, abs(FFT))
    plt.xlabel('Frequency')
    plt.ylabel('Amplitude')
    plt.show()
