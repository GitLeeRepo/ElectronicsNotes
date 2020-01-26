# Overview

Notes on electronics

# References

## Suppliers

* [SparkFun](https://www.sparkfun.com/)
* [Mouser](https://www.mouser.com/)
* [Jameco](https://www.jameco.com/)

## Udemy

* [Crash Course Electronics and PCB Design](https://www.udemy.com/crash-course-electronics-and-pcb-design/learn/v4/overview)

## YouTube Refences

tbd

## My Other Notes

### Notes in this repository

* [GreatCoursesNotesCh01-06](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/GreatCoursesNotesCh01-06.md#overview)
* [GreatCoursesNotesCh07-12](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/GreatCoursesNotesCh07-12.md#overview)
* [TransistorSupplementGC](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/TransistorSupplementGC.md#overview)
* [CircuitSimulators](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/CircuitSimulators.md#overview)
* [EquipmentNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/EquipmentNotes.md#overview)
* [PartsNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/PartsNotes.md#overview)
* [ArduinoNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/ArduinoNotes.md#overview)
* [PICNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/PICNotes.md#overview)
* [USB2Notes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/USB2Notes.md#overview)

### Notes in Other Repositories

* [USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview)
* [HardwareInfoNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/HardwareInfoNotes.md#overview)
* [NotesGuidelines](https://github.com/GitLeeRepo/NotesGuidlines/blob/master/NotesGuidelines.md#overview)

# Table of Contents

tbd

# Concepts and Terminology

* **Analog Electronics** -- involves **smoothly varying signals**.  **Signals** that can take on **varying voltages** or other characteristics. On a **scope** they are represented by **sine waves** and other **continuously varying wave types**.

* **CMOS chip** -- **Complimentary Metal Oxide Semiconductor** -- an **Integrated Circuit package**

* **Conductors** -- carry **electrical charge**.  They are made of materials such as **copper**, **gold**, **silver**, and **aluminum**.  These materials have **electrons** that are **loosely** bound to the **outer shell (valence shell)** of their **atoms**, so those **electrons** can be easily moved as **current**, which is pushed by a **voltage** force.

* **Conventional Current** -- refers to the **flow of holes** along a **conductor** from **positive to negative**.  This contrasts with **electron current** which refers to the flow of **electrons** in the **opposite direction** from **negative to positive**.  Generally, by convention, when we are referring to **current** in **electronics we are referring to **conventional current**.

* **Current** -- in **electronics** it is generally referring to **conventional current** in which the **holes** flow from **positive** to **negative**.  It is **measured** in **amperes**.  Refer to **conventional current**, **electron current** and **holes** for more details.

* **Current Source** -- A **current source** is an electronic circuit that **delivers or absorbs an electric current** which is **independent of the voltage** across it.  There are **two types**. An **independent current source (or sink)** delivers a **constant current**. A **dependent current source** delivers a current which is **proportional** to some other **voltage** or **current** in the circuit. **Current-stable nonlinear implementation** is implemented by **active electronic components** (**transistors**) having **current-stable nonlinear output** characteristic when driven by **steady input quantity (current or voltage)**. These circuits behave as **dynamic resistors changing their present resistance to compensate current variations**. For example, if the **load increases its resistance**, the **transistor decreases** its present **output resistance** (and vice versa) to keep up a **constant total resistance in the circuit**. ([Wikipedia](https://en.wikipedia.org/wiki/Current_source))

* **Digital Electronics** -- involves a **fixed voltage** that varies between **on/off** states.  On a **scope** they are represented by **square waves** that are either **on** or **off**.  In reality, **digital electronics** is built on **analog electronics** it is just a **model** that sits on top of it.

* **Electron Current** -- refers to the **flow of electrons** along a **conductor** from **negative to positive**.  This contrasts with **conventional current** which refers to the flow of **holes** in the **opposite direction** from **positive to negative**.  Generally, by convention, when we are referring to **current** in **electronics we are referring to **conventional current**.

* **EPROM** -- **Erasable Programmable Read Only Memory**

* **Floating** -- a **floating connection** is one that **isn't tied** to either a **voltage source** or **ground**.

* **Gain** -- a measure of the ability of a **two-port circuit (often an amplifier)** to **increase the power or amplitude of a signal** from the **input to the output port** by **adding energy** converted from some **power supply** to the **signal**. It is usually defined as the **mean ratio** of the **signal amplitude** or **power** at the **output port** to the amplitude or power at the input port. It is often expressed using the **logarithmic decibel (dB) units** ("dB gain"). A **gain greater than one** (greater than zero dB), that is **amplification**, is the defining property of an **active component** or circuit, while a **passive circuit** will have a **gain of less than one**.

* **Holes** -- create when an **electron** in a **conductor** moves to the **next atom**.  If the **current** is viewed as moving from **positive to negative**, say from **left to right**, the **holes** move in the **opposite** direction, from **right to left**.  The flow of **electrons** is referred to as **electron current** with the flow of the **holes** referred to as **conventional current**.

* **Impedance** -- the **measure of the opposition that a circuit presents to a current when a voltage is applied**. **Impedance** extends the **concept of resistance to AC circuits**, and possesses **both magnitude and phase**, unlike resistance, which has only magnitude. When a circuit is driven with **direct current (DC)**, there is **no distinction between impedance and resistance**; the latter can be thought of as **impedance with zero phase angle**. The notion of **impedance** is useful for performing **AC analysis** of electrical networks, because it allows **relating sinusoidal voltages and currents by a simple linear law**. **Impedance** is a **complex number**, with the same units as resistance, for which the SI unit is the **ohm (Ω)**. Its **symbol is usually Z**. ([Wikipedia](https://en.wikipedia.org/wiki/Electrical_impedance))

* **Insulators** -- **resist** **electrical charge**.  They are made of materials whose **electrons** are **tightly bound** to their **outer shell (valence shell)** and don't flow easily from on **atom** to the next.

* **Line level** -- the specified **strength** of an **audio signal** used to **transmit analog sound** between **audio components** such as CD and DVD players, television sets, audio amplifiers, and mixing consoles.  **Line level** it is **between weaker audio signals sources** and **stronger signals**, such **loudspeakers**. ([Wikipedia/edited](https://en.wikipedia.org/wiki/Line_level))

* **Op-amp** -- **Operational Amplifier** -- have **two inputs**, ""inverting (-)** and **non-inverting (+)**, along with **one output**.  The **polarity** of the **signal** is **reversed** between the **inverting input** and the **output**.  The **signal** at the **non-inverting input retains its polarity*** at the **output**. (paraphrasing from "Timer, Op Amp, & Optoelectronic Circuits & Projects** by Forrest M. Mims III)

* **Output Impedance** --  of an electrical network is the measure of the **opposition to current flow (impedance)**, both **static (resistance)** and **dynamic (reactance)**, into the **load network** being connected that is internal to the electrical source. The **output impedance** is a measure of the source's **propensity to drop in voltage when the load draws current**. The **output impedance** is sometimes referred to as the **source impedance** or **internal impedance**. In the case of a **nonlinear device**, such as a **transistor**, the term **"output impedance"** usually refers to the **effect upon a small-amplitude signal**, and will **vary with the bias point** of the **transistor**. ([Wikipedia](https://en.wikipedia.org/wiki/Output_impedance))

* **Pitch** -- the **distance** between **component pins**.

* **Pull Down and Pull Up Resistors** -- used in **digital circuits** to prevent **floating inputs** where the a **switch/gate/connection** is not connected to either **power** or **ground**, it is **indeterminate** and can bounce **between on and off** due to **extraneous signals and interference**.  Refer also to the **Pull Down and Pull Up Resistors** section for more information and diagrams.
  * **Pull Up Resistor** is connected in **parallel** between a **switch** and a **logic circuit/microcontroller** and is connected to the **voltage source** (typically 3.3 or 5V).  When the **switch is open**, without the **pull up resistor**  it would be **floating**, but with it is connected through the **resistor** to the **voltage source** so the **pin** remains in a **high state (3.3V or 5V)** which is what is desired.  This is **inverting** in the sense that when the **switch is closed** the **pin is off**, i.e., pushing the switch turns it off.  **Pull up resistors** are **builtin** to a lot of **microcontrollers** and therefore don't need to be added to the outside circuit.
  * **Pull Down Resistor** is connected in **parallel** between a **switch** and a **logic circuit/microcontroller** and is connected to **ground** .  When the **switch is open**, without the **pull down resistor**  it would be **floating**, but with it is connected through the **resistor** to  **ground** so the **pin** remains in a **low state (0V)** which is what is desired. This a a **non-inverting** in that when the **switch is closed** the **pin is on**.  **Pull down resistors** typically are **not builtin to microcontrollers** and therefore need to be **added to the external circuit**.  

* **TTL chip** -- **Transistor Transistor Logic**

* **Vcc** -- positive supply voltage where the **"c" stands for collector**.  Technically this applies to **BPJ (Bipolar Junction)** circuits.  It is **equivalent to Vdd** in **FET** circuits, and are sometimes the labels are used interchangeably.  See also **Vdd**, **Vee**, and **Vss**.

* **Vdd** -- positive supply voltage where the **"d" stands for drain**.  Technically this applies to **FET (Field Effect Transistor)** circuits.  It is **equivalent to Vcc** in **PBJ** circuits, and are sometimes the labels are used interchangeably.  See also **Vcc**, **Vee**, and **Vss**.

* **Vee** -- negative supply voltage where the **"e" stands for emitter**.  Technically this applies to **BPJ (Bipolar Junction)** circuits.  It is **equivalent to Vss** in **FET** circuits, and are sometimes the labels are used interchangeably.  See also **Vcc**, **Vdd**, and **Vss**.  More rarely used in diagrams than the others.

* **Vss** -- negative supply voltage where the **"s" stands for source**.  Technically this applies to **FET (Field Effect Transistor)** circuits.  It is **equivalent to Vee** in **FET** circuits, and are sometimes the labels are used interchangeably.  See also **Vcc**, **Vdd**, and **Vee**.

* **VCO** -- **Voltage Controlled Oscillator** -- **integrated circuit** that has **pins** for external **resistors** and **capacitors**, which are used to generate an **oscillated signal for timing** purposes.

# Digital and Analog Electronics

## Analog Electronics

### Types of parts

* **resistors** --  **resists current**, **drops voltages**
* **capacitors** -- **stores electrical charge**
* **inductors/coils** -- **store/transfer electromagnetic energy**
* **diodes** -- a **semi-conductor device** that allows **current to flow in one direction only**
* **transistors** -- a **semi-conductor device** that is used as **amplifiers** and **switches**
* **batteries** -- **source** of electrical **current** / **voltage generators**
* **wires** -- used as **conductors** so that electrical **current** and **signals** flow from on **electrical element to another**.

## Digital Electronics

* **Digital electronics** is a **two state system** in which the state is either **on** or **off**.

* Many **digital systems** are based on a **fixed voltage** that is either **on** or **off**, with the **5V** system being the **most common**.  In a **5V system** **zero volts** represents **digital zero** and **5V** represents **digital one**. **3.3V** and **1.8V** are also **common**.

* **Digital signals** are represented by **square waves** on a **oscilloscope**. 

* **Analog to Digital converters** are used to **convert analog signals** to **digital**.  **Digital to Analog converts** do the reverse.  There is a certain **level of errors** that are going to occur, but in a well designed system they are generally not noticeably.  These errors occur both during **conversion** and **compression/decompression**.

### Type of Digital Parts

* **Integrated Circuits** -- for the **DIP (Duel Inline Package**), which has **pins** that go through **hole** in the **circuit board**, the **top** is typically marked with an **indentation**.  The **power pin** is typically on the **upper right**.  The **ground** is typically on the **bottom left**.  **Pin 1** is on the **top left** with **pin 2** being the next one on the **left**, and then wrapping around to the **bottom right** once the **bottom left** is reached, continuing to the **top right** for the **highest numbered pin**, i.e., they are counted in a **counter-clockwise** direction.

* **Micro Controlers** -- are **little computers** on a **chip**.  The **PIC family** of **chips** are an example, among many others.

* **And Gates**

* **Inverter Gates**

# Units of Measure

## Basic SI Units of Measure

Quantity   | Name      | Symbol | Fundamental Units
-----------|-----------|--------|----------------------
Time       | Second    | s      | NA
Length     | Meter     | m      | NA
Mass       | Kilogram  | kg     | NA
Force      | Newton    | N      | 1kg*m/s^2
Charge     | Coulomb   | C      | 6.24x10^18 electrons
Energy     | Joule     | J      | 1N*m
Current    | Ampere    | A      | 1C/s
Voltage    | Volt      | V      | 1J/C
Power      | Watt      | W      | 1J/s

## Prefixes in SI System

Symbol | Prefix  | Scaling Factor
a      | atto    | 10^-18
f      | femto   | 10^-15
p      | pico    | 10^-12
n      | nano    | 10^-9
u      | micro   | 10^-6
m      | milli   | 10^-3
k      | kilo    | 10^3
M      | mega    | 10^6
G      | giga    | 10^9
T      | tera    | 10^12
P      | peta    | 10^15
E      | exa     | 10^18


# Calculations

The variables represent:

* **P is power in Watts**
* **I is current in Amperes**
* **V is voltage in Volts**
* **R is resistance in Ohms**

## Ohm's Law

* **V = IR**
* **I = V/R**
* **R = V/I**

### Current Calculation in a Series Circuit

When calculating **current** in a circuit with **multiple resistors** that are **in series**, simply **add all resistances** and then apply **Ohm's Law** to determine your **current**, **I = V/R**.

## Power Calculations

**Power** is **work** which is **energy expended**.

* **P = VI** -- **voltage times current equals power**.  This is **true** for **DC** when everything is **in phase**.
* **P = (V^2)/R** -- using **substitution** from **Ohm's Law** where  **(V^2)/R** comes from **I = V/R** so **P = V\*V/R = (V^2)/R**.  Note this is **important** because **power** is not **proportional** to voltage, but to **voltage squared**, which is why it is **important** to **lower voltage** in systems.  Over the years **voltage** in circuits went from typically being **12V** to **5V**, **3.3V**, **1.8V**, **1.5V**, and **1.2V** systems.

### Definition of Power

* **dW = V \* dQ/dt** -- the **change** in **power** is **equal** to the **change** in **current** per the **Unit time**. This is equivalent to the **P = VI** derivation.

# Current

* **Current** is defined as the **amount of charge q(electrons)** that passes a **fixed point** as a **function of time**. Mathematically, **current** is **equal to the amount of charge per unit of time**.  The equation is **i = dq/dt**.

* **Current** -- in **electronics** it is generally referring to **conventional current** in which the **holes** flow from **positive** to **negative**.  It is **measured** in **amperes**.  Refer to **conventional current**, **electron current** and **holes** for more details.

* **Conventional Current** -- refers to the **flow of holes** along a **conductor** from **positive to negative**.  This contrasts with **electron current** which refers to the flow of **electrons** in the **opposite direction** from **negative to positive**.  Generally, by convention, when we are referring to **current** in **electronics we are referring to **conventional current**.

* **Electron Current** -- refers to the **flow of electrons** along a **conductor** from **negative to positive**.  This contrasts with **conventional current** which refers to the flow of **holes** in the **opposite direction** from **positive to negative**.  Generally, by convention, when we are referring to **current** in **electronics we are referring to **conventional current**.

* **Holes** -- create when an **electron** in a **conductor** moves to the **next atom**.  If the **current** is viewed as moving from **positive to negative**, say from **left to right**, the **holes** move in the **opposite** direction, from **right to left**.  The flow of **electrons** is referred to as **electron current** with the flow of the **holes** referred to as **conventional current**.


![Current01.png](images/Current/Current01.png)

Refer to the **[Current Sourcing and Sinking](#current-Sourcing-and-sinking)** section for additional details

# Voltage

* **Voltage** is what helps us to **move the charge** through a **conductor** by using **pressure/force**.

* The **difference** between the **charge** at the **source** and at the **ground** is the **potential energy (U)** which is the **basis of voltage**.

* **Voltage mathematical definition: V=U/q0**, where **U** is the **potential energy in joules** and **q0** is the **charge in coulombs**.

* This equation results in **1V = 1J/1C**, where **J = Joules** and **C = Coulombs**

## Generation of Voltage

There are a number of ways to **generate voltage**, but most are based on either **chemicals**, **magnetic fields**, or **photo-electric effect**.

### Batteries

* **Chemical Batteries** are devices that use **chemicals (wet or dry)** to **create an accumulation of charge** and hence a **voltage**.

* The **positive** side of the **battery** is the **Anode**.

* The **negative** side of the **battery** is the **Cathode**.

* The **amount** of **charge** in a **battery** is often on the **label**.  For example, a **1.5V (actual 1.2V) Ni-MH battery** might show **2400mAh**, which means it can **supply 2400mA** for **one hour**.  This is **not** a very **accurate** way of representing the amount stored, since if you drained it by **2400mA** it would become **ineffective before one hour**, because it does **not maintain the full charge** over time .  A more accurate way would be to use **watt/hours** which accounts for the **drop in voltage over time**.

* The **amount of energy stored** is **proportional to the size** of the **battery**.  This  is why a **AAA battery** does **not** hold as much as much **charge** as a **AA** battery.  While a **1.2V Ni-MH AA battery** might have **2400mAh** and equivalent **AAA battery** might only have **800mAh**.

* **9V rectangular batteries**, which have the **two connectors** at the **top**, are actually made up of **6 1.5V cells wired in series** to produce the **9V**.

* **Batteries** have an **internal resistor** that supplies a **small amount of resistance**, which prevents it from being an **ideal battery**. When you **measure** the **voltage** on a **meter** it is **unloaded**, which means there is **very little current**, since the **current** is proportional to the **load/resistance**.  So because the **battery** only has a **very small amount** of **resistance** the **voltage** will **drop very little** when the **meter** is connected, so you are getting a **fairly accurate approximation of the ideal voltage**.

* If you **measure** the **current** directly between the **leads** of a **1.5V battery**, you are going to get a **high current** (in the **5A to 9A** range) for a **short time** and then the **current** is going to **start dropping fairly rapidly** as it **heats up** causing **more resistance**.  If you leave it connected for to long you will eventually **damage the battery**.

#### Batteries in Series and Parallel

* **Batteries in Series** -- used to increase the **voltage** -- **4 1.5V batteries in series** is **6V**.

* **Batteries in Parallel** -- used to increase the **current** -- **4 1.5V batteries in parallel** remains only **1.5V**, but the **current** is **4 times greater**.  If the **circuit resistance** is **1 KΩ** the **total current** would be **24 mA** since the **6 mA** of a **1.5V** system is **multiplied by 4**, or it will last **4 times longer in time** if the **current is the same**.  Keep in mind though that there are **variations** in each **batteries voltage, resistance, and remaining charge**, so the **4 times** is only a **rough estimation**.

You have to be **very careful** when configuring **batteries** not to get the **polarities mixed up**, otherwise you can **burn out the circuit and/or battery**.  In addition, on **high current batteries** such as **car batteries** and **lithium ion (cell phones)** can hurt you through **shock or explosion**.

Note that if the **batteries** are **loose** and the **same terminals are touching**, this is **not a problem**.  The **problem occurs** when these **batteries** are placed **in a circuit with a load**.

#### Battery Reliability

If you **push a battery too hard** by giving it a **load that exceeds** its capabilities.  Also, note that if the **resistance** in the circuit is **too low**, the battery voltage will also **start dropping**, but in this case you are **overheating the battery** which is causing **more resistance**.

# Ground

**Ground** is a **reference point** from which to **evaluate voltages**.  In **many circuits** it is typically **0 V**, but it doesn't have to be.  **Every circuit must have a ground**.  

With **batteries ground** is typically the **negative terminal** of the **battery**, although it might be a **combination** of the **negative terminal** of the **battery** and the **frame** of the **enclosure**.  For example, **automobiles** typically use both the **negative terminal** of the **battery** and the **frame of the car** as the ground, with the **two connected to each other**.

# Controlled Sources (Sourcing and Sinking)

**Controlled sources** in which **one source controls another** is the basis for many of electronic circuits, such as **amplifiers** 

* **Voltage Controlled Voltage Source (VCVS)** 
* **Current Controlled Voltage Source (CCVS)** 
* **Voltage Controlled Current Source (VCCS)** 
* **Current Controlled Current Source (CCCS)** 

* **Current Source** -- A **current source** is an electronic circuit that **delivers or absorbs an electric current** which is **independent of the voltage** across it.  There are **two types**. An **independent current source (or sink)** delivers a **constant current**. A **dependent current source** delivers a current which is **proportional** to some other **voltage** or **current** in the circuit. **Current-stable nonlinear implementation** is implemented by **active electronic components** (**transistors**) having **current-stable nonlinear output** characteristic when driven by **steady input quantity (current or voltage)**. These circuits behave as **dynamic resistors changing their present resistance to compensate current variations**. For example, if the **load increases its resistance**, the **transistor decreases** its present **output resistance** (and vice versa) to keep up a **constant total resistance in the circuit**. ([Wikipedia](https://en.wikipedia.org/wiki/Current_source))

## Current Sourcing and Sinking

From: [current-sourcing-sinking](https://startingelectronics.org/articles/current-sourcing-sinking/)

* A **current source** is when a **load** is **connected to a device** so that the **device supplies current to the load** (sources current) then the configuration is said to be **current sourcing**. An example is a series resistor and LED connected between a microcontroller pin and GND. When the microcontroller pin is switched high (logic 1) then the microcontroller will source current to the load. In this configuration a logic 1 will supply power to the load (switch the LED on) and a logic 0 will switch power to the load off (switch the LED off).

* **Current sinking** is When a **load** is **connected to a device** so that **current flows from the power supply through the load and into the device**, then the configuration is said to be **current sinking**. When current flows into the device, it is said to be sinking current.

![Current02.png](images/Current/Current02.png)

Another view

![Current03.png](images/Current/Current03.png)



## Sourcing as related to Power

![Current03.png](images/VoltageCurrentSources/VoltageCurrentSources01.png)

# VCC vs VSS vs VDD vs VEE

From [StackExchange](https://electronics.stackexchange.com/questions/17382/what-is-the-difference-between-v-cc-v-dd-v-ee-v-ss)

Back in the 1960s or earlier, logic was implemented with **bipolar transistors**. Even more specifically, they were **NPN** because for some reasons I'm not going to get into, NPN were faster. Back then it made sense to someone that the **positive supply voltage would be called Vcc** where the **"c" stands for collector**. Sometimes (but less commonly) the **negative supply was called Vee** where **"e" stands for emitter**.

When **FET** logic came about, the same kind of naming was used, but now the **positive supply was Vdd (drain)** and the **negative Vss (source)**. With **CMOS** this makes no sense, but it persists anyway. Note that the **"C" in CMOS stands for "complementary"**. That means both N and P channel devices are used in about equal numbers. A **CMOS inverter** is just a P channel and a N channel MOSFET in its simplest form. With roughly equal numbers of N and P channel devices, drains aren't more likely to be positive than sources, and vice versa. However, the Vdd and Vss names have stuck for historical reasons. Technically **Vcc/Vee is for bipolar** and **Vdd/Vss for FETs**, but in practice today **Vcc and Vdd mean the same**, and **Vee and Vss mean the same**.

# Semiconductors

* **Semiconductors** are **neither good conductors** or **good insulators**, they are **neutral**. 

* **Doping agents** are **atoms** that introduced to make it **good** at either **conducting** or **insulating**.

* **Phosphorus** a **N-type dopant** is added, which has **5 electrons** compared to the **4 electrons** of the **silicon** in their **valence shells**.  This causes the **overall charge** to become **slightly negative**.  This creates an **N-type semiconductor**

* **Boron** a **P-type dopant** is added, which has **3 electrons** compared to the **4 electrons** of **silicon** in their **valence shells**.  This causes the **overall charge** to become **slightly positive**. This creates an **P-type semiconductor**

## Semiconductor Materials

* **Silicon (Si)** -- has **4 electrons** in its **valence shell** when it is **neutral**
* **Born (B)** -- has **3 electrons** in its **valence shell** and is used as a **P-type dopant**
* **Phosphorus (P)** has **5 electrons** in its **valence shell** and is used as a **N-type dopant**

## Devices and Their Approximate Current Needs

Device/System               | Average Current Drain
----------------------------|----------------------
Single Gate in a uProcessor | 10nA
Single Gate in a TTL Chip   | 5mA
Light Emitting Diode        | 20mA
Digital TTL Chip            | 30mA
LCD Calculator              | 50mA
27" TV                      | 2A
Personal Computer           | 5A
Hair Dryer                  | 10A


# Typical Component Characteristics

## Resistors

* **Resistors** drop **voltages** as the **current** passes through them.

* **Resistors** are used to **control voltages and currents**

### Resistor Color Code

![Current03.png](images/Components/Resistor/ResistorColorCode01.png)

## Capacitors

Refer to the [PartsNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/PartsNotes.md#overview) document for a lot more info on **capacitors**.

**Capacitors store electrical charge**

Here are some **symbols** for both the **polarized** and **non-polarized** types:

![CapacitorTypes01.png](images/Components/Capacitor/CapacitorTypes01.png)

* A **capacitor** consists of two **plates**, separated by a **dielectric**, which could be **air**, **paper**, or among many other **materials**.

![CapacitorTypes02.png](images/Components/Capacitor/CapacitorTypes02.png)

Refer to the **Inductors section** for information **contrasting capacitors and inductors**.

### Ceramic

**Ceramic capacitors** are **non-polarized**. They are the **most commonly used capacitor** in electronics. The are made from a **ceramic material** from which their **dielectric** is made. Ceramic capacitors are usually **both physically and capacitance-wise small**. It’s hard to find a ceramic capacitor much larger than **10µF**.

### Electrolytic

**Electrolytic capacitors** are great because they can pack a lot of capacitance into a relatively small volume. If you need a capacitor in the **range of 1µF-1mF**, you’re most likely to find it in an electrolytic form. They’re especially **well suited to high-voltage** applications because of their **relatively high maximum voltage ratings**.

**Aluminum electrolytic capacitors**, the **most popular** of the electrolytic family, usually look like little **tin cans**, with both leads extending from the bottom.

**Electrolytic** caps are usually **polarized**. They have a **positive pin – the anode** – and a **negative pin called the cathode**. When voltage is applied to an electrolytic cap, the **anode** must be at a **higher voltage** than the **cathode**. The **cathode** of an **electrolytic** capacitor is usually **identified with a ‘-’ marking**, and a **colored strip** on the case. The leg of the **anode** might also be **slightly longer** as another indication. If **voltage** is applied in **reverse** on an **electrolytic** cap, they’ll **fail spectacularly** (making a pop and bursting open), and permanently. After popping an electrolytic will **behave like a short circuit**.

## Inductors

Refer to [Wikipedia](https://en.wikipedia.org/wiki/Inductor) for more info and **images** of various kinds to **inductors**

**Electromagnetic induction** is where a **changing current** in **one circuit** will **induce**  a **changing current** in **another circuit**.  The **intermediator** between the **two separate currents** is the **magnetic field**.

**inductance** is measured in **henrys**, typically in the **mH to uH range**.  A full **henry** would be a massive amount of **inductance**.

The letter **L** is used to represent **inductance**.

![Inductance01.png](images/Components/Inductor/Inductance01.png)

**Inductors** are used to **resist changes in the current flowing through it**.  They are used as **filters** to **pass low frequency signals** and **resist high frequency signals**.

An **inductor** consists of **wound wire**, either are around an **inductive material**, such as **iron ferrite**, or around **air**

**Inductor in a DC Circuit**:

![InductorInDC01.png](images/Components/Inductor/InductorInDC01.png)

In a **DC circuit** where the **current** is generally stable, **no inductance** will be produced.  There will be inductance when the **inductor** is **charging up/current increasing**.  If however, you were to move an **inductive material** through it, the **movement** would cause a **current to be generated**.  In an **AC** circuit where the current is **continually alternating** a **current is generated**. 

You can **generate a magnetic field** with **currents**.

**Inductor Images** from the  [Wikipedia](https://en.wikipedia.org/wiki/Inductor) page:

![InductorPhotos01.png](images/Components/Inductor/InductorPhotos01.png)

The above photos shows a selection of **low value inductors**.

![InductorPhotos02.png](images/Components/Inductor/InductorPhotos02.png)

The above is a selection of **ferrite core inductors**, with some **transformers** containing **two inductors** in them at the top.


**Inductor symbols**:

![InductorSymbols01.png](images/Components/Inductor/InductorSymbols01.png)

**Inductors** are used in:

* **Power supply** circuits
* **Filters**

In many cases, wherever you can use an **inductor**, you can also use a **capacitor**, and **vice versa**, with the **capacitor** being preferred in many **circuits**, particularly **digital circuits**.

![InductorInDC02.png](images/Components/Inductor/InductorInDC02.png)

In the image above, the **inductor stores charge** in the **magnetic field** when the **switch** is connected to the **battery**.  When the **switch** is changed to the **load side**, the **inductor discharges into it**.  Note how the **current** flows in the **opposite direction** when the **magnetic field collapses**, while the **voltage polarity remains the same**.

The circuit above is referred to as an **RL circuit**, which is a circuit that consists of a **resistor** and an **inductor**, either in **series driven by a voltage source** or in **parallel driven by a current source**.  There are **differential equations** that solve for this type of circuit.

Like a **capacitor**, an **inductor** is a **reactive component** that does **not dissipate power**.

**Inductors** tend to **block high frequencies** and let **low frequencies pass**, while **capacitors** tend to **block low frequencies** and let **high frequencies pass**.

If the **frequency goes up** the **impedance goes up**. **XL = 2pi \* fL** where **XL** (**L** is subscript) is the **reactance** and **fl** being the **frequency \* the inductance**.  Which is similar the the **capacitance equation XC = 1/(2pi \* fC)** (the **inverse of the **inductance**)

**Lenz's law** states that an **inductor** will **generate a voltage to oppose the current with an opposite polarity**.

**Examples of inductors** include:

* **Ferrite beads** -- to **remove noise**
* **Adjustable inductors** allow you to **change the inductance** through varying the number of times the coil is wound.


## Transformers

**Transformers** consist of at least two **inductors**. This is because the **current** and **voltage** are **out of phase by 90 deg**.

If you have the **same number of turns** on **both sides** you will get the **same voltage** on both sides.  **Isolated circuits** use **isolation transformers** like this, such as in **medical devices** and other **devices** that need this kind of **isolation**.

When you **step up voltage** with a **transformer** you get **stepped down current**.  The **high transmission power lines** have small relative  **currents**.

## Diodes and LEDs

**LEDs** are **diodes** that **emit light (Light Emitting Diodes)** and so they both share **common properties**.


### Common Properties

TBD -- Decide how to merge/combine with diode and LED entry


* Current only flows in **one direction** from **anode (positive)** to **cathode (negative)**.  They **won't work** when plugged in **backwards**.

* The **longer lead** on an **LED** indicates the **positive lead**

* **Anode** is the **positive lead** -- made from **P-type** material

* **Cathode** is the **negative lead** -- made from **N-type** material

* **Forward voltage** is the amount of **voltage** absorbed by the **LED/diode**.  Since **Kirchhoff's Voltage Law** shows that the total amount of **voltage absorbed** by a circuit must be **equal** to the **voltage provided**. So if an **LED** has an average **forward voltage** of **2.2V** and its placed on a **9V sourced circuit**, a **resistor** must be added to the **circuit** to **absorb** the **remaining 6.8V**.  Assuming a **20mA current**, according to **Ohms Law** we need a **340Ω resistor (6.8/.02)** 

* The **diode/LED** will try to **maintain its forward voltage** with the **current varying accordingly**. This is one of the **properties** of **diodes** that make them useful in being able to help **regulate voltage amounts**.

* **Bias**
  * **Forward Bias** -- when the **power source** is turned on, with the **negative side** connected to the **cathode (N-type material)** and the **positive side** is connected to the **anode (P-type)**, **current** can flow and the **diode/LED** is said to be **forward biased**.
  * **Reverse Bias** -- when the **power source** is **reversed** and turned on, with the **positive side** connected to the **cathode (N-type material)** and the **negative side** is connected to the **anode (P-type)**, **no current** can flow and the **diode/LED** is said to be **reverse biased**.


## Diode

TBD -- Decide how to merge/combine with diode and LED entry

## Zener Diode

**Zener diodes** are designed to operate in the **breakdown region**.  They are used for **voltage stabilization**, **voltage regulation** and as a **voltage reference**.

## LED

Refer to:

* [All about LEDs](https://learn.adafruit.com/all-about-leds/what-is-an-led) --image from this site

### TBD Decide how to merge/combine with diode and common entry

* Current only flows in **one direction** from **anode (positive)** to **cathode (negative)**.  They **won't work** when plugged in **backwards**.

* The **longer lead** on an **LED** indicates the **positive lead (anode)** and the **"bulb"** has a **flat side** which indicates the **negative lead (cathode)**.

* **Anode** is the **positive lead**

* **Cathode** is the **negative lead**

![LED01.png](images/Components/LED/LED01.png)

* **Forward voltage** is the amount of **voltage** absorbed by the **LED**.  Since **Kirchhoff's Voltage Law** shows that the total amount of **voltage absorbed** by a circuit must be **equal** to the **voltage provided**. So if an **LED** has an average **forward voltage** of **2.2V** and its placed on a **9V sourced circuit**, a **resistor** must be added to the **circuit** to **absorb** the **remaining 6.8V**.  Assuming a **20mA current**, according to **Ohms Law** we need a **340Ω resistor (6.8/.02)** 

* **Typical forward voltages** for cheaper off the shelf **LEDs** is in the range of **2.1 to 2.5 V**, I have some that are **3.1 to 3.3 V**.

* In general **green** requires more **forward voltage** than **red** because **green** is a **higher frequency** than **red**, with **blue** being **higher** than **green** (picture the **spectrum order**)

* **Continuous Current** -- typically in the range of **10mA to 20mA ? (verify)**. The **Continuous Forward Current** specification of an **LED** serves to tell you the **maximum current** that an **LED** can be fed continuously without being **damaged** or **destroyed**.  If you provide **more current** to an **LED** than what is specified in the **continuous forward current** value, you risk **blowing** and **destroying** the **LED**. ([learningaboutelectronics.com](http://www.learningaboutelectronics.com/Articles/LED-specifications-continuous-forward-current))

* **Luminous Intensity** -- measure in **mcd** -- TBD

## Op Amps (a.k.a., op-amps, opamps)

Refer to:

* [Handbook Of Operational Amplifier Applications](pdf/HandbookOfOperationalAmplifierApplications.pdf) -- Texas Instrument
* [Op Amps for Everyone](pdf/OpAmpsForEveryone.pdf) -- Texas Instruments


### Overview of Op Amps

* **Op amp** -- **Operational Amplifier** -- have **two inputs**, ""inverting (-)** and **non-inverting (+)**, along with **one output**.  The **polarity** of the **signal** is **reversed** between the **inverting input** and the **output**.  The **signal** at the **non-inverting input retains its polarity*** at the **output**. (paraphrasing from "Timer, Op Amp, & Optoelectronic Circuits & Projects** by Forrest M. Mims III)

* **Op amps** can be thought of as **virtual amplifiers**, in that they contain numerous **amplification components (transistors, etc)** on a **single chip**.

* **Op amps** try to behave like an **ideal amplifier** and under the correct circumstances, by obeying the rules, they **sort of behave like one**, to a degree, for example, you can't generate more voltage than the power input voltage, and you can't generate more **current** than the **datasheet** indicates it can produce.   In other words, you can't break the laws of physics.

* A **theoretical ideal amplifier** would be able to output **infinite current**, have **infinite input impedance**, **zero output impedance**. In reality they have varying **limits** on all these things.  For example, it may only be able to **output 1A or less**, depending on the inputs.

*  In the **ideal op amp** both the **inverted** and **non-inverted currents are zero** and the **difference between the two is zero**.  In reality, the **inputs** will have **small currents** and there will be **small differences between them**.  In reality, the **more ideal the op amp**, the **more expensive it is**.

* If a **datasheet** indicates an **op amp** can source **500mA**, don't push it to the envelope since it may behave erratically.  As you approach the limits it will not behave **linearly**.  You should probably only push it up to **300mA** or so.  If you need **500mA** get an **op amp** that can source **1A**.

* It is **important** to realize that the **inputs** shown on **op amp diagrams** **are NOT where you connect the power supply**.  On the actual **hardware** there will be **separate pins** for the **power supplies negative and positive inputs**.  Sometimes **diagrams** or **circuit simulators** will show the **power supply** connections on the **sides of the triangle**, but many times they do not.  In the case of **circuit simulators** you can usually right-click or double-click to bring up a **properties box** to enter the **positive and negative power supply voltages**.

## Noninverting Op Amp

From: [Op Amps for Everyone](pdf/OpAmpsForEveryone.pdf) -- Texas Instruments


The **noninverting op amp** has the **input signal** connected to its **noninverting input**, thus its **input source** sees an **infinite impedance**. There is **no input offset voltage** because **VOS = VE = 0**, hence the negative input must be at the same voltage as the positive input. The op amp output drives current into RF until the negative input is at the voltage,VIN. This action causes VIN to appear across RG.

![OpAmp01.png](images/Components/OpAmp/OpAmp01.png)
Figure 3.2

Note the above does not show the **positive and negative power inputs**.  Also note that **RF** and **RG** are often referred to as **R1** and **R2** in other references.

The **voltage divider rule** is used to **calculate VIN**; **VOUT is the input to the voltage divider**,and **VIN is the output of the voltage divider**. Since **no current** can flow into **either op amp lead**, use of the voltage divider rule is allowed. Equation 3–1 is written with the aid of the voltage divider rule, and algebraic manipulation yields Equation 3–2 in the form of a gain parameter.

![OpAmp02.png](images/Components/OpAmp/OpAmp02.png)
Equation 3-1 and 3-2


When **RG becomes very large with respect to RF**, (RF/RG)⇒0 and Equation 3–2 reduces
to:

**VOut = 1**

## Inverting Op Amp

From: [Op Amps for Everyone](pdf/OpAmpsForEveryone.pdf) -- Texas Instruments

The **noninverting input** of the **inverting op amp** circuit is **grounded**. One assumption made is that the **input error voltage is zero**, so the **feedback** keeps **inverting the input** of the op amp at a **virtual ground (not actual ground but acting like ground)**. The **current flow** in the **input leads** is **assumed to be zero**, hence the **current flowing through RG equals the current flowing through RF**. Using **Kirchoff’s law**, we write Equation 3–4; and the minus sign is inserted because this is the inverting input. Algebraic manipulation gives Equation 3–5.

![OpAmp03.png](images/Components/OpAmp/OpAmp03.png)
Figure 3.3

Note the above does not show the **positive and negative power inputs**.  Also note that **RF** and **RG** are often referred to as **R1** and **R2** in other references.

![OpAmp04.png](images/Components/OpAmp/OpAmp04.png)
Equation 3-4 and 3-5

* If **RF** and **RG** are the **same**, the **output voltage** will be the **input voltage inverted**, since you are multiplying it by **-1**.

* The **RF** and **RG resistors** are typical set from **1k** to **10s of k**

## Op Amp Characteristics/Properties

Note that many of the examples here use the **LM796 op amp**, which is a **good quality op amp** (around $1.53 for a single one, which is more expensive than cheaper varieties)

* **Current Input Bias** -- the **amount of current** going into and out of the **inputs**, which in the **ideal op amp** we want to be **zero**.  On the **LM796 op amp** it is **0.1pA**.

* **Gain Bandwidth Product (GBP)** -- the **gain** times the **bandwidth**.  So if you want to **amplify a signal by a factor of 1**, and the **GBP** is **17MHz** (the GBP on the **LM796**), then the **highest signal** you can process is **17MHz**. If on the other hand you want to **multiply the gain** by **17**, then the **highest signal** you can process is **1MHz**.

* **Slew Rate** -- often measure in **micro volts per second**, is how **fast** it can **adjust** to **changes in signals**.  You have to make sure whatever **signal** you are trying to process is **within the slew rate**.

* **Voltage Input Offset** -- the **differential voltage between the two inputs**.  In the **ideal op amp** this is **zero**.  On the **LM796

* When choosing a **resistor** to go **between the power supply and collector terminal**,  a good rule of them is to choose one that **delivers half the supply voltage to the collector**.

# 555 Timer Microchip


* **DIP (Dual Inline Plug )** -- the common form used on **bread boards** and **through hole boards**.

## Pinout

![555Pinout01.png](images/Components/555/555Pinout01.png)

![555Pinout02.png](images/Components/555/555Pinout02.png)

## Functional Diagram

![555Functional01.png](images/Components/555/555Functional01.png)

* **Threshold (pin 6)**  -- **Compares the voltage** applied to the terminal with a **reference voltage of 2/3 Vcc**. The amplitude of voltage applied to this terminal is responsible for the **set state of the flip-flop**.  In an **astable configuration** this will **trigger** when the **capacitor is charged to Vcc**.
* **Trigger (pin 2)** -- Responsible for **transition of the flip-flop from set to reset**. The output of the timer depends on the amplitude of the external trigger pulse applied to this pin.  In an **astable configuration** this will **trigger**

## 555 Monostable

**Monostable mode** is configured to send out **one pulse** with a configured **timing**.

## 555 Astable

Refer to:

* [555 Astable pg1](http://www.learnabout-electronics.org/Oscillators/osc43.php)
* [555 Astable pg2](http://www.learnabout-electronics.org/Oscillators/osc44.php)


**Astable mode** is configured to send out **continuously repeating pulses** with a certain **frequency** and **duty cycle**.

Image from **CircuitLab**.

![555Astable01.png](images/Components/555/555Astable01.png)

Another view:

![555Astable02.png](images/Components/555/555Astable02.png)


* With the **R1**, **R2**, and **C1** values above this circuit will generate a **1kHz square wave**

* **Bigger capacitor** and **resistors** causes a **slower pulse rate (lower frequency)**

* **Smaller capacitor** and **resistors** causes a **faster pulse rate (higher frequency)**

![555AstableChart01.png](images/Components/555/555AstableChart01.png)


### Duty Cycle

* **Duty Cycle** is a term that describes the **percentage of each cycle taken up by the active or high period** of the **square wave** (in the case of the 555).

* At **50%** the **high period** takes up **50% of the full cycle**

* At **greater than 50%** the **high period** takes up **more than 50% of the full cycle**

* At **less than 50%** the **high period** takes up **less than 50% of the full cycle**

![555DutyCycle01.png](images/Components/555/555DutyCycle01.png)

# Miscellaneous Tips

### Use a Capacitor after Battery Input

* placing a **capacitor** after the **battery input connection** will help to **smooth out the power** as load is put on a **battery** and as the battery **depletes**.  An **electrolytic capacitor (can like enclosure)** is the best type for this, with **4.7uF** typical for a **4.5 volt DC** that is under **500mA**.

### Drawing more current quickly

* When you need to more **quickly draw a current**, run a connection to **ground** with a **.1uF capacitor** to **draw current from**, with a **100kΩ resistor** to add a load to the **power supply**. ([Udemy Electronics Course](https://www.udemy.com/crash-course-electronics-and-pcb-design/learn/v4/overview) by Andre LaMothe around 55 minutes in on the bonus Op Amp video)

### Use only half the power rating of a resistor

* It is better to over design your system, and spend a little more, by making sure your **resister's power rating** is **twice your requirements**.  For example, if you need a **110mW of load on the resister**, don't use a **1/4W resistor** but use **1/2W resistors** to provide a **bigger buffer**.  Your circuits will be much more reliable if your circuit periodically gets more **voltage** than you anticipated.

# Digital Logic Circuits

## Boolean Algebra

* Two possible numbers, **1 or 0**

* The **inverse**, referred to as the **compliment** is written with a **line (bar) over the variable**, for example, **A bar**.

* **A AND B** is written algebraically as **A \* B** or as **AB**.  This is not pronounced as **A times B**, but rather as **A AND B**.

* **A OR B** is written algebraically as **A + B**.  This is not pronounced as **A plus B**, but rather as **A OR B**.

* The **complement of AND is OR**

* The **complement of OR is AND**.

### OR Boolean Logic

![LogicOR02.png](images/Components/Logic/LogicOR-02.png)

### AND Boolean Logic

![LogicAND02.png](images/Components/Logic/LogicAND-02.png)

### NOR Boolean Logic

![LogicNOR02.png](images/Components/Logic/LogicNOR-02.png)

The above shows that **NOR** is the direct **inverse** of **OR**.

### NAND Boolean Logic

![LogicNAND02.png](images/Components/Logic/LogicNAND-02.png)

The above shows that **NAND** is the direct **inverse** of **AND**.

### XOR Boolean Logic

![LogicXOR.png](images/Components/Logic/LogicXOR-02.png)

### XNOR Gate

![LogicXNOR02.png](images/Components/Logic/LogicXNOR-03.png)

![LogicXNOR03.png](images/Components/Logic/LogicXNOR-02.png)


The above shows that **XNOR** is the direct **inverse** of **XOR**

### De Moran's Theorems

![LogicDeMorganLaws-01.png](images/Components/Logic/LogicDeMorganLaws-01.png)

The above shows that the **complement of AND is OR** and the **complement of OR is AND**.

## Gates

From my **Circuit Simulator applet** circuit:

![LogicGates01.png](images/Components/Logic/LogicGates01.png)

Note that **all the gates** can be created with a **combination of NAND and NOR gates**

### AND Gate

![LogicAND.png](images/Components/Logic/LogicAND-01.png)

### OR Gate

![LogicOR.png](images/Components/Logic/LogicOR-01.png)

### NOT (Inverter) Gate

Also referred to as the **compliment**.

![LogicNOT.png](images/Components/Logic/LogicNOT-01.png)

### NAND Gate

![LogicNAND.png](images/Components/Logic/LogicNAND-01.png)

### NOR Gate

![LogicNOR.png](images/Components/Logic/LogicNOR-01.png)

### XOR Gate

![LogicXOR.png](images/Components/Logic/LogicXOR-01.png)

### XNOR Gate

![LogicXNOR.png](images/Components/Logic/LogicXNOR-01.png)

### Digital Circuit Gates (NAND and NOR)

**Digital circuits** such as in **microcontrollers** and **microprocessors** predominately use **NAND and NOR gates**.  One of the reasons for this is they work better with **NPN transistors** which **prefer these gates**, whereas **PNP transistors** work better with **AND and OR gats**.  All of the **other gates can be constructed with NAND and NOR gates**.

![LogicNANDGateDerivatives01.png](images/Components/Logic/LogicNANDGateDerivatives-01.png)

Refer to [Transistor Transistor Logic](https://www.youtube.com/watch?v=FvdgxOAjJ_U&index=4&list=PLFC56DF3A0E2B9756) YouTube video for examples of **building the gates** using nothing but **NOR gates**

## Flip-Flops

Much of the information is from:

* [Flip-flops](https://www.globalspec.com/learnmore/semiconductors_electronics/digital_logic_devices/flip_flops)

**Flip-flops** are digital **logic devices** that synchronize changes in **output state (1 or 0)** according to a **clocked input**. Because they use **sequential logic**, **flip-flops control and are controlled by other circuitry** in a **specific sequence** that is determined by both a **control clock** and **enable/disenable control signals**.

Several **types of flip-flops** are available:

* **D flip-flops** have **one data input (D)** and **two outputs (Q and Q’)**.

* **S-R flip-flops** have either **set (S) and reset (R) inputs**, or set **(S) and clear (C) inputs**. Depending on the input values, the **two complementary outputs (Q and Q’) change** according to the device’s logical function **at the moment of the clock input’s active transition**. **Active high** and **active low S-R flip-flops** are available.

* **J-K flip-flops**, a **type of S-R device**, define the flip-flop’s indeterminate state.

* **Toggle** or **T flip-flops**, a **single input version of the J-K flip-flop**, toggle the output with each clock pulse. Typically, T flip-flops are **used to develop counters, registers, and similar devices**.

## Pull Up and Pull Down Resistors in Logical Circuits

* **Pull Down and Pull Up Resistors** -- used in **digital circuits** to prevent **floating inputs** where the a **switch/gate/connection** is not connected to either **power** or **ground**, it is **indeterminate** and can bounce **between on and off** due to **extraneous signals and interference**.  

### Pull Up Resistor

* **Pull Up Resistor** is connected in **parallel** between a **switch** and a **logic circuit/microcontroller** and is connected to the **voltage source** (typically 3.3 or 5V).  When the **switch is open**, without the **pull up resistor**  it would be **floating**, but with it is connected through the **resistor** to the **voltage source** so the **pin** remains in a **high state (3.3V or 5V)** which is what is desired.  This is **inverting** in the sense that when the **switch is closed** the **pin is off**, i.e., pushing the switch turns it off.  **Pull up resistors** are **builtin** to a lot of **microcontrollers** and therefore don't need to be added to the outside circuit.

![PullUpResistor01.png](images/Components/Logic/PullUpResistor01.png)

### Pull Down Resistor

* **Pull Down Resistor** is connected in **parallel** between a **switch** and a **logic circuit/microcontroller** and is connected to **ground** .  When the **switch is open**, without the **pull down resistor**  it would be **floating**, but with it is connected through the **resistor** to  **ground** so the **pin** remains in a **low state (0V)** which is what is desired. This a a **non-inverting** in that when the **switch is closed** the **pin is on**.  **Pull down resistors** typically are **not builtin to microcontrollers** and therefore need to be **added to the external circuit**.  

![PullDownResistor01.png](images/Components/Logic/PullDownResistor01.png)

## Logisim

Refer to:

* [Logisim Beginner's Tutorial](https://www.youtube.com/watch?v=cMz7wyY_PxE&t=187s) -- YouTube video
* [Logisim Website](http://www.cburch.com/logisim/)

**Logisim** is a **Java based digital logic simulator**.  Refer to this repository's **electronics/Logisim directory** for example circuits.

## Clocks and Oscillators

### Oscillators

An **oscillator** is a component that **oscillates at specific frequencies**.  It can either be based on the behaviors of natural materials, such as **crystals**, or generated from **electronic components** through **capacitance**, **inductance** and **resistance**.

* **Crystal oscillators** have a **piezoelectric** properties, which when you apply an **electrical current** it **changes shape** causing it to **oscillate** and **emit an oscillating signal**.

* **LC Inductors** consist of **capacitors** and **inductors** that  **oscillate** signals.  The **oscillation** is determined by **fr = 1 / sqrroot(LC)**.

* **VCO** -- **Voltage Controlled Oscillator** -- **integrated circuit** that has **pins** for external **resistors** and **capacitors**, which are used to generate an **oscillated signal for timing** purposes.

### Clocks

**Clocks** are used in:
* **Microprocessors**
* **Integrated circuits**
* **Communications** --  **SPI**, **I2C**, etc

**Clocks** are systems used to **regulate various operations** that require consistent **timings**.  They can make use of **oscillators** for these consistent **timings**.

Refer to [Oscillators and Clocks](https://www.youtube.com/watch?v=8P2oMYlk2UM&list=PLFC56DF3A0E2B9756&index=5) YouTube video.

# Circuit Examples

## Voltage Regulator

Circuit I created in CircuitLab with lots of meters to show what's going on.  The **50MΩ resistor** is equivalent to my **Fluke** which is allowing only a miniscule amount of **current**:

![VoltageDivider01.png](images/Voltage/VoltageDivider01.png)

# Audio -- Side Notes (move later to a more audio specific document)

## Audio Frequencies

From: [Wikipedia](https://en.wikipedia.org/wiki/Audio_frequency)

Frequency (Hz)   | Octave     |Description
-----------------|------------|-------------------------
16 to 32         | 1st        | The lower human threshold of hearing, and the lowest pedal notes of a pipe organ.
32 to 512        | 2nd to 5th |	Rhythm frequencies, where the lower and upper bass notes lie.
512 to 2,048     | 6th to 7th | Defines human speech intelligibility, gives a horn-like or tinny quality to sound.
2,048 to 8,192   | 8th to 9th | Gives presence to speech, where labial and fricative sounds lie.
8,192 to 16,384  |10th        | Brilliance, the sounds of bells and the ringing of cymbals and sibilance in speech.
16,384 to 32,768 |11th        | Beyond brilliance, approaching and just passing the upper human threshold of hearing

Piano:

* Lowest C note on a standard 88-key piano is **32.7 H**
* Highest note on a standard 88-key piano is **1.19 kH**

## Typical Electrical Specs

* **Speakers** -- **4 to 8 ohm**
* **Line level** -- the specified **strength** of an **audio signal** used to **transmit analog sound** between **audio components** such as CD and DVD players, television sets, audio amplifiers, and mixing consoles.  **Line level** it is **between weaker audio signals sources** and **stronger signals**, such **loudspeakers**. ([Wikipedia/edited](https://en.wikipedia.org/wiki/Line_level))

Use	               |Nominal level | Nominal level, Vrms | Peak amplitude, Vpk |Peak-to-peak amplitude, Vpp
-------------------|--------------|---------------------|---------------------|----------------------------
Professional audio | +4 dBu       | 1.228               | 1.736               | 3.472
Consumer audio     | −10 dBV      | 0.316               | 0.447               | 0.894

## Current vs Voltage in Loudspeakers

Normal commercial **loudspeakers** are meant to be **driven** with a **voltage signal**, **not a current signal**



