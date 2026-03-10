# Design Evolution and Improvements

The P Cube has not remained static since initial construction. Over approximately two years of active use, several components failed or degraded, leading to design iterations and improvements.

## 8.1 Lighting System Evolution

**Original Design**: 4–5 LEDs connected in series. Problem: If a single LED fails, the entire series circuit breaks. This occurred after limited use.

**Replacement Solution**: Switched to truck side-marker LEDs (24W headlight and 2.4W brake light), salvaged from decommissioned trucks at ₹20 each, configured in parallel.

- Significantly brighter output suitable for night riding
- Proven reliability over extended use
- Salvaged from e-waste, supporting sustainability goals
- Multiple internal emitters provide some redundancy
- Connected to 12V tap (rather than full 24V) for extended life

## 8.2 Chain Tensioning System

The dual-sprocket arrangement created a mechanical coupling problem: tightening the pedal-side chain would loosen the motor-side chain, and vice versa. No static tightening solution worked.

**Custom Tensioner Design**:

- PVC electrical conduit pipe as the support structure
- Used ball bearing (sourced from motorcycle repair shop) as the contact point
- Mounted to frame using hose clamps for adjustable tension

The tensioner bearing maintains constant tension on the slack side of the chain, accommodating both the pedal chain and motor chain variations simultaneously. This is one of the most important design refinements.

## 8.3 Discovery of Hybrid Operation Mode

**Important Finding**: Initially assumed simultaneous pedaling and motor operation would stress the system. After 1–2 weeks of testing, discovered both can operate simultaneously without adverse effects. Hybrid mode (pedal + throttle) provides torque assist, significantly improved acceleration, better climbing performance, extended range, and enhanced urban riding safety.

## 8.4 Battery Selection Refinement

**Original Plan**: 24V lithium-ion battery pack for superior energy density. Constraint: Appropriate lithium packs with BMS exceeded ₹3,000–4,000, consuming a disproportionate share of the ₹7,000 budget.

**Decision**: Switched to sealed lead-acid batteries salvaged from old UPS systems. Cost often free to ₹500 per battery. No special BMS required. Inherent thermal management with no runaway risk.

**Learning**: Two batteries had to be replaced after two years due to deep discharge damage—highlighting the importance of charging discipline with lead-acid batteries.