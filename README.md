# Fuzzy Logic Air Conditioner Controller

## Overview

This project aims to design and implement a Fuzzy Logic Air Conditioner controller for a feedback system simulation. The controller regulates room temperature based on external disturbances such as room temperature and target temperature. The goal is to maintain the room temperature close to the target temperature while considering outside temperature fluctuations.

## Simulation Description

The feedback system simulation consists of controlling room temperature with an air conditioner. The external disturbances include room temperature and target temperature. The air conditioner can be switched on/off, and the target temperature can be adjusted using a temperature dial. When the air conditioner is off, the room temperature tracks the outside temperature. When the air conditioner is on, it works to maintain the target temperature despite outside temperature changes.

## Inputs and Outputs

### Inputs:
- Room Temperature: Range between 0 and 40 degrees Celsius.
- Target Temperature: Range between 0 and 40 degrees Celsius.

### Outputs:
- Command: Range between -10 and 10, indicating the intensity of air conditioner operation.

### Design Document

The design document outlines decisions regarding linguistic variables, terms, and rules for the Fuzzy Logic system.

#### Linguistic Variables:

1. Room Temperature:
   - Terms: Cold, Cool, Comfortable, Warm, Hot
   - Membership Functions: Triangular or Trapezoidal

2. Target Temperature:
   - Terms: Very Cold, Cold, Moderate, Warm, Hot
   - Membership Functions: Triangular or Trapezoidal

3. Command:
   - Terms: Very Cold, Cold, Cool, Warm, Very Warm
   - Membership Functions: Triangular or Trapezoidal

#### Rules:

A rule matrix defines the relationship between input and output variables. These rules translate into a set of fuzzy logic rules for the system.

### Diagrams

Diagrams for each linguistic variable are be provided, illustrating the setup of terms and membership functions.

## Implementation

The implementation involves coding the Fuzzy Logic controller based on the design decisions outlined in the design document. The controller utilizes the Mamdani fuzzy inference method to determine the appropriate command for the air conditioner based on input variables (room temperature and target temperature).

## Conclusion

This project aims to demonstrate the effectiveness of Fuzzy Logic in controlling an air conditioner in a feedback system. By considering room temperature, target temperature, and outside temperature fluctuations, the controller will strive to maintain a comfortable room temperature while optimizing energy consumption.









