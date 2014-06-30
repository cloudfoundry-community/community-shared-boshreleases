Community Shared BOSH Releases
==============================

This project references BOSH release tarballs from across the BOSH community.

Additionally, it allows BOSH release tarballs to be uploaded to a shared blobstore. This is useful for BOSH releases that are not already sharing their tarballs (for example, core Cloud Foundry projects `cf` and `cf-mysq`).

Releases
--------

- **cf** v170 (1.5G), v173 (2.5G)

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-170.tgz
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-173.tgz
```

- **cf-mysql** v8

```
bosh upload release https://community-shared-boshreleases.s3.amazonaws.com/boshrelease-cf-mysql-8.tgz
```

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
