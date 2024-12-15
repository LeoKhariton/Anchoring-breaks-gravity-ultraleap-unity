# Anchoring breaks gravity

https://github.com/user-attachments/assets/cd8cda79-ced4-4ecd-9ef6-52df71963ddb

This project presents a scene demonstrating the problem that occurs when using Ultralap Unity Plugin 7.0.1 with Unity 2022.3.23f1.

Initially, all 3 objects are marked as "use gravity".

Objects that are initially detached from the anchor are attached to it and retain gravity after disconnection.

However, the object originally attached to the anchor does not have gravity when detached.
