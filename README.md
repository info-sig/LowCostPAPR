# LowCostPAPR

Main inspiration point: https://github.com/jcl5m1/ventilator/wiki/Build-a-Low-Cost-PAPR

## Technical requirements

### Air flow rate

Total lung capacity is about 6L and respiratory rate is in order of (depending on the age) 12 to 18 breaths per minute.

Minimal flow rate for breathing is calculated to:
>minimum: 6L * 12/min = 72 L/min
maximum: 6L * 18/min = 108 L/min
average: 90L/min

for good engineering measure we will multiply the average by 1.5

>Desired flow rate = 135L/min

### Pressure

In accordance to European standard **EN250:2000 Respiratory equipment.**

Breathing pressure should be in range:

- Work of breathing: < 3.0 joules per litre
- Peak respiratory pressure: ±25 mbar (±2500 Pa) (inhalation or exhalation)
- Inhalation work of breathing: <0.3 joule per litre
- Pressure spikes with no measurable positive work of breathing: <10 mbar (1000 Pa)
- Pressure spikes with measurable positive work of breathing: <5 mbar (500 Pa)

![Breathing Resistance](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Breathing_Resistance.svg/2880px-Breathing_Resistance.svg.png)
