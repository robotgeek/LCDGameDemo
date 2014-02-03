```
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
 * 
 *  Control Behavior:
 *    The LCD will display title text, then randomly generate 'heart' icons
 *    across the LCD. In the upper right corner there will be a small stick 
 *    figure - your 'hero'. By moving the joustick up/down/left/right the user
 *    can control the 'hero' to collect the hearts. Once all the hearts are
 *    collected, a 'you win!' label appears.
 *    Clicking the pushbutton will reset the game and regenerate a new field
 *    of hearts. The hearts are randomly selected. The random seed is generated
 *    from the Knob.
 *
 *  References
 *      RobotGeek LCD Documentation http://learn.trossenrobotics.com/30-robotgeek-getting-started-guides/dev-kits/57-robotgeek-i2c-lcd-getting-started-guide
 *      RobotGeek Libraries and Tools (Included LCD Library) https://github.com/trossenrobotics/robotGeekLibrariesAndtools/archive/master.zip
 *      Custom Character guide http://learn.trossenrobotics.com/28-robotgeek-getting-started-guides/61-robotgeek-i2c-lcd-library#customChar 
 *  
 ***********************************************************************************/
```