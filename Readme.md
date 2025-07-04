# Introduction 

Platform administrators face the challenge of observing the activities within the entire platform. There are multiple sources that provide information, gateway locks, audit logs, and the platform inventory itself. Additionally, there is a need to obtain this data quickly to observe and react to events automatically.

To address this, a solution has been developed based on Fabric Real-Time Intelligence (RTI). This solution extracts information from audit logs through the API, gateway locks via a script included in the solution, and the inventory of the whole platform through the API.

The following architecture illustrates how the solution interacts with different components to receive, process, store, present dashboards, and react to the platform's information. It also enables longer retention of logs for historical purposes and allows comparison of the current state with previous states to create custom solutions.


