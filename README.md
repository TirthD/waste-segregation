# waste-segregation
The management of waste is a critical issue in today's world, as it has a significant impact on the environment. In this context, a waste segregating machine that can efficiently segregate dry and wet waste can prove to be an innovative solution. This project aims to develop a waste segregating machine that utilizes Arduino, Aluminium foil as a moisture sensor, and IR sensor to detect waste.

The proposed prototype employs an Arduino micro-controller that receives input from the Aluminium foil regarding the moisture content of the waste in the form of capacitance and IR sensor to detect waste. The waste is segregated into two separate sections, dry and wet, to facilitate the recycling process.

The system is designed to be low-cost, compact, and user-friendly. The use of Arduino ensures that the prototype can be easily programmed and updated. The Aluminium foil sensor, used to detect the moisture content of the waste, can be circumscribed in terms of the moisture level. The machine can handle a wide range of waste types, making it versatile and suitable for use in a variety of settings.

In summary, This prototype can help manage waste more effectively, reduce the environmental impact, and facilitate the recycling process.

![image](https://github.com/TirthD/waste-segregation/assets/90318231/0d6d0d94-c325-48cd-860f-8ec96aa5a746)

The circuit diagram provides a clear and concise overview of the system's functioning and enables effective troubleshooting and maintenance of the machine. Various sensors, a motor and a LCD display are controlled and synced through Arduino UNO micro-controller, providing a seamless user experience that is minimal and requires little to none efforts from the user.

1. Moisture Sensor:
Initially, the waste to be segregated is put on a platform that is covered in aluminium foil. Aluminium foil covering is used as a moisture sensor(SEN1) to determine whether the waste is dry or wet. The Aluminium foil is connected to the Arduino, and its capacitance changes according to the moisture content of the waste. The Arduino reads the capacitance and determines whether the waste is dry or wet based on the predetermined limits given to the micro-controller.

2. IR and Ultrasonic Sensor:
The IR sensor(U5) is used to detect if there is any waste present on the platform, and the ultrasonic sensor(DIST1/DIST2) checks the amount of waste in each section. Both sensors are connected to the Arduino micro-controller. The Arduino reads the input from the sensors and decides which section the waste should be sorted into.

3. Servo Motor and LCD:
The machine uses a servo motor(SERVO1) to flip the platform, on which the waste is placed, in dry and wet sections. The servo motor is connected to the Arduino and the motion of it is operate by the micro-controller. The LCD is used to display the capacity of the dry and wet waste sections and the segregation/flip made for the current waste placed on the platform.

4. LM7805:
The circuit includes a LM7805(U3) voltage regulator circuit that regulates the input voltage and provides a stable 5V supply to the components.

Overall, the circuit diagram of the waste segregation machine includes various components such as sensors, micro-controller, voltage regulator circuit, and moisture sensor that work together to efficiently segregate the waste into dry and wet sections.
