# HMM
HMM wireshark
Three instance of 5G networks are given called norm, hijack and DoS. 
In the DoS attack instance, referred as DoS, a large number of Registration_Request signals are sent by a large number of broiler terminals in a short period of time. And the broiler terminals will not sent the signal of Authentication_Response to consume high portion of computing resource in 5G core network.
Then in the hijack attack instance, referred as hijack, the Authentication_Request signal sent by the access management function (AMF) in 5G core network to the terminal will be intercepted by 5G radio access network (RAN). When the timer of the registration process at the terminal side is out, the terminal will send Registration_Request signal, then Authentication_Request signal will be intercepted by RAN again. And repeat the above process.
Three data collections of the three instance are given, which are the signals of registration process sent and received at the terminal in 5G networks.
