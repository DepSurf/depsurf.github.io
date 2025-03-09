# Function: <code>change_napi_defer_hard_irqs</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589567314,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:385",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589576402,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:386",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int change_napi_defer_hard_irqs(struct net_device * dev, long unsigned int val)
```

```json
{
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589463968,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:386",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463968,
      "name": "change_napi_defer_hard_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int change_napi_defer_hard_irqs(struct net_device * dev, long unsigned int val)
```

```json
{
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590202336,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:406",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590202336,
      "name": "change_napi_defer_hard_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591788972,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:408",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store"
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
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593582316,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:408",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store"
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
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594053948,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:408",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store"
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
  "name": "change_napi_defer_hard_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594844431,
      "name": "change_napi_defer_hard_irqs",
      "external": false,
      "loc": "net/core/net-sysfs.c:420",
      "file": "net/core/net-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int change_napi_defer_hard_irqs(struct net_device * dev, long unsigned int val)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int change_napi_defer_hard_irqs(struct net_device * dev, long unsigned int val)
```
</details>
</li>
</ul>
