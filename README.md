.Prerequisites
* Update https://github.com/r3dact3d/fluffy-ee/settings/secrets/actions[GitHub Secrets]
** AH_TOKEN - Galaxy or Automation Hub API Key
** EE_REGISTRY_PASSWORD - DockerHub or Image Registry Password

NOTE: The playbook default is looking for Key Pair named ansible-runner.  
      If you use a Key Pair named something different, update the variable called link:https://github.com/r3dact3d/aws-cli/blob/main/infra-setup/aws-infra.yaml#L11["aws_keypair"]


.Ansible Execution Environment Builder
* Run workflow

image::https://github.com/r3dact3d/fluffy-ee/actions/workflows/build-ee.yml/badge.svg[link="https://github.com/r3dact3d/fluffy-ee/actions/workflows/build-ee.yml"]
