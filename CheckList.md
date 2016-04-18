#These are the list of process that need to be tested before a release.

Regions
  * All EC2 Regions should be auto updated
  * Add/Remove Regions

Credential
  * When credential selection get changed, Favorite endpoint should also get changed under Regions selection
  * Add/Remove Credentials

Instances
  * Terminate Instance
  * Connect to Public DNS
  * Start/Stop option for Instance if it's EC2 Endpoints
  * Attach EBS Volumes
  * Attach Elastic IP with instances

Images
  * Image AMI's Filter
  * Launch Instance
  * Instance Type on Launch Instance

Key pairs
  * Create & Delete Key Pairs

Security Group
  * Grant New Permission
  * Create & Delete Security Group

Volumes & Snapshots
  * Create & Delete volumes
  * Attach Volume
  * Detach Volume

**Note**
To be tested in current version of Firefox and lower versions