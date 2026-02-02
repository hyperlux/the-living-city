![Solar Facades](/the-living-city/images/energy-solar-facades.png)

# APPENDIX B: THE ENERGY SYSTEMS

## Technical Specifications for Metabolism in the Living City

---

## B.1 Generation Portfolio

### Solar Photovoltaics

The primary energy source for the Living City is solar radiation:

**Total installed capacity target**: 500 MW per 100,000 residents

**Distribution**:
| Location | % of Total | Capacity/100K | Notes |
|----------|------------|---------------|-------|
| Rooftops | 40% | 200 MW | Building-integrated and retrofit |
| Facades | 15% | 75 MW | South/east/west facing |
| Ground-mount | 20% | 100 MW | Parks, infrastructure, parking |
| Solar roads | 10% | 50 MW | High-traffic areas |
| Windows | 10% | 50 MW | Transparent PV |
| Other | 5% | 25 MW | Canopies, furniture, etc. |

**Technology specifications**:
- Primary: Perovskite-silicon tandem cells (40%+ efficiency)
- Secondary: Organic PV for flexible applications (15%+ efficiency)
- Lifespan: 30+ years with <0.5%/year degradation
- Manufacturing: Local production of key components

### Wind

Supplementary generation from urban and peri-urban wind:

**Capacity target**: 50 MW per 100,000 residents

**Types**:
- Building-integrated small turbines: 20 MW
- Peri-urban community wind: 30 MW

**Siting considerations**:
- Turbines integrated into building architecture (not visible additions)
- Peri-urban installations within 20 km
- Noise standards strictly enforced (<35 dB at nearest residence)

### Waste-to-Energy

Organic waste streams produce biogas:

**Sources**:
- Food waste (anaerobic digestion): 70%
- Sewage sludge (anaerobic digestion): 20%
- Agricultural residues: 10%

**Output**: 20 MW equivalent per 100,000 residents

**Products**:
- Biogas (methane) for high-temperature industrial processes
- Heat for district heating network
- Electricity (when excess capacity)

### Geothermal

Low-temperature geothermal for heating/cooling:

**Applications**:
- Ground-source heat pumps for buildings
- Seasonal thermal storage
- District heating/cooling pre-conditioning

**Capacity**: 30 MW thermal per 100,000 residents

---

## B.2 Storage Systems

### Electrical Storage

**Battery systems**:

| Level | Capacity | Type | Purpose |
|-------|----------|------|---------|
| Building | 50 kWh avg | Solid-state | Daily cycling, backup |
| Neighborhood | 5 MWh | Solid-state/flow | Local balancing |
| District | 50 MWh | Flow batteries | Seasonal variation |
| City | 500 MWh | Multiple types | Grid stability |

**Total storage target**: 100 kWh per resident (10 GWh per 100,000)

**Technology mix**:
- Solid-state lithium: 40% (high density, fast response)
- Vanadium flow: 30% (long duration, long life)
- Gravity storage: 20% (underground, very long duration)
- Hydrogen: 10% (seasonal storage, transport fuel)

### Thermal Storage

**Hot water storage**:
- Building-level tanks: 500 L per household
- Neighborhood tanks: 100,000 L per 1,000 residents
- Underground seasonal storage: 10,000,000 L per 100,000 residents

**Ice storage** (for cooling):
- Building-level: 50 kWh-thermal equivalent per 100 m²
- District: 1 MWh-thermal per 1,000 residents

**Phase change materials**:
- Integrated into building mass
- 5-10 kWh-thermal per 100 m² floor area

### Hydrogen

For seasonal storage and specific applications:

**Production**: Electrolysis from excess renewable generation
**Storage**: Underground caverns and distributed tanks
**Use cases**:
- Seasonal electricity regeneration
- Industrial high-temperature heat
- Heavy transport fuel (trains, ships)
- Backup power for critical facilities

**Target capacity**: 1,000 kg H2 per 100 residents (seasonal storage)

---

## B.3 Distribution Networks

### Electrical Grid

**Architecture**: Distributed, meshed, self-healing

**Levels**:
1. Building level: DC microgrid (48V typical)
2. Neighborhood level: AC microgrid (240V)
3. District level: Medium voltage AC (11 kV)
4. City level: High voltage AC (110 kV)

