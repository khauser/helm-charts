
<a name="icm-as-3.0.0"></a>
## [icm-as-3.0.0](https://github.com/khauser/helm-charts/compare/icm-as-2.0.0...icm-as-3.0.0)

> 2023-11-22

### Chore

* generated changelog for icm-as:major icm-job:patch icm-replication:patch icm-web:patch
* bump versions of icm-as:major icm-job:patch icm-replication:patch icm-web:patch

### Feat

* my test file
* adfasdf


<a name="icm-as-2.0.0"></a>
## [icm-as-2.0.0](https://github.com/khauser/helm-charts/compare/icm-as-1.5.0...icm-as-2.0.0)

> 2023-11-20

### Chore

* bump versions icm-as:major icm-job:minor and dependent charts


<a name="icm-as-1.5.0"></a>
## [icm-as-1.5.0](https://github.com/khauser/helm-charts/compare/icm-as-1.4.0...icm-as-1.5.0)

> 2023-11-15

### Chore

* bump versions icm-as:minor and dependent charts

### Feat

* kube_ping with labels ([#450](https://github.com/khauser/helm-charts/issues/450)) * fix creation of service account and according roles * fix: service account name * roles and bindings are created only once with the service account

### Fix

* can't enable job server without deploying controller ([#448](https://github.com/khauser/helm-charts/issues/448)) ([#449](https://github.com/khauser/helm-charts/issues/449))


<a name="icm-as-1.4.0"></a>
## [icm-as-1.4.0](https://github.com/khauser/helm-charts/compare/icm-as-0.2.8...icm-as-1.4.0)

> 2023-11-01

### Chore

* bump versions icm-as:minor and dependent charts

### Ci

* automate release process ([#393](https://github.com/khauser/helm-charts/issues/393)) ([#395](https://github.com/khauser/helm-charts/issues/395))
* automate release process ([#393](https://github.com/khauser/helm-charts/issues/393)) ([#395](https://github.com/khauser/helm-charts/issues/395))

### Feat

* support secrets store csi v1  ([#384](https://github.com/khauser/helm-charts/issues/384)) ([#400](https://github.com/khauser/helm-charts/issues/400))
* provide prometheus endpoints ([#377](https://github.com/khauser/helm-charts/issues/377)) ([#378](https://github.com/khauser/helm-charts/issues/378))
* add NewRelic Integration ([#333](https://github.com/khauser/helm-charts/issues/333))
* update helm unittest plugin ([#318](https://github.com/khauser/helm-charts/issues/318))
* enable/disable recreation of database ([#201](https://github.com/khauser/helm-charts/issues/201))
* no appServer.enable needed ([#116](https://github.com/khauser/helm-charts/issues/116))
* cluster persistence owner shall be 150 (intershop) ([#116](https://github.com/khauser/helm-charts/issues/116))
* set release versions ([#91](https://github.com/khauser/helm-charts/issues/91))
* **icm:** redis configuration ([#335](https://github.com/khauser/helm-charts/issues/335)) ([#349](https://github.com/khauser/helm-charts/issues/349))

### Fix

* build via new commit ([#310](https://github.com/khauser/helm-charts/issues/310))
* use securityGroup configuration for azure file ([#310](https://github.com/khauser/helm-charts/issues/310))
* remove comment sign ([#115](https://github.com/khauser/helm-charts/issues/115))
* relication configmap ([#106](https://github.com/khauser/helm-charts/issues/106)) ([#107](https://github.com/khauser/helm-charts/issues/107))
* fix lint test for icm-charts ([#99](https://github.com/khauser/helm-charts/issues/99))
* **icm:** reenable weblayer ([#295](https://github.com/khauser/helm-charts/issues/295)) ([#297](https://github.com/khauser/helm-charts/issues/297))

### ICM

* Remove ICM cluster ID ([#50](https://github.com/khauser/helm-charts/issues/50))


<a name="icm-as-0.2.8"></a>
## [icm-as-0.2.8](https://github.com/khauser/helm-charts/compare/icm-as-0.2.6...icm-as-0.2.8)

> 2022-05-10

### Feat

* Add umbrella chart icm ([#11](https://github.com/khauser/helm-charts/issues/11)) ([#13](https://github.com/khauser/helm-charts/issues/13))
* Add icm related helm charts to public helm chart repo ([#10](https://github.com/khauser/helm-charts/issues/10))

### ICM

* Fix startup probe ([#38](https://github.com/khauser/helm-charts/issues/38))


<a name="icm-as-0.2.6"></a>
## icm-as-0.2.6

> 2022-03-31

