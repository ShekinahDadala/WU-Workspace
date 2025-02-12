# WU-Workspace

Title: DevOps Engineer
Program domain: CPE
Work function\description: To manage and maintain our Spinnaker sandbox and upgrade the configuration in gitlab 

Business requirement: Cloud Platform Engineer
Manager: Roshan Shetty / Narender Potla
Phone Number: +91 7799221259 (update your Mobile number)


**IN PROD ENV: THERE WILL BE NO INGRESSES, ONLY LOADBALANCERS**

Similar way follow the search for “App-Privx-CICD-Engg” as well, (Privx is the terminal to access SANDBOX (STAGING))
Once Privx access is granted, click on okta sandbox, search with 10.7.96.183 ip
Run export command
            export KUBECONFIG=/home/ubuntu/.kube/WANV-SAN-0-EKS-CL-Sandbox-Core-Tools-001
            Select namespace: oes
Urls to Access:

ISD url:- https://oes-sbx.wureachnonprod.awswuintranet.net/ui/   (Staging)

Spinnaker url:- https://spinnaker-sbx.wureachnonprod.awswuintranet.net/#/applications/appdemosamples/executions  (Staging)

Ssd url:- http://ssd-sbx.wureachnonprod.awswuintranet.net/ssdservice/v1/spinnakerevents  (Staging) 

**SANDBOX (STAGING):** 10.7.96.183                                                                                                                                                                                                                                  
export KUBECONFIG=/home/ubuntu/.kube/WANV-SAN-0-EKS-CL-Sandbox-Core-Tools-001                                                                                                                                                                                       
namespace: oes

**DR IP:** 10.10.203.4

**PRODUCTION IP:** 10.39.5.176  ::     
export KUBECONFIG=~/.kube/WANV-SAP-9-EKS-CD-Tools.config

namespace: oes (blue) - Prometheus and Grafana is configured in monitoring ns - 4.0.3.1  -- CURRENTLY RUNNING PROD ENV                                                                                                                                                
namespace: isd (green) - Prometheus and Grafana is configured in same ns i.e isd - 2024.06.00

TO VIEW GIT REPOS: cd swapnil in PROD ENV

in green , sandbox we have configured, in monitoing also we do have grafana installed but i dont have dns name

LC0c@TF.5.og
