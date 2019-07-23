# TFM
This Master's Degree Thesis describes the development and implementation of a blockchain-based Chain of Custody for digital evidences.
Developed system has four main components or subsystems: a permissioned blockchain, a file repository and two web applications.
Web apps allow users to interact with the blockchain, file repository stores evidences' copies and the blockchain register the changes in the system (new evidences, transference of these...)

For the blockchain implementation I have used the framework Hyperledger Fabric. To make things easier, I have also use the tool Hyperledger Composer which eases the work with Fabric. Hyperledger Composer let you to define *Business Networks*. The defined Business Network for this project is here: https://github.com/JTrillo/HyperledgerComposer/tree/master/coc

Both web applications have been developed with Angular. One of these allows system's users to register and consult evidences (https://github.com/JTrillo/Angular/tree/master/Apps/CoC-App). The other one, ease system's administrators to manage new users (https://github.com/JTrillo/Angular/tree/master/Apps/CoC-Admin-App).

## Grade obtained --> 9.5/10
