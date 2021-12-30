# dashboards
<details closed>
<summary>Show plan for dev</summary>

```hcl
yandex_iam_service_account.sa: Refreshing state... [id=ajelcu8ktrngf1lgd671]
yandex_iam_service_account.sa: Refreshing state... [id=ajei1hcalifth2d1hue9]
yandex_kms_symmetric_key.kms_key: Refreshing state... [id=abjebasm88tsuk22306j]
yandex_iam_service_account.service_account: Refreshing state... [id=aje8ljtdi7vejgjbuuac]
yandex_iam_service_account.node_account: Refreshing state... [id=ajefbrdne36bqdbep77q]
yandex_iam_service_account.sa: Refreshing state... [id=aje0bl9opun799ads72q]
yandex_resourcemanager_folder_iam_member.sa_storage_editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/storage.admin/serviceAccount:ajei1hcalifth2d1hue9]
yandex_iam_service_account_static_access_key.sa: Refreshing state... [id=aje9nkdaqplr8e2dmj9u]
yandex_resourcemanager_folder_iam_member.sa_storage_editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/storage.admin/serviceAccount:ajelcu8ktrngf1lgd671]
yandex_iam_service_account_static_access_key.sa: Refreshing state... [id=ajeuhasko7l20fbrv3cf]
yandex_storage_bucket.bucket: Refreshing state... [id=ke-images-svc-dev]
yandex_storage_bucket.bucket: Refreshing state... [id=imgsearch-dev]
yandex_resourcemanager_folder_iam_member.node_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/container-registry.images.puller/serviceAccount:ajefbrdne36bqdbep77q]
yandex_resourcemanager_folder_iam_member.service_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/editor/serviceAccount:aje8ljtdi7vejgjbuuac]
yandex_resourcemanager_folder_iam_member.sa_storage_editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/storage.editor/serviceAccount:aje0bl9opun799ads72q]
yandex_iam_service_account_static_access_key.sa: Refreshing state... [id=ajeni6gcvmtj2bel5sg6]
yandex_kubernetes_cluster.kube_master: Refreshing state... [id=catu3nt06759k64eq5c2]
yandex_storage_bucket.bucket: Refreshing state... [id=suggester-dev]
yandex_kubernetes_node_group.node_group: Refreshing state... [id=cati8tun40f9naakqaua]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
random_password.password[0]: Refreshing state... [id=none]
random_password.password: Refreshing state... [id=none]
yandex_mdb_redis_cluster.redis_cluster: Refreshing state... [id=c9qaqlhb0u0aimvkg8kh]
google_dns_record_set.record_set[1]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/*.dev.cluster.kznexpess.com./CNAME]
google_dns_record_set.record_set[0]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/dev.cluster.kznexpess.com./A]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
yandex_vpc_subnet.b: Refreshing state... [id=e2lk2cce79gionfhq93b]
yandex_vpc_subnet.a: Refreshing state... [id=e9bduvnv8iu9q3ssb3jp]
random_password.user_passwords[2]: Refreshing state... [id=none]
random_password.user_passwords[1]: Refreshing state... [id=none]
random_password.user_passwords[0]: Refreshing state... [id=none]
yandex_mdb_kafka_cluster.kafka_cluster: Refreshing state... [id=c9qm1t4b5aq07d2n8u4f]
yandex_mdb_postgresql_cluster.cluster: Refreshing state... [id=c9qc9s7ia9iajtobgvol]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.ingress-static-ip.yandex_vpc_address.ingress_static_ip: Refreshing state... [id=e9b5a6mtmji71tbs3bfs]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.ingress-nginx.helm_release.ingress-nginx: Refreshing state... [id=ingress-nginx]
helm_release.prometheus-operator: Refreshing state... [id=prometheus-operator]
helm_release.drone-sa: Refreshing state... [id=drone-sa]
kubernetes_namespace.namespace: Refreshing state... [id=infra-global-configs]
kubernetes_service_account.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]
kubernetes_service.kube-dns-upstream: Refreshing state... [id=kube-system/kube-dns-upstream]
kubernetes_service.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]
kubernetes_manifest.node-local-dns: Refreshing state...
helm_release.elasticsearch_operator: Refreshing state... [id=eck-operator]
helm_release.jaeger_operator: Refreshing state... [id=jaeger-operator]
kubernetes_namespace.namespace: Refreshing state... [id=svc-internal-kafka-proxy]
helm_release.neo4j: Refreshing state... [id=recommendations-neo4j]
helm_release.cert-manager: Refreshing state... [id=certmanager]
helm_release.redis-k8s: Refreshing state... [id=redis]
helm_release.redis-k8s: Refreshing state... [id=search-composer-redis]
helm_release.kubed: Refreshing state... [id=kubed]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.elastic-cluster: Refreshing state... [id=search-v1-cluster]
module.elasticsearch.helm_release.elastic-cluster: Refreshing state... [id=es-cluster]
helm_release.kafka-proxy: Refreshing state... [id=kafka-proxy-mcs]
kubernetes_namespace.namespace: Refreshing state... [id=svc-internal-postfix]
kubernetes_namespace.namespace: Refreshing state... [id=infra-logging]
kubernetes_config_map.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]
kubernetes_daemonset.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.permission-manager: Refreshing state... [id=permission-manager]
helm_release.issuers: Refreshing state... [id=certmanager-issuers]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:

  # kubernetes_daemonset.node-local-dns will be updated in-place
  ~ resource "kubernetes_daemonset" "node-local-dns" {
        id               = "kube-system/node-local-dns"
        # (1 unchanged attribute hidden)


      ~ spec {
            # (2 unchanged attributes hidden)



          ~ template {

              ~ spec {
                    # (13 unchanged attributes hidden)

                  ~ container {
                        name                       = "node-cache"
                        # (9 unchanged attributes hidden)


                      ~ port {
                          - host_port      = 53 -> null
                            name           = "dns"
                            # (2 unchanged attributes hidden)
                        }
                      ~ port {
                          - host_port      = 53 -> null
                            name           = "dns-tcp"
                            # (2 unchanged attributes hidden)
                        }
                      ~ port {
                          - host_port      = 9253 -> null
                            name           = "metrics"
                            # (2 unchanged attributes hidden)
                        }



                        # (6 unchanged blocks hidden)
                    }


                    # (6 unchanged blocks hidden)
                }
                # (1 unchanged block hidden)
            }
            # (2 unchanged blocks hidden)
        }
        # (1 unchanged block hidden)
    }

Plan: 0 to add, 1 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.
kubernetes_secret.secret: Refreshing state... [id=infra-global-configs/gcr-ro-secret]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
kubernetes_secret.secret: Refreshing state... [id=svc-internal-postfix/postfix-smtp-password]
kubernetes_secret.secret["infra-logging"]: Refreshing state... [id=infra-logging/cloud-ca-pem-secret]
kubernetes_secret.secret["kube-system"]: Refreshing state... [id=kube-system/cloud-ca-pem-secret]
kubernetes_secret.secret["infra-ingress-nginx"]: Refreshing state... [id=infra-ingress-nginx/cloud-ca-pem-secret]
kubernetes_secret.secret["infra-ingress-nginx"]: Refreshing state... [id=infra-ingress-nginx/es-infra-password]
kubernetes_secret.secret["kube-system"]: Refreshing state... [id=kube-system/es-infra-password]
kubernetes_secret.secret["infra-logging"]: Refreshing state... [id=infra-logging/es-infra-password]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
kubernetes_secret.secret: Refreshing state... [id=svc-internal-kafka-proxy/kafka-common-proxy-secret]

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:

  # kubernetes_secret.secret["infra-ingress-nginx"] will be updated in-place
  ~ resource "kubernetes_secret" "secret" {
        id        = "infra-ingress-nginx/cloud-ca-pem-secret"
        # (3 unchanged attributes hidden)

      ~ metadata {
          ~ annotations      = {
              - "banzaicloud.com/last-applied"   = "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" -> null
              - "logging.banzaicloud.io/default" = "watched" -> null
            }
            name             = "cloud-ca-pem-secret"
            # (5 unchanged attributes hidden)
        }
    }

  # kubernetes_secret.secret["kube-system"] will be updated in-place
  ~ resource "kubernetes_secret" "secret" {
        id        = "kube-system/cloud-ca-pem-secret"
        # (3 unchanged attributes hidden)

      ~ metadata {
          ~ annotations      = {
              - "banzaicloud.com/last-applied"   = "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" -> null
              - "logging.banzaicloud.io/default" = "watched" -> null
            }
            name             = "cloud-ca-pem-secret"
            # (5 unchanged attributes hidden)
        }
    }

Plan: 0 to add, 2 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.postfix: Refreshing state... [id=postfix]
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-calico]
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-nginx-ingress]
helm_release.kafka-proxy: Refreshing state... [id=common-kafka-proxy]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.logging-operator.helm_release.logging-operator: Refreshing state... [id=logging-operator]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.logging-operator-logging.kubernetes_secret.es_ca_pem_secret: Refreshing state... [id=infra-logging/es-ca-pem-secret]
module.logging-operator-logging.helm_release.logging-operator-logging: Refreshing state... [id=logging-operator-logging]

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:

  # module.logging-operator-logging.kubernetes_secret.es_ca_pem_secret will be updated in-place
  ~ resource "kubernetes_secret" "es_ca_pem_secret" {
        id          = "infra-logging/es-ca-pem-secret"
        # (3 unchanged attributes hidden)

      ~ metadata {
          ~ annotations      = {
              - "banzaicloud.com/last-applied"   = "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" -> null
              - "logging.banzaicloud.io/default" = "watched" -> null
            }
            name             = "es-ca-pem-secret"
            # (5 unchanged attributes hidden)
        }
    }

Plan: 0 to add, 1 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.
```

