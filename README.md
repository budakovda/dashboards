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

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:


Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:


No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
  # yandex_compute_instance_group.drone-runners will be updated in-place
  ~ resource "yandex_compute_instance_group" "drone-runners" {
        id                  = "cl19fm292eva23j1e6gr"
        name                = "lite-drone-runners"
        # (9 unchanged attributes hidden)



      ~ instance_template {
          ~ metadata           = {
              ~ "docker-container-declaration" = (sensitive)
                # (1 unchanged element hidden)
            }
            name               = "drone-lite-runner-{instance.index}"
            # (5 unchanged attributes hidden)




            # (4 unchanged blocks hidden)
        }

        # (3 unchanged blocks hidden)
    }

Plan: 0 to add, 1 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.
  # yandex_compute_instance_group.drone-runners will be updated in-place
  ~ resource "yandex_compute_instance_group" "drone-runners" {
        id                  = "cl1mrari66n3tv9dbfvk"
        name                = "android-drone-runners"
        # (9 unchanged attributes hidden)



      ~ instance_template {
          ~ metadata           = {
              ~ "docker-container-declaration" = (sensitive)
                # (1 unchanged element hidden)
            }
            name               = "drone-android-runner-{instance.index}"
            # (5 unchanged attributes hidden)




            # (4 unchanged blocks hidden)
        }

        # (3 unchanged blocks hidden)
    }

