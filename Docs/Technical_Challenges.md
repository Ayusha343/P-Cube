# Technical Challenges and Solutions

The development process was not straightforward. Several significant engineering challenges emerged during construction, each requiring creative problem-solving and iterative refinement.

##  Challenge: Sprocket-Hub Assembly and Loosening

**Problem**: A standard bicycle hub has threads only on the right side (pedal side). To utilize the empty left side for the motor sprocket, a double-threaded hub was sourced. However, the left-side thread is a reverse thread—a critical detail that causes the sprocket to loosen rather than tighten as the wheel rotates forward.

**Solution Attempts**:

- **Attempt #1 – Washers**: Added metal washers to prevent loosening. Result: Failed completely.
- **Attempt #2 – Welding**: Considered welding the sprocket to the hub. Rejected due to risk of bearing damage from heat.

**Final Solution**: Used two-part Araldite epoxy adhesive to create a chemical bond between the hub and freewheel. Creates near-weld-strength bond without heat damage, remains removable for future maintenance, and cost only ₹100–200. Result: Intact and reliable after 2+ years of operation.

##  Challenge: Sprocket-Freewheel Misalignment and Welding Failure

After securing the freewheel to the hub with epoxy, the sprocket's central hole was slightly smaller than the freewheel's outer diameter, preventing direct assembly. The sprocket was taken to a lathe workshop where the central hole was precisely enlarged.

Critical issue: The welder was operating impaired, creating uneven welds with severe wobbling and runout. The assembly had to be completely dismantled, defective welds cut and removed, components re-aligned, and a second welding attempt made successfully.

## Challenge: Spoke Melting During Welding

Welding heat inadvertently contacted one of the installed spokes, melting it. This required complete wheel disassembly and replacement of the damaged spoke.

Lesson: Due to this failure and thermal risks, the decision was made to minimize welding. The sprocket is now attached to the hub using Araldite epoxy, with only four minimal tack welds—keeping heat exposure minimal.

## Challenge: High-Current DC Switching

The system required switching between series (24V operation) and parallel (12V charging) battery configurations. High-current DPDT switches rated for 15–20A were priced at ₹1,000– ₹2,000. A purchased switch also had a delicate pin that broke during soldering.

**Creative Solution**: Developed a plug socket configuration using 2-pin female plug sockets (~₹15–20 total) with thick DC power cables as contact elements. Manual reconfiguration by removing/reinserting cables changes the battery configuration.

| Attribute | DPDT Switch vs. Plug Socket Solution |
| --- | --- |
| Cost | ₹1,000–₹2,000 vs. ₹20–30 |
| Reliability | Single-point failure vs. Proven over 2 years |
| Elegance | Single toggle vs. Manual reconfiguration |
| Current Handling | Rated vs. Adequate for system load |

## Challenge: Motor Mounting and Slip Prevention

A sandwich-style clamping mechanism using two soft iron plates was used, but the motor slipped during high-torque conditions due to insufficient friction between metal-to-metal surfaces.

**Solution**: Inserted strips of old bicycle tube rubber between the mounting bracket and frame. This increased friction, added vibration dampening, reduced noise, and protected the frame from corrosion — at essentially zero cost (recycled material). Motor slipping was completely eliminated.