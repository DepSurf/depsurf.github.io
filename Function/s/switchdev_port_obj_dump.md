# Function: <code>switchdev_port_obj_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int switchdev_port_obj_dump(struct net_device * dev, struct switchdev_obj * obj, switchdev_obj_dump_cb_t * cb)
```

```json
{
  "name": "switchdev_port_obj_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587803872,
      "name": "switchdev_port_obj_dump",
      "external": true,
      "loc": "net/switchdev/switchdev.c:550",
      "file": "net/switchdev/switchdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump",
        "net/switchdev/switchdev.c:switchdev_port_vlan_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803872,
      "name": "switchdev_port_obj_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int switchdev_port_obj_dump(struct net_device * dev, struct switchdev_obj * obj, switchdev_obj_dump_cb_t * cb)
```

```json
{
  "name": "switchdev_port_obj_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588017744,
      "name": "switchdev_port_obj_dump",
      "external": true,
      "loc": "net/switchdev/switchdev.c:547",
      "file": "net/switchdev/switchdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump",
        "net/switchdev/switchdev.c:switchdev_port_vlan_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588017744,
      "name": "switchdev_port_obj_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int switchdev_port_obj_dump(struct net_device * dev, struct switchdev_obj * obj, switchdev_obj_dump_cb_t * cb)
```

```json
{
  "name": "switchdev_port_obj_dump",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588175680,
      "name": "switchdev_port_obj_dump",
      "external": true,
      "loc": "net/switchdev/switchdev.c:547",
      "file": "net/switchdev/switchdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/switchdev/switchdev.c:switchdev_port_fdb_dump",
        "net/switchdev/switchdev.c:switchdev_port_vlan_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588175680,
      "name": "switchdev_port_obj_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int switchdev_port_obj_dump(struct net_device * dev, struct switchdev_obj * obj, switchdev_obj_dump_cb_t * cb)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int switchdev_port_obj_dump(struct net_device * dev, struct switchdev_obj * obj, switchdev_obj_dump_cb_t * cb)
```
</details>
</li>
</ul>
