# PreampPAL

Project done in 3th year of Masters.

# Description

The goal of this team is to perform a low-noise pre-amplifier that amplifies the needle signal to a line level signal. To accomplish this we started by understanding what was a preamplifier for a record player, namely, what was a preamplifier with reverse RIAA equalization that would amplify the needle signal to a line level signal.

So this team is responsible for the electronics of the turntable audio. This task consists of manipulating low-value and very sensitive voltages. 

# 1st Step: Tests and Simulation

Having said this, we started the search for a preamplifier that corresponded to our needs, i.e. a preamplifier that applied what was described above and low noise (because the values received by the needle are very low).

We chose a range of preamplifiers and set out for the simulation phase using the LTSpice program.

We performed several simulations in LTSpice in terms of noise and equalization in order to choose the best pre-amplifier. At the end of this phase we started to develop the circuit.

<img src="https://github.com/RCarapinha/PreampPAL/blob/master/Simulation/1.JPG" width="500">

# 2nd Step: Breadboard Tests

The first test to be performed was to make sure that the voltage regulator (low noise) correctly converted the value from 5V to 3.3V, and this test was successful. The second test was to verify the amplification and RIAA equalization. For this, a weak signal was applied to the input and we compared the output values obtained with the theoretical output values.

<img src="https://github.com/RCarapinha/PreampPAL/blob/master/Preamp%20Board/breadboard.png" width="500">

# 3rd Step: PCB Design

After we carried out the tests and validated the operation of the circuit, the next step of the team was to develop the PCB (in EAGLE software) so that we could finish the work.

<img src="https://github.com/RCarapinha/PreampPAL/blob/master/Preamp%20Board/pcb.png" width="500">

# 4rd Step: Final Work

Once the PCB has been designed, we start to build the board and assemble the components on it, something that must be done with great care to avoid errors or noise. Finally, we tried to isolate the whole board, for a better functioning.

<img src="https://github.com/RCarapinha/PreampPAL/blob/master/Preamp%20Board/final.png" width="500">
