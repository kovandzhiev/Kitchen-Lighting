# Kitchen-Lighting
It's an Arduino project to make easy and half automatic lighting in our kitchen

## The problem
![Diagram](https://raw.githubusercontent.com/kovandzhiev/Kitchen-Lighting/dev/images/Kitchen-lighting-problem.drawio.svg)

Some times the light is not enough to do things in the kitchen. Also when we make coffee in the morning. To switch on the lights you need to go back and in the left to press the switch. Usually the lights is forgotten to switch off after using.

## Optimization steps
1. Central switch will be replaced with main button
2. New button will be added at the center of the kitchen on the cupboard above the sink. To be easy to press it wherever you are
3. PIR sensor will be added at the centre of the kitchen. To keep light on when the kitchen is occupied
4. A micro controller with LED driver will be processed all logic, also smooth on and off the light

## Materials
1. Central button (it has not selected yet)
2. Cupboard button (it has not selected yet)
3. PIR sensor - Paradox DG467 360° Ceiling Mounted Digital Motion Detector
4. Micro controller - Digispark ATtiny85
5. A reset button

## Modification
- In PIR sensor the relay will be replaced with a resistor to lower ghost consumption

## References


## Tools
- [draw.io](https://app.diagrams.net/) my favorite diagram editor
- [Markdown helper](http://markdown-it.github.io/)