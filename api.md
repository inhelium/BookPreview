# namespace `DelormeInbound` {#namespace_delorme_inbound}



## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`DelormeInbound::Address`](#class_delorme_inbound_1_1_address)    | 
`class `[`DelormeInbound::Consts`](#class_delorme_inbound_1_1_consts)    | 
`class `[`DelormeInbound::DelormeTranslator`](#class_delorme_inbound_1_1_delorme_translator)    | 
`class `[`DelormeInbound::Event`](#class_delorme_inbound_1_1_event)    | IPC Outbound [Event](#class_delorme_inbound_1_1_event) Schema
`class `[`DelormeInbound::InReachStatus`](#class_delorme_inbound_1_1_in_reach_status)    | InReach device status information
`class `[`DelormeInbound::IPCPayload`](#class_delorme_inbound_1_1_i_p_c_payload)    | 
`class `[`DelormeInbound::LocationPoint`](#class_delorme_inbound_1_1_location_point)    | Represent Point device information
`class `[`DelormeInbound::Program`](#class_delorme_inbound_1_1_program)    | 
`class `[`DelormeInbound::TestService`](#class_delorme_inbound_1_1_test_service)    | 
# class `DelormeInbound::Address` {#class_delorme_inbound_1_1_address}






## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------

## Members

# class `DelormeInbound::Consts` {#class_delorme_inbound_1_1_consts}






## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------

## Members

# class `DelormeInbound::DelormeTranslator` {#class_delorme_inbound_1_1_delorme_translator}






## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline void Start()` | 
`public inline void Stop()` | 

## Members

#### `public inline void Start()` {#class_delorme_inbound_1_1_delorme_translator_1ab656b2995c15a994bf1e9fc3c7f507df}





#### `public inline void Stop()` {#class_delorme_inbound_1_1_delorme_translator_1a98cbe061823b7a4f5428693cbdecf26b}





# class `DelormeInbound::Event` {#class_delorme_inbound_1_1_event}


IPC Outbound [Event](#class_delorme_inbound_1_1_event) Schema



## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  Event()` | 

## Members

#### `public inline  Event()` {#class_delorme_inbound_1_1_event_1a94e925f39a19206077bd26598d89e02c}





# class `DelormeInbound::InReachStatus` {#class_delorme_inbound_1_1_in_reach_status}


InReach device status information



## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  InReachStatus()` | 
`public inline  InReachStatus(int autonomous,int lowBattery,int intervalChange,int resetDetected)` | 

## Members

#### `public inline  InReachStatus()` {#class_delorme_inbound_1_1_in_reach_status_1a55616cdea3062305931e191b83da643e}





#### `public inline  InReachStatus(int autonomous,int lowBattery,int intervalChange,int resetDetected)` {#class_delorme_inbound_1_1_in_reach_status_1abe74a1df8c703ce16d7c9302fe209526}





# class `DelormeInbound::IPCPayload` {#class_delorme_inbound_1_1_i_p_c_payload}






## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------

## Members

# class `DelormeInbound::LocationPoint` {#class_delorme_inbound_1_1_location_point}


Represent Point device information



## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  LocationPoint(double latitude,double longitude,double altitude,int gpsFix,double course,double speed)` | 

## Members

#### `public inline  LocationPoint(double latitude,double longitude,double altitude,int gpsFix,double course,double speed)` {#class_delorme_inbound_1_1_location_point_1aca6e6050c6edfa0f7ef54b59590bcd7c}





# class `DelormeInbound::Program` {#class_delorme_inbound_1_1_program}






## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------

## Members

# class `DelormeInbound::TestService` {#class_delorme_inbound_1_1_test_service}

```
class DelormeInbound::TestService
  : public ServiceBase
```  





## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  TestService()` | 
`protected inline override void OnStart(string [] args)` | 
`protected inline override void OnStop()` | 

## Members

#### `public inline  TestService()` {#class_delorme_inbound_1_1_test_service_1aa7f94cf940c97598c9b201a9149022f4}





#### `protected inline override void OnStart(string [] args)` {#class_delorme_inbound_1_1_test_service_1ad862a1e86275b8255c488e3a6c22e7a5}





#### `protected inline override void OnStop()` {#class_delorme_inbound_1_1_test_service_1aec1ccdc7a327467217fc45406acf6d8e}





