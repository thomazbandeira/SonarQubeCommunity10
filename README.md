# SonarQubeCommunity

- [Implantar o SONAR](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fthomazbandeira%2FSonarQubeCommunity10%2Fmain%2FSonarAzureDeploy.json)



- OBS.: última versão mapeada: Community 10.4.1

UPDATES: Caso deseja configurar no Azure DevOps, Você deve adicionar uma chave a mais referente a Java SDK.

Ex.: 
        - task: SonarQubeAnalyze@5
          inputs:
            jdkversion: 'JAVA_HOME_17_X64'
