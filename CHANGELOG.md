## Release notes engine v1.199.2   
### Bug fixes   
* [03660c7a571b306822b1ffed7678d29c4e717572](https://github.com/Qovery/engine/commit/03660c7a571b306822b1ffed7678d29c4e717572): fix(keda): remove hard-coded aws annotations  (Pierre Gerbelot)
## Release notes engine v1.199.1   
### Others   
* [38295f50fcb2e44605ecab16785369bdaba4fb62](https://github.com/Qovery/engine/commit/38295f50fcb2e44605ecab16785369bdaba4fb62): feat(QOV-1593): nginx to be spread across several nodes  (benjaminch)
## Release notes engine v1.199.0   
### Others   
* [38295f50fcb2e44605ecab16785369bdaba4fb62](https://github.com/Qovery/engine/commit/38295f50fcb2e44605ecab16785369bdaba4fb62): feat(QOV-1593): nginx to be spread across several nodes  (benjaminch)
## Release notes engine v1.198.1   
### Bug fixes   
* [00f6d24ecc5e639255a1cfcfd49ecb219b60cceb](https://github.com/Qovery/engine/commit/00f6d24ecc5e639255a1cfcfd49ecb219b60cceb): fix: use 0.40.1 image version for thanos to be able to connect to mexico region  (Pierre Gerbelot)
## Release notes engine v1.198.0   
### Features   
* [16227c8308412a7be815cd9b99f84cb1ac02388a](https://github.com/Qovery/engine/commit/16227c8308412a7be815cd9b99f84cb1ac02388a): feat(tags): propagate tag to nodes started by Karpenter  (Pierre Gerbelot)
## Release notes engine v1.197.0   
### Others   
* [59961a88c109ea1bc1ad862a42351181ae4edaf0](https://github.com/Qovery/engine/commit/59961a88c109ea1bc1ad862a42351181ae4edaf0): feat(QOV-1563): allow to customize dns ndots config in services  (benjaminch)
## Release notes engine v1.196.0   
### Others   
* [5b96620056cd891169eefe9e55084416f53a416c](https://github.com/Qovery/engine/commit/5b96620056cd891169eefe9e55084416f53a416c): feat(QOV-1583): configure Bottlerocket settings for karpenter nodegroup with max-pods  (Guillaume Dubroeucq)
## Release notes engine v1.195.0   
### Features   
* [6e17e5967c349165597665afae9d2a67f3affef0](https://github.com/Qovery/engine/commit/6e17e5967c349165597665afae9d2a67f3affef0): feat(EKS): add gp3 to karpenter nodegroup  (Guillaume Dubroeucq)
## Release notes engine v1.194.0   
### Others   
* [490e81689225f8592e4a8cbcf93da96d24ef1953](https://github.com/Qovery/engine/commit/490e81689225f8592e4a8cbcf93da96d24ef1953): Revert "feat(QOV-1583): update karpenter nodegroup max-pods and gp3"  (Guillaume Dubroeucq)
## Release notes engine v1.193.0   
### Features   
* [6545f5123f160ffe9b34dc63ee0e9484c82e250d](https://github.com/Qovery/engine/commit/6545f5123f160ffe9b34dc63ee0e9484c82e250d): feat(tags): allow to add custom tag to AWS resources  (Pierre Gerbelot)
   
### Others   
* [f8e05166ef3524f8ed2f23ee4f68d47485792faa](https://github.com/Qovery/engine/commit/f8e05166ef3524f8ed2f23ee4f68d47485792faa): feat(QOV-1525): add support for Pod Identity addon in EKS  (Guillaume Dubroeucq)
## Release notes engine v1.192.0   
### Others   
* [d8be7cb83807f4d7993c552d14100869cfff0390](https://github.com/Qovery/engine/commit/d8be7cb83807f4d7993c552d14100869cfff0390): feat(QOV-1583): update karpenter nodegroup max-pods and gp3  (Guillaume Dubroeucq)
## Release notes engine v1.191.0   
### Others   
* [a02edac8c590cf032d9414806462128a1c01d03b](https://github.com/Qovery/engine/commit/a02edac8c590cf032d9414806462128a1c01d03b): feat(QOV-1509): Scaleway to support Gateway API stack  (benjaminch)
   
* [b57acd38698d0dc63a22a7ff707276dcc9421862](https://github.com/Qovery/engine/commit/b57acd38698d0dc63a22a7ff707276dcc9421862): feat(gateway-api): Introduce proper structs for load-balancers  (benjaminch)
   
* [8b16d57ec4d2532fe0a21d3cc87b8594c1d37747](https://github.com/Qovery/engine/commit/8b16d57ec4d2532fe0a21d3cc87b8594c1d37747): fix(QOV-1556): envoy add HPA on gateways  (benjaminch)
   
* [0c7fbae81fc6b17a51760a108e48c1e5d6d1a663](https://github.com/Qovery/engine/commit/0c7fbae81fc6b17a51760a108e48c1e5d6d1a663): fix(QOV-1556): envoy add HPA on gateways  (benjaminch)
## Release notes engine v1.190.0   
### Bug fixes   
* [500420e9b748b719c834bb68a0c22ec05046f410](https://github.com/Qovery/engine/commit/500420e9b748b719c834bb68a0c22ec05046f410): fix(obs): remove secrets and configmaps from kube-state-metrics scraping  (Pierre Gerbelot)
   
### Others   
* [c0ca0a3f0edc58f3003c8e5d436ddb04832ea307](https://github.com/Qovery/engine/commit/c0ca0a3f0edc58f3003c8e5d436ddb04832ea307): feat(QOV-1556): envoy add HPA on gateways  (benjaminch)
## Release notes engine v1.189.1   
### Bug fixes   
* [a2b39dc672e30d3e0e61f96fc55cc9d330be8d68](https://github.com/Qovery/engine/commit/a2b39dc672e30d3e0e61f96fc55cc9d330be8d68): fix: force lowercase for Docker registry URLs  (Guillaume Da Silva)
## Release notes engine v1.189.0   
### Features   
* [3fd1830f7c8dad14b661998158941ad6c6cedc28](https://github.com/Qovery/engine/commit/3fd1830f7c8dad14b661998158941ad6c6cedc28): feat: add http metric for for envoy  (Pierre Gerbelot)
## Release notes engine v1.188.1   
### Bug fixes   
* [20767fe0c5d4ccda1595ca3e86483bb288ace4ee](https://github.com/Qovery/engine/commit/20767fe0c5d4ccda1595ca3e86483bb288ace4ee): fix(helm): remove secrets from helm error  (Σrebe - Romain GERARD)
## Release notes engine v1.188.0   
### Others   
* [ef6c00c8800e4ec23c293e8688671cd61877bb39](https://github.com/Qovery/engine/commit/ef6c00c8800e4ec23c293e8688671cd61877bb39): feat(QOV-1507): GCP to support Gateway API stack  (benjaminch)
   
* [747642296e29f4125643d17984e75fb056f0d6cc](https://github.com/Qovery/engine/commit/747642296e29f4125643d17984e75fb056f0d6cc): fix(secrets) Add raw json into secrets so it is obfuscated  (Antoine Promerova)
## Release notes engine v1.187.1   
### Others   
* [b80089be0bc5dbc01296898219329642ba57d566](https://github.com/Qovery/engine/commit/b80089be0bc5dbc01296898219329642ba57d566): fix(alert-config): provide namespace  (Pierre Gerbelot)
## Release notes engine v1.187.0   
### Features   
* [a6df23afa11bcfdeb292da73f9d7a340b50fe5cf](https://github.com/Qovery/engine/commit/a6df23afa11bcfdeb292da73f9d7a340b50fe5cf): feat: Add apply_immediately field for managed databases  (Guillaume Da Silva)
   
### Bug fixes   
* [4a92dc54b145403fc88a62c399bbfb31a721234c](https://github.com/Qovery/engine/commit/4a92dc54b145403fc88a62c399bbfb31a721234c): fix: deploy alert manager config for gcp and azure cluster  (Pierre Gerbelot)
   
### Internal changes   
* [61c92ebccc71fd52486a76b454abb0fb6a9a4ec7](https://github.com/Qovery/engine/commit/61c92ebccc71fd52486a76b454abb0fb6a9a4ec7): chore: remove deps  (Σrebe - Romain GERARD)
   
* [593b20ab6d5797404261a31773f0f75caf7a95a8](https://github.com/Qovery/engine/commit/593b20ab6d5797404261a31773f0f75caf7a95a8): chore: remove vault completly  (Σrebe - Romain GERARD)
   
### Tests   
* [2022c08fae57e6cd3a1f4e369ad29d342050cbd0](https://github.com/Qovery/engine/commit/2022c08fae57e6cd3a1f4e369ad29d342050cbd0): tests(azure): update test cluster kubeconfig secret  (benjaminch)
   
### Others   
* [3d32789203ef54b2b7f8719bc58fd1b59d645d6b](https://github.com/Qovery/engine/commit/3d32789203ef54b2b7f8719bc58fd1b59d645d6b): feat(QOV-997): implement helm chart deployment with automatic retry for transient errors  (Guillaume Dubroeucq)
## Release notes engine v1.186.0   
### Others   
* [2d79076902f580bccb87fb316523d310899db317](https://github.com/Qovery/engine/commit/2d79076902f580bccb87fb316523d310899db317): feat(QOV-1508): Azure to support Gateway API stack  (benjaminch)
## Release notes engine v1.185.0   
### Features   
* [a57fba83192059c43c684aba36952bdd30493f52](https://github.com/Qovery/engine/commit/a57fba83192059c43c684aba36952bdd30493f52): feat: improve AWS network resources naming with clear tags  (Guillaume Da Silva)
## Release notes engine v1.184.1   
### Bug fixes   
* [e9c4d6ff7727526907b90983edf5c1b8c9b72f41](https://github.com/Qovery/engine/commit/e9c4d6ff7727526907b90983edf5c1b8c9b72f41): fix(job): restore force_trigger for lifecycle jobs  (Fabien FLEUREAU)
## Release notes engine v1.184.0   
### Features   
* [b530cb274029e66b2b25e05604b6f50e4ec1ba16](https://github.com/Qovery/engine/commit/b530cb274029e66b2b25e05604b6f50e4ec1ba16): feat(keda): add GCP support  (Pierre Gerbelot)
## Release notes engine v1.183.0   
### Features   
* [a87ab9fcd9f171824cea11ad7bf2afadf0ab6d7b](https://github.com/Qovery/engine/commit/a87ab9fcd9f171824cea11ad7bf2afadf0ab6d7b): feat: add disk IOPS and throughput support for AWS EBS gp3 volumes  (Guillaume Da Silva)
## Release notes engine v1.182.1   
### Others   
* [841d2976bf106cf435f298a79fc6f9498117d06f](https://github.com/Qovery/engine/commit/841d2976bf106cf435f298a79fc6f9498117d06f): fix(QOV-1540): prevent Beyla DaemonSet from running on AWS nodegroups  (Pierre Gerbelot)
## Release notes engine v1.182.0   
### Features   
* [b402b3481043e3920e3d9bc03b55f56a4b177546](https://github.com/Qovery/engine/commit/b402b3481043e3920e3d9bc03b55f56a4b177546): feat(alert): improve email template for alertnotification  (Pierre Gerbelot)
   
### Others   
* [00cb613a025aa74906ad5ed0d2cdfe29c736b676](https://github.com/Qovery/engine/commit/00cb613a025aa74906ad5ed0d2cdfe29c736b676): chore(QOV-1400): allow to retrieve envoy gateway logs  (benjaminch)
## Release notes engine v1.181.0   
### Others   
* [e6b6b91cfadbc4aa265466752051622b42a25dea](https://github.com/Qovery/engine/commit/e6b6b91cfadbc4aa265466752051622b42a25dea): feat(QOV-1537): change karpenter priority class to system-node-critical  (Guillaume Dubroeucq)
## Release notes engine v1.180.1   
### Others   
* [45725ab28d3840c9cd5519945355eeeae70009c3](https://github.com/Qovery/engine/commit/45725ab28d3840c9cd5519945355eeeae70009c3): fix(QOV-1532): reduce CPU resource requests to 100m in karpenter.yaml  (Guillaume Dubroeucq)
   
* [8ed47584fa5461c557305383bc2084cc7ea4db90](https://github.com/Qovery/engine/commit/8ed47584fa5461c557305383bc2084cc7ea4db90): fix(QOV-1532): remove c6g.medium instance type from karpenter nodegroup  (Guillaume Dubroeucq)
## Release notes engine v1.180.0   
### Others   
* [3eb54afa966fe9783ff6bfe1eb7bfa3f3ec705a5](https://github.com/Qovery/engine/commit/3eb54afa966fe9783ff6bfe1eb7bfa3f3ec705a5): feat(QOV-1532): add instance type to karpenter nodegroup  (Guillaume Dubroeucq)
## Release notes engine v1.179.0   
### Features   
* [9a91c5274ff45c9f1644d108f4f6966706abc7e9](https://github.com/Qovery/engine/commit/9a91c5274ff45c9f1644d108f4f6966706abc7e9): feat(alert): add support for email receveir  (Pierre Gerbelot)
## Release notes engine v1.178.0   
### Features   
* [9a81d3c47057838da0218e98cdc06de4bd873bb5](https://github.com/Qovery/engine/commit/9a81d3c47057838da0218e98cdc06de4bd873bb5): feat(keda): allow 0 instance when keda is enabled  (Pierre Gerbelot)
   
### Internal changes   
* [f132e64a8205addd3d3a6b36fb63620a3c71fb3c](https://github.com/Qovery/engine/commit/f132e64a8205addd3d3a6b36fb63620a3c71fb3c): chore: improve payload parsing error  (benjaminch)
## Release notes engine v1.177.1   
### Bug fixes   
* [97d3511f2218cd3688b45004d13e14181b18ca39](https://github.com/Qovery/engine/commit/97d3511f2218cd3688b45004d13e14181b18ca39): fix: resolve terraform service deployment freeze deadlock (QOV-1444)  (Fabien FLEUREAU)
## Release notes engine v1.177.0   
### Features   
* [42f9b01a84645a82adf67748d2f9aa594492bd58](https://github.com/Qovery/engine/commit/42f9b01a84645a82adf67748d2f9aa594492bd58): feat: support terraform resource extraction from deployments [QOV-1444]  (Fabien FLEUREAU)
## Release notes engine v1.176.0   
### Features   
* [f907b99cb72e96e1f1036a40a8164b3e60c47fe8](https://github.com/Qovery/engine/commit/f907b99cb72e96e1f1036a40a8164b3e60c47fe8): feat(keda): add autoscaling support with secret reference transformation  (Pierre Gerbelot)
## Release notes engine v1.175.1   
### Others   
* [9b32d60d701f098a068fc10e7ebe412f47e6842b](https://github.com/Qovery/engine/commit/9b32d60d701f098a068fc10e7ebe412f47e6842b): chore(external-dns): prevent args source order from changing  (benjaminch)
## Release notes engine v1.175.0   
### Features   
* [e5c70819092f63aff3ccbf43702dc9cc5e0b052b](https://github.com/Qovery/engine/commit/e5c70819092f63aff3ccbf43702dc9cc5e0b052b): feat(keda): add fallback parameter in the ScaledObject  (Pierre Gerbelot)
## Release notes engine v1.174.0   
### Features   
* [0249bd7661c81bff8ab592918b7482de0c91c099](https://github.com/Qovery/engine/commit/0249bd7661c81bff8ab592918b7482de0c91c099): feat(keda): add keda profile and manage service monitor  (Pierre Gerbelot)
## Release notes engine v1.173.1   
### Bug fixes   
* [1861c8073c367ae075bd15555599bb11eec866d6](https://github.com/Qovery/engine/commit/1861c8073c367ae075bd15555599bb11eec866d6): fix(helm): shorten rollback timeout when unlocking a release  (Σrebe - Romain GERARD)
   
* [9f3e150f771c1516559ef0de932b912628179d57](https://github.com/Qovery/engine/commit/9f3e150f771c1516559ef0de932b912628179d57): fix(terraform): fix karpenter nodegroup lifecycle  (Guillaume Dubroeucq)
## Release notes engine v1.173.0   
### Others   
* [8d1f193c43d1cf18c1d0f0b3cd0e02ea969bce8b](https://github.com/Qovery/engine/commit/8d1f193c43d1cf18c1d0f0b3cd0e02ea969bce8b): chore(QOV-1400): add whole enchilada tests for EKS gateway API  (bchastanier)
   
* [ae52095234f89dc5dcc07cb2785a3981b8d6674d](https://github.com/Qovery/engine/commit/ae52095234f89dc5dcc07cb2785a3981b8d6674d): chore(QOV-1488): introduce cluster profile adv setting for coredns addon  (bchastanier)
   
* [424956bb94718569ebbc65f11573dd6e3f7339dc](https://github.com/Qovery/engine/commit/424956bb94718569ebbc65f11573dd6e3f7339dc): feat(QOV-1400): add cluster adv setting for compression  (bchastanier)
   
* [be4b20d36a3950b547d4105ee09d610e7771f105](https://github.com/Qovery/engine/commit/be4b20d36a3950b547d4105ee09d610e7771f105): feat(QOV-1400): add cluster adv setting for custom_http_errors  (bchastanier)
   
* [30dc55ed0d2572cc531002e69ab4e07f88780da5](https://github.com/Qovery/engine/commit/30dc55ed0d2572cc531002e69ab4e07f88780da5): feat(QOV-1400): add cluster adv setting for default backend  (bchastanier)
   
* [96fc194ab6f7ed44a1204f7ccf070eef9ace4413](https://github.com/Qovery/engine/commit/96fc194ab6f7ed44a1204f7ccf070eef9ace4413): feat(QOV-1400): add cluster adv setting for num of trusted hops  (bchastanier)
   
* [d1da712fafbd23adbbe298187c6eebf3d7994408](https://github.com/Qovery/engine/commit/d1da712fafbd23adbbe298187c6eebf3d7994408): feat(QOV-1400): add service adv setting for circuit breaker  (bchastanier)
   
* [b488498dd189dd94fd9764cf4522d083f259af64](https://github.com/Qovery/engine/commit/b488498dd189dd94fd9764cf4522d083f259af64): feat(QOV-1400): add service adv setting for custom_http_errors  (bchastanier)
   
* [b59dfeedfb5fe6957e57da10634dac5dca446fa4](https://github.com/Qovery/engine/commit/b59dfeedfb5fe6957e57da10634dac5dca446fa4): feat(QOV-1400): add service adv setting for envoy access log format  (bchastanier)
   
* [5627e6e0ba30d6135438939a385502efb939725a](https://github.com/Qovery/engine/commit/5627e6e0ba30d6135438939a385502efb939725a): feat(QOV-1400): fix envoy cluster adv settings  (bchastanier)
## Release notes engine v1.172.0   
### Features   
* [ad001179a62a9a3a18dcbbc5d183193cb3ed0fae](https://github.com/Qovery/engine/commit/ad001179a62a9a3a18dcbbc5d183193cb3ed0fae): feat(keda): allow cluster agent to retried with Keda ScaledOject  (Pierre Gerbelot)
## Release notes engine v1.171.2   
### Bug fixes   
* [cb8c620ac30bf052101a88913987820321221e02](https://github.com/Qovery/engine/commit/cb8c620ac30bf052101a88913987820321221e02): fix(keda): allow raw_yaml to define trigger-level fields in scalers  (Pierre Gerbelot)
   
### Internal changes   
* [f81127fea98b6ff4bc6c82b15f9e3e77658bca1c](https://github.com/Qovery/engine/commit/f81127fea98b6ff4bc6c82b15f9e3e77658bca1c): chore(ci): Use precedent changelog  (Σrebe - Romain GERARD)
## Release notes engine v1.171.1   
### Bug fixes   
* [7db9564b064939801b634f157660fc94cd24f28f](https://github.com/Qovery/engine/commit/7db9564b064939801b634f157660fc94cd24f28f): fix(keda): ensure TriggerAuthentication is created before ScaledObject  (Pierre Gerbelot)
## Changelog   
### Internal changes   
* 0f28943d5dc0beb3dd6ed14035ebf7798423ebf1 chore(ci): bump for changelog
## Changelog   
### Internal changes   
* 9ff33121f0ce8d902c89df55c557f624f57d0fcd chore(ci): update goreleaser
## Changelog   
### Internal changes   
* 67bed130c419cb1af5c2bf7a5e9bd2fe516eadd4 chore: reset changelog
