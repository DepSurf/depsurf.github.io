# Function: <code>xdp_umem_clear_dev</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589120892,
      "name": "xdp_umem_clear_dev",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:96",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589354524,
      "name": "xdp_umem_clear_dev",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:137",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589812352,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:139",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589812352,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590037264,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590037264,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591070144,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591070144,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503791568,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503791568,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236410592,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236410592,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297633712,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297633712,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279696592,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279696592,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589640864,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589640864,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589365392,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365392,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590082896,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590082896,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```

```json
{
  "name": "xdp_umem_clear_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590133104,
      "name": "xdp_umem_clear_dev",
      "external": true,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xsk.c:xsk_notifier",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590133104,
      "name": "xdp_umem_clear_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem * umem)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
