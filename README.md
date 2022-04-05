# Shipa and SUSE Rancher Fleet Example
Example Repo for SUSE Rancher Fleet Deployments

## Leveraging
Installing Fleet is straight forward from their docs:
https://fleet.rancher.io/quickstart/

Once installed, will need to install Crossplane into a Kubernetes Cluster
and have Shipa bound to a Kubernetes Cluster. This example is wired
to Shipa Cloud [/crossplane/crossplane-secret.yaml].

Finally, will need to apply the fleet-config.yaml to your Fleet cluster. 

Happy Fleeting!
