# Reaper RHEL 9 RPM Repository

Public, signed RPM package repository. Package signatures and repository metadata are cryptographically verified by the published repository configuration.

## Browse the repository

**[https://johngrimmreaper.github.io/rhel9-rpms/](https://johngrimmreaper.github.io/rhel9-rpms/)**

## Configure the repository

Repository signing-key fingerprint:

```text
E4C3D7CD300357A507C2B237FF303241B8B8606D
```

### Reaper RHEL 9 RPM Repository - rhel-9 - stable

Repository ID: `reaper-rhel9-stable-rhel-9-stable`

```bash
sudo rpm --import https://johngrimmreaper.github.io/rhel9-rpms/RPM-GPG-KEY
sudo curl -fsSL https://johngrimmreaper.github.io/rhel9-rpms/repo/reaper-rhel9-stable-rhel-9-stable.repo -o /etc/yum.repos.d/reaper-rhel9-stable-rhel-9-stable.repo
sudo dnf makecache --refresh
```

RPM signatures: on; repository metadata signatures: on.

---

This README is generated automatically from the published repository snapshot.
