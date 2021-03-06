# class ControllerElementState

 **Member values** 

|Member name|Data type|Description|Usage|
|-----------|---------|-----------|-----|
|handle| [ControllerElementHandle](ControllerElementHandle.md#)|Controller element handle|To set handle, you simply assign a value directly to a field within handle. You can also use the parent message's HasField\(\) method to check if a message type field value has been set.|
|event\_type|int|Type of controller element event that occured|You can manipulate the field event\_type as if it were a regular field. To clear the value of event\_type and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|
|axis\_value|float|Axis value \(set between -1.0 and 1.0\); only set if 'axis' controller element, otherwise set to zero|You can manipulate the field axis\_value as if it were a regular field. To clear the value of axis\_value and reset it to the default value for its type, you call the ClearField\(\) method of the Message interface.|

**Parent topic:** [Base \(Python\)](../../summary_pages/Base.md)

