# SMA-Compliant-Gripper
Gripper arm for ROVs/AUVs and other underwater applications. Claw itself is a compliant mechanism to adapt to many different geometries. Actuation using shape memory composites. Eliminates wear and tear, reduces inspection times. Can be produced using hybrid FDM+CNC fabrication methods.

****PROJECT STATUS****- Currently in early planning and experimentation stages, not yet finalized rib geometry or integrated actuation. Still making early, proof of concept designs. Please refer to JOURNAL.md for full project build log.

This project is to validate a paper that I intend to publish in the near future on the broader idea of compliant structures and SMA actuation.

My design must meet 6 main objectives-
  1) All compliant mechanisms and be made out of materials that may be printed using standard FDM 3D printers with multi material capabilities.
  2) FMD printed components be strictly print-in-place: no assembley of any sort.
  3) All components be printed with little to no supports, brims etc. that need manual removal afterwards.
  4) The SMA actuated parts be easy to produce automatically
  5) Final wiring and assembley be as quick and simple to perform as possible.
  6) No electrical discharge into surrounding water.

I intend to use the following materials-
  1) Thermoplastic Polyurethane of an appropriate shore hardness to make gripper jaws
  2) Poly Lactic Acid to provide structural strength where needed
  3) Nitinol springs with required specifications (thickness, threshold temperature, etc)
  4) Aluminum sheaths to insulate heated nitinol and prevent it from melting plastic components.

The claw itself is a ribbed compliant structure which is the first of 2 compliant mechanisms employed in my design. It can be made out of softer Thermoplastic Polyurethane (TPU). The Flexible materials and geometry allow the gripper to adapt to many different geometries without applying excessive force that may damage objects that it holds. The rigid back parts will be made of PLA which interfaces with the PTU with an intricate network of print in place dovetail slots etc.

There are a few obvious flaws with using nitinol to apply constant force necessary to hold objects for an extended time in a simple tug-off-war arrangement: nitinol alone may not provide sufficient force to grip an object, applying constant current to nitinol will cause it to heat up constantly leading to thermal runaway that will damage the gripper by melting parts. Solving this problem brings us to our second compliant mechanism, a bistable rib structure. Bistable ribs are compliant mechanisms that have two stable configurations (hence the name). I was considering using a design resembling a ribcage to give us open, and closed shapes for the gripper. Two nitinol springs will pull the ribs between configurations. When one spring pulls it will create tension in the other where the latter spring may once again be used to open or close the claw. I have attached a rough illustration for reference.

<img width="318" height="437" alt="image" src="https://github.com/user-attachments/assets/6f6f4cc9-f3f6-402d-98c0-827e62290839" />
