# Mikroservisler:

## MariaDB:

İmaj sahibi: bitnami
İmaj ismi: mariadb
İmaj versiyonu: 10.4

Volume mount path: /bitnami/mariadb

## Magento:

İmaj sahibi: bitnami
İmaj ismi: magento
İmaj versiyonu: 2

Volume mount path: /bitnami/magento

### Portlar: 

LocalPort1: 80
ContainerPort1: 8080

LocalPort2: 443
ContainerPort2: 8443

## Elasticsearch:

İmaj sahibi: bitnami
İmaj ismi: elasticsearch
İmaj versiyonu: 7

Volume mount path: /bitnami/elasticsearch

### Not: Her bir servisin kendine ait bir volume’a sahip olması gerekmektedir. Bu nedenle belirlediğiniz volume isimlerini Yaml dosyasının en sonunda “volumes:” başlığı altında belirtmeyi unutmayınız.