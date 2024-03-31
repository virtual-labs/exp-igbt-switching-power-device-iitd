### Theory


**Representation of IGBT:**

Fig. 1(a) and 1(b) show the symbolic representation of IGBT and a typical IGBT package available in market.

<br>

<table border="0" align="center" style="width:100%; border:none;">
  <tr>
<td style="width:50%">
<center>

<br>
<img src="images/th1.png">
<br><br>
Fig. 1(a). Symbolic representation of IGBT.
<br><br>
</center>
</td>
<td style="width:50%">
  
<center>

<br>
<img src="images/th2.png">
<br><br>
Fig. 1(b). A typical IGBT package.
<br><br>
</center> 
    </td>
  </tr>
</table>
<br>

<br>
<div style="float: left; width:100%;"><br>
  
**Introduction to IGBT:**

Fig. 2 shows the internal structure of an IGBT. Some of the key features of IGBT are compiled and given below.

</div>

<center>
<img src="images/th3.png" height="350px">

<br>
Fig. 2. Internal structure of IGBT.
<br>
</center>
<br>

1.  Insulated-Gate Bipolar Transistor (IGBT) is a semiconductor power device. It combines the advantages of a BJT and a MOSFET. It has high input impedance, like MOSFET, and low on-state conduction losses, like BJT. However, it shows higher switching time especially during the turn-off transition.<br>

2.  It has a four PNPN layer structure: a) Two P-type doped (p) layers. b) Two N-type doped layers- one is heavy doped (n+) and the other is lightly doped (n-). It has three junctions: n+-p (J<sub>1</sub>), p-n- (J<sub>2</sub>) and n--p (J<sub>3</sub>).<br>
3.  The  SCR has three external terminals namely: Anode (A), Cathode (K) and Gate (G).<br><br>


**Operating modes of IGBT:**
<br>

1.  Forward Blocking State: An IGBT is a voltage controlled device. When the Collector voltage is made more positive with respect to the Emitter and the Gate current is zero, the Collector current is negligible.

2.  Forward Conducting State: When the Gate voltage is made more positive than the Emitter voltage, n carriers are drawn into the p-channel near the gate region; this results in a forward bias of the n-p and p-n junctions. Current freely flows from collector to emitter.<br>
During forward conduction, the IGBT will operate in any one of the following states, depending on the values of Collector-to-Emitter voltage (VCE) and the Gate voltage (VGE) values: Cut-off region, Active region or Saturation region.
  
3.  Once the SCR starts conducting, gate loses control over the device. It continues conducting even after gate signal is removed. However, if the forward anode current (I<sub>A</sub>) is reduced below a level known as the ‘holding current’ (I<sub>H</sub>), the SCR goes to blocking state. The holding current is less than the latching current.

4.  Reverse Blocking State:  When the Emitter voltage is higher with respect to the Collector voltage, no current can flow through the device even with gate current applied.<br><br>



**Characteristics of the IGBT:**

There are two important characteristics defined for an IGBT:

1.  Output Characteristics: It is the plot between the Collector-to-Emitter voltage (VCE) and the Collector current (IC) for a fixed Gate-to-Emitter voltage (VGE). The circuit diagram to plot the characteristics is given in Fig. 3. Voltage ‘VCE’ is measured by the voltmeter while the ammeter measures the current ‘IC’.<br><br>

<center>
<img src="images/th4.png" height="350px">

<br>
Fig. 3. Circuit diagram for Output characteristics.
<br>
</center>
<br> 

The output characteristics of IGBT is shown in Fig. 4.

<center>
<img src="images/th5.png" height="350px">

<br>
Fig. 4. Output characteristics of IGBT.
<br>
</center>
<br> 
IGBT has three operating regions: Cutoff region, Linear region and Saturation region as shown in Fig. 4. <br><br>

a)  In cutoff region, the Gate voltage is lower than the threshold (VT) and the IGBT doesn’t conduct.<br>
b)  In linear region, the Collector current IC varies in proportion to the Collector-to-Emitter voltage VCE. IGBT is operated in the linear region for switching actions.<br>
c)  In the saturation region, the Collector current remains almost constant for any increase in the value of VCE.<br>

<div style="float: left; width:100%;"><br>
  
2.  Transfer Characteristics: It is the plot between the Gate-to-Emitter voltage (V<sub>GE</sub>) and the Collector current (I<sub>C</sub>) for a fixed value of Collector-to-Emitter voltage (V<sub>CE</sub>). The circuit diagram to plot the characteristics is given in Fig. 5. Voltage ‘V<sub>GE</sub>‘ is measured by the voltmeter while the ammeter measures the current ‘I<sub>C</sub>’.
</div>

<center>
<img src="images/th6.png" height="350px">

<br>
Fig. 5. Circuit diagram for Transfer characteristics.
<br>
</center>
<br>


<div style="float: left; width:100%;"><br>
  
The Transfer characteristics of IGBT is shown in Fig. 6. 
</div>

<center>
<img src="images/th7.png" height="350px">

<br>
Fig. 6. Transfer characteristics of IGBT.
<br>
</center>
