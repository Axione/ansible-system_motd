# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.0.0](https://github.com/lotusnoir/ansible-system_motd/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`9452a26`](https://github.com/lotusnoir/ansible-system_motd/commit/9452a266c163fc0dd16ad5595a7358956753521d)
- update core, molecule + gitlab-ci [`9b14653`](https://github.com/lotusnoir/ansible-system_motd/commit/9b146538a1b0932409d8e61bd679236a8d5e74a9)
- fix lint [`8e8c05f`](https://github.com/lotusnoir/ansible-system_motd/commit/8e8c05f715d522e71d087a766db202643e4174fc)
- fix molecule paralelism and little updates [`51f4326`](https://github.com/lotusnoir/ansible-system_motd/commit/51f432613a8a11df65e1799980486ad4e3ff2294)
- add support for ubuntu24 [`83546c0`](https://github.com/lotusnoir/ansible-system_motd/commit/83546c094fd1f3984814e6fb9a32ec360c62f818)
- add file to remove for redhat distrib [`5825bc7`](https://github.com/lotusnoir/ansible-system_motd/commit/5825bc70b32a57ec183080fc7805d4ec6cc030f6)
- add version on molecule play image to maintain support on old release [`15318cb`](https://github.com/lotusnoir/ansible-system_motd/commit/15318cb74115dba6a2e565e7313424a6cee6b316)
- update molecule [`b478456`](https://github.com/lotusnoir/ansible-system_motd/commit/b47845664189b4b69d47476c2c78b25939ebbc56)
- add redhat 9 to default supported distrib [`c6c10b4`](https://github.com/lotusnoir/ansible-system_motd/commit/c6c10b44df69126c641d917e7c5eda86807b0362)
- add redhat 8 to default supported distrib [`0adde97`](https://github.com/lotusnoir/ansible-system_motd/commit/0adde970be0a2bc5ebbf4ee0f4d76793c9869056)

## [2.0.0](https://github.com/lotusnoir/ansible-system_motd/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`87cbcb3`](https://github.com/lotusnoir/ansible-system_motd/commit/87cbcb341744e5ac5326a86599a04c56f9a5df78)
- update readme + precommit + include vars [`43c0470`](https://github.com/lotusnoir/ansible-system_motd/commit/43c04704e11c9bf0e4a5f0bf2a651c776e3a09fe)
- change import tasks to include in order to support facts on name [`86ad046`](https://github.com/lotusnoir/ansible-system_motd/commit/86ad046fde6aaf08f4862bdb6fab8ee22097a89a)

## [1.1.0](https://github.com/lotusnoir/ansible-system_motd/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`9976f13`](https://github.com/lotusnoir/ansible-system_motd/commit/9976f13a416fbb3783a02ddfbc7a118e69e75b22)

## [1.0.0](https://github.com/lotusnoir/ansible-system_motd/compare/0.4.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`bd2d98d`](https://github.com/lotusnoir/ansible-system_motd/commit/bd2d98d69336bb09d44f118cba69fe6981c33832)
- add precommit for lint [`fcf27ea`](https://github.com/lotusnoir/ansible-system_motd/commit/fcf27ea09035cb0d4c91b89907f4d57ed1f3bb29)
- remove file for ubuntu [`8cd0bde`](https://github.com/lotusnoir/ansible-system_motd/commit/8cd0bdefd87ba92971b030ad23252fc0e39e6302)
- change motd to remove for ubuntu [`58049fc`](https://github.com/lotusnoir/ansible-system_motd/commit/58049fc4ede53fe0679f873da769444e8b92dd71)
- fix checks [`819e169`](https://github.com/lotusnoir/ansible-system_motd/commit/819e169805bf6c58660ff3948860bbb5fdd6a47d)
- add new molecule all scenario [`f9571a4`](https://github.com/lotusnoir/ansible-system_motd/commit/f9571a433cae6eed2df34d17164ef6310a8f118b)
- split distro for molecule tests on ci [`bb6392e`](https://github.com/lotusnoir/ansible-system_motd/commit/bb6392ec00ae09ba5df02347e402962400577098)
- update checks and Readme [`04a3efd`](https://github.com/lotusnoir/ansible-system_motd/commit/04a3efd38b192d49197e6e8d9efc02d5c44a1121)
- update meta [`c1696f3`](https://github.com/lotusnoir/ansible-system_motd/commit/c1696f346a2b7364e701160f7b82756e27ddc420)
- fix centos 7 / 8 [`f26da43`](https://github.com/lotusnoir/ansible-system_motd/commit/f26da43b2c3392507b9dc8cd3a0cc906016935a9)

## [0.4.0](https://github.com/lotusnoir/ansible-system_motd/compare/0.3.1...0.4.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`08af066`](https://github.com/lotusnoir/ansible-system_motd/commit/08af066ee2119248efb463cc00f128fd17d75299)

## [0.3.1](https://github.com/lotusnoir/ansible-system_motd/compare/0.3.0...0.3.1) - 2022-06-30

### Commits

- fix: wrong path on remove [`9e13abd`](https://github.com/lotusnoir/ansible-system_motd/commit/9e13abd878cc6c899ea7610f138d4cc4904e19b0)
- remove supported oraclelinux, bug to fix [`a339a87`](https://github.com/lotusnoir/ansible-system_motd/commit/a339a8792d151f63cdd9ad6f4cb4a750d7cc2a49)

## [0.2.0](https://github.com/lotusnoir/ansible-system_motd/compare/0.1.0...0.2.0) - 2022-06-02

### Commits

- fix: remove unsupported centos8 + minor fixes [`7853ea9`](https://github.com/lotusnoir/ansible-system_motd/commit/7853ea926a88dadd0815eb42ddb44729333e9fe4)

## 0.1.0 - 2021-11-18

### Commits

- initial commit [`676b7e7`](https://github.com/lotusnoir/ansible-system_motd/commit/676b7e7610fb19601df163488421ad0d96f9be72)