**Key features**:
- Every node can island (operate independently)
- Automatic fault detection and isolation
- Self-healing topology reconfiguration
- Bidirectional power flow at all levels
- Real-time market pricing signals

**Redundancy**:
- Minimum 2 paths between any two points
- N-1 reliability (any single component can fail)
- 99.99% uptime target

### District Heating Network

**Operating temperatures**:
- Supply: 60-80°C (lower than traditional systems)
- Return: 25-40°C
- Low-temperature enables more waste heat recovery

**Sources**:
- Data centers (waste heat capture)
- Industrial processes
- Combined heat and power plants
- Large heat pumps (electricity to heat)
- Solar thermal
- Geothermal

**Coverage**: 80% of buildings connected

### District Cooling Network

**Operating temperatures**:
- Supply: 4-7°C
- Return: 12-15°C

**Sources**:
- Seawater/lake cooling (where available)
- Absorption chillers (powered by waste heat)
- Large-scale ice storage (charged overnight)
- Ground-coupled cooling

**Coverage**: 50% of buildings connected (primarily commercial/institutional)

---

## B.4 Building Energy Systems

### New Construction Standards

**Net-positive requirement**:
- All new buildings must generate more energy than they consume annually
- Minimum: 110% of consumption (10% surplus)
- Target: 150% of consumption (50% surplus)

**Efficiency standards**:
| Component | Requirement |
|-----------|-------------|
| Envelope U-value | < 0.15 W/m²K |
| Windows U-value | < 0.8 W/m²K |
| Air tightness | < 0.6 ACH @ 50 Pa |
| Ventilation | Heat recovery > 85% |
| Lighting | < 5 W/m² (LED, daylight-controlled) |
| Appliances | Only highest efficiency rating |

**Generation requirements**:
- Roof: 100% coverage with solar (unless shaded)
- Facades: South/east/west surfaces with solar where feasible
- Integration with building management system

### Retrofit Standards

**Phased requirements by building age**:

| Building Age | Year Required | Standard |
|--------------|---------------|----------|
| Post-2020 | Immediate | Net-positive |
| 2000-2020 | Year 5 | Net-zero |
| 1980-2000 | Year 10 | 50% reduction |
| Pre-1980 | Year 15 | 50% reduction |

**Retrofit support**:
- City financing (low-interest loans)
- Technical assistance
- Standardized retrofit packages
- Performance guarantees

### Building Management Systems

**Required intelligence**:
- Real-time monitoring of all energy flows
- Predictive control (weather, occupancy, price forecasts)
- Demand response participation (automatic load shifting)
- Integration with city coordination layer

**Data provided**:
- Second-by-second generation and consumption
- Thermal state (temperatures, comfort)
- Occupancy patterns
- Equipment status

---

## B.5 Industrial Energy

### Industrial Zones

**Principles**:
- Co-locate industries with complementary energy profiles
- Waste heat from one process becomes input for another
- Shared infrastructure reduces capital costs

**Example industrial ecology**:
```
Data Center (waste heat 40°C) →
  → Greenhouse heating
  → Absorption chilling
  → Aquaculture water heating

Manufacturing (waste heat 60°C) →
  → District heating
  → Drying processes
  → Space heating

High-temp processes (waste heat 200°C+) →
  → Electricity generation (ORC)
  → Steam for other processes
  → District heating
```

### Electrification

**Targets**:
- 100% electrification of building heating/cooling
- 100% electrification of light industry
- 80% electrification of medium industry
- 50% electrification of heavy industry (remainder hydrogen/biogas)

**Timeline**: Complete electrification of buildings within 10 years; industrial transition within 25 years

---

## B.6 Transport Energy

### Electric Vehicles

**Fleet composition**:
| Type | % Electric | Notes |
|------|-----------|-------|
| Personal vehicles | 100% | Electric only within city |
| Autonomous pods | 100% | City-owned fleet |
| Delivery robots | 100% | Battery swapping |
| Buses | 100% | Opportunity charging |
| Trucks | 80% | Electric for urban, hydrogen for long-haul |
| Rail | 100% | Catenary or battery |

### Charging Infrastructure

**Levels**:
- Home charging: Every residence has access to Level 2 (7 kW)
- Destination charging: All parking includes Level 2
- Rapid charging: Every 500 m in urban core (150 kW+)
- Ultra-rapid: Key locations (350 kW+)

