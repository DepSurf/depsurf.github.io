# Function: <code>queue_change_owner</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588703406,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int queue_change_owner(struct net_device * ndev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589560544,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1665",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589560544,
      "name": "queue_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int queue_change_owner(struct net_device * ndev, kuid_t kuid, kgid_t kgid)
```

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589569328,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1716",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589569328,
      "name": "queue_change_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589476226,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1732",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590215086,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1787",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591791393,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1795",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593585153,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1795",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594057281,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1823",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594847761,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1835",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502264888,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235006804,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295760368,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278501262,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588310142,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588022926,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588641966,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_change_owner",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588781454,
      "name": "queue_change_owner",
      "external": false,
      "loc": "net/core/net-sysfs.c:1634",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_change_owner"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int queue_change_owner(struct net_device * ndev, kuid_t kuid, kgid_t kgid)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int queue_change_owner(struct net_device * ndev, kuid_t kuid, kgid_t kgid)
```
</details>
</li>
</ul>
