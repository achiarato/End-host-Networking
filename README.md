# End-host SRv6 Networking

The use case follows the Cisco open source project called Jalapeno: https://github.com/cisco-open/jalapeno/blob/main/README.md

Applications request Network Services to the end-host where they reside. The end-host process the Network Services requests by interacting with a remote HTTP working as a SRv6 SIDs/uSID Policy Engine. The resulted SRv6 Networking Policies are provisioned at the end-host layer by onboarding a virtual data plane into the end-host platform meaning that packets reaching the network infrastructure are ready to be stateless forwarded based on the processed network services applied at the end-host layer.

Main benefit is reducing gap from Application and Network layer by a more efficient binding between Application Network Services and Networking Policies.
Application Network Services can be closer to the intent such as "low latency", "minimum bandwidth", and so on. The end-host layer is capable to transform them into a real SRv6 Policy with SID lists reflecting the real network topology. The process is fully automated providing greater agility and efficiency.

## Hello End-host SRv6 Networking!

Diagramma

Spiegazione del disegno

### Topology



Descrizione della topologia e screenshot dell'intero processo automatizzato

# Code

Link al GoVPP client: ....
Link al SR-APP: ....
