Hands-on lab series

The same project, broken into ten progressive labs you can actually run yourself — building up from raw Terraform to a full CI/CD pipeline.

Do these in order, and do the early ones manually, from your own terminal, before the pipeline automates them. Typing the az and terraform commands yourself first is what makes the pipeline make sense later — automating a step you've never run by hand teaches you nothing.


Labs:

1. Environment setup

2. Terraform fundamentals — state and first resources

3. Provision AKS, ACR, and Key Vault

4. Containerize and push the app manually

5. Deploy to AKS by hand with kubect

6. Wire Key Vault into the pod via CSI + RBAC

7. Build the CI stages in Azure DevOps

8. Add the gated Terraform CD stage

9. Automate the Kubernetes deploy stage

10. Operate it: scaling, secret rotation, mentoring


Lab 0: 

Get every CLI tool installed and authenticated before touching any Azure resource.

Steps

    1. Install Azure CLI, Terraform CLI, kubectl, and Docker Desktop (or a Linux Docker daemon).
    2. az login, then az account set --subscription "<your sub>".
    3. Create an Azure DevOps organization and project if you don't have one, and clone this repo into it.

  Verify: az account show, terraform version, kubectl version --client, and docker ps all return without error.

  



  


