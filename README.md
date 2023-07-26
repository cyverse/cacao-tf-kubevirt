# cacao-tf-kubevirt
CACAO(Cloud Automation & Continuous Analysis Orchestration) is a project enabling cloud automation & continuous analysis orchestration on multi-cloud. It allows user to import templates defined in various templating language(e.g. terraform, ansible, argo workflow) from any git hosting solution (e.g. Github, Gitlab); and deploy it to a cloud provider (e.g. OpenStack, AWS, K8S).

This is CACAO formatted Terraform and Ansible meant to deploy a private Kubevirt cluster built on top of k3s.

More information about CACAO can be found in [in this repo](https://gitlab.com/cyverse/cacao)

Once deployed through CACAO, you can immediately use SSH to retreive your kubeconfig and verify functionality by following [this lab](https://kubevirt.io/labs/kubernetes/lab1.html) to deploy your first instance.