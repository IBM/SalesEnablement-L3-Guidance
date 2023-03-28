IBM Technology Zone (TechZone) should be used for demonstration environments if possible. Their are many environments already built and collections that utilize them.

The focus here is on IBM Cloud platform, so I'll relate how we created the environment and collection related to the IBM Cloud Satellite L3 learning plan.

You can find the collection for the IBM Cloud Satellite L3 <a href="https://techzone.ibm.com/collection/se-l3-ibm-cloud-satellite" target="_blank">here</a>.

If an existing environment cannot be leveraged for your needs, you will want to create a **custom request** in the TechZone portal <a href="https://custom-requests.ideas.aha.io/ideas/new" target="_blank">here</a>. I don't know how long this typically takes as I worked through the process through past contacts in TechZone.

The key pieces of work from an IBM Cloud platform perspective are:

   - identify what you want to do and the resources required to do it
   - decide if you want a **shared** environment where all users utilize the same cloud resources, or a **dedicated** environment where each user gets their own dedicated resources

There are several factors that will go into deciding if you want a **shared** or **dedicated** environment, such as:

   - provisioning time required for resources
   - costs associated with required resources
   - complexity of defining a shared environment
   - maintenance/monitoring of shared environments (what happens if someone corrupts a resource)

For **shared** resources, the biggest issue was identifying the appropriate IAM permissions required to allow a user to productively use the environment and accomplish your goals and NOT be able to cause issues with the environment. For IBM Cloud Satellite, we defined both roles and policies that were common for all users and then very narrow policies that scope access to very specific resources (e.g. a namespace within Kubernetes clusters). While IBM Cloud documentation as a whole tends to be pretty good, some offerings still have work to go in documenting and implementing fine-grained access control with IAM.

To get started in developing your TechZone environment, you should leverage existing content creation guidance available on the TechZone portal.
