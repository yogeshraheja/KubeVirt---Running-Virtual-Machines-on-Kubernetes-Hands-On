# KubeVirt---Running-Virtual-Machines-on-Kubernetes-Hands-On
Stop running two platforms. Learn to run VMs alongside containers on Kubernetes with real, hands-on KubeVirt demos

## Enroll: https://www.udemy.com/course/kubevirt-running-virtual-machines-on-kubernetes-hands-on/?referralCode=9F9F5EAD09C877E09792

## Enroll: https://www.thinkrook.com/courses

Most organizations don’t get to pick between containers and virtual machines. They run both. Containers live on Kubernetes, while legacy apps, Windows workloads and stateful systems stay on VMware, KVM or something similar. The result is two platforms, two toolsets and two teams doing the same job twice.

KubeVirt fixes that. It’s an open-source CNCF project that extends Kubernetes so virtual machines run natively next to containers, on the same cluster, with the same tools and the same workflows. A VM becomes just another Kubernetes object: you create it with kubectl, expose it with a Service, store its disk on a PVC and scale it like any other workload. It’s also the upstream project behind Red Hat’s OpenShift Virtualization, so what you learn here applies to real-world platforms.

This course takes you from zero to confident with KubeVirt, with clear explanations first and hands-on demos for every concept. You’ll start with the problem KubeVirt solves, using simple analogies instead of documentation-speak. Then you’ll go inside the architecture (virt-api, virt-controller, virt-handler and virt-launcher) and trace exactly how a VM is created, step by step.

Then you build. You’ll set up a two-node Kubernetes cluster from scratch, install KubeVirt and virtctl, and create your first virtual machine declaratively with YAML and with virtctl. From there you’ll:

- Configure VMs with cloud-init
- Standardize hardware with instancetypes and preferences
- Expose VMs outside the cluster and SSH into them
- Attach persistent data disks using an NFS provisioner
- Scale fleets of VMs with VirtualMachineInstanceReplicaSets and VirtualMachinePools
- Use the Containerized Data Importer (CDI) to build persistent root disks
- Cover the production concepts every operator runs into: feature gates, live migration, snapshots and restores, hotplug volumes, VM health probes and disk expansion

# What makes this course different

Most KubeVirt content is either a dry walk through the docs or a quick “look, a VM is running” demo with no explanation of why it works. This course does both properly. The theory is short, visual and beginner-friendly, and the demos are real, live and unedited, so you see the commands, the output and what to check when something doesn’t work. Every concept is built on a simple example, not a wall of YAML.
