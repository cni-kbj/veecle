
# ![Veecle](https://file.notion.so/f/s/df49c87a-4821-45ad-b917-d7cff9ad5e6f/Untitled.png?id=817287b0-4824-4a91-993d-1084f80ce112&table=block&spaceId=1cbc9a02-d8de-4bde-83fd-b2e7ef7e0b68&expirationTimestamp=1678785616198&signature=SoWLRrHOviuiIKxbdCOpD8uHPmwRbYbib-szRwljTmc&downloadName=Untitled.png)

Veecle | All Cars. One Software. Our mission is to bridge the gap between existing supplier components and smart apps running on top through unified software. We provide a platform to tackle next-gen automotive connected & security demands. 

Veecle has 3 different product lines: 

- **NoS**: a Rust heap-free, asynchronous and type-safe runtime for automotive. NoS acts as the gateway that allows Nteract to communicate with the vehicle in a secure and safe way.  This unit is secure by design, updatable over-the-air, and fully testable over virtual pipelines. Designed for rapid and agile development. 

- **Nteract:** a Rust Android Automotive HAL providing secure & safe APIs to communicate to any vehicle. This provides secure & safe APIs to communicate with any vehicle. It acts as the security gateway between the non-secure, connected Android world and the in-vehicle highly secure domain. This unit talks to the rest of the vehicle via NoS: this allows for domain separation and access control. This allows for zero-cost secure integration of HMI and applications 

- **Veecle Studio & Cloud Services** consist of a set of tools that can be used to deploy, test, monitor and manage our instances. At its core, this is a set of secure APIs that allows interconnecting visual tools for development, deployment, data visualisation, data storage and fleet management. It’s intended for in-house developers but the restricted API access can be used for end customers (e.g. phone apps).  
        

## Hardware support
- Infineon Aurix™ TC3XX Tricore™ Microcontroller
- ARM Cortex-M based Embedded controllers


## Upcoming
Our vision is to open the automotive industry by bringing the paradigm shift that occurred in the smartphone world with iOS and Android. \
Stay tuned! Our first release is coming soon!

1. Examples of how to develop AURIX™ drivers that exploit Rust’s compiler to avoid configuration and usage errors. 
2. Dependency-free libraries for:
    - Asynchronous execution: embedded code is heavily event and I/O driven. Veecle async library massively reduces the complexity of code that relies on multitasking
    - Type-state API: most embedded execution work in a state-machine fashion. Veecle type-state library enforces execution order and rules at compile type
    - Type-safe processing: embedded data are transmitted via binary protocols. Veecle encoder library provides type-safe, memory-safe, and allocation-free binary encoders and decoders 

## Learn more
Are you interested in Veecle? \
Visit us at www.veecle.io or Write us at info@veecle.io