</details>
<details closed>
<summary>Show plan for global</summary>

```hcl
yandex_kms_symmetric_key.kms_key: Refreshing state... [id=abjctm8lnnf1hbf8kq4t]
yandex_iam_service_account.node_account: Refreshing state... [id=ajegpc964dn70k5fcknj]
yandex_iam_service_account.service_account: Refreshing state... [id=aje2t4drvoi57erqj37n]
yandex_iam_service_account.service_account: Refreshing state... [id=ajeeg5e0lb5lhbn1k8k2]
yandex_iam_service_account.service_account: Refreshing state... [id=ajekr00hp7cnocr0u25c]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.dns-zone.yandex_dns_zone.zone: Refreshing state... [id=dnsepvoc0qd1ml561v06]
yandex_resourcemanager_folder_iam_member.service_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/editor/serviceAccount:aje2t4drvoi57erqj37n]
yandex_resourcemanager_folder_iam_member.node_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/container-registry.images.puller/serviceAccount:ajegpc964dn70k5fcknj]
yandex_resourcemanager_folder_iam_member.service_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/editor/serviceAccount:ajeeg5e0lb5lhbn1k8k2]
yandex_resourcemanager_folder_iam_member.service_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/editor/serviceAccount:ajekr00hp7cnocr0u25c]
yandex_kubernetes_cluster.kube_master: Refreshing state... [id=cat1elp4pjlt7rbe7bvk]
yandex_compute_instance_group.drone-runners: Refreshing state... [id=cl1mrari66n3tv9dbfvk]
yandex_compute_instance_group.drone-runners: Refreshing state... [id=cl19fm292eva23j1e6gr]
yandex_kubernetes_node_group.node_group: Refreshing state... [id=cat35u34eoo2ja61292h]
