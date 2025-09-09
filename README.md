# WTP-For-EV-Charging
Wireless Power Transfer (WPT) for Electric Vehicles

A research and modeling project focused on wireless charging technology for electric vehicles, exploring design, simulation, and efficiency optimization of inductive power transfer systems.

📖 Project Overview

Electric Vehicles (EVs) are a sustainable alternative to fossil-fuel-based transportation. However, the charging infrastructure remains a barrier to large-scale adoption due to:

Limited charging stations.

Time-consuming manual plug-in charging.

Equipment wear and tear from continuous plugging/unplugging.

Impact of large-scale EV charging on the power grid.

This project focuses on wireless charging of EVs using Wireless Power Transfer (WPT) technology.
It explores the design, theoretical modeling, and efficiency calculations of a WPT system and highlights challenges, possible topologies, and real-world applications such as dynamic EV charging roads.

⚡ Key Features

Comparative study of AC, DC, and Smart EV Charging methods.

Design of a wireless charging system using:

AC-DC Rectifier

DC-AC Inverter

Mutually Coupled Inductors

Buck/Boost Converter

Analysis of Series-Series (SS), Series-Parallel (SP), and Parallel topologies for maximum power transfer efficiency.

Theoretical efficiency calculations based on coupling coefficient (k) and Quality Factor (Q).

Identification of challenges in real-world implementation and scalability.

Case study: Sweden's first EV charging road.

🔧 System Architecture

The WPT system consists of four main stages:

AC-DC Rectification: Converts grid AC to DC for stable charging input.

DC-AC Inversion: Converts DC back to AC for wireless transmission via magnetic coupling.

Wireless Power Transfer via Coils: Energy transfer through mutually coupled inductors tuned at resonance for maximum efficiency.

Buck/Boost Conversion: Regulates voltage to meet EV battery charging requirements.

🧮 Theoretical Model

The system is modeled using resonance conditions:

𝐿
𝑝
=
𝐿
𝑠
L
p
	​

=L
s
	​

 and 
𝐶
𝑝
=
𝐶
𝑠
C
p
	​

=C
s
	​

 for optimal resonance.

Efficiency (
𝜂
η) is directly proportional to:

𝜂
∝
𝑘
2
⋅
𝑄
𝑝
⋅
𝑄
𝑠
η∝k
2
⋅Q
p
	​

⋅Q
s
	​


where:

k = Coupling coefficient between coils

Qp, Qs = Quality factors of primary and secondary circuits

Higher k and Q values lead to improved efficiency.

📈 Use Cases

Static Wireless Charging: Vehicles charge while parked, eliminating manual plug-in.

Dynamic Wireless Charging Roads: Continuous charging while EVs are in motion.

Smart Grid Integration: Reducing peak demand through SCADA and load curve monitoring.

Integration with renewable energy sources like solar for sustainable charging.

📊 Challenges & Future Scope

Standardization: Need for universal coil and charging pad designs across manufacturers.

Grid Impact: Large-scale deployment must be managed to avoid grid instability.

Efficiency: Limited by distance and alignment of coils; requires advanced topologies like LCC compensation.

Safety Concerns: EMF exposure and heat dissipation must meet regulatory standards.
