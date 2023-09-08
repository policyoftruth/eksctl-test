**References:**

* <https://github.com/dtaivpp/bottlerocket-opensearch>
* <https://eksctl.io/usage/minimum-iam-policies/>

**Notes:**

* create a non-commited `local.env` and add your AWS creds via env vars for less of a headache.
* CLI - `eksctl create cluster -f mycluster.yaml`
* Be very mindful of the `eksctl` tool's IAM requirements. YOLO AWS admin will not work!
* If curious, the `eksctl` tool reminds me of the kOps project but less agnostic.
* It generates it's AWS objects via a Cloud Formation stack set. 
