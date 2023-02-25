# Electric-Motor-Temperature

Business Objective:
Predict Motor Speed based on other attributes available
The dataset comprises several sensor data collected from a permanent magnet synchronous
motor (PMSM) deployed on a test bench. The PMSM represents a ccTest bench measurements
were collected by the LEA department at Paderborn University. This dataset is mildly
anonymized.
All recordings are sampled at 2 Hz. The dataset consists of multiple measurement sessions,
which can be distinguished from each other by the column &quot;profile_id&quot;. A measurement session
can be between one and six hours long.
The motor is excited by hand-designed driving cycles denoting a reference motor speed and a
reference torque. Currents in d/q-coordinates (columns &quot;i_d&quot; and i_q&quot;) and voltages in d/q-
coordinates (columns &quot;u_d&quot; and &quot;u_q&quot;) are a result of a standard control strategy trying to
follow the reference speed and torque. Columns &quot;motor_speed&quot; and &quot;torque&quot; are the resulting
quantities achieved by that strategy, derived from set currents and voltages.
Most driving cycles denote random walks in the speed-torque-plane in order to imitate real
world driving cycles to a more accurate degree than constant excitations and ramp-ups and -
downs would.
