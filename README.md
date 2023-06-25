[![Simulation](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml)

# Lesson 3 - Energy Storage

The goal this lesson is to familiarize you with the various ways of modeling generators in GridLAB-D. The specific learning objectives are the following

1. How to connect a battery.

## Batteries

Batteries can be connected to either single phase or 3-phase nodes on a network through an inverter.  There are 

## Tasks

The following tasks are illustrated in [`main.glm`](main.glm):

1. Add a medium size commercial battery with 50% SOC, discharging at 100 kW, using an inverter with 200 kW rated power (see [`main.glm@6`](main.glm#L6-L27))
    1. Add a meter ([`main.glm@7`](main.glm#L7-L27)).
    2. Add an inverter ([`main.glm@13`](main.glm#L13-L26)).
    3. Add the battery ([`main.glm@16`](main.glm#L16-L25)).

# Exercises

1. Add three household batteries to `load_75`, discharging at 10 kW, each using a 20 kW inverter.

# More Information

* [Battery](https://docs.gridlabd.us/index.html?owner=arras-energy&project=gridlabd&branch=master&folder=/Module/Generators&doc=/Module/Generators/Battery.md)

# Next Lesson

* [Lesson 5 - Running simultions over time](../../../lesson-5)