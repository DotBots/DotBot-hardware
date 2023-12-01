# DotBot Assembling manual

This document will guide you through the DotBot assembling workflow.

## Material & Tools

Make sure you have all required [components](./COMPONENTS.md) and that you
eventually followed the [compopent preparation](PREPARING.md), if needed.

You will just require access to an Allen screwdriver (1.5mm).

<div align="center">
  <img src="dist/images/DotBot-pcb-prepared.jpg" height="150px" alt="PCB prepared"/>
  <img src="dist/images/DotBot-components.jpg" height="150px" alt="DotBot components"/>
</div>

## Let's go!

1. Start by mounting the ball caster. For this step, you need:
  - 2x 10mm M2 screws
  - 1x Pololu ball caster
  - 1x Pololu ball caster holder
  - 1x Pololu ball caster spacer

  <div align="center">
    <img src="dist/images/DotBot-ball-caster-assembling.jpg" width="200px" alt="Ball caster assembling"/>
  </div>

  Once done it should look like this:

  <div align="center">
    <img src="dist/images/DotBot-ball-caster-mounted.jpg" width="200px" alt="Ball caster assembling"/>
  </div>

2. Mount the motors. For this step, you need:
  - 4x 5mm M2 screws
  - 2x motor holders
  - 1x left motor (the one with the **black** wire soldered on the `+` pad)
  - 1x right motor (the one with the **red** wire soldered on the `+` pad)

  1. Place one of the motor in the holder, on the corresponding side (left or
    right) of the PCB. It is important that the red wire is on **top** and on the
    **read** side, regardless if it's the right or left motor:
    <div align="center">
      <img src="dist/images/DotBot-motor-with-holder.jpg" width="200px" alt="Ball caster assembling"/>
    </div>
  2. Screw the motor:
    <div align="center">
      <img src="dist/images/DotBot-motor-with-holder-mounted.jpg" width="200px" alt="Ball caster assembling"/>
    </div>
  3. Repeat the operation for the other motor. You should end up with the
     following setup:
    <div align="center">
      <img src="dist/images/DotBot-mounted-without-wheels.jpg" width="200px" alt="Ball caster assembling"/>
    </div>

3. And last but not least, plug the JST connectors and put the wheels on the
  motor shafts and you are done!

<div align="center">
  <img src="dist/images/DotBot-mounted.jpg" width="500px" alt="Ball caster assembling"/>
</div>
