---
title: "AlmaLinux Modified packages"
---

This table lists AlmaLinux packages with modified sources.

| Package | AlmaLinux 8 | AlmaLinux 9 | Commentary |
| --- | --- | --- | ---- |
| abrt |<b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/abrt/commit/a49539fafaa3d63476b0aca3cbf0919416ded786) | Doesn't require modification |- Remove requirements for rhel-related packages <br>- Add support for GPG subkeys <br>- Disable rhtsupport|
| anaconda | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/anaconda/commit/b9c39d05d3eef81319bf5fd49208d78bc3e83203) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/anaconda/commit/a7e96ccaba29d6e3d3d7e48241f3f34cf2558ab2) | - Add AlmaLinux support patches <br>- Remove rhel-related requirements |
| anaconda-user-help | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/anaconda-user-help/commit/e06e7c65f75bd70c8b3b4b9c405aa6eb70f89d87) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/anaconda-user-help/commit/8189f189f8baba3cd7c383d92e488ba6166f59db) |- Apply AlmaLinux branding patch |
| bluez | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/bluez/commit/88204f929628e652781bb06bf9823086100727e9) | Doesn't require modification |- Debrand for AlmaLinux |
| cloud-init | <b>Git commit:</b><br>[8]( https://git.almalinux.org/rpms/cloud-init/commit/1508331c917e37cb8551536d6f976eee6a273fc2) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/cloud-init/commit/55630d1c1a884961f85829852a150c35a4011c09) |- Apply AlmaLinux support patch |
| clufter | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/clufter/commit/d9bf103ec6660b0374080dd25463ae4d7d010706) | Doesn't require modification |- This change helps build clufter with a new version of pacemaker |
| crash | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/crash/commit/b4a0b91d49f3232f877adf6288735e131cd3662a) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/crash/commit/45800a12458cbf0cc378e78855f50b707a6fad30)  |- Debrand for AlmaLinux|
| dnf | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/dnf/commit/619df95b9edbc8571c73ff34202daae0b2627e0c) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/dnf/commit/7ad9001b8e9035d1bda6c151dd739873a6227e01) |- Debrand for AlmaLinux |
| eth-tools | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/eth-tools/commit/6dcd14c7ee226a96929b5403a331c62570fd72ee) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/eth-tools/commit/b36f64560bcf6e005d0265d17dfdc1976921a49c) |- Apply AlmaLinux support patch
| firefox | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/firefox/commit/14135a8233d8eab1acad34e9d89ff90b311c55a7) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/firefox/commit/b077702a832e59b3d2aa19bd97f6e37588d482ee) |- Debrand for AlmaLinux
| fwupd | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/fwupd/commit/657b8ce0193b0801f42b729b4edd4c5a67ea3acc) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/fwupd/commit/d2a18c3e2ee419b300e34682f5ea6355247d5991) |- Use AlmaLinux secure boot cert
| fwupdate | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/fwupdate/commit/1329d57b09e56b4e03003546de3acebbbb8f8c04) | Doesn't require modification|- Use AlmaLinux secure boot cert |
| gcc | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/gcc/commit/cc1caac2399c4092bf94c2084514493191880b0c) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/gcc/commit/3874b606153c1d61bc55a523c93e60baf789047a) |- Debrand for AlmaLinux<br>- Use bugs.almalinux.org instead of Red Hat bugzilla |
| gnome-settings-daemon | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/gnome-settings-daemon/commit/ea6b7152659f432f1cf526525bafb14ce1d78ddb) | Doesn't require modification|- Disable subman plugin |
| golang-github-cpuguy83-go-md2man | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/golang-github-cpuguy83-go-md2man/commit/c588b8c65a51dfbc8b2506ffd525ab63ecffba27) |Doesn't require modification |- Fix compilation error |
| grub2 |<b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/grub2/commit/33d2c41b51cb5f249b35e4a0d63c1d14bf45f4d4) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/grub2/commit/c5253d0d2e694a98261ba5133ea9f79106f76d8f) |- Use AlmaLinux secure boot cert<br>- Debrand for AlmaLinux |
| gstreamer1-plugins-bad-free |Doesn't require modification  | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/gstreamer1-plugins-bad-free/commit/4c5ae9f3c7f43997b4ff6c0dc5fdf9bb2ae344c9) |- Added wayland-protocols-devel to BuildRequires to fix build |
| hplip | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/hplip/commit/4b2a9aa41df8d259e7c59e573344f748d7af390c) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/hplip/commit/3d3e591d57b2762c47885e4cf3f6980cb371ebff) |- Add AlmaLinux support<br>- Fix permission for custom created gpg dir<br>- Change gpg server to pgp.mit.edu |
| initial-setup | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/initial-setup/commit/afd963bfb2093779ccaadd636847a71bee4f8e49)  | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/initial-setup/commit/e6f8b66291c747e0bd3131d799ac1ca9380f8616) |- AlmaLinux debrand patch |
| kernel | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/kernel/commit/273ff5a1639b7aa4281b9d12df0844833e4b174e) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/kernel/commit/b3893ae5fe5b195d08796fdeb7c8299af14ed5a5) |- Use AlmaLinux secure boot cert<br>- Debrand for AlmaLinux |
| kernel-rt | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/kernel-rt/commit/1cc2bb69323a86c570fffefd79d02191f20f3cd1) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/kernel-rt/commit/b3b715bbe5e7adef10364e64647095b31011a697) |- Use AlmaLinux secure boot cert<br>- Debrand for AlmaLinux |
| libdnf | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/libdnf/commit/62d20182f6e3f3b19dc6c9324b6e32079f88f2da) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/libdnf/commit/825f016fd21c7f75ddb5dac902d3e0b81978c4ba) |- Debrand for AlmaLinux<br>- Add support for GPG subkeys for repodata signing |
| libguestfs | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/libguestfs/commit/284df1d1cdfee467b7d132c0b0c08797473baaad) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/libguestfs/commit/be7a16351ade716cf3c2b8a003e081a2ceacacd0) |- Fix build for AlmaLinux |
| libreoffice | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/libreoffice/commit/7f7be42a96379ce83a9b2bbf1cfa5a03eef61d98)| <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/libreoffice/commit/41ecbcbca3e91c0503d325d613df02a81b4f773f) |- Debrand for AlmaLinux |
| libreport | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/libreport/commit/a3b5337005f0f2e7d8a1ac29471b2303e3808469) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/libreport/commit/edd1819ae51218681b8f7867b362061d7ab1c6b5) |- Debrand for AlmaLinux |
| mongo-tools | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/mongo-tools/commit/fc4e50154e1d56ee3478d2966fd6fa76c8d6b370) | Doesn't require modification|- Use golang instead of go-toolset-1.10-golang BR |
| nginx | <b>Git commit:</b><br>8:<li>[a8-stream-1.14](https://git.almalinux.org/rpms/nginx/commit/a2a7289a0c043020a2dbf2cc518f4b7b1642eb10)</li><li>[a8-stream-1.16](https://git.almalinux.org/rpms/nginx/commit/11fd354236f99d6518fa71b73904d869ebc20bdd)</li><li>[a8-stream-1.18](https://git.almalinux.org/rpms/nginx/commit/c2226342dbc12a52a6ebdf706b2f89403b45c34e)</li><li>[a8-stream-1.20](https://git.almalinux.org/rpms/nginx/commit/abb001e0947d0c865bfeaa52fd0f8b88a793cec9)</li> | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/nginx/commit/866617d21031f21e60aeb6827feb8437c605b2fd) |- Debrand for AlmaLinux |
| opa-ff | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/opa-ff/commit/349cff1caea18466ccdbb7839dc8a18b557ae092) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/opa-ff/commit/c5a7fc55b8f368b2af08bf09b7fda73f40e02f3a) |- Add AlmaLinux detection |
| opa-fm | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/opa-fm/commit/706e0dec03e10398b7b22b2c44c89dd00901f62f) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/opa-fm/commit/c18f918c3f9f5198d7774c8d9bf4849de1a80619) |- Add AlmaLinux detection |
| openscap | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/openscap/commit/2a29d3a5f26394755c10d6bde2444532f8b0440c) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/openscap/commit/731a227034cf6626b3c653cba5aa1d5e2621babd) |- Add AlmaLinux definitions | 
| osbuild | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/osbuild/commit/7b66e9611a33b6d7a53402b15c8f4e7e69a54f1b) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/osbuild/commit/3912a5767bdf2506d108d5b40b08e8a44cbcd3f2)|- Add AlmaLinux runners |
| osbuild-composer | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/osbuild-composer/commit/871d52df46c868cef087583d04fb0705e45423eb) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/osbuild-composer/commit/2ecdc50c9c9280dafdc7a9d546dc48a0492feb6a) |- Add AlmaLinux support patch |
| pcs | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/pcs/commit/1066fd3ebc6c09a42f80706d59f2d49d54d2080f) | Doesn't require modification |- Debrand logo |
| perl-AnyEvent | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/perl-AnyEvent/commit/7df8a744d97fbb6b31ace8f6bef17177bae18d37) | Doesn't require modification |- Use patch for fix ssltest|
| python2 | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/python2/commit/c6c16b43455d5c0cafa9c2313c2ee71086535d61) |Doesn't require modification |- Add AlmaLinux to supported distros |
| python3 | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/python-psycopg2/commit/4e9ae78a23ce76ee0292634f6eb4b018dc0879a8) |Doesn't require modification | - Add AlmaLinux to supported distros |
| python-nss | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/python-nss/commit/43e6c2c074aa364c5691d2b0b0316365ab6ac328)|Doesn't require modification |- Fix FTBFS with NSS v3.58+ caused by conflicting struct names |
| python-psycopg2 | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/python-psycopg2/commit/4e9ae78a23ce76ee0292634f6eb4b018dc0879a8) |Doesn't require modification |- Add patch <i>0001-Mark-_test_external_close-as-expected-failure.patch</i> |
| redhat-rpm-config |<b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/redhat-rpm-config/commit/5cc5eaf654481add2b245b182653c932cc36111f) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/redhat-rpm-config/commit/3cce17f25c4700ffbc23de78a492f2085cee1dba) |- Fix AlmaLinux detection |
| rpm-ostree | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/rpm-ostree/commit/bf2f06b445140c9786e1fe50301a734e6094b77c) |Doesn't require modification |- Add libassuan-devel to BR|
| s390utils | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/s390utils/commit/7c6a3e182f09e2f141b0460e7bb2190dc27b4c80) |Doesn't require modification |- Fix detection <i>5*</i> version kernels to allow builds on AlmaLinux 9 nodes |
| scap-security-guide | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/scap-security-guide/commit/0e201cce7fac24fe09d8238251917993e5fa25f7) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/scap-security-guide/commit/f68f0f633d25426d08ae6aa904f1cb67f0639de6) |- Add AlmaLinux patch |
| shim | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/shim/commit/09b7c524d446c38d44cd395b7492c611c8bb13fb) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/shim/commit/1c0a90cc2ed25ee8477040ddbd71fe4c689f9f36) |- Use AlmaLinux binary and cert |
| shim-unsigned-x64 | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/shim-unsigned-x64/commit/7d184fed577f82ba6fd1ed992ce1fcbe45a38844) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/shim-unsigned-x64/commit/7b7c17dc74ba3f474269442ce55c175255f41408) |- Use AlmaLinux cert and SBAT entry |
| shim-unsigned-aarch64 |Doesn't require modification | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/shim-unsigned-aarch64/commit/f4663c11a3dba94bbbe2e77b97850323a8d6954f) |- Use AlmaLinux cert and SBAT entry |
| sos | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/sos/commit/8fdc9d3543771d26499222fdfa5741ca572f9891) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/sos/commit/385c4f2abae810a33832f11c39e1c27dfb52b4de) |- Debrand for AlmaLinux |
| subscription-manager | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/subscription-manager/commit/31d63783159b9b6c4a593ad158af5fb47669fdad) | <b>Git commit:</b> <br> [9](https://git.almalinux.org/rpms/subscription-manager/commit/e415540e20de8813197a983bd9e545886f5b73d3) |- Debrand for AlmaLinux |
| thunderbird | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/thunderbird/commit/f17f8521488d3d48b0061cec08d795b8ba4d857f) | <b>Git commit:</b><br> [9](https://git.almalinux.org/rpms/thunderbird/commit/dd5ecbc4851476d1e1e73759e75dcb350146c40f) |- Debrand for AlmaLinux |
| virt-manager | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/virt-manager/commit/a4a6bbffb06cc711d6d1c95c9253762bb9b127f0) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/virt-manager/commit/811ee55238fb13fd132f18db1d45b72865b482c4) |- Add AlmaLinux support patch |
    
List of modified packages that don't require debranding after AlmaLinux 8.7 and AlmaLinux 9.1 versions:
| Package | AlmaLinux 8 | AlmaLinux 9 | Commentary |
| --- | --- | --- | ---- |
| WALinuxAgent | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/WALinuxAgent/commit/19bfe138ed9a46302727997cfccfbd8fc0acbac9) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/WALinuxAgent/commit/961450f8ce1c628e83b718a5794a44f12e7a3150) | - Add AlmaLinux support patch |
| chrony | <b>Git commit:</b><br>[8](https://git.almalinux.org/rpms/chrony/commit/4d3e2ca2654b08b8d17790cabb368ea7d2566977) | <b>Git commit:</b><br>[9](https://git.almalinux.org/rpms/chrony/commit/8ef8f9012bb746dbcef83f2891d1c6b3ebc73c9e) |- Use CloudLinux/RHEL NTP pool instead of AlmaLinux|