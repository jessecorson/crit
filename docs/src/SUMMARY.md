# Summary

- [Introduction](README.md)

- [Design](design.md)

- [Getting Started](getting-started.md)

- [Crit Guide](crit-guide/overview.md)
  - [System Requirements](crit-guide/system-requirements.md)
  - [Installation](crit-guide/installation.md)
  - [Configuration](crit-guide/configuration.md)
  - [Container Runtimes](crit-guide/container-runtimes.md)
  - [Running Etcd](crit-guide/running-etcd.md)
  - [Control Plane Sizing](crit-guide/control-plane-sizing.md)
  #- [Generating Certificates](crit-guide/generating-certificates.md)
  - [Bootstrapping a Worker](crit-guide/bootstrapping-a-worker.md)
    - [Bootstrap Token](crit-guide/bootstrap-token.md)
    - [Bootstrap Server](crit-guide/bootstrap-server.md)
  - [Configuring Control Plane Components](crit-guide/configuring-control-plane-components.md)
  - [Installing a CNI](crit-guide/installing-a-cni.md)
  - [Installing a Storage Driver](crit-guide/installing-a-storage-driver.md)
  - [Configuring Authentication](crit-guide/configuring-authentication.md)
  - [Kubelet Settings](crit-guide/kubelet-settings.md)
  - [Exposing Cluster DNS](crit-guide/exposing-cluster-dns.md)

- [Security Guide](security-guide/overview.md)
  - [Encrypting Kubernetes Secrets](security-guide/encrypting-kubernetes-secrets.md)
  - [Enabling Pod Security Policies](security-guide/enabling-pod-security-policies.md)
    - [Pod Security Policy Examples](security-guide/pod-security-policy-examples.md)
  - [Audit Policy Logging](security-guide/audit-policy-logging.md)
  - [Disabling Anonymous Authentication](security-guide/disabling-anonymous-authentication.md)
  - [Kubelet Server Certificate](security-guide/kubelet-server-certificate.md)
  - [Encrypting Shared Cluster Files](security-guide/encrypting-shared-cluster-files.md)

- [Cinder Guide](cinder-guide/overview.md)
  - [What is Cinder](cinder-guide/what-is-cinder.md)
  - [Installation](cinder-guide/installation.md)
  - [Configuration](cinder-guide/configuration.md)
  - [Features](cinder-guide/features.md)

- [FAQ](faq.md)

- [Command Reference](command-reference.md)
  - [Crit Commands](crit-commands/crit.md)
    - [General Commands](crit-commands/general.md)
      - [crit template](crit-commands/crit-template.md)
      - [crit up](crit-commands/crit-up.md)
      - [crit version](crit-commands/crit-version.md)
    - [Certs Commands](crit-commands/crit-certs.md)
      - [crit certs init](crit-commands/crit-certs-init.md)
      - [crit certs list](crit-commands/crit-certs-list.md)
      - [crit certs renew](crit-commands/crit-certs-renew.md)
    - [Config Commands](crit-commands/crit-config.md)
      - [crit config import](crit-commands/crit-config-import.md)
    - [Create Commands](crit-commands/crit-create.md)
      - [crit create token](crit-commands/crit-create-token.md)
    - [Generate Commands](crit-commands/crit-generate.md)
      - [crit generate hash](crit-commands/crit-generate-hash.md)
      - [crit generate kubeconfig](crit-commands/crit-generate-kubeconfig.md)
      - [crit generate token](crit-commands/crit-generate-token.md)

  - [Cinder Commands](cinder-commands/cinder.md)
    - [General Commands](cinder-commands/general.md)
      - [cinder load](cinder-commands/cinder-load.md)
      - [cinder version](cinder-commands/cinder-version.md)
    - [Create Commands](cinder-commands/cinder-create.md)
      - [cinder create cluster](cinder-commands/cinder-create-cluster.md)
      - [cinder create node](cinder-commands/cinder-create-node.md)
    - [Delete Commands](cinder-commands/cinder-delete.md)
      - [cinder delete cluster](cinder-commands/cinder-delete-cluster.md)
      - [cinder delete node](cinder-commands/cinder-delete-node.md)
    - [Export Commands](cinder-commands/cinder-export.md)
      - [cinder export kubeconfig](cinder-commands/cinder-export-kubeconfig.md)
    - [Get Commands](cinder-commands/cinder-get.md)
      - [cinder get clusters](cinder-commands/cinder-get-clusters.md)
      - [cinder get images](cinder-commands/cinder-get-images.md)
      - [cinder get ip](cinder-commands/cinder-get-ip.md)
      - [cinder get kubeconfigs](cinder-commands/cinder-get-kubeconfigs.md)
      - [cinder get nodes](cinder-commands/cinder-get-nodes.md)