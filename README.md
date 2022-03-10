# Sign API with key in Luna HSM
  
  
1. Setup Datapower and Luna integration. The goal is for DP to be able to obtain the key stored in Luna. Follow the steps in: https://cpl.thalesgroup.com/sites/default/files/content/integration_guides/field_document/2020-07/007-013512-001_IBM_DataPower_SafeNetNetworkHSM_IntegrationGuide_RevA.pdf  
2. Create Datapower policy for JSON message and sign the message
3. Add the custom datapower policy to API Assembly