Plan: 0 to add, 1 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.
module.dns-record.yandex_dns_recordset.record_set[2]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-main-db-replica-1.prod/A]
module.dns-record.yandex_dns_recordset.record_set[16]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-acceptance.dev.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[14]: Refreshing state... [id=dnsepvoc0qd1ml561v06/pg-for-services.dev.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[13]: Refreshing state... [id=dnsepvoc0qd1ml561v06/jaeger-collector/A]
module.dns-record.yandex_dns_recordset.record_set[8]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-service.prod.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[12]: Refreshing state... [id=dnsepvoc0qd1ml561v06/data-kafka-proxy.prod/A]
module.dns-record.yandex_dns_recordset.record_set[22]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-db-master.dev/A]
module.dns-record.yandex_dns_recordset.record_set[3]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-main-db-master.prod/A]
module.dns-record.yandex_dns_recordset.record_set[18]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-postamat.dev.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[9]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-auth-service.dev.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[19]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-postamat.prod.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[17]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-acceptance.prod.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[6]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-main-db-master.dev/A]
module.dns-record.yandex_dns_recordset.record_set[1]: Refreshing state... [id=dnsepvoc0qd1ml561v06/vmcluster-insert/A]
module.dns-record.yandex_dns_recordset.record_set[5]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-db-master.prod/A]
module.dns-record.yandex_dns_recordset.record_set[0]: Refreshing state... [id=dnsepvoc0qd1ml561v06/vmcluster-select/A]
module.dns-record.yandex_dns_recordset.record_set[21]: Refreshing state... [id=dnsepvoc0qd1ml561v06/elasticsearch-proxy.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[7]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-service.dev.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[15]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-main-db-replica-2.prod/A]
module.dns-record.yandex_dns_recordset.record_set[20]: Refreshing state... [id=dnsepvoc0qd1ml561v06/zipkin-collector/A]
module.dns-record.yandex_dns_recordset.record_set[11]: Refreshing state... [id=dnsepvoc0qd1ml561v06/data-kafka-proxy.dev/A]
module.dns-record.yandex_dns_recordset.record_set[10]: Refreshing state... [id=dnsepvoc0qd1ml561v06/api-auth-service.prod.mcs/A]
module.dns-record.yandex_dns_recordset.record_set[4]: Refreshing state... [id=dnsepvoc0qd1ml561v06/wms-db-replica-1.prod/A]
gcore_storage_s3.storage: Refreshing state... [id=1705]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
random_password.user_passwords[1]: Refreshing state... [id=none]
random_password.user_passwords[0]: Refreshing state... [id=none]
yandex_vpc_subnet.b: Refreshing state... [id=e2lselb6v820rhnulbrr]
yandex_vpc_subnet.a: Refreshing state... [id=e9b10kh1kopq669o3vhp]
random_password.password[3]: Refreshing state... [id=none]
random_password.password[0]: Refreshing state... [id=none]
random_password.password[1]: Refreshing state... [id=none]
random_password.password[2]: Refreshing state... [id=none]
yandex_mdb_postgresql_cluster.cluster: Refreshing state... [id=c9qtvchfiflqqa8o2oa4]
random_password.password[0]: Refreshing state... [id=none]
random_password.password[1]: Refreshing state... [id=none]
yandex_vpc_subnet.es_subnet["ru-central1-b"]: Refreshing state... [id=e2lhvvb0io56chrr8ji8]
yandex_vpc_subnet.es_subnet["ru-central1-c"]: Refreshing state... [id=b0cj6vnsu12p3kuakr7a]
yandex_vpc_subnet.es_subnet["ru-central1-a"]: Refreshing state... [id=e9beul0gftd7epvli0l0]
random_password.password: Refreshing state... [id=none]
google_dns_record_set.record_set[0]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/internal.kznexpess.com./A]
google_dns_record_set.record_set[1]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/*.internal.kznexpess.com./CNAME]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
yandex_mdb_postgresql_cluster.cluster: Refreshing state... [id=c9q286212nijlnuin6o3]
yandex_mdb_postgresql_cluster.cluster: Refreshing state... [id=c9qlfm9s5cpd5h20sdjv]
google_dns_record_set.record_set[1]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/*.infra.cluster.kznexpess.com./CNAME]
google_dns_record_set.record_set[0]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/infra.cluster.kznexpess.com./A]
yandex_mdb_elasticsearch_cluster.elastic: Refreshing state... [id=c9q2qlu2el3evjkartpn]

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
module.lb-network.yandex_vpc_subnet.lb-net: Refreshing state... [id=e9b1el7t7aln4e2oaqs0]
module.ingress-static-ip.yandex_vpc_address.ingress_static_ip: Refreshing state... [id=e9b7ajue1nu6dkejffcp]
module.wg_static_ip.yandex_vpc_address.ingress_static_ip: Refreshing state... [id=e9ba32u6ft8m99u5h7r9]
module.wg-gate.tls_private_key.default: Refreshing state... [id=f55de1be693f1c11165a513e9b8b061a4c8a7c05]
module.wg-gate.local_file.private_key_pem: Refreshing state... [id=f17c52d980070dc0a01d2e853f41536e2dc5cbfa]
module.vmcluster.helm_release.victoria-metrics-cluster: Refreshing state... [id=vmcluster]
module.yandex_metrics_sa.yandex_iam_service_account.sa: Refreshing state... [id=aje37mmsbgvpi4ov8b22]
helm_release.elastic-cluster: Refreshing state... [id=es-cluster]
helm_release.jaeger_operator: Refreshing state... [id=jaeger-operator]
module.wg-gate.yandex_compute_instance.wireguard: Refreshing state... [id=fhmrqdg9l90o7uo45g7n]
module.ingress-nginx.helm_release.ingress-nginx: Refreshing state... [id=ingress-nginx]
helm_release.prometheus-blackbox-exporter: Refreshing state... [id=blackbox]
helm_release.cert-manager: Refreshing state... [id=certmanager]
helm_release.victoria-metrics-operator: Refreshing state... [id=victoria-metrics-operator]
helm_release.zipkin: Refreshing state... [id=zipkin]
helm_release.elasticsearch_operator: Refreshing state... [id=eck-operator]
module.yandex_metrics_sa.yandex_iam_service_account_api_key.sa-api-key: Refreshing state... [id=ajeuooee9fuhgmlamls5]
module.yandex_metrics_sa.yandex_resourcemanager_folder_iam_member.sa-editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/monitoring.viewer/serviceAccount:aje37mmsbgvpi4ov8b22]
helm_release.jaeger_operator: Refreshing state... [id=jaeger]
helm_release.kubed: Refreshing state... [id=kubed]
module.wg-gate.local_file.script: Refreshing state... [id=76c6e4f048e66570d6cd41d8ee8c6ec17de52005]
module.wg-gate.null_resource.ansible: Refreshing state... [id=7846423943787834639]

Note: Objects have changed outside of Terraform

Terraform detected the following changes made outside of Terraform since the
last "terraform apply":

  # module.wg-gate.local_file.script has been deleted
  - resource "local_file" "script" {
      - content              = <<-EOT
            #!/bin/sh
             while ! echo exit | nc 178.154.220.139 22; do sleep 1; done
        EOT -> null
      - directory_permission = "0777" -> null
      - file_permission      = "0777" -> null
      - filename             = "/tmp/wait-instance.sh" -> null
      - id                   = "76c6e4f048e66570d6cd41d8ee8c6ec17de52005" -> null
    }
  # module.wg-gate.local_file.private_key_pem has been deleted
  - resource "local_file" "private_key_pem" {
      - content              = (sensitive) -> null
      - directory_permission = "0777" -> null
      - file_permission      = "0400" -> null
      - filename             = "/tmp/adminroot" -> null
      - id                   = "f17c52d980070dc0a01d2e853f41536e2dc5cbfa" -> null
    }

Unless you have made equivalent changes to your configuration, or ignored the
relevant attributes using ignore_changes, the following plan may include
actions to undo or respond to these changes.

─────────────────────────────────────────────────────────────────────────────

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  + create

Terraform will perform the following actions:

  # module.wg-gate.local_file.private_key_pem will be created
  + resource "local_file" "private_key_pem" {
      + content              = (sensitive)
      + directory_permission = "0777"
      + file_permission      = "0400"
      + filename             = "/tmp/adminroot"
      + id                   = (known after apply)
    }

  # module.wg-gate.local_file.script will be created
  + resource "local_file" "script" {
      + content              = <<-EOT
            #!/bin/sh
             while ! echo exit | nc 178.154.220.139 22; do sleep 1; done
        EOT
      + directory_permission = "0777"
      + file_permission      = "0777"
      + filename             = "/tmp/wait-instance.sh"
      + id                   = (known after apply)
    }

Plan: 2 to add, 0 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.
kubernetes_namespace.namespace: Refreshing state... [id=logging]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.yandex_metrics_secret.kubernetes_secret.secret: Refreshing state... [id=monitoring/yandex-monitoring-bearer-token]
kubernetes_manifest.prometheus_rule: Refreshing state...
random_password.cookie_secret: Refreshing state... [id=none]
random_password.password[1]: Refreshing state... [id=none]
random_password.password[0]: Refreshing state... [id=none]
random_password.client_secret: Refreshing state... [id=none]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
htpasswd_password.hash[0]: Refreshing state... [id=PW243261243130242f7238644a3536354653574a777371464456416e452e304f776964336342556e4544593571484b76794d6e3337646d5a3373523432]
htpasswd_password.hash[1]: Refreshing state... [id=PW2432612431302470345a453570545156726b737a4b7633713868546365654c517670796154647a756b4638457866414863425065663055346e515257]

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
module.yandex_metrics_exporter.helm_release.yandex_metrics: Refreshing state... [id=yandex-monitoring]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.dex.helm_release.dex: Refreshing state... [id=dex]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.issuers: Refreshing state... [id=certmanager-issuers]

Note: Objects have changed outside of Terraform

Terraform detected the following changes made outside of Terraform since the
last "terraform apply":

  # module.yandex_metrics_secret.kubernetes_secret.secret has been changed
  ~ resource "kubernetes_secret" "secret" {
        id        = "monitoring/yandex-monitoring-bearer-token"
        # (3 unchanged attributes hidden)

      ~ metadata {
          + annotations      = {}
          + labels           = {}
            name             = "yandex-monitoring-bearer-token"
            # (4 unchanged attributes hidden)
        }
    }

Unless you have made equivalent changes to your configuration, or ignored the
relevant attributes using ignore_changes, the following plan may include
actions to undo or respond to these changes.

─────────────────────────────────────────────────────────────────────────────

No changes. Your infrastructure matches the configuration.

Your configuration already matches the changes detected above. If you'd like
to update the Terraform state to match, create and apply a refresh-only plan:
  terraform apply -refresh-only

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.oauth2-proxy.helm_release.oauth2-proxy: Refreshing state... [id=oauth2-proxy]
kubernetes_secret.secret: Refreshing state... [id=monitoring/grafana-env-secret]
kubernetes_secret.secret: Refreshing state... [id=monitoring/postgres-grafana-db-password]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

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

  # kubernetes_manifest.prometheus_rule will be updated in-place
  ~ resource "kubernetes_manifest" "prometheus_rule" {
      ~ object   = {
          ~ metadata   = {
              ~ annotations                = {
                  - "prometheus-operator-validated" = "true"
                } -> (known after apply)
              ~ labels                     = null -> (known after apply)
                # (14 unchanged elements hidden)
            }
            # (3 unchanged elements hidden)
        }
        # (1 unchanged attribute hidden)
    }

Plan: 0 to add, 1 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.
kubernetes_secret.secret["ingress-nginx"]: Refreshing state... [id=ingress-nginx/es-infra-password]
kubernetes_secret.secret["monitoring"]: Refreshing state... [id=monitoring/es-infra-password]
kubernetes_secret.secret["kube-system"]: Refreshing state... [id=kube-system/es-infra-password]
kubernetes_secret.secret["logging"]: Refreshing state... [id=logging/es-infra-password]
kubernetes_service.service: Refreshing state... [id=logging/kibana-service]
kubernetes_secret.secret["monitoring"]: Refreshing state... [id=monitoring/cloud-ca-pem-secret]
kubernetes_secret.secret["kube-system"]: Refreshing state... [id=kube-system/cloud-ca-pem-secret]
kubernetes_secret.secret["logging"]: Refreshing state... [id=logging/cloud-ca-pem-secret]
kubernetes_secret.secret["ingress-nginx"]: Refreshing state... [id=ingress-nginx/cloud-ca-pem-secret]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
kubernetes_ingress.ingress: Refreshing state... [id=logging/kibana-logs-ingress]

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:

  # kubernetes_secret.secret["ingress-nginx"] will be updated in-place
  ~ resource "kubernetes_secret" "secret" {
        id        = "ingress-nginx/cloud-ca-pem-secret"
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
helm_release.prometheus-operator: Refreshing state... [id=prometheus-operator]
helm_release.elastic-exporter: Refreshing state... [id=logging-elastic-exporter]
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-calico]
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-nginx-ingress]
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
module.logging-operator-logging.kubernetes_secret.es_ca_pem_secret: Refreshing state... [id=logging/es-ca-pem-secret]
module.logging-operator-logging.helm_release.logging-operator-logging: Refreshing state... [id=logging-operator-logging]

Terraform used the selected providers to generate the following execution
plan. Resource actions are indicated with the following symbols:
  ~ update in-place

Terraform will perform the following actions:

  # module.logging-operator-logging.kubernetes_secret.es_ca_pem_secret will be updated in-place
  ~ resource "kubernetes_secret" "es_ca_pem_secret" {
        id          = "logging/es-ca-pem-secret"
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

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
```

</details>
<details closed>
<summary>Show plan for prod</summary>

```hcl
yandex_iam_service_account.sa: Refreshing state... [id=ajed96ifp4qaov45rghv]
yandex_iam_service_account.service_account: Refreshing state... [id=aje2a4iqcn5gg994j3f9]
yandex_kms_symmetric_key.kms_key: Refreshing state... [id=abj67timo5kdsdvehih8]
yandex_iam_service_account.node_account: Refreshing state... [id=ajecnf836grbe66mdcgh]
yandex_iam_service_account_static_access_key.sa: Refreshing state... [id=ajeknv9n0jbvs0guoj8c]
yandex_resourcemanager_folder_iam_member.sa_storage_editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/storage.editor/serviceAccount:ajed96ifp4qaov45rghv]
yandex_storage_bucket.bucket: Refreshing state... [id=suggester-prod]
yandex_iam_service_account.sa: Refreshing state... [id=aje9a0dv0b2scghmoa8b]
yandex_resourcemanager_folder_iam_member.node_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/container-registry.images.puller/serviceAccount:ajecnf836grbe66mdcgh]
yandex_resourcemanager_folder_iam_member.service_account: Refreshing state... [id=b1gdpq9otvfh360t4r5e/editor/serviceAccount:aje2a4iqcn5gg994j3f9]
yandex_kubernetes_cluster.kube_master: Refreshing state... [id=catqm9o14gj5arf3d7pi]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
yandex_iam_service_account_static_access_key.sa: Refreshing state... [id=ajebjbue2nofdhgkj2qp]
yandex_resourcemanager_folder_iam_member.sa_storage_editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/storage.admin/serviceAccount:aje9a0dv0b2scghmoa8b]
yandex_kubernetes_node_group.node_group: Refreshing state... [id=catppqmnhocqd63lebo9]
yandex_storage_bucket.bucket: Refreshing state... [id=imgsearch-prod]
yandex_kubernetes_node_group.additional_node_groups["browserless_chrome"]: Refreshing state... [id=cat6lmd9001suiggjf98]
yandex_kubernetes_node_group.additional_node_groups["airflow_dags"]: Refreshing state... [id=catbqpfv4mtimm81mtla]
yandex_kubernetes_node_group.additional_node_groups["apps"]: Refreshing state... [id=catsjcr3cjhijkp678vo]
yandex_kubernetes_node_group.additional_node_groups["data_apps"]: Refreshing state... [id=cathank4k2a99vi8kuj0]
yandex_kubernetes_node_group.additional_node_groups["prometheus"]: Refreshing state... [id=cat3ujnjl1pgfs4bminf]
yandex_kubernetes_node_group.additional_node_groups["infra_services"]: Refreshing state... [id=cat1inlp67t4m1ithhgu]
yandex_kubernetes_node_group.additional_node_groups["es_search_v1"]: Refreshing state... [id=catb1fl5surk2fqvmpok]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
random_password.password: Refreshing state... [id=none]
yandex_mdb_redis_cluster.redis_cluster: Refreshing state... [id=c9qh6rhk9r7oei371cd8]
random_password.user_passwords[0]: Refreshing state... [id=none]
yandex_vpc_subnet.a: Refreshing state... [id=e9b83vr1lh7vq4kdnql5]
yandex_vpc_subnet.b: Refreshing state... [id=e2ljq2ljau5j53rvgvc5]
yandex_mdb_postgresql_cluster.cluster: Refreshing state... [id=c9qu43s4k97ou79l5oti]
google_dns_record_set.record_set[0]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/prod.cluster.kznexpess.com./A]
google_dns_record_set.record_set[1]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/kznexpresscom/rrsets/*.prod.cluster.kznexpess.com./CNAME]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
google_dns_record_set.record_set[0]: Refreshing state... [id=projects/kazanexpress-184010/managedZones/ke-main/rrsets/analytics.business.kazanexpress.ru./A]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.cert-manager: Refreshing state... [id=certmanager]
module.ingress-static-ip.yandex_vpc_address.ingress_static_ip: Refreshing state... [id=e9b7kkdb563ntvrlike3]
module.ingress-static-ip.yandex_vpc_address.ingress_static_ip: Refreshing state... [id=e9bbh17fl7vlsr3pnksj]
module.yandex_metrics_sa.yandex_iam_service_account.sa: Refreshing state... [id=aje2juqm0tegpqgvk58b]
helm_release.elastic-cluster: Refreshing state... [id=search-v1-history-cluster]
module.ingress-nginx.helm_release.ingress-nginx: Refreshing state... [id=ingress-nginx-api]
module.ingress-nginx.helm_release.ingress-nginx: Refreshing state... [id=ingress-nginx]
module.yandex_metrics_sa.yandex_resourcemanager_folder_iam_member.sa-editor: Refreshing state... [id=b1gdpq9otvfh360t4r5e/monitoring.viewer/serviceAccount:aje2juqm0tegpqgvk58b]
module.yandex_metrics_sa.yandex_iam_service_account_api_key.sa-api-key: Refreshing state... [id=ajebgqgf3jvgsh325m4e]
helm_release.redis-k8s: Refreshing state... [id=search-composer-redis]
helm_release.redis-k8s: Refreshing state... [id=redis]
helm_release.elastic-cluster: Refreshing state... [id=search-v1-es]
helm_release.kafka-proxy: Refreshing state... [id=kafka-proxy-mcs]
helm_release.drone-sa: Refreshing state... [id=drone-sa]
helm_release.jaeger_operator: Refreshing state... [id=jaeger-operator]
helm_release.kubed: Refreshing state... [id=kubed]
helm_release.elasticsearch_operator: Refreshing state... [id=eck-operator]
helm_release.prometheus-operator: Refreshing state... [id=prometheus-operator]
kubernetes_service_account.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]
kubernetes_service.kube-dns-upstream: Refreshing state... [id=kube-system/kube-dns-upstream]
kubernetes_service.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]
helm_release.issuers: Refreshing state... [id=certmanager-issuers]
kubernetes_manifest.node-local-dns: Refreshing state...
kubernetes_namespace.namespace: Refreshing state... [id=svc-internal-postfix]
kubernetes_namespace.namespace: Refreshing state... [id=infra-logging]
kubernetes_namespace.namespace: Refreshing state... [id=infra-global-configs]
module.cloud-dns-secret.kubernetes_secret.secret: Refreshing state... [id=infra-certmanager/cloud-dns-secret]
module.eab-secret.kubernetes_secret.secret: Refreshing state... [id=infra-certmanager/zerossl-eab-secret]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.issuer.kubernetes_manifest.cluster_issuer: Refreshing state...

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
module.yandex_metrics_secret.kubernetes_secret.secret: Refreshing state... [id=infra-monitoring/yandex-monitoring-bearer-token]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
kubernetes_config_map.node-local-dns: Refreshing state... [id=kube-system/node-local-dns]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
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
module.yandex_metrics_exporter.helm_release.yandex_metrics: Refreshing state... [id=yandex-monitoring]
helm_release.permission-manager: Refreshing state... [id=permission-manager]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
kubernetes_secret.secret: Refreshing state... [id=svc-b2bc-backend/redis-prod-api-secret]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.

Note: Objects have changed outside of Terraform

Terraform detected the following changes made outside of Terraform since the
last "terraform apply":

  # kubernetes_daemonset.node-local-dns has been changed
  ~ resource "kubernetes_daemonset" "node-local-dns" {
        id               = "kube-system/node-local-dns"
        # (1 unchanged attribute hidden)

      ~ metadata {
            name             = "node-local-dns"
          ~ resource_version = "65204420" -> "65378261"
            # (5 unchanged attributes hidden)
        }

        # (1 unchanged block hidden)
    }

Unless you have made equivalent changes to your configuration, or ignored the
relevant attributes using ignore_changes, the following plan may include
actions to undo or respond to these changes.

─────────────────────────────────────────────────────────────────────────────

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
kubernetes_secret.secret: Refreshing state... [id=infra-global-configs/gcr-ro-secret]
kubernetes_secret.secret["infra-ingress-nginx"]: Refreshing state... [id=infra-ingress-nginx/cloud-ca-pem-secret]
kubernetes_secret.secret["infra-logging"]: Refreshing state... [id=infra-logging/cloud-ca-pem-secret]
kubernetes_secret.secret["kube-system"]: Refreshing state... [id=kube-system/cloud-ca-pem-secret]
kubernetes_secret.secret["infra-ingress-nginx-api"]: Refreshing state... [id=infra-ingress-nginx-api/cloud-ca-pem-secret]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
kubernetes_secret.secret["infra-logging"]: Refreshing state... [id=infra-logging/es-infra-password]
kubernetes_secret.secret["infra-ingress-nginx-api"]: Refreshing state... [id=infra-ingress-nginx-api/es-infra-password]
kubernetes_secret.secret["kube-system"]: Refreshing state... [id=kube-system/es-infra-password]
kubernetes_secret.secret["infra-ingress-nginx"]: Refreshing state... [id=infra-ingress-nginx/es-infra-password]

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

  # kubernetes_secret.secret["infra-ingress-nginx-api"] will be updated in-place
  ~ resource "kubernetes_secret" "secret" {
        id        = "infra-ingress-nginx-api/cloud-ca-pem-secret"
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
              - "banzaicloud.com/last-applied"   = "UEsDBBQACAAIAAAAAAAAAAAAAAAAAAAAAAAIAAAAb3JpZ2luYWyceFuTozqW9X/xc1WXJEx+6XwrLgJjIydCF6MvJiYAcRIjgUkb3zhR/30is7r6nJ7onjkxD47Q9pK0L95aXtLvi3I8iOZ0PhyHxcviChdfFrqcysXL7wv/+3+OTb94WWxzMG1z6FOuE3bwAioSnnOVZABz+omByTcwyTmfRUiCbE/2CmAn54mngN3yuD2QPfEyjj8/dBg9ZpKhdPCxRDbe7etbZjBNQ+XREPdMrG8aaEfybCMspjQUS25HJWZxkrY95n1y4f29q5g4FkZtdL+euaFUhNjSob41ofuUsYSUBi9ZP9I0hE8qwpGePZcNo5e+jb8w8XeMUCuWVI4e58lQgfFUSrwpH6ukhqNHxRgpMLoKUywA9DnXgUKQ5f1qEkE7NtHk8X7a+ya5VFF7qERyVpxiDqCf/Zu5mYTLEsCc7TXmwoZ/z9Op8R95UkwxM+sN4zbJjH3PuOsrNN3LaBrpbJ00TDzORZRx/JoBTHchJjm3fob09sOmHN8VcC9lf77lZsoKlMzlHJ5yUD/099Eyhj1l4IVKDnk/efkg/GwQjrAF2O3JpYwIYjN+L8PJb/zVLUPue92pQ8ltUMzhtQI4olgNgrWusFbxWN98q8t0UOsUjqBG5D0/rPJMZFdmU5eBaUtnfcrRdClDdRTWLrUMYRO111zgqWIK1iDZSWFHEZF9BdSUSrHO5rdNzuxVRfSVYTIXcFRF/zZr6Uo+KLCZidwg+hA9FE1grxyKbR1jopBya2RRyuGODKOfOuq+EzQqUXJsOj7TbDylMcUFLE5iTnaVoa3i6sjCyU27N0AN3bJYvSpMw7LDmMaEZdIem+jm1MDFuePBOnRhGWm3Yclc8tVdyPXJ7zNY8edrBpO+4HhLUT1Tpo40BHMdipEELSbsO1LhaErrFQKpdQ4J0lJDxu95Fa0f3Goj+lXH7QgboZcMvW1SjBMaYprx5ErC9sS4XZfhzx7jDokzgWnW6/cCKo8LHGZS44xDPw21lwphaKSpAInPDRRkLxIdjcvNbeQM2U4G4alyVJCK9p5aj1XD6MnPM5r4CgicCZukQHk5F2HW0W3GFckkpVlvPcqhxwX1WJgMzKo1Zy32TeIxTjwprENjrShWeYqpx/nbNTNYaIAdytfXxuA+6/VOmJYxLmIa4r0CCasH0Ul/dVX5ahL7t1tjViwHfJPi9iD48kZi2pYmEX9fm+9CwUWYpIyLScE1yow6lsC9qrDNNViNu1ipFIxz4RhIhN0TOZUy0rBArtBv414ABaXRkmCyJ8wrZThCKfSSo/VjxzyahgIJqCMtxlh0lImZ36RtN1rYfYPJIe3MjTMPa2HmfCAkY17sG8Jqrlku1zPFGGcfHMWxR0IbZAJ7NVxDFq0Bj4sHNdktR+cTiVZdyjVmyLVl3G5ZTKiOqNwF+FJbfspFsakCe6u75MoMNCVrzxrYaxWrtbTJuQrvhIRJSzjuuHlDkh+h6rmTyXFb5WdIJWUlau/C6mtqxWsV3fMMJYDfRqfiN5j6k63NyiuddtaYnHk/vZJ+vWwCnKYhfM3MhAijmAjb8Xy11072IOhuOFoj3k+44qNPHTU14eqQSdz7nXgqZn6vY8xqia+7Pb1UEVUFJ4cqFHQLx6lh2Uz7+5jvvTbthcj71XEX0ns+twfRPz8UIknq6ANn6UNjPe/2fKMdtS3ntq9mes4kPWaOPurDRPNY3Is9vwuD1U62mWDhjfTJTI0NhYRjaSlpotGrULLNeoMyNCUyULgw7lpk40Z3NGyslSy6hypI3DQkHo3oJTUFyll9a2IvyPolLBwMOdBQG3WoxfjOOZ1y3jpFp/dckGUh6ankOhdIdf4wShG5U8nb99ysdrkZkzrkD+1PEYPFXEbpaRc9u7tw9cQcuiv424OL0C07ZSozIR3aOAc6UtxlNP5+07bNGDIbLtt1ya2r+dpRQi83qH5o1J40Dh2CRVCHOuSwVZUR+9RJl3oWjtqPUgCLK7mCNdN3EicBlRNng9oQYLvqdgQpwIOQNGsMjvicPEk5AT3jYIPIQXCcMtbO1V4VhW0fMlz5jYHTJ9fLFshYpWyf3HgkjmlHpOrpRlns+533YF3iVyIJGBZ4F46v4jBd0+js7nBLKvY2V2B5qkJ9YgE+b1DrVug4V+h81/zjTCWzAKuOxvadITqnjgcKsNzkyE65uU9ppy8qGrsmpLvqsRozpgYlFckHETShyos9TjZIRAR/v5WWnJjUl8riu+wnxEIdad4Gem4tN/RYZeNBz2DlH35qG8rdcB0SzC1NqPk4uxT/1ERg89e1kYp/aiMd/0kb0dxAQuCYNCxhct8GWa+3BOqODvpSGrzLen2qZXsqee3q2fMzEd6o+eD2YvOHTqLyg+/pvs2l/cVt7abo3byKyERke6BmREVHcooxz6T40EJLth+9hkNO9y1pLF4yQ3dFNn5gT/+MiQ9sU3Do7+J2LUJ8+Mm7iccEjWh/PxY9zKtI4CoWhkLlFj2Maiim3V4Zyl3/Zw1I8q9zwpga7DFAPDW33qfeAWTIP2wgPIXWoIlWtDQJJWiFaX9eUt5K6phNuvdCKmEmnPomkHaIdIudSAgB9zQdWiocKzQX9w249ztOh9KfXsm8hoU4uhtIXtN+hes5c2jYrnXwdt8idVHZEbJOLRlSgA9JUMdmWYYaCLG+ZowcdD9euNTv9WN6UrhFBXh2C0ih3o9PHNOIO3TeIltmgpY1wA8tra1DuPQticvOslSqWDtKaSe9NtIWArhXZpIngilMBT3XgTdsZtHX/sqj0XhpohTRGO/KWTlpgKfcJmExvJ3IkJwz87wpuF2nA6UVHwuK1ZX29FFG0M9ne2dIvTdYn3Nh44a9zSJyH7qnhUYGVnzibE9vVCSYSe0ycy/ILEQ5eIjdxl0JxyEbFJbYo3U+DTuGnczo+YM/0oGoKtJQRtaveksVwBvm2FwLYkTcdnm/incxLUtwDzlORiKSqxZa+b1eynh9T5EwVYc5NzQu0POjjCajMRFZf//4XyfcUV6dT+s0ak81uj8JkF35YfJlNF12kh5TfxXS3l2KIQMS8w3h44EO1mwdshWH1YN2VDZS93q2c43e7tLYvYrxSdnjg4v2VXbJkAfUo1Jc2eHZ/VBbQnhOLTzZmNtNhqLMb+ODxOlDoFHsJMRkT9e1VTPnq3IXeE41KJVjO6ZmXBf97VbGa6hQOxOcJA0fnSZQKeXiUnYJaAyMlEyB6vTV7ylVgsxy8AZuxqmO1S2TKhdxe8xF8i5N8sid9sL2FihJvRKKTDnC53v9Lgy5kMeECz6Nea9ummWP3NRLJsFm81iZPDInziwvHuebxm+wDqfXfO9RJu+kCeFazy1R1puEHIMUYE8F9lwjGOhYuIW1V8WXj1wkphjGpwK1m9338ZyKEVbAzAq8OXVEEsXFWVnFakH8EhBPA+FlEu+4gXgX60DDj/vM+sY/7yfUU0DHjIdLCsK7kBRrIHz/sHL4h4bk0M9ksdSgpZ881nmvmUkU5WqrmViqw3Qkj6kUYcsZE0kFaa5iSlNIx3SPSWZwnEEyU4Ap5+uNQmMnzMeYfnIH4+GNgv9Zh4nBc/MO31k03rm5B+lMo1SIogTprIf2xm7jRXRqr5zx1pjwRLHYVagGkqm8xPRSBp5fI/vYAHOilp7TeIwyBJx88Ph2JjseWFn2Cpd7SkrQ2jKC6xLjrd+nTgGsLy2JSJdsSVA7DFLE4uNpJyeYmudrYTTX2KKdVJ62a5D18In2yuUhvWZ8ei3NyBRqw3T//UqAOG/mcKMEedc9EdkwppVJhI7b1y2ySuJkV83aTx/ney2fAe3Euun0g+MkzZknBKyvKRaesipgc9LTgbq0U0EqLZbZ8VozL1VR0qfQJgWHJ9UlewX0sbJvbsPfrrtwNebSvqfD+saw2uU4XaYMt3Vs3QKNtg5adwvcE53pPRVHtzRi9K3CMiAZMS5mQWuEQwsu76gK3ZhJ0lOczVUE/Y1DWTonAQ+F0IjYLUjOihWADAksUYK5TRzaq6WMVu91VGyyWY1aghOL6aaY9b0yZ9RIfZG8ADRQU9PR9WYm+2LfblSAWSrbmO/b1+LwPAuoHNIRII26sK540K64Vn0K1e2IRJABKdcOMxlqGLmInrgK3G+FxbN2UpTH5F0GBczQipVD8uDR8iZlu21C168RiQgAjg7vXDyeIQvPrpbtyR/sOzfklHeeKqS+KX5fKlvcqwCXuR1bgb1SW+NuHHvOI3efR+1TFYc3Ooxd3a+uHJK5DuhIAhpmH30Enh85zza7QJ/V3k6yn7ZCGMRDGBaMxiWgmybwDJ2pkCE9ciM4k8WJ9ZNSDk3zwyTy/UjYQE4aqrBw2lcSTZL507rMxqzs6mXRuwHZ2w/NlBFh3QqvAeF304T3JxY+o10sLhVsXxuunlIpAIXtU+2Mzi66f9zlUzaIg9y3JzLrKZ/btW/uNy3wtrDkkHOR1wjmG4jvnP01Hbb48WVhDoNevCzypj410+LLom+m8tdjVjkMx6mcDsfh/GHa49vbYXj7W1UOc3mo7fGi/3Y4ftPNb+XFTouXxa2c6rbRH9vWp+ZzITv0zXkq+3HxskAAwa8QfEXPDKxeHPdlidSHx3Io3xqND43V58XL//9Xz2u/fYLsMTaLl8XPmeKP7wX8CO+3l19x/23x8vuPL4vfXn69xv3+49OcPtd/Gj+dnhYvi7g8twf/eBoXXxbHsTl9hr14WfBRl1Oz+LKYDn3z76L/8eX/Hu2fK/3by3+r9T9S+HOx62P/zZbn6Ws5jvbQ6F9z/rcf5vcfP/4551+jv5Ix+ooQg87LcvWCHLX48R9fFkP5iX86+lqXX8em/3r+1UAf4Hks648Z5lI1X8+P89T0iy+LU3M+Xk5180e1nly4RBA8Lb4szo39bXsYzOJl8a0cD9+u8Ns/djp/+9NG3356On/71+4vh492rpbP/+8Jlujrc7l8/rpclk9fq6dl89V9Xi5R5ThwVZcfbfqzIxa7sXy/NIsf/xUAAP//UEsHCCmcjD+tDgAA2hUAAFBLAQIUABQACAAIAAAAAAApnIw/rQ4AANoVAAAIAAAAAAAAAAAAAAAAAAAAAABvcmlnaW5hbFBLBQYAAAAAAQABADYAAADjDgAAAAA=" -> null
              - "logging.banzaicloud.io/default" = "watched" -> null
            }
            name             = "cloud-ca-pem-secret"
            # (5 unchanged attributes hidden)
        }
    }

Plan: 0 to add, 3 to change, 0 to destroy.

─────────────────────────────────────────────────────────────────────────────

Note: You didn't use the -out option to save this plan, so Terraform can't
guarantee to take exactly these actions if you run "terraform apply" now.

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.postfix: Refreshing state... [id=postfix]

No changes. Your infrastructure matches the configuration.

Terraform has compared your real infrastructure against your configuration
and found no differences, so no changes are needed.
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-nginx-ingress]
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-nginx-ingress-api]
module.logging-operator.helm_release.logging-operator: Refreshing state... [id=logging-operator]
helm_release.logging-operator-pipeline: Refreshing state... [id=logging-pipeline-calico]

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
              - "banzaicloud.com/last-applied"   = "UEsDBBQACAAIAAAAAAAAAAAAAAAAAAAAAAAIAAAAb3JpZ2luYWyMeFuTozj+5Xfxc9W0BCYnnW/FRWBs5EToAtrY2ABEJUYCkza2MR393Tec1b29EzHzj3kggh9H0u8i6XCk31fleOTN+XI8Dau31Q2uvq1UOZWrt99X3o//Mzb96m21z8C0z6BHmIrp0fUJj1nGZJwCxMgXBiZPwzhjbOEB9tMc5xIgO2OxK4HZs6g94hy7KUNfDxlGl+p4KG10Ki0THfL6nmpEkkC6JEA95du7AsoWLN1xgwgJ+JqZUfKFn4VpT1kfX1k/dxXlp0LLneq3C9OE8AAZMtT3JnBeUhrjUqM17UeSBPBFhihUi+vQYXSTj/EvjP+JYWL4mojRZSweKjCeS4F25WMT13B0CR9DCUZHIoI4gB5jypcWpFm/mbjfjk04uayfck/H1ypsjxWPL5IRxAD00v/QNhVwXQKY0Vwhxk3wZ552jf7OkyCCqN7uKDNxqs1nyhxPWtNchtNIFmMnQewyxsOUofcUIHIIEM6Y8VJL7Z82YWiWwLmW/eWe6SktrHgpl+CcgfqhfoyGUuRKDa9EMMj6yc0G7qUDt7kpwCHH1zLEFl3QZxlMXuNt7qnlfNadPJbM+MUS3CqAQoLkwGnrcGMki9TdM6pMBrlN4AhqC39mx02W8vRGTeJQMO3Jos6ZNV3LQJ64MWslAtiE7S3jaKqohDWID4KbkYc4r4CcEsG36fKxy6i5yZC8U4SXAo6y6D8WJRzBBgl2CxY7izx4D3njmxuDfF9HCEtLOrVlrITBAx5GL7HlfOAkLK341HRsIel4TiKCClic+RIfKk1ayeSJBpOTdB+AaLKnkXyXiARlhxCJME2FOTXh3a6BgzLbhXXgwDJUTkPjpWSbmYvt2etTWLHXWwrjvmBoT6x6IVSeSACWOuAj9luE6Q9LBqMujVtwS24ziC0lFKRszqpw+2BGad5vOmZG2HC1ptbHLkEoJgEiKYtvOGjPlJltGfxaY8zGUcoRSXv1WUDpMo6CVCiUMuglgXITzjUJFeEg9piGHOc8VuG43t1HRi3TCT84V7b0E97OiXFpNYyu+NqjsScBRyk3cQKkmzEepB3Zp0ziVBCS9sYlDLqME5cG8UCN3DLaIk/HLmXYFdzYJFKSIJkliLiMfdxSjbgCyCZse2s06tNeHbhuKWU8IgHKJYhpPfBOeJubzDYTzz/ujd7QDLBdgtojZ+s7jkhb6pj/2Tc7BJzxIE4o45OEWyvV8lQC5yaDNlNgMx4iKRMwLoWtIeYmx2IqRahgYTlcfYw5BxIKrQRGOMfULUUwQsHVmlnbx4G6JAm4xaEKFR8j3hHKF3YXpt0pbvIG4WPS6TujLlJcL9mAcUrdyNOY1kzRTGwXghBKnxzFkIsD46ccuTXcQhpuAYuKB9HpPbMuZxxuuoQpRC3HlFG7pxEmKiTi4KNrbdg548Wu8s297uIb1VCXtL0oYG5VJLfCxJcqmDEO4hYz1DH9YQl2grJndirGfZVdIBGEllY7c6NuieHvVThnqRUDdh/tit1h4k2m1hu3tNtFIXxh/fSO++268VGSBPA91ZOFKUGYm45lm1zZ6QNbs2bW1mL9hCo2esSWUxNsjqlAvdfxl2Jhcx0hWgt0O+TkWoVEFgwfq4CTPRynhqYL6ecxy9026TnP+s3pEJA5W9oj718f0sJxYqsjo8lDIbUccrZTttyXS9tXC7mkgpxSW53UcSJZxOciZzPXSB5Em3Ia3HEfL0SbgAs4lobgJhzdyor3aa+t1Jpi4UtUaGfL03GnOhI0xggazoH0YycJsEtCck10YWW0vjeR66f9GhY2ggwoqLQ81nz8ZIxMGWvtolM543hdCHIumcq4JTtvGAUPnalk7WemN4dMj3EdsIfyppDCYinD5HwIX51DsHmhNjkU7OPBeOCUndSVniwVmCgDKpTMoST6cVemTamld0y025IZR7GtLbla76z6oaz2rFBgY8T9OlABg62sNM8TO1mrhdsyHwUHBlViA2uqZhzFPhETo4PcYWC66n4CCUADFyRtNArZEr8IMQG1IH9n4SNnKKG0XapcFoVpHyLYeI2G0xfXixaISCY0j+8s5Kekw0L2ZCcN8rzOfdAu9ioe+xRxdAjGd36cbkl4cQ6oxRX9WCqwPleBOlMfXXZW61TWaamsy6zYc0/FCwebjkTmk1pkSWwXFGC9yywzZXqekk5dZTh2TUAO1WMzplQOUkicDdxvApkVOYp3Fg8x+nEvDT5Toa6VQbPoJ4sGKlSs9dXSGqbJqUrHo1rAxjv+0jaEOcE2wIgZEhP93LsE/dJEYPffayMZ/dJGKvr/tBHJNMQYjnFDYyry1k97tcdQdWRQ11KjQ9qrcy3ac8lqRy2ul/LgTvST24vd3zqJiCffk7zNhPmL29pd0TtZFeIJi/ZI9GgVHc4IQiwV/KmF1jQf3YZBRvIWNwatqSaHIh2f2Mu/YvyJ7QoGvUPUbnmAjr94N3YpJyHp51PRw6wKOaoirgmUTtHDsIZ8OuRSE+Z4v2qA43+fE0JEI5cC7Mqldb/0DsBD9rQBd6W1BU24IaWOCbY2iPSXNWGtILbeJbkbEAFTbtd3bikbC6c48BhjMCfJ0BJuG64Yn3dg7g+MDKU3veNlCwt+cnYQvyf9BtVLapOg3Sr/Y95b8irTE6SdXFNLAjbEfh3pdRkowPn2llJ8VP14ZUJ91o/pRaLWKsCrU0ACVT6+MERCZpNlb5ky5aSsAXooYUwdwLVncFR2hiZCRsqWUtnJrRGm4MC5UR2/YERgwsml9t1ht/C+9jYuCcdrEyYWidChXKSd+GjKTBwUw8cZD/El1a+7gpltMhBSsbEgSN5ITx5lCL1sMTO15GeD1CXjJmrox8JD56F6UihLw4pNjObkTniMqFAO1XOBF87LwbXofTyUcBzSQSKBXFJn03CgyE61Wp78kQxYVqGCIjRe1RsiAdpR22SKY82jtsv6TXSISFmCOWAoHjGPb4or6fVqLaLtnFhcVx1iTJOosF4fZThphTBP+/n5X8fMlm6dTdskbM+1Nb9wkN7YcfJEOF0PgpwSbxOQ3lnzIQUCsR1m45EMRu9tvOfHzYN0RDRC9WoxS219zEKbXEboLM3pwXj7Lrp4yHziEsFv9PjqPNUW565dc1c0+n4XAS+z+/jAUfLg1sgPAiKck21t5MLYpjz4rl0NUmbIjIket0V/v5fRFkqrXTCK44aNduPLhDB+LbsYNBqGUiRAdurm9YRIjhcxuAPT41RH8p4KmfGoPWU8/hQ6fmR2e6W5AVIQt4Q8lTb3WK4+ucZX/JhQwaYx6+Vd0fSR6XpNBdjtHhudhfrMqGHF43JX6APWwfSe5S6hYsZNALdqabE07sTF6CcAudI3l9qCvoq4Uxhzk2z9yHisi2F8Kax2d/gxXhI+wgroRYIPuw5xLBm/SCNpzbFXAuwqwN1UoAPTEB0i5Sv4PM9s7+zrfEJcCVREWbAmIJi5IEgB7nnHjc2eGpJBLxXFWoGWfPFY576nOpaEyb2ifC2P0wk/ppIHLaOUxxUkmYwISSAZkxzhVKMohXghABHGtjtpjR3Xz3fyxR2UBXcC/mcdxgfXyTo003CcmZ79ZCFhwnlRgmRRQ3un9/HKO5lLe7w3OjgTxA+VVQNBZVYici1916st89gBfSaGXJJoDFML2Nngsv2CD8w3ouwlKnOCS9CaMoTbEqG91yd2AYwnDA5xF++xX9sUEotGp/NBTDDRr7dCK6aQsQ5CuspsQdrDF9JLhwXklrLpvdQjlVYbJPmPGwb8sluCneT4U/WYp8OYVDrmKmrf95aRAsWHalFe8rjMtXgFpOPbplMPhuIkoy7nsL4liLvSSJ8ucU8G4pBO+okwSKSnW03dRIZxn0ATFwyeZRfnEqhTZT6chn3cDsFmzIT5TIbtnSJ5yFCyTihq68g4hTWa2m+dPXDOZCFzwk9OqfnoGYmEj1OsHUT9VnObFEzMVhU4ERW4JyhdqhB6O5vQZIl9FnCuLGz2IL5IWgA8xLC0YsRMbJNerkW4+azDYpcuclQCnGlEdsWi5kpfrEaoq2AFIL6cmo5sdwvOi7zdSR/RRLQRy9v34vi6cCht3GEgtLzSrniQrrhVfQLl/WRxPwVCbG2qU6uh+Mp77Egw3wuDFmUnVhbhT+EXMLU2tBziBwvXdyHafRM4Xm3hEANgq2Bm/PEKaXBxlGjP3mA+mcbnrHNlIdRdsnktTTFXPiozM7YcuaUy2tnZ5pKFTp6F7UsVBXcyjF3db24M4qX2yYh9EqTPdQReHxlLdwdfXWRuJtFPe861xQIYFJREJSC7xnc1WQgXATkxzRkVxZn2k5Q2SbLjxLN8xHTAZwVlUNjtOw4nQb1pW6ZjWnb1uugdH+fmqZlSzI1ToS3AbNZNML/Q4NU6RPxawfa9YfIlERwQ2L7U9mgfwvl5lk/owI8ib894UVO2tFtPz3fF0b4w+JgxntUWzHYQzYz+dzps9ce3lT4OavW2ypr63Eyrb6u+mcq/LrPKYThN5XQ8DZenaU4fH8fh4x9VOSzlsTanq/rH8fSban6WVzOt3lb3cqrbRj2Hrc/NV0d67JvLVPbj6m1lAQt+h+C79UrB5m3tvAEonx7LofxoFDo2Rl1Wb//r312v/fwC6WNsVm+rXy353985fIb38+2vuP+xevv9j2+rn29/3cb9/seXOX31/zJ+OT2v3lZReWmP3uk8rr6tTmNz/gp79bZioyqnZvVtNR375j9F/8f//rYayi+8uXyvy+9j03+//FXLJ3IZy/oJH4ef5/L7nyVcfVudm8vpeq6bvxN9cSxo22Cz+ra6NObn/jjo1dvqt3I8/naDv/2/sS6//ctQv/3ydvnt3/i/Hp9Tu7GbqlmXL9/X/4TO9/XLq/X9Vf2E3227Kpt/2q9K2eA5Zb+qszqM5ee1Wf3xfwMAAP//UEsHCFeE1txrDgAA5hQAAFBLAQIUABQACAAIAAAAAABXhNbcaw4AAOYUAAAIAAAAAAAAAAAAAAAAAAAAAABvcmlnaW5hbFBLBQYAAAAAAQABADYAAAChDgAAAAA=" -> null
              - "logging.banzaicloud.io/default" = "watched" -> null
            }
            name             = "es-ca-pem-secret"
            # (5 unchanged attributes hidden)
        }
    }

Plan: 0 to add, 1 to change, 0 to destroy.
