# xMediatorInstanceManager  
REST interface for managing the mediator process instances inside the mediator VM  

### Location  
The xMediatorInstanceManager (xMIM) is part of the HighPerformanceNetworkInterface.  

### Description  
The vendor specific MediatorInstanceManagers, which are located inside the respective mediator VMs and administrating the individual mediator processes, are equipped with a harmonized REST API.  
This allows the MW SDN application layer to manage the vendor specific mediator processes.  
The xMediatorInstanceManager defines that REST API.  

A full integration of the MediatorInstanceManagers into the MW SDN application layer via the ApplicationPattern might be future work.  

### Relevance
The xMediatorInstanceManager allows automation of the management of the approximately 42,000 mediator processes.  

### Resources
- [Specification](./spec/)
- [TestSuite](./testing/)
- [Implementation](./server/)

### Comments
./.
