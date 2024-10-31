# Linux Kernel Configuration Fragments

A project containing Linux kernel configuration fragments.

## Minimal Bootlable Configuration

This configuration enables a minimal setup suitable for virtualized
environments and tested with Debian Testing. It includes the following
fragments:

* `kvm_guest.config`
* `virtio-fs.config`
* `systemd.config`
* `distro.config`
* `storage.config`

Example:

```sh
make tinyconfig \
  kvm_guest.config
  virtio-fs.config
  systemd.config
  distro.config
  storage.config
```

## eBPF-Ready Configuration

* `kvm_guest.config`
* `virtio-fs.config`
* `systemd.config`
* `distro.config`
* `storage.config`
* `numa.config`
* `ebpf.config`

## License

This project is licensed under the GNU General Public License v2.0. See
the [LICENSE](LICENSE) file for more details.
