```mermaid
graph TD
    Trip[Trip - Central Entity]

    Driver[Driver]
    Truck[Vehicle / Truck]
    Route[Route]
    Customer[Customer]
    Time[Time]

    Fuel[Fuel Consumption]
    Maintenance[Maintenance Events]
    Safety[Safety Incidents]

    Driver --> Trip
    Truck --> Trip
    Route --> Trip
    Customer --> Trip
    Time --> Trip

    Trip --> Fuel
    Trip --> Maintenance
    Trip --> Safety

