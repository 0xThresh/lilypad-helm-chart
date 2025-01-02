# Lilypad Helm Chart
Helm chart to provision Lilypad Resource Providers on Kubernetes. 

## Features to Support
1. Create Lilypad RPs - one RP per pod 
2. Ability to spin up new Ethereum addresses when a new pod is spun up if no pre-existing wallets are available, storing their private key as Kubernetes secrets using the address as the secret name. This would require a data structure to track which wallets are in use 