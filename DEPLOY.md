# Deploy

An AFG can be deployed in many different configurations. It is entirely up to
you to decide how and where AFG components will execute to achieve the overall
simulation.

### Overview

If you aren't familiar yet with AFG architecture, please read the
[overview](./ARCHITECTURE.md)

### Development or Basic Deployment

At the bare minimum, you need a `Controller` and a `Sensor` configured together
to begin simulating an AFG.

1. Follow instructions in the `Controller`
[DEPLOY.md](https://github.com/acbodine/afg-controller/DEPLOY.md)

2. Follow instructions in the `Sensor`
[DEPLOY.md](https://github.com/acbodine/afg-sensor/DEPLOY.md)

### Advanced Deployment

Moving from a Development or Basic Deployment to an Advanced one is quite simple;
its a matter of deploying any number of `Sensors` and possibly scaling up the
number of `Controllers` based on throughput needs.

Follow the same steps for provisioning more `Controllers` and `Sensors` as you
did in the Basic Deployment section above.

> NOTE: It may be useful for you to play with changing the `Sensors` emission
> frequencies to increase or decrease the data throughput of your AFG.
