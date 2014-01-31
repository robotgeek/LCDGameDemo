/***********************************************************************************
 *       ___________________________________
 *      |  _______________________________  |
 *      | |RobotGeek I2C LCD              |\|
 *      | | 'Collect the Hearts' Game     | |
 *      | |                               | |
 *      | |_______________________________|/|
 *      |___________________________________|
 *
 *  The following sketch will use the RobotGeekLCD , a joystick, a knob, and a
 *   button to create a simple  video game
 *
 *  Products
 *    http://www.robotgeek.com/robotGeek-pushbutton
 *    http://www.robotgeek.com/robotgeek-lcd-wmount
 *    http://www.robotgeek.com/robotGeek-pushbutton
 *    http://www.robotgeek.com/robotgeek-rotation-knob
 *    http://www.robotgeek.com/robotgeek-joystick
 *  
 *  Wiring
 *    RobotGeek Sensor Shield With Geekduino
 *      The RobotGeek I2C LCD will plug directly into the 4-pin I2C port on
 *      the sensor shield using a 4-pin sensor cable. Normally the sensor cable
 *      will be plugged in with the following orientation:
 *        SCL    - Yellow
 *        SDA    - White
 *        5v/VCC - Red
 *        G/GND  - Black
 *  
 *   Digital Input  2 - Pushbutton       
 *   Analog Input 0 - Rotational Knob
 *   Analog Input 1 - Joystick Horizontal
 *   Analog Input 2 - Joystick Vertical
 *
 *
 *  Control Behavior:
 *    The state of value of each sensor will be displayed to the LCD
 *    B:Button
 *    K:Knob
 *    X:Joystick Horizontal
 *    Y:Joystick Vertical   
 * 
 *
 *  References
 *      RobotGeek LCD Documentation http://learn.trossenrobotics.com/30-robotgeek-getting-started-guides/dev-kits/57-robotgeek-i2c-lcd-getting-started-guide
 *      RobotGeek Libraries and Tools (Included LCD Library) https://github.com/trossenrobotics/robotGeekLibrariesAndtools/archive/master.zip
 *      Custom Character guide http://learn.trossenrobotics.com/28-robotgeek-getting-started-guides/61-robotgeek-i2c-lcd-library#customChar 
 *  
 ***********************************************************************************/