**Integration**:
- V2G (vehicle-to-grid) mandatory for all vehicles
- Smart charging responds to grid conditions
- Vehicles as distributed storage (target: 50 kWh per vehicle × 50,000 vehicles = 2.5 GWh)

---

## B.7 Grid Management

### Real-Time Balancing

**Supply-side management**:
- Generation forecasting (weather-based)
- Storage dispatch optimization
- Inter-city power trading

**Demand-side management**:
- Real-time pricing signals
- Automated demand response
- Interruptible load contracts

### Market Design

**Wholesale market**:
- 15-minute intervals
- Locational marginal pricing
- Ancillary services markets (frequency, reserves)

**Retail market**:
- Time-of-use rates for all customers
- Real-time pricing opt-in
- Community aggregation options

**Peer-to-peer trading**:
- Neighbors trade directly
- Blockchain-based settlement
- City oversight for fairness

### Emergency Protocols

**Stages**:
1. Normal: Full market operation
2. Alert: Voluntary conservation, price signals
3. Emergency: Automatic load shedding (non-critical first)
4. Restoration: Phased reconnection, black start procedures

**Priority loads** (always protected):
- Hospitals and healthcare
- Water treatment
- Communications
- Emergency services
- Food refrigeration

---

## B.8 Environmental Performance

### Pollution Elimination

**Target**: Zero harmful emissions

**Tracked pollutants**:
- Particulate matter (PM2.5, PM10)
- Heavy metals (lead, mercury, cadmium)
- Industrial chemicals and solvents
- Plastic waste and microplastics

**Strategy**: Closed-loop industrial processes, clean energy, materials selection

### Waste Streams

**Target**: 95%+ diversion from landfill

**Strategy**:
- Biological waste → composting/biochar
- Technical materials → remanufacturing
- Residuals → high-temperature plasma processing

### Ecosystem Impact

**Target**: Net positive biodiversity

**Strategy**:
- Green corridors connecting to regional ecosystems
- Native species habitat integration
- Pollinator support systems
- Soil health restoration

### Environmental Health Targets

**Annual targets per capita**:
| Year | Waste to Landfill | Air Quality Index | Water Quality |
|------|-------------------|-------------------|---------------|
| Year 1 | 200 kg | Good | Meets standards |
| Year 5 | 50 kg | Excellent | Exceeds standards |
| Year 10 | 10 kg | Excellent | Pristine |
| Year 15 | 0 kg | Excellent | Restorative |

---

## B.9 Costs and Financing

### Capital Investment

**Total energy system investment**: $50,000 per resident ($5B per 100,000)

**Breakdown**:
| Component | % | $/resident |
|-----------|---|------------|
| Generation | 35% | $17,500 |
| Storage | 25% | $12,500 |
| Distribution | 20% | $10,000 |
| Building systems | 15% | $7,500 |
| Management/IT | 5% | $2,500 |

### Operating Costs

**Annual per resident**: $800 (compared to $2,000+ in conventional cities)

**Breakdown**:
- Maintenance: $300
- Operations: $200
- Replacement reserves: $200
- Administration: $100

### Financing Mechanisms

**Public investment**:
- Green bonds (25-year, 3% interest)
- Federal/state grants
- Pollution reduction incentives

**Private investment**:
- Building owner financing (tied to energy savings)
- Community energy cooperatives
- Institutional investors (pension funds, insurance)

**Cost recovery**:
- Energy sales (at market rates)
- Grid services (balancing, reserves)
- Resource recovery revenues (recycled materials, compost, biochar)

---

## B.10 Governance

### Energy Authority

**Responsibilities**:
- Grid operation and planning
- Tariff setting
- Emergency response
- Investment coordination

**Structure**:
- Independent board (technical experts, resident reps)
- Accountable to city council
- Transparent operations (public data, open meetings)

### Community Energy

**Rights**:
- Any group of residents can form energy cooperative
- Cooperatives can own generation, storage
- Cooperatives can trade on wholesale market
- City provides technical support

**Typical cooperative scale**:
- Neighborhood level (1,000-5,000 residents)
- Shared ownership of local generation
- Collective purchasing power
- Democratic governance

---

*End of Appendix B*
