# LowCostPAPR

Main inspiration point: https://github.com/jcl5m1/ventilator/wiki/Build-a-Low-Cost-PAPR

## Technical requirements

For internal use only, not to be published publicly.

### Air flow rate

Total lung capacity is about 6L and respiratory rate is in order of (depending on the age) 12 to 18 breaths per minute.

Average resting respiratory rates by age are:

- birth to 6 weeks: 30–40 breaths per minute
- 6 months: 25–40 breaths per minute
- 3 years: 20–30 breaths per minute
- 6 years: 18–25 breaths per minute
- 10 years: 17–23 breaths per minute
- **Adults**: 12-18 breaths per minute[9]
- Elderly ≥ 65 years old: 12-28 breaths per minute.
- Elderly ≥ 80 years old: 10-30 breaths per minute.

Minimal flow rate for breathing is calculated to:
>minimum: 6L * 12/min = 72 L/min
>maximum: 6L * 18/min = 108 L/min
>average: 90L/min

for good engineering measure we will multiply the average by 1.5

>Desired flow rate: 135L/min

### Pressure

In accordance to European standard **EN250:2000 Respiratory equipment.**

Breathing pressure should be in range:

- Work of breathing: < 3.0 joules per litre
- Peak respiratory pressure: ±25 mbar (±2500 Pa) (inhalation or exhalation)
- Inhalation work of breathing: <0.3 joule per litre
- Pressure spikes with no measurable positive work of breathing: <10 mbar (1000 Pa)
- Pressure spikes with measurable positive work of breathing: <5 mbar (500 Pa)

![Breathing Resistance](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Breathing_Resistance.svg/2880px-Breathing_Resistance.svg.png)

### Filter connector types

- EUROFILTER&reg; 7592/D
- STANAG 4155 (NATO)
- 3M&trade; EA/Case
- DIN 40mm
- Deprecated: 60mm used on Yugoslavian M1 gas mask

TODO: Find out more about each type because there are a lot of potential types
