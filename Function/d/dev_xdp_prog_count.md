# Function: <code>dev_xdp_prog_count</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_prog_count",
      "external": false,
      "loc": "net/core/dev.c:9067",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach"
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
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_xdp_prog_count",
      "external": false,
      "loc": "net/core/dev.c:9326",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 dev_xdp_prog_count(struct net_device * dev)
```

```json
{
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589942032,
      "name": "dev_xdp_prog_count",
      "external": true,
      "loc": "net/core/dev.c:9316",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942032,
      "name": "dev_xdp_prog_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 dev_xdp_prog_count(struct net_device * dev)
```

```json
{
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591475392,
      "name": "dev_xdp_prog_count",
      "external": true,
      "loc": "net/core/dev.c:9054",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475392,
      "name": "dev_xdp_prog_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 dev_xdp_prog_count(struct net_device * dev)
```

```json
{
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593244880,
      "name": "dev_xdp_prog_count",
      "external": true,
      "loc": "net/core/dev.c:9041",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593244880,
      "name": "dev_xdp_prog_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 dev_xdp_prog_count(struct net_device * dev)
```

```json
{
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593705568,
      "name": "dev_xdp_prog_count",
      "external": true,
      "loc": "net/core/dev.c:9049",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593705568,
      "name": "dev_xdp_prog_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 dev_xdp_prog_count(struct net_device * dev)
```

```json
{
  "name": "dev_xdp_prog_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594483888,
      "name": "dev_xdp_prog_count",
      "external": true,
      "loc": "net/core/dev.c:9167",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:dev_xdp_attach",
        "net/core/dev.c:dev_xdp_attach"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594483888,
      "name": "dev_xdp_prog_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
u8 dev_xdp_prog_count(struct net_device * dev)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
