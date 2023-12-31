# Miniproject Synopsis

# Problem Statement

# DESIGN OF RF TO DC CIRCUIT FOR ENERGY HARVESTING

# Abstract

RF (radio frequency) to DC (direct current) converts an RF signal into a DC voltage. This process can be implemented in many applications like wireless power transmission, wireless data transfer, and energy harvesting. The conversion process can be used to power many devices through the transmission of Radio Frequency and converting it to DC voltage which can be used to power devices that are difficult to access or in remote locations and wirelessly charge batteries. The process allows transmitting power to these devices wirelessly, without any need for a physical connection to a power source.  


# INTRODUCTION

The application of Wireless Power Transfer (WPT) is vast as it can be used in many applications like medical devices or implants, home and industry automation, security and safety. This can be used where the wire or cables are impractical or inconvenient and are useful in places where the power source is limited or unavailable.RF to DC is the part of Wireless Power Transfer in which data or power can be transferred through radio frequency and converted to DC voltage through CMOS technology. To obtain the desired output the conversion should go through the processes like rectification, amplification, filtering, and DC to DC conversion. The implementation of CMOS technology is often used for rectification, amplification, and filtering stages mainly because of its low power consumption, small form factor, and compatibility with integrated circuits. The output of the conversion process results in a DC voltage that can be used to power a wide range of devices, from small sensors to larger electronic systems. 


# LITERATURE SURVEY   

[1]	The optimization of four voltage multiplier rectifiers using a first-order L-matching network for energy harvesting in a DBS device revealed that the 2-stage charge pump rectifier was the best rectifier based on conversion efficiency.

[2]	This paper presents a low-power head-mountable deep brain stimulation (DBS) device operated with harvested energy. The electrical energy generated by a mini solar panel is used to operate the low-power head-mountable DBS device. The DBS device consists of a power management unit, a low-power microcontroller, and a constant current source. The proposed indoor solar energy harvesting system can supply a sufficient amount of dc power to run the DBS device or to charge the battery for the DBS device. The energy harvesting scheme might increase the longevity of the low-power DBS device 

[3]	This paper presented a circular meander dipole antenna for a head-mountable passive DBS device, which had a bandwidth of 15 MHz at a return loss of -10 dB at the ISM band of 915 MHz and a maximum antenna gain of −4.1 dB at free space. The presence of a hat model near the antenna altered the antenna parameters, resulting in a shift of resonance frequency and a reduction of antenna gain.

[4]	A study of rectifier circuits using a first-order LC matching technique revealed that the Greinacher voltage doubler was the best rectifier for low-density RF energy transmitters. CMOS diode rectifiers could further enhance rectification performance. To maintain safety regulations, the received power of the proposed dipole antenna should be less than a few mWs.  
[5]	A biomedical system concept is proposed and a battery-less transceiver is demonstrated using 0.18-m CMOS technology. An integrated RF-dc converter is used as an RF-powering source and the transceiver achieves a data rate of 100 kb/s while using ASK modulation. The phase noise of 108.0 dBc/Hz is achieved at an offset frequency of 300 kHz, and the receiver achieves a sensitivity of 69 dBm for a BER below 10. The impact of RF powering is also investigated, with a difference of 4 dB in receiver sensitivity between an external voltage supply and RF powering.

# METHODOLOGY 

The methodology for designing an RF to DC converter circuit involves several key considerations. First, the circuit must include a rectifier to convert the AC signal from the RF source into a DC  Signal. Next, a DC-to-DC converter may be required to boost the low input voltage to a higher  Output voltage, depending on the application. This can be achieved using a combination of charge Pumps and ring oscillators. Finally, a voltage regulator may be implemented to ensure a stable Output voltage. The design of the RF to DC converter circuit should take into account the specific requirements of the application, such as the desired output voltage, input frequency range, and load resistance. The circuit should also be designed using appropriate components and materials to ensure optimal performance, efficiency, and reliability. Simulation software can be used to evaluate the performance of the circuit and optimize its design. Various parameters can be adjusted to determine the impact on circuit performance, such as component values, circuit topology, and input signal characteristics. The results of simulations can be used to refine the design of the RF to DC converter circuit. Finally, the RF to DC converter circuit can be implemented using appropriate fabrication techniques and materials. The circuit can be tested and evaluated to ensure that it meets the desired specifications and performance requirements. Any necessary modifications can be made to the circuit design based on testing results  

# BLOCK DIAGRAM

![image](https://github.com/xbnj/Miniproject/assets/42709556/757af7b8-d901-47f0-9418-9d2263c1e103)

# TIME SCHEDULE   

![image](https://github.com/xbnj/Miniproject/assets/42709556/8be77914-be53-42da-adfb-83f34db280fe)

# ESTIMATED BUDGET  (HARDWARE)


![image](https://github.com/xbnj/Miniproject/assets/42709556/ae5a77c0-4707-41dc-9c42-18615aa06332)

# REFERENCES 

  [1] Md. Kamal Hossain, et. al. “RF rectifiers for EM power harvesting in a Deep Brain Stimulating device” DOI 10.1007/s13246-015-0328-7 2020.
 
  [2] Khaleda Akhter Sathi, et. al. “Design and Implementation of a Low Power Energy Harvested Head-mountable Deep Brain Stimulation Device”, 2020, Dhaka, Bangladesh. 
  
  [3]H. Chapade and R. Zele, "On-chip RF to DC Power Converter for Bio-Medical Applications," 2019 32nd International Conference on VLSI Design and 2019 18th 
International Conference on Embedded Systems (VLSID), Delhi, India, 2019, pp. 522-524, doi: 10.1109/VLSID.2019.00117. 

  [4]M. K. Hosain, A. Z. Kouzani, M. F. Samad and S. J. Tye, "A Miniature Energy Harvesting Rectenna for Operating a Head-Mountable Deep Brain Stimulation Device," 	in 	IEEE 	Access, 	vol. 	3, 	pp. 	223-234, 	2015, 	doi: 10.1109/ACCESS.2015.2414411.
  
  [5] Abbas Z. Kouzani, et. al. “Design and Analysis of an Antenna for Wireless  Energy Harvesting in a Head-mountable DBS Device”, Osaka, Japan, July 2013.
  
  [6] Abbas Z. Kouzani, et. al. “Design and Analysis of Efficient Rectifiers for  Wireless Power Harvesting in DBS Devices”, DOI 978-1-4673-6322-8/13/2013.
  
  [7 ]M. K. Hosain, A. Z. Kouzani, S. Tye, D. Mortazavi and A. Kaynak, "Compact stacked planar inverted-F antenna for passive deep brain stimulation implants," 2012 Annual        International Conference of the IEEE Engineering in Medicine and Biology Society, San Diego, CA, USA, 2012, pp. 851-854, doi: 10.1109/EMBC.2012.6346065.
  
  [8] Design of RF to DC conversion circuit for energy harvesting in CMOS 0.13-μm technology https://doi.org/10.1063/1.5080902  2012 
  
  [9]K. You, H. Kim, M. Kim and Y. Yang, "900 MHz CMOS RF-to-DC converter using a cross-coupled charge pump for energy harvesting," 2011 IEEE International Symposium on Radio-Frequency    Integration Technology, Beijing, China, 2011, pp. 149-152, doi: 10.1109/RFIT.2011.6141795.
  
  [10] Hsiao Chin Chen, et. al. “Batteryless Transceiver Prototype for Medical  
   Implant in 0.18- m CMOS Technology”, IEEE TRANSACTIONS ON MICROWAVE THEORY AND TECHNIQUES, VOL. 62, NO. 1, JANUARY 
 
 

  
 
