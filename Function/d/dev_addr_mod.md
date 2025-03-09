# Function: <code>dev_addr_mod</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dev_addr_mod(struct net_device * dev, unsigned int offset, const void * addr, size_t len)
```

```json
{
  "name": "dev_addr_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591564432,
      "name": "dev_addr_mod",
      "external": true,
      "loc": "net/core/dev_addr_lists.c:572",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:device_get_ethdev_address",
        "net/ethernet/eth.c:platform_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591564432,
      "name": "dev_addr_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dev_addr_mod(struct net_device * dev, unsigned int offset, const void * addr, size_t len)
```

```json
{
  "name": "dev_addr_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593342496,
      "name": "dev_addr_mod",
      "external": true,
      "loc": "net/core/dev_addr_lists.c:572",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:device_get_ethdev_address",
        "net/ethernet/eth.c:platform_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593342496,
      "name": "dev_addr_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void dev_addr_mod(struct net_device * dev, unsigned int offset, const void * addr, size_t len)
```

```json
{
  "name": "dev_addr_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_addr_mod",
      "external": true,
      "loc": "net/core/dev_addr_lists.c:572",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/net_failover.c:net_failover_create",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:device_get_ethdev_address",
        "net/ethernet/eth.c:platform_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596855824,
      "name": "dev_addr_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071593804256,
      "name": "dev_addr_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1065
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dev_addr_mod(struct net_device * dev, unsigned int offset, const void * addr, size_t len)
```

```json
{
  "name": "dev_addr_mod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_addr_mod",
      "external": true,
      "loc": "net/core/dev_addr_lists.c:572",
      "file": "net/core/dev_addr_lists.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/net_failover.c:net_failover_create",
        "net/core/rtnetlink.c:rtnl_create_link",
        "net/ethernet/eth.c:device_get_ethdev_address",
        "net/ethernet/eth.c:platform_get_ethdev_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597780796,
      "name": "dev_addr_mod.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071594585664,
      "name": "dev_addr_mod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1065
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void dev_addr_mod(struct net_device * dev, unsigned int offset, const void * addr, size_t len)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
