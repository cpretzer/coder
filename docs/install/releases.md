# Releases

Coder releases are cut directly from main in our
[Github](https://github.com/coder/coder) on the first Tuesday of each month.

We recommend enterprise customers test the compatibility of new releases with
their infrastructure on a staging environment before upgrading a production
deployment.

We support two release channels:
[mainline](https://github.com/coder/coder/2.10.0) for the edge version of Coder
and [stable](https://github.com/coder/coder/releases/latest) for those with
lower tolerance for fault. We field our mainline releases publicly for two weeks
before promoting them to stable.

### Mainline releases

- Intended for customers with a staging environment
- Gives earliest access to new features
- May include minor bugs
- All bugfixes and security patches are supported

### Stable releases

- Safest upgrade/installation path
- May not include the latest features
- Security vulnerabilities and major bugfixes are supported

> Note: We support major security vulnerabilities (CVEs) for the past three
> versions of Coder.

## Installing stable

When installing Coder, we generally advise specifying the desired version from
our Github [releases page](https://github.com/coder/coder/releases).

You can also use our `install.sh` script with the `stable` flag to install the
latest stable release:

```shell
curl -fsSL https://coder.com/install.sh | sh -s -- --stable
```

Best practices for installing Coder can be found on our [install](./index.md)
pages.

## Release schedule

| Release name | Date               | Status           |
| ------------ | ------------------ | ---------------- |
| 2.7.0        | January 01, 2024   | Not Supported    |
| 2.8.0        | Februrary 06, 2024 | Security Support |
| 2.9.0        | March 07, 2024     | Stable           |
| 2.10.0       | April 03, 2024     | Mainline         |
| 2.11.0       | May 07, 2024       | Not Released     |
| 2.12.0       | June 04, 2024      | Not Released     |
