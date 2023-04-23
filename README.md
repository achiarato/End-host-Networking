# End-host SRv6 Networking

The use case follows the Cisco open source project called Jalapeno: https://github.com/cisco-open/jalapeno/blob/main/README.md

Applications request Network Services to the end-host where they reside. The end-host process the Network Services requests by interacting with a remote HTTP working as a SRv6 SIDs/uSID Policy Engine. The resulted SRv6 Networking Policies are provisioned at the end-host layer by onboarding a virtual data plane into the end-host platform meaning that packets reaching the network infrastructure are ready to be stateless forwarded based on the processed network services applied at the end-host layer.

Main benefits are:
- Microservice Architecture with granular binding between Application Network Services and Networking Policies 
- End-to-end networking with no more hand-off between virtual and physical environment (traffic stateless forwarded)
- Agility, Control and Automation with Application Network Service ---> Network Policies translation and provisioning made at the host layer with more direct control from the Applications theirself


## Hello End-host SRv6 Networking!

![image](https://user-images.githubusercontent.com/125906326/233828381-ec3402eb-76ed-43a6-94eb-b0070d9766bd.png)

### Code

govpp-client: https://github.com/achiarato/govpp-client 

SRv6 uSID Policy Engine: https://github.com/achiarato/sr-app
