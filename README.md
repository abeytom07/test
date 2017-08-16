# test
Test Application

1. Download https://github.com/abeytom07/test/blob/master/appdtest-1.0.0.jar
2. Replace the params given in `<>` and execute the 

```
java -Dappdynamics.controller.hostName=comcast-aps.saas.appdynamics.com \
    -Dappdynamics.controller.port=443 -Dappdynamics.controller.ssl.enabled=true \
    -Dappdynamics.agent.applicationName=Einstein -Dappdynamics.agent.tierName=Maestro:AnswerFlow_WC \
    -Dappdynamics.agent.nodeName=AppD_Debug_Node1 \
    -Dappdynamics.agent.accountName=comcast-aps -Dappdynamics.agent.accountAccessKey=<access-key> \
    -javaagent:</path/to/javaagent.jar> -jar appdtest-1.0.0.jar
```
