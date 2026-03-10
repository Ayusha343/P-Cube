# Component Failures and Lessons Learned

Despite careful design, several components failed over the two-year testing period. Each failure provided valuable insights into system reliability and component selection.

## 1 LED Headlight Failure

**Issue**: Initial LED headlight (4–5 LEDs in series) failed when a single LED burned out, breaking the entire circuit

**Root Cause**: Series-connected LEDs create a single point of failure

**Solution**: Replaced with truck side-marker LEDs (parallel connected with appropriate current limiting)

**Learning**: Always design lighting systems with redundancy — parallel connections with individual protection are superior

## 2 Brake Light Switch Failure (Multiple Instances)

**Issue**: Brake light switch failed multiple times over the two-year period

**Root Cause**: Vibration from pedaling and motor operation caused solder joints to crack

**Fix**: Resoldered connections; protective epoxy potting later applied to reduce vibration fatigue

**Learning**: Sensitive electrical components need mechanical support, vibration-dampening mounts, and conformal coating

## 3 Accelerator Throttle Replacement

**Issue**: Original 23mm handlebar throttle failed after ~2 years

**Failure Mode**: Internal potentiometer became unreliable, causing jerky power delivery

**Solution**: Replaced with identical new throttle unit (cost: ~₹250)

**Learning**: Electronic throttle life is limited; plan for periodic replacement

## 4 Battery Replacement Due to Deep Discharge

**Critical Issue**: Two 12V lead-acid battery had to be replaced after two years due to deep discharge damage. Lead-acid batteries require disciplined charging practices: charge after each use before dropping below 50% capacity, avoid complete discharge cycles, and monitor battery voltage with the integrated voltmeter to avoid overdischarge. This remains one of the most important operational lessons.

## 5 Mechanical Wear: Brakes and Tires

Beyond the electrical system, normal bicycle maintenance components required periodic replacement:

- **Brake pads**: Required replacement approximately every 3–4 months due to normal wear
- **Bicycle tires**: Required replacement as rubber degraded from use and UV exposure
- **Chain lubrication**: Regular maintenance required to prevent rust and wear

These are normal bicycle maintenance items, easily managed and inexpensive (₹200–500 per replacement).

## 6 Power Cable Failure

**Issue**: Charging cable deteriorated after two years, creating intermittent charging connection

**Solution**: Replaced with new charging cable (cost: ~₹20)

**Learning**: External cables require periodic inspection and replacement as normal maintenance