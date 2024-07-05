# RPi_DPIPE
#### This package is designed to light up digital pipe on raspberry-pi with python language
#### 1.CADT is for Common-Anode-Digital-Pipe
#### 1.CCDT is for Common-Cathode-Digital-Pipe

# How to use it?
#### import libs (we choose CADT to display)
    import RPi_DPIPE.CADT as CA
#### Create an instance and initialize
    digital_pipe = CA.CADT_PIPE()
    digital_pipe.initalize()
#### Check default absolte position of each pipe and connect to your device 
    print(digital_pipe.Intro_Pipe())
#### If no problem,let's display a number,such as 5
    digital_pipe.draw_number(num=5)
#### Then display a letter like a and B
    digital_pipe.draw_letter(letter='a')
    digital_pipe.draw_letter(letter='B')
    
