## Global Hub 1.5.0 release

### Bundle snapshot

- snapshot name is `release-globalhub-1-5-pvplm`
- Consists of images
```
 - containerImage: 'quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-agent-globalhub-1-5@sha256:fba2fb39957c6bb71643c8077ccb50c2e971c3dadeb861f483fdc9eac37494ba'
      name: multicluster-global-hub-agent-globalhub-1-5
      source:
        git:
          context: ./
          dockerfileUrl: agent/Containerfile.agent
          revision: 34c1f9ad0caa7fe837547e1db14714e203e91a24
          url: 'https://github.com/stolostron/multicluster-global-hub'
    - containerImage: 'quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-manager-globalhub-1-5@sha256:f0b83f98b6bf86d428c7574f99f71000004f165bfc25fd935d3019f5a740c5f2'
      name: multicluster-global-hub-manager-globalhub-1-5
      source:
        git:
          context: ./
          dockerfileUrl: manager/Containerfile.manager
          revision: 34c1f9ad0caa7fe837547e1db14714e203e91a24
          url: 'https://github.com/stolostron/multicluster-global-hub'
    - containerImage: 'quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-operator-bundle-globalhub-1-5@sha256:bee3b9ef0691eb0fe21f330a5f929fa470e13913f3f3f865993a795961c03546'
      name: multicluster-global-hub-operator-bundle-globalhub-1-5
      source:
        git:
          revision: 1cfe9570616df2ca5e7361f4a1792002255ca0b1
          url: 'https://github.com/stolostron/multicluster-global-hub-operator-bundle'
    - containerImage: 'quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-operator-globalhub-1-5@sha256:2bb95b3345db7a78ff1918d368523bc204b8fd4d54173fd663d05f8a636471fb'
      name: multicluster-global-hub-operator-globalhub-1-5
      source:
        git:
          context: ./
          dockerfileUrl: operator/Containerfile.operator
          revision: 79bc3749824d1b547caef871b5a0c213c74137fb
          url: 'https://github.com/stolostron/multicluster-global-hub'
    - containerImage: 'quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/postgres-exporter-globalhub-1-5@sha256:ccbac6039c76075dfff69d0c3b2d91023ec2b3a728de92fe7071eeef890856bb'
      name: postgres-exporter-globalhub-1-5
      source:
        git:
          context: ./
          dockerfileUrl: Containerfile.konflux
          revision: 2bc40fb7398a4824e94b537b812b8a88c5fb76de
          url: 'https://github.com/stolostron/postgres_exporter'
    - containerImage: 'quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/glo-grafana-globalhub-1-5@sha256:73fdf00538e63595b7cc92d484e087ff815579a95d7259c579c6e7dc1beacff6'
      name: glo-grafana-globalhub-1-5
      source:
        git:
          context: ./
          dockerfileUrl: Containerfile.konflux
          revision: 3436239d0a4d6b9d00488b1d44ae8dbd37c5a6e8
          url: 'https://github.com/stolostron/glo-grafana'
```