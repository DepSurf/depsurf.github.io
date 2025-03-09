# Function: <code>bpf_xdp_link_release</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589340208,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9299",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589340208,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238368,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9558",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238368,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9559",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962448,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071592697802,
      "name": "bpf_xdp_link_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9297",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591500112,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071594583874,
      "name": "bpf_xdp_link_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9284",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593270000,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071596323700,
      "name": "bpf_xdp_link_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9296",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593728128,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    },
    {
      "addr": 18446744071596853735,
      "name": "bpf_xdp_link_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void bpf_xdp_link_release(struct bpf_link * link)
```

```json
{
  "name": "bpf_xdp_link_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_xdp_link_release",
      "external": false,
      "loc": "net/core/dev.c:9414",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:bpf_xdp_link_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594506320,
      "name": "bpf_xdp_link_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071597778706,
      "name": "bpf_xdp_link_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bpf_xdp_link_release(struct bpf_link * link)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
