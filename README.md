Community Shared BOSH Releases
==============================

This project references BOSH release tarballs from across the BOSH community.

Additionally, it allows BOSH release tarballs to be uploaded to a shared blobstore. This is useful for BOSH releases that are not already sharing their tarballs (for example, core Cloud Foundry projects `cf` and `cf-mysq`).

CPI releases
------------

-	**aws-cpi** used with new bosh-micro CLI https://github.com/cloudfoundry-incubator/bosh-aws-cpi-release v1 (28.9MB)

```
wget https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-bosh-aws-cpi-1.tgz
```

-	**openstack-cpi** https://github.com/cloudfoundry-incubator/bosh-openstack-cpi-release v1 (28.3MB)

```
wget https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-bosh-openstack-cpi-1.tgz
```

Releases
--------

-	**admin-ui** [v2](https://github.com/cloudfoundry-community/admin-ui-boshrelease/tree/v2) (20M), [v3](https://github.com/cloudfoundry-community/admin-ui-boshrelease/tree/v3) (20M), [v5](https://github.com/cloudfoundry-community/admin-ui-boshrelease/tree/v5) (45M)

```
bosh upload release https://admin-ui-boshrelease.s3.amazonaws.com/boshrelease-admin-ui-3.tgz
bosh upload release https://admin-ui-boshrelease.s3.amazonaws.com/boshrelease-admin-ui-5.tgz
```

-	**bosh** see http://boshartifacts.cloudfoundry.org/file_collections?type=releases
-	**cf** [v170](https://github.com/cloudfoundry/cf-release/tree/v170) (1.5G), [v173](https://github.com/cloudfoundry/cf-release/tree/v173) (2.5G), [v175](https://github.com/cloudfoundry/cf-release/tree/v175) (2.7G), [v176](https://github.com/cloudfoundry/cf-release/tree/v176) (2.8G), [v177](https://github.com/cloudfoundry/cf-release/tree/v177) (3.1G), [v178](https://github.com/cloudfoundry/cf-release/tree/v178) (3.1G), [v179](https://github.com/cloudfoundry/cf-release/tree/v179) (3.1G),[v180](https://github.com/cloudfoundry/cf-release/tree/v180) (3.1G), [v182](https://github.com/cloudfoundry/cf-release/tree/v182) (3.2G), [v183](https://github.com/cloudfoundry/cf-release/tree/v183) (3.2G),[v187](https://github.com/cloudfoundry/cf-release/tree/v187) (3.3G), [v188](https://github.com/cloudfoundry/cf-release/tree/v188) (3.3G), [v189](https://github.com/cloudfoundry/cf-release/tree/v189) (3.5G), [v190](https://github.com/cloudfoundry/cf-release/tree/v190) (3.5G), [v191](https://github.com/cloudfoundry/cf-release/tree/v191) (3.5G), [v192](https://github.com/cloudfoundry/cf-release/tree/v192) (3.5G), [v193](https://github.com/cloudfoundry/cf-release/tree/v193) (3.5G), [v194](https://github.com/cloudfoundry/cf-release/tree/v194) (3.5G), [v195](https://github.com/cloudfoundry/cf-release/tree/v195) (3.6G), [v196](https://github.com/cloudfoundry/cf-release/tree/v196) (3.6G), [v197](https://github.com/cloudfoundry/cf-release/tree/v197) (3.6G), [v198](https://github.com/cloudfoundry/cf-release/tree/v198) (3.7G), [v199](https://github.com/cloudfoundry/cf-release/tree/v199) (3.8G), [v200](https://github.com/cloudfoundry/cf-release/tree/v200) (3.8G), [v201](https://github.com/cloudfoundry/cf-release/tree/v201) (4.3G), [v202](https://github.com/cloudfoundry/cf-release/tree/v202) (4.3G), [v203](https://github.com/cloudfoundry/cf-release/tree/v203) (4.3G)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-170.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-173.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-175.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-176.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-177.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-178.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-179.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-180.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-182.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-183.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-187.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-188.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-189.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-190.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-191.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-192.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-193.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-194.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-195.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-196.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-197.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-198.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-199.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-200.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-201.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-202.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-203.tgz
```

-	<strong id="cf-mysql">cf-mysql</strong> [v8](https://github.com/cloudfoundry/cf-mysql-release/tree/v8) (118M), [v9](https://github.com/cloudfoundry/cf-mysql-release/tree/v9) (259M), [v10](https://github.com/cloudfoundry/cf-mysql-release/tree/v10) (255M), [v11](https://github.com/cloudfoundry/cf-mysql-release/tree/v11) (255M)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-mysql-8.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-mysql-9.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-mysql-10.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-mysql-11.tgz
```

-	**cf-services-contrib** [v5](https://github.com/cloudfoundry-community/cf-services-contrib-release/tree/v5) (795.7M)

```
bosh upload release https://cf-contrib.s3.amazonaws.com/boshrelease-cf-services-contrib-5.tgz
```

-	**cf-riak-cs** [v2](https://github.com/cloudfoundry-incubator/cf-riak-cs-release/tree/v2) (196.8M), [v4](https://github.com/cloudfoundry-incubator/cf-riak-cs-release/tree/v4) (197.7M) [v5](https://github.com/cloudfoundry-incubator/cf-riak-cs-release/tree/v5) (215.7M)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-riak-cs-2.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-riak-cs-4.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-riak-cs-5.tgz
```

-	**consul** [v4](https://github.com/cloudfoundry-community/consul-boshrelease/tree/v4) (61.5M), [v5](https://github.com/cloudfoundry-community/consul-boshrelease/tree/v5) (57.5M), [v6](https://github.com/cloudfoundry-community/consul-boshrelease/tree/v6) (57.8M),[v7](https://github.com/cloudfoundry-community/consul-boshrelease/tree/v7) (60M), [v8](https://github.com/cloudfoundry-community/consul-boshrelease/tree/v8) (58M), [v10](https://github.com/cloudfoundry-community/consul-boshrelease/tree/v10) (62.2M)

```
bosh upload release https://consul-boshrelease.s3.amazonaws.com/boshrelease-consul-4.tgz
bosh upload release https://consul-boshrelease.s3.amazonaws.com/boshrelease-consul-5.tgz
bosh upload release https://consul-boshrelease.s3.amazonaws.com/boshrelease-consul-6.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-consul-7.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-consul-8.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-consul-10.tgz
```

-	**crate** [v1](https://github.com/cloudfoundry-community/crate-boshrelease/tree/v1) (114.7M)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-crate-1.tgz
```

-	**docker** [v4](https://github.com/cf-platform-eng/docker-boshrelease/tree/v4) (32M), [v5](https://github.com/cf-platform-eng/docker-boshrelease/tree/v5) (20M), [v6](https://github.com/cf-platform-eng/docker-boshrelease/tree/v6) (20M), [v7](https://github.com/cf-platform-eng/docker-boshrelease/tree/v7) (30M), [v8](https://github.com/cf-platform-eng/docker-boshrelease/tree/v8) (30.2M), [v9](https://github.com/cf-platform-eng/docker-boshrelease/tree/v9) (30.2M), [v10](https://github.com/cf-platform-eng/docker-boshrelease/tree/v10) (89.4M), [v11](https://github.com/cf-platform-eng/docker-boshrelease/tree/v11) (89.5M)
```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-4.tgz
bosh upload release https://docker-boshrelease.s3.amazonaws.com/boshrelease-docker-5.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-6.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-7.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-8.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-9.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-10.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-docker-11.tgz
```

-	**docker-registry** [v1](https://github.com/cloudfoundry-community/docker-registry-boshrelease/tree/v1) (32M)

```
bosh upload release https://docker-registry-boshrelease.s3.amazonaws.com/boshrelease-docker-registry-1.tgz
```

-	**mesos** [v1](https://github.com/cf-platform-eng/shipyard-boshrelease/tree/v1) (384.9M)

```
bosh upload release https://mesos-boshrelease.s3.amazonaws.com/boshrelease-mesos-1.tgz
```

-	**networking** [v1](https://github.com/cf-platform-eng/networking-boshrelease/tree/v1) (7.6KB)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-networking-1.tgz
```

-	**redis** [v9](https://github.com/cloudfoundry-community/redis-boshrelease/tree/v9) (1M)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-redis-9.tgz
```

The joiner release to advertise the redis service over consul:

[v2](https://github.com/drnic/redis-consul-boshrelease/tree/v2) (1.4K)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-redis-consul-2.tgz
```

-	**shipyard** [v3](https://github.com/cf-platform-eng/shipyard-boshrelease/tree/v3) (6.1M)

```
bosh upload release https://shipyard-boshrelease.s3.amazonaws.com/boshrelease-shipyard-3.tgz
```

-	**sslproxy** [v5](https://github.com/cloudfoundry-community/sslproxy-boshrelease/tree/v5) (2.4M)

```
bosh upload release https://sslproxy-boshrelease.s3.amazonaws.com/boshrelease-sslproxy-5.tgz
```

-	**tree** [v2](https://github.com/cloudfoundry-community/tree-boshrelease/tree/v2) (43KB)

```
bosh upload release https://tree-boshrelease.s3.amazonaws.com/boshrelease-tree-2.tgz
```

Follow the version links above for deployment manifest/spiff template examples.

Usage
-----

```
bosh upload release URL
```

Adding releases
---------------

Most projects' owners can upload their own BOSH release tarballs using `bosh share releases` from the `bosh-gen` project. If a project owner is not sharing tarballs, such as cf-release and cf-mysql-release, then they can be shared using this project.

For example, with cf-release:

```
$ cd path/to/cf-release
$ bosh create release --with-tarball releases/cf-173.yml
```

This creates `releases/cf-173.tgz`.

Change back to this `community-shared-boshreleases` project:

```
$ cd ../community-shared-boshreleases
$ bosh share release ../cf-release/releases/cf-173.tgz
...
https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-173.tgz
```

The resulting URL can now be added to the `README.md` above.

One time only, please email [Dr Nic Williams](mailto:&#x64;&#x72;&#x6E;&#x69;&#x63;&#x77;&#x69;&#x6C;&#x6C;&#x69;&#x61;&#x6D;&#x73;&#x40;&#x67;&#x6D;&#x61;&#x69;&#x6C;&#x2E;&#x63;&#x6F;&#x6D;) and he will set you up with access:

-	Read/write credentials to the AWS S3 account for your BOSH release blobstores/buckets

When he gives you the AWS S3 credentials, place them in `config/private.yml` of this project:

```yaml
---
blobstore:
  s3:
    access_key_id:     ACCESS
    secret_access_key: SECRET
```

Finally, so they are useful for other `bosh-gen` projects, place them in the `~/.fog` file and you'll easily be able to reuse them for each new BOSH release:

```yaml
:community:
  :aws_access_key_id:     ACCESS
  :aws_secret_access_key: SECRET
```
