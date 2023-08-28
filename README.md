# Four_Way_Traffic_Light_Control_System
The aim of the project is to implement a traffic light controller using Arduino Uno. Where a traffic is controlled in a pre-defined timing system. The effectiveness of four-way stop signs with that of the traffic lights in controlling traffic at an intersection.

In today’s high speed life, traffic congestion becomes a serious issue in our day to day activities. It brings down the productivity of individual and thereby the society as lots of work hour is wasted in the signals. High volume of vehicles, the inadequate infrastructure and the irrational distribution of the signalling system are main reasons for this chaotic congestions. It indirectly also adds to the increase in pollution level as engines remain on in most cases, a huge volume of natural resources in forms of petrol and diesel is consumed without any fruitful outcome. Therefore, in order to get rid of these problems or at least reduce them to significant level, newer schemes need to be   implemented by bringing in sensor based automation technique in this field of traffic signalling system.

The objectives of this projects are 
1) To detect the vehicle approaching on a certain road using an IR sensor
2) To avoid road accidents.
  
The system consist of density based IR sensors which detect vehicle on particular flank according to number of vehicles passing through the assigned section of the road. There are four sensors placed on four sides of a four way. IR sensors contain IR transmitter and IR receiver in itself. As the vehicle passes through these IR sensors, the  IR  sensor  will  detect  the  vehicle  &  will  send  the information  to  the  Arduino. The Arduino will count the number of vehicles and provide the glowing time to LED according to the density of vehicle.
The system works on following three conditions.

1.	At normal condition the LED’s will glow according to priorities set in the Arduino program.
2.	When vehicle is arriving on the particular road i.e. the density of road is heavy the LED will glow green for higher time than the average or visa-versa.
3.	When density of road is equal on all four roads the traffic signal LED’s will glow according to the priorities set.

