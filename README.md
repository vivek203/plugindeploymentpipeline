# plugindeploymentpipeline
Automated plugin deployment to vSphere environments using VMware Cloud Automation Services

Steps:
1. Deploy a VCSA using CAS Blueprint
2. Download the plugin from: https://pure-vmware-plugin-repository.s3-us-west-1.amazonaws.com/vsphere/HTML5/purestorage-vsphere-plugin.zip
3. Create a pipeline to deploy the plugin downloaded in step 2 to the VCSA created in step 1
4. If everything above is done, think of something else useful to the user