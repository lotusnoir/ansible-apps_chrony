# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.2.0](https://github.com/lotusnoir/ansible-apps_chrony/compare/4.1.0...4.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`bcbff13`](https://github.com/lotusnoir/ansible-apps_chrony/commit/bcbff13a9bb288eca68038fa312f9b305add2b25)

## [4.1.0](https://github.com/lotusnoir/ansible-apps_chrony/compare/4.0.0...4.1.0) - 2025-11-17

### Commits

- update core and molecule [`4d554d5`](https://github.com/lotusnoir/ansible-apps_chrony/commit/4d554d5af34fd2dd039a654d84052efc84b2b56b)
- add oraclelinux10 support + lint and core fixes [`c045c02`](https://github.com/lotusnoir/ansible-apps_chrony/commit/c045c029f686b8544d8bbef27e3d92394e4ee32e)

## [4.0.0](https://github.com/lotusnoir/ansible-apps_chrony/compare/3.3.0...4.0.0) - 2025-10-30

### Commits

- update core [`ae1a657`](https://github.com/lotusnoir/ansible-apps_chrony/commit/ae1a6577174df06112ed9c2cc4b9ac7d9e5de8c7)
- update core, molecule + gitlab-ci [`414b284`](https://github.com/lotusnoir/ansible-apps_chrony/commit/414b2842743557e08d873e724f9074a403a6efc4)
- fix linting [`7db0a3a`](https://github.com/lotusnoir/ansible-apps_chrony/commit/7db0a3ab2b989b3e0394d500cfbe75852521896e)
- update molecule [`81e0673`](https://github.com/lotusnoir/ansible-apps_chrony/commit/81e0673205ed431e5b868d9e4e66150e4a3de5b8)
- changes on molecule [`50f551b`](https://github.com/lotusnoir/ansible-apps_chrony/commit/50f551b96f00fa202e75d9eacd56b4d710f5ad8d)
- add variables [`80de045`](https://github.com/lotusnoir/ansible-apps_chrony/commit/80de045aacdc2490a68608b792f5c898a0bc7ab9)
- add variables [`e78d261`](https://github.com/lotusnoir/ansible-apps_chrony/commit/e78d261d8161b832ad4e8aa859f7007d2fe5f9f5)
- speed up deploy + add molecule vars [`631f8a4`](https://github.com/lotusnoir/ansible-apps_chrony/commit/631f8a4195206c93a5c319968f9795a18760fd86)
- add feature to wite log as adm user instead of root [`82c3bc0`](https://github.com/lotusnoir/ansible-apps_chrony/commit/82c3bc02d77f553fc6f238f75af32d5bea7c172d)
- fix lint [`1fccc8c`](https://github.com/lotusnoir/ansible-apps_chrony/commit/1fccc8cc019b294db5c840fc8e13e2a2359e18c1)

## [3.1.0](https://github.com/lotusnoir/ansible-apps_chrony/compare/3.0.0...3.1.0) - 2025-02-28

### Commits

- fix linting [`62bde04`](https://github.com/lotusnoir/ansible-apps_chrony/commit/62bde04f16b4bc931195f8ee89cac0f5e5b260f1)
- update pre-commint and lint [`88fc488`](https://github.com/lotusnoir/ansible-apps_chrony/commit/88fc488d79c3144575666a05cb3b76f0e64e40c2)
- add support for ubuntu24 [`5a9e7c9`](https://github.com/lotusnoir/ansible-apps_chrony/commit/5a9e7c9e95e17adc96d3aee5a365d0f985c689a9)
- add version on molecule play image to maintain support on old release [`9f7e0e5`](https://github.com/lotusnoir/ansible-apps_chrony/commit/9f7e0e52c319fae48e5185fbd0495740fd181e34)
- update yamllint [`2a9a539`](https://github.com/lotusnoir/ansible-apps_chrony/commit/2a9a539950a354f9716baa25e0f40d772e2468ae)
- remove support for debian10 / ubuntu18 / redhat8 [`a36628c`](https://github.com/lotusnoir/ansible-apps_chrony/commit/a36628c90fcfe1360484309dfe74618a8d3cbf2a)
- update molecule [`8f9f039`](https://github.com/lotusnoir/ansible-apps_chrony/commit/8f9f0396b982ddc264ee306adb72952f29045082)
- change default config [`21fc846`](https://github.com/lotusnoir/ansible-apps_chrony/commit/21fc84630b4779b9a1c850f361570ee40f584138)
- feature add daemon opts change [`2391cb8`](https://github.com/lotusnoir/ansible-apps_chrony/commit/2391cb82bab974dc3a5dcd3bc69cfc1950804cff)
- remove update cache [`c1e856a`](https://github.com/lotusnoir/ansible-apps_chrony/commit/c1e856a7c123f182c1238dbdb919c4178d8f1882)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_chrony/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`55c718a`](https://github.com/lotusnoir/ansible-apps_chrony/commit/55c718a8fecbd30b251a51e2b4b5255227d4fc81)
- update readme + precommit + include vars [`40f078c`](https://github.com/lotusnoir/ansible-apps_chrony/commit/40f078ce213c466e4565222a07fe572acddec901)
- better mode view + ansible comment on template file [`d156f7a`](https://github.com/lotusnoir/ansible-apps_chrony/commit/d156f7ae0bb58fe3ca7cc23fbbc34f964ec59158)
- update molecule playbook order and main include vars [`d3f6ea1`](https://github.com/lotusnoir/ansible-apps_chrony/commit/d3f6ea134c528f7c7acad41e45cd7d215f986ee0)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_chrony/compare/0.1.0...1.0.0) - 2023-06-14

### Commits

- add debian12 support [`318caf5`](https://github.com/lotusnoir/ansible-apps_chrony/commit/318caf559f532042b448bf493b5aaacbdf7f2b33)
- add galaxy id [`f40d57a`](https://github.com/lotusnoir/ansible-apps_chrony/commit/f40d57ab20ac1772098030c99167691e83aa0fad)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`c9b92e0`](https://github.com/lotusnoir/ansible-apps_chrony/commit/c9b92e0fb03530a49b9f807d90ecd81043c77158)
- include new changelog [`ffa944d`](https://github.com/lotusnoir/ansible-apps_chrony/commit/ffa944d35bb86dbd435e6a768afca8332612be3b)
- include secret detection [`a9b2fbf`](https://github.com/lotusnoir/ansible-apps_chrony/commit/a9b2fbf84e9ac24cfb489506f942316ed873de4b)
- add precommit for lint [`5a0f77d`](https://github.com/lotusnoir/ansible-apps_chrony/commit/5a0f77de526c1bb727e747ebcf93d3fa1a9872ac)
- fix checks [`702c75c`](https://github.com/lotusnoir/ansible-apps_chrony/commit/702c75cd118bd164fc4fc1fd4d86461f3a6d2b47)
- add new molecule all scenario [`7a916a4`](https://github.com/lotusnoir/ansible-apps_chrony/commit/7a916a4a296bfb0275a90681377e2773ccfd58ad)
- initial commit [`b8cc169`](https://github.com/lotusnoir/ansible-apps_chrony/commit/b8cc169f164da4444999fefdf87120e9e2d30e6d)
