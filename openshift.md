**Intro 2 k8s**

-   Read about Kubernetes, why it was created, its uses and how it
    achieves isolation.

    Answer the following questions:

    -   What is k8s?

        > What is desired state? (In k8s scope)

        > Give 3 uses for k8s.

**Cluster component**

-   Read about the components in a k8s cluster.

    For each component, describe what it achieves and why we need it:

    -   Apiserver

        > Etcd

        > Scheduler

        > K8s node

        > Controller manager

        > Kubeproxy

        > Kubelet

        > Container runtime

**Nodes**

-   Read about k8s nodes.

    Answer the following questions:

    -   What are the states of the node?

        > Explain the process of adding a node to the cluster.

        > How can you know when a node stops working?

        > Can you store storage on the node, how?

**Control plane**

-   Read about the control plane.

    Answer the following questions:

    -   What are the components that make up the control plane?

        > Explain the relationship between the control plane and the
        > workers.

**Plugin architecture**

-   Read about CNI, CSI and CRI.

    Answer the following questions:

    -   For each of the above explain what it is.

        > What are plugins in k8s? How can you make one?

**Cri-o**

-   Read about cri-o.

    Answer the following questions:

    -   What is cri-o? How does it differ from k8s?

        > Why would we use cri-o instead of k8s?

**Artifacts**

-   Read about software artifacts, k8s artifacts, and best practices in
    storing them.

    Answer the following questions:

    -   Why do we need artifacts?

        > How do you store artifacts securely?

        > What is the common versioning system that is used with
        > artifacts?

**Pods**

-   Read about pods is k8s.

    Answer the following questions:

    -   How do pods differ from containers?

        > What are the different lifecycle stages of a pod?

        > How can we limit the amount of resources that a pod is taking?
        > Should we do that?

**Namespaces and resources**

-   Read about namespaces in k8s, limit ranges and quotas.

    Answer the following questions:

    -   How do namespaces differ from project in openshift?

        > Why do we need namespaces?

        > Can you limit the amount of resources taken by a namespace? If
        > so why do you need to limit the amount of resources taken by a
        > pod?

**Workloads and controllers**

-   Read about the different workloads and controllers in k8s.

    Answer the following questions:

    -   List all of the workloads and controllers, for each of them,
        > explain what does it do and when will we use it.

        > What is the difference between a statefullset and a
        > deployment?

**Custom workloads and controllers**

-   Read about custom resources in k8s.

    Answer the following questions:

    -   What is a cr and what is a crd, what is the difference between
        > them?

        > What is an operator?

        > How can you make a custom resource?

**Probes**

-   Read about probes in k8s.

    Answer the following questions?

    -   What are the 3 kinds of probes in k8s?

        > Why and when should we use each probe?

**Dns resolution**

-   Read about the dns resolution in k8s.

    Answer the following questions:

    -   Explain the dns resolution in k8s, from start to finish?

        > Can k8s function without it?

        > What is the difference between a pod dns resolution and a
        > service dns resolution?

**Services**

-   Read about services in k8s.

    Answer the following questions:

    -   What are the different kind of services in k8s.

        > What is a node port, how does it work?

        > How do services achieve high availability?

        > What are discovery, load balancing and endpoints in the
        > context of services?

**RBAC and service accounts**

-   Read about cluster roles, service accounts, and RBAC in k8s.

    Answer the following questions:

    -   What is a cluster role binding?

        > What is a service account token?

        > What is a imagepullsecret?

        > Explain what is RBAC, how can you achieve it in k8s?

**Secrets and configmaps**

-   Read about secrets and configmaps.

    Answer the following questions:

    -   What is the difference between a secret and a configmap?

        > How do you "mount" secrets and configmaps?

**Markings**

-   Read about labels, annotations, and taints.

    Answer the following questions:

    -   What is the difference between the three?

        > Why and when should we use each one?

        > Can a label have impact on the object in openshift?

**Pod placement**

-   Read about how the placement of the pod can be influenced in k9s.

    Answer the following questions:

    -   What component is responsible for assigning a node to a pod in
        > k8s? How does this process work?

        > What are the different methods of controlling the placement of
        > a pod in k8s? What is the difference between each one?

**Ingress**

-   Read about the different kinds of ingresses in k8s.

    Answer the following questions:

    -   What is the difference between a ingress and a route?

        > What is the difference between a ingress an the loadbalancer
        > type?

**Networkpolicies**

-   Read about networkpolices.

    Answer the following questions:

    -   What is pod isolation?

        > What is multitenancy?

        > How are networkpolicies used in order to achieve multitenancy?

**Volumes**

-   Read about volumes, persistent and ephemeral in k8s.

    Answer the following questions:

    -   Why do we need volumes?

        > What are the different types of volumes?

        > What is the relationship between a pv and a pvc?

        > What is a storageclass?

        > What are mount propagations in a pod?

**Pod security**

-   Read about pod security in k8s.

    Answer the following questions:

    -   What is a scc?

        > What does drop capabilities mean?

        > What is a pod security profile

