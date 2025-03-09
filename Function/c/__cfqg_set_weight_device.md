# Function: <code>__cfqg_set_weight_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t __cfqg_set_weight_device(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool on_dfl, bool is_leaf_weight)
```

```json
{
  "name": "__cfqg_set_weight_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902176,
      "name": "__cfqg_set_weight_device",
      "external": false,
      "loc": "block/cfq-iosched.c:1757",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfqg_set_weight_device",
        "block/cfq-iosched.c:cfqg_set_leaf_weight_device",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902176,
      "name": "__cfqg_set_weight_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cfqg_set_weight_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190592,
      "name": "__cfqg_set_weight_device",
      "external": false,
      "loc": "block/cfq-iosched.c:1781",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_set_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_set_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190592,
      "name": "__cfqg_set_weight_device.constprop.99",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cfqg_set_weight_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583306752,
      "name": "__cfqg_set_weight_device",
      "external": false,
      "loc": "block/cfq-iosched.c:1772",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_set_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_set_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306752,
      "name": "__cfqg_set_weight_device.constprop.101",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cfqg_set_weight_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583368928,
      "name": "__cfqg_set_weight_device",
      "external": false,
      "loc": "block/cfq-iosched.c:1777",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_set_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_set_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368928,
      "name": "__cfqg_set_weight_device.constprop.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cfqg_set_weight_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583546624,
      "name": "__cfqg_set_weight_device",
      "external": false,
      "loc": "block/cfq-iosched.c:1757",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_set_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_set_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583546624,
      "name": "__cfqg_set_weight_device.constprop.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cfqg_set_weight_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583761632,
      "name": "__cfqg_set_weight_device",
      "external": false,
      "loc": "block/cfq-iosched.c:1760",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_set_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_set_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761632,
      "name": "__cfqg_set_weight_device.constprop.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
ssize_t __cfqg_set_weight_device(struct kernfs_open_file * of, char * buf, size_t nbytes, loff_t off, bool on_dfl, bool is_leaf_weight)
```
</details>
</li>
</ul>
