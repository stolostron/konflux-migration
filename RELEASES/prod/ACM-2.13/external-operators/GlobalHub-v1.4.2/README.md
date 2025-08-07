## Global Hub 1.4.2 release

### Bundle snapshot

- snapshot name is `release-globalhub-1-4-d52n6`
- Consists of images
```
           {
            "containerImage": "quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/glo-grafana-globalhub-1-4@sha256:047b6c378e2b37339dd498c9025060f20812014bde4d0c98183f1a1201c21e66",
            "name": "glo-grafana-globalhub-1-4",
            "source": {
              "git": {
                "context": "./",
                "dockerfileUrl": "Dockerfile.ocp",
                "revision": "a044ef24103c346848bfe290898a1a8f27cb8090",
                "url": "https://github.com/stolostron/glo-grafana"
              }
            },
            "repository": "quay.io/redhat-prod/multicluster-globalhub----multicluster-globalhub-grafana-rhel9",
            "tags": [
              "1.4.2",
              "1.4.2-1753320224",
              "a044ef24103c346848bfe290898a1a8f27cb8090",
              "a044ef2"
            ],
            "rh-registry-repo": "registry.redhat.io/multicluster-globalhub/multicluster-globalhub-grafana-rhel9",
            "registry-access-repo": "registry.access.redhat.com/multicluster-globalhub/multicluster-globalhub-grafana-rhel9"
          },
          {
            "containerImage": "quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-agent-globalhub-1-4@sha256:0f4683d18404b4a9412e42ed417f6d3ac0024b3c57aa72c9162ff72d6ea8d394",
            "name": "multicluster-global-hub-agent-globalhub-1-4",
            "source": {
              "git": {
                "context": "./",
                "dockerfileUrl": "agent/Containerfile.agent",
                "revision": "08cdb84f2c0ab70fd1ba09c337c6283e59540826",
                "url": "https://github.com/stolostron/multicluster-global-hub"
              }
            },
            "repository": "quay.io/redhat-prod/multicluster-globalhub----multicluster-globalhub-agent-rhel9",
            "tags": [
              "1.4.2",
              "1.4.2-1753321485",
              "08cdb84f2c0ab70fd1ba09c337c6283e59540826",
              "08cdb84"
            ],
            "rh-registry-repo": "registry.redhat.io/multicluster-globalhub/multicluster-globalhub-agent-rhel9",
            "registry-access-repo": "registry.access.redhat.com/multicluster-globalhub/multicluster-globalhub-agent-rhel9"
          },
          {
            "containerImage": "quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-manager-globalhub-1-4@sha256:2be8bc79667018386235823e322ae10788e4e7e889c10e63566ae27a65dcabf1",
            "name": "multicluster-global-hub-manager-globalhub-1-4",
            "source": {
              "git": {
                "context": "./",
                "dockerfileUrl": "manager/Containerfile.manager",
                "revision": "1783d624b6c31a71627b1486d3f469169de91fa0",
                "url": "https://github.com/stolostron/multicluster-global-hub"
              }
            },
            "repository": "quay.io/redhat-prod/multicluster-globalhub----multicluster-globalhub-manager-rhel9",
            "tags": [
              "1.4.2",
              "1.4.2-1753341557",
              "1783d624b6c31a71627b1486d3f469169de91fa0",
              "1783d62"
            ],
            "rh-registry-repo": "registry.redhat.io/multicluster-globalhub/multicluster-globalhub-manager-rhel9",
            "registry-access-repo": "registry.access.redhat.com/multicluster-globalhub/multicluster-globalhub-manager-rhel9"
          },
          {
            "containerImage": "quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-operator-bundle-globalhub-1-4@sha256:fdc0c228ca38db30f89812e41c09ec96d9276ed844b0801013375bbffd6c1a16",
            "name": "multicluster-global-hub-operator-bundle-globalhub-1-4",
            "source": {
              "git": {
                "revision": "718b44a60f08d7670e4031792ca51ef0a4b87363",
                "url": "https://github.com/stolostron/multicluster-global-hub-operator-bundle"
              }
            },
            "repository": "quay.io/redhat-prod/multicluster-globalhub----multicluster-globalhub-operator-bundle",
            "tags": [
              "1.4.2",
              "1.4.2-1753342728",
              "718b44a60f08d7670e4031792ca51ef0a4b87363",
              "718b44a"
            ],
            "rh-registry-repo": "registry.redhat.io/multicluster-globalhub/multicluster-globalhub-operator-bundle",
            "registry-access-repo": "registry.access.redhat.com/multicluster-globalhub/multicluster-globalhub-operator-bundle"
          },
          {
            "containerImage": "quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/multicluster-global-hub-operator-globalhub-1-4@sha256:c5b3b3907e8135d3eedba40e27ba18a232ea4f30854d652059fcb14f82a8bf15",
            "name": "multicluster-global-hub-operator-globalhub-1-4",
            "source": {
              "git": {
                "context": "./",
                "dockerfileUrl": "operator/Containerfile.operator",
                "revision": "08cdb84f2c0ab70fd1ba09c337c6283e59540826",
                "url": "https://github.com/stolostron/multicluster-global-hub"
              }
            },
            "repository": "quay.io/redhat-prod/multicluster-globalhub----multicluster-globalhub-rhel9-operator",
            "tags": [
              "1.4.2",
              "1.4.2-1753321085",
              "08cdb84f2c0ab70fd1ba09c337c6283e59540826",
              "08cdb84"
            ],
            "rh-registry-repo": "registry.redhat.io/multicluster-globalhub/multicluster-globalhub-rhel9-operator",
            "registry-access-repo": "registry.access.redhat.com/multicluster-globalhub/multicluster-globalhub-rhel9-operator"
          },
          {
            "containerImage": "quay.io/redhat-user-workloads/acm-multicluster-glo-tenant/postgres-exporter-globalhub-1-4@sha256:ea906dcf8d45956251df22e269fe0b8fa8d49734e96a61b10db7b25d626b2e6a",
            "name": "postgres-exporter-globalhub-1-4",
            "source": {
              "git": {
                "context": "./",
                "dockerfileUrl": "Dockerfile",
                "revision": "4aec615f24bb75bbb1e84899d6ab7a71a35f16e6",
                "url": "https://github.com/stolostron/postgres_exporter"
              }
            },
            "repository": "quay.io/redhat-prod/multicluster-globalhub----multicluster-globalhub-postgres-exporter-rhel9",
            "tags": [
              "1.4.2",
              "1.4.2-1753321506",
              "4aec615f24bb75bbb1e84899d6ab7a71a35f16e6",
              "4aec615"
            ],
            "rh-registry-repo": "registry.redhat.io/multicluster-globalhub/multicluster-globalhub-postgres-exporter-rhel9",
            "registry-access-repo": "registry.access.redhat.com/multicluster-globalhub/multicluster-globalhub-postgres-exporter-rhel9"
          }
```
