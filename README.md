# CSA CPU Sim Lab

Implementation of **Computer System Architecture (CSA) practicals** using **CPU Sim** and **Mano's Basic Computer** architecture.

This repository contains the machine configuration, assembly programs, practical documentation, and screenshots of the results.

## Practicals

| Practical | Description                                           |
| --------- | ----------------------------------------------------- |
| 01        | Create a machine based on Basic Computer architecture |
| 02        | Implement the Fetch routine                           |
| 03        | ADD two user-entered numbers                          |
| 04        | SUBTRACT two user-entered numbers                     |
| 05        | Implement logical operations                          |
| 06        | Implement memory-reference instructions               |
| 07        | Implement register-reference instructions             |
| 08        | Implement additional register-reference instructions  |
| 09        | Implement CIR and CIL instructions                    |
| 10        | Sum integers until a negative number is read          |
| 11        | Sum integers until zero is read                       |

## Software

* CPU Sim 4.0.11 or later
* Java

## Repository Structure

```text
CSA-CPU-Sim-Lab/
├── README.md
├── machine/
│   └── BasicComputer.cpu
├── practical-01-machine/
│   ├── README.md
│   └── screenshots/
├── practical-02-fetch/
│   ├── README.md
│   └── screenshots/
├── practical-03-add/
│   ├── P03_ADD.a
│   ├── README.md
│   └── screenshots/
├── practical-04-subtract/
│   ├── P04_SUBTRACT.a
│   ├── README.md
│   └── screenshots/
├── practical-05-logical-operations/
│   ├── P05_LOGICAL.a
│   ├── README.md
│   └── screenshots/
├── practical-06-memory-reference/
│   ├── P06_MEMORY_REFERENCE.a
│   ├── README.md
│   └── screenshots/
├── practical-07-register-reference/
│   ├── P07_REGISTER_REFERENCE.a
│   ├── README.md
│   └── screenshots/
├── practical-08-register-reference/
│   ├── P08_REGISTER_REFERENCE.a
│   ├── README.md
│   └── screenshots/
├── practical-09-cir-cil/
│   ├── P09_CIR_CIL.a
│   ├── README.md
│   └── screenshots/
├── practical-10-sum-until-negative/
│   ├── P10_SUM_UNTIL_NEGATIVE.a
│   ├── README.md
│   └── screenshots/
└── practical-11-sum-until-zero/
    ├── P11_SUM_UNTIL_ZERO.a
    ├── README.md
    └── screenshots/
```

## Basic Computer

The practicals are implemented using a **16-bit Basic Computer** architecture with:

* 16-bit data
* 12-bit memory addresses
* 4096 memory locations
* Accumulator-based architecture
* Microprogrammed control

The machine configuration is provided in:

```text
machine/BasicComputer.cpu
```

## Practical Documentation

Each practical contains:

* Aim
* Procedure
* Program
* Output/Results
* Screenshots
* Observations
* Result

## Screenshots

Screenshots are included to demonstrate the execution and results of the practicals in CPU Sim.

## Author

**Tanya Goyal**

MSc Information Technology – Embedded AI
IMT Atlantique, France

## Note

This repository contains the implementation work for the CSA CPU Sim laboratory practicals.
