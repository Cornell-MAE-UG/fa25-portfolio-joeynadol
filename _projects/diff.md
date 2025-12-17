---
layout: project
title: Custom Gearbox Design
description: Engineered a system using Solidworks and Ansys
technologies: [Solidworks, Ansys]
image: /assets/images/diffcasing.png
---

[Download a PDF of the report here:] ({{ "/assets/jbn56_zes5_Senior_Design_2025.pdf" | relative_url }})

This project focused on the design and validation of a lightweight custom front differential casing for the Cornell Baja SAE TG22 vehicle. With the increasing competitiveness of Baja SAE and the effective requirement for four-wheel drive, minimizing driveline mass and rotational inertia became a key vehicle-level objective. The existing front differential, adapted from a Porsche 996 limited-slip unit, delivered strong vehicle dynamics but was significantly overbuilt for Baja SAE usage. In particular, the OEM 8620 steel casing contributed substantial rotational mass, increasing frictional losses and shock loading on upstream drivetrain components. The goal of this project was therefore to redesign the differential casing to reduce mass while preserving durability, stiffness, and vehicle handling performance.

A 7075-T6 aluminum casing was selected to achieve the targeted weight reduction, while hardened steel sleeves and wear inserts were strategically integrated to manage gear contact forces and bearing interfaces. The design retained full backward compatibility with the OEM differential internals to mitigate risk, while eliminating the separate ring gear carrier by integrating it directly into the casing. This reduced mechanical complexity, removed eight bolted connections, and improved serviceability. Material choices and wear-surface solutions—including EDM-manufactured 4340 steel sleeves, AR500 thrust plates, SpeediSleeves for bearing seats, and helicoil inserts for threaded joints—were driven by a balance of manufacturability, fatigue resistance, and long-term reliability.

Analytical modeling was used to derive worst-case gear loads based on driveline torque, torque bias ratio, gear geometry, and Belleville washer preload from the Wavetrac mechanism. These loads informed a multi-stage finite element analysis strategy. Initial small-scope FEA provided early validation, while an expanded-scope model incorporating the front gearbox allowed boundary conditions to more accurately reflect real load paths. The final FEA showed acceptable stress distributions, with load transfer occurring as expected through the casing halves and bolted joints. Minimum factors of safety exceeded design requirements for all critical components, confirming that the aluminum structure could safely withstand combined tangential, radial, and axial loading.

The final design achieves a mass reduction of approximately 1.8 lb relative to the OEM casing, lowering rotational inertia while maintaining structural robustness. This weight savings enabled drivetrain upsizing elsewhere on the vehicle at net-zero mass penalty, improving torque delivery without sacrificing reliability. Manufacturing drawings were completed and the casing was approved for production within budget, with assembly and vehicle testing planned for the upcoming semester. Overall, the project demonstrates a successful application of mechanical design, load derivation, FEA, and manufacturing-informed decision-making to meet performance, reliability, and competition-driven constraints.
