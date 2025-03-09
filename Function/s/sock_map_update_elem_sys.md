# Function: <code>sock_map_update_elem_sys</code>

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
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681680,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:568",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681680,
      "name": "sock_map_update_elem_sys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589664720,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:562",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589664720,
      "name": "sock_map_update_elem_sys",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:553",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592709009,
      "name": "sock_map_update_elem_sys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590421392,
      "name": "sock_map_update_elem_sys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:547",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594595307,
      "name": "sock_map_update_elem_sys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071592019712,
      "name": "sock_map_update_elem_sys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:549",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596332024,
      "name": "sock_map_update_elem_sys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071593835360,
      "name": "sock_map_update_elem_sys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:545",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596860818,
      "name": "sock_map_update_elem_sys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594209920,
      "name": "sock_map_update_elem_sys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
```

```json
{
  "name": "sock_map_update_elem_sys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595007344,
      "name": "sock_map_update_elem_sys",
      "external": true,
      "loc": "net/core/sock_map.c:547",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595007344,
      "name": "sock_map_update_elem_sys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int sock_map_update_elem_sys(struct bpf_map * map, void * key, void * value, u64 flags)
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
