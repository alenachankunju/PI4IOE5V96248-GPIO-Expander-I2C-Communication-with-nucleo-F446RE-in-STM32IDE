# PI4IOE5V96248-GPIO-Expander-I2C-Communication-with-nucleo-F446RE-in-STM32IDE
I2C communication with GPIO Expander

1.Add the following code to your main.c file\n
2.In the .ioc file, set the I2C pins as follows: PB9 for I2C-SDA and PB8 for I2C-SCL.
3.Build the project.
4.Connect the GPIO Expander to the Nucleo board using the respective pins mentioned above.
5.Ensure that the GPIO Expander is powered by connecting it to the 3V power source.
6.Flash the project onto the Nucleo board.
7.Confirm the I2C communication between the Nucleo board and the GPIO Expander using a Logic Analyzer.
8.If the I2C communication is successful, proceed to check the functionality of each GPIO PORT using LEDs.


