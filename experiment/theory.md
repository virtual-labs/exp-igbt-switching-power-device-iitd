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

4.  SCR has three operating modes: Forward Blocking, Forward Conduction and Reverse Blocking as shown in Fig. 4. 'I<sub>H</sub>' is the holding current and 'I<sub>L</sub>' is the latching current. The Forward breakover voltages 'V<sub>BO1</sub> , V<sub>BO2</sub> and V<sub>BO3</sub>' (V<sub>BO1</sub> <V<sub>BO2</sub> <V<sub>BO3</sub>) correspond to the Gate currents 'I<sub>g1</sub>, I<sub>g2</sub>  and I<sub>g3</sub>'  (I<sub>g1</sub> > I<sub>g2</sub> > I<sub>g3</sub>) respectively.



<div style="float: left; width:100%;"><br>
  
**Circuit Diagram to plot 'v-i' Characteristics**

The v-i characteristics of SCR can be obtained using the circuit diagram given in Fig. 3. AC supply is connected in series with SCR and a resistive load. In order to obtain the v-i characteristics, the Anode-to-Cathode voltage (v<sub>AK</sub>) and Anode current (i<sub>A</sub>) are to be recorded using any one of the following methods:

1.  Using Analog measuring instruments: Voltmeters and Ammeters
2.  Using Digital Storage Oscilloscope

**• Method-1: Using Analog measuring instruments: Voltmeters and Ammeters**
</div>

<center>
<img src="images/th6.png" height="350px">

<br>
Fig. 5. Circuit Diagram using meters.
<br>
</center>
<br>

Steps for experimentation (Refer Fig. 5): 

  1.  Ammeter to measure the anode current and Voltmeter to measure the anode-to-cathode voltage (v<sub>AK</sub>) are to be connected in series and parallel respectively to the SCR.

  2.  The gate supply circuit consists of a battery in series with the  rheostat and an Ammeter. The rheostat (R<sub>g</sub>) limits the gate current (I<sub>g</sub>) magnitude since only a very small amount of gate current is required to trigger the SCR into ON-state.

  3.  The input supply voltage is increased in steps and the corresponding Voltmeter and Ammeter readings are to be tabulated. The data points indicate the v-i characteristics.<br><br>


**Instruments required for the above method:**


<table border="0" align="center" style="width:100%; border:none;">
  <tr>
<td style="width:50%">
<center>
  
**Instrument**
</center>
</td>
<td style="width:50%">
  
<center>
  
**Quantity**
</center> 
    </td>
  </tr>

  <tr>
<td style="width:50%">
<center>
  
SCR mounted on a heat sink
</center>
</td>
<td style="width:50%">
   
<center>
  
**1**
</center> 
    </td>
  </tr>

  <tr>
<td style="width:50%">
<center>
Variable AC supply (autotransformer)
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>

  <tr>
<td style="width:50%">
<center>
Rheostats (Rating: 1 KΩ, 100 KΩ)
</center>
</td>
<td style="width:50%">
  
<center>
  
**2**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
Multi-meter
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
AC- Voltmeter
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
AC-Ammeter
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
DC-Ammeter
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
</table>



**• Method-2: Using Digital Oscilloscope (DSO)**


<center>
<img src="images/th7.png" height="350px">

<br>
Fig. 6. Circuit Diagram using probes.
<br>
</center>
<br>

Steps for experimentation (Refer Fig. 6): 

  1.  A hall effect current probe is used to measure the anode current (i<sub>A</sub>) and a differential voltage probe (DVP) to is used to measure the anode-to-cathode voltage (v<sub>AK</sub>).<br>
  2.  Measure the anode current using the hall effect current probe (connect this probe to channel-2 of DSO which displays on y-axis). The voltage probe is connected across the SCR to measure the anode-to-cathode voltage (connect this probe to channel-1 of DSO which displays on x-axis).<br>
  3.  The gate supply circuit consists of a battery in series with a rheostat and a DC ammeter. The rheostat (R<sub>g</sub>) limits the gate current (I<sub>g</sub>) magnitude since only a very small amount of gate current is required to trigger the SCR into ON-state.<br>
  4.  Increase the input supply voltage (v<sub>in</sub>) gradually and observe the current-vs-voltage profile simultaneously on the DSO screen. This trace is the v-i characteristics of the SCR.<br<br>
  


**Instruments required for the above method:**


<table border="0" align="center" style="width:100%; border:none;">
  <tr>
<td style="width:50%">
<center>
  
**Instrument**
</center>
</td>
<td style="width:50%">
  
<center>
  
**Quantity**
</center> 
    </td>
  </tr>

  <tr>
<td style="width:50%">
<center>
  
SCR mounted on a heat sink
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>

  <tr>
<td style="width:50%">
<center>
Variable AC supply (autotransformer)
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>

  <tr>
<td style="width:50%">
<center>
Rheostats (Rating: 1 KΩ, 100 KΩ)
</center>
</td>
<td style="width:50%">
  
<center>
  
**2**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
Multi-meter
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
Digital Oscilloscope (DSO)
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
Differential Voltage Probe
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
  
  <tr>
<td style="width:50%">
<center>
Current Probe
</center>
</td>
<td style="width:50%">
  
<center>
  
**1**
</center> 
    </td>
  </tr>
</table>

