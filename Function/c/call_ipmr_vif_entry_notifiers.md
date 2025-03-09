# Function: <code>call_ipmr_vif_entry_notifiers</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int call_ipmr_vif_entry_notifiers(struct net * net, enum fib_event_type event_type, struct vif_device * vif, vifi_t vif_index, u32 tb_id)
```

```json
{
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588185456,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:642",
      "file": "net/ipv4/ipmr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588185456,
      "name": "call_ipmr_vif_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588543081,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:648",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588739753,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:651",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589172084,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589396708,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590383685,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:619",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590441253,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:619",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590366750,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:619",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591159241,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:621",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592817991,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:614",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594693129,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:623",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595085189,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:623",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595897989,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:623",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503055752,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235730268,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296763952,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279109454,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589001988,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588725044,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589438372,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
  "name": "call_ipmr_vif_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589482964,
      "name": "call_ipmr_vif_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/ipmr.c:645",
      "file": "net/ipv4/ipmr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int call_ipmr_vif_entry_notifiers(struct net * net, enum fib_event_type event_type, struct vif_device * vif, vifi_t vif_index, u32 tb_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int call_ipmr_vif_entry_notifiers(struct net * net, enum fib_event_type event_type, struct vif_device * vif, vifi_t vif_index, u32 tb_id)
```
</details>
</li>
</ul>
