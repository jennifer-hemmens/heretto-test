Notifications regarding cluster activity.

|Code Type|Value|Description|
|---------|-----|-----------|
|A|65778|Error. A task has failed to be processed and attempts to complete processing have been halted.|
|B|70945|Warning. A task has not been completed within the expected time frame. The system will continue to attempt to complete the task.|
|G|10010|Confirmation. Confirmation that a task has been successfully completed. Code extensions are used to provide further information about the time taken to complete the task: -   <a id="li\_54BF809F9BE14B969C684D475E3FFD3F"/>3-a. Task completed within a timeframe < 20m-   <a id="li\_FA43142D959F4E718EE4311639048FF7"/>3-b. Task completed within a timeframe < 40m-   <a id="li\_36A45623852E4AF39142C1E49ABE8D31"/>3-c. Task completed within a timeframe = 50m-   <a id="li\_35118D1183764205BE314752FF68A0DC"/>3-d. Task completed within a timeframe > 60m-   <a id="li\_89BFC27B1C0D4E3589E6F79EC8F4531B"/>3-e. Task completed within a timeframe > 80m|
|X|99999|Log. Supplemental message transaction log has been generated \(in response to a configuration setting\).|

