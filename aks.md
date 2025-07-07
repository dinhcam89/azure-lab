# AKS Labs Review & Notes

## Lab 1: Create new AKS cluster
- **What I did**
    - [  ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 2: Understanding important concepts on AKS
- **What I did**
    - [ ]
- **What I learned**
    - Azure AKS CSI:
        1. Compare File/Block and Object Storage
        2. Purpose of Azure AKS CSI Storage Driver
        3. Types of Azure AKS CSI Storage Driver
    - Public vs Private Cluster:
    - Azure CNI:
        1. Underlay(Physical-based) vs Overlay(Virtual) Network:
        2. AKS Networking Model: Overlay Network (most common in K8s) and Flat Network
    - Azure CNI vs Kubenet:
        1. Azure CNI: each *Pod* get an IP address from VNet
        2. Kubenet: each *Node* get an IP address from VNet, pod traffic will be SNAT
    - Node Pool:
        1. Ephermeral vs Managed Disk:
           + Ephermeral: Stateless, temporary, free, data not persistent
           + Managed Disk: Stateful, data persistent,    
    - Cluster authorizations
        1. Azure AD authentication with Kubernetes RBAC: Authenticate with Azure AD + Authorize with Kubernetes RBAC
        2. Azure AD authentication with Azure RBAC     : Authenticate with Azure AD + Authorize with Azure RBAC 
        3. Local accounts with Kubernetes RBAC         : Authenticate with account(kubeconfig file) + Authorize with Kubernetes RBAC
- **Knowledge notes**
    - Azure AKS CSI Storage Driver => a storage driver that can be used to store cluster data externally + manage independently

---

## Lab 3: Deploy simple application into AKS
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 4: Cluster & NodePool operations
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 5: Integrate with Azure Key Vault
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 6: Namespace actions
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 7: Storage in AKS
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 8: Ingress Controller
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]

---

## Lab 9: DNS
- **What I did**
    - [ ]
- **What I learned**
    - [ ]
- **Knowledge notes**
    - [ ]