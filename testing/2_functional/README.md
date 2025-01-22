# Functional Testing 

#### The content of the Functional Testing is summarized in the following index file:
- [Index](./xMediatorInstanceManager+test.functional.index.yaml)

#### Details on the individual testcases can be found here:
- [Completeness](./completeness/)  
  Most individual services are tested for providing a ResponseCode different from 404.  
  (The usual validation for ResponseCode 204 or 200 with the correct ResponseBody cannot be applied as proprietary management interfaces cannot be simulated.)

#### Manual test cases
- [LiveCycle](./liveCycle/)
  Requires a physical device.  
  Mediator gets created, searched in list and deleted.  
