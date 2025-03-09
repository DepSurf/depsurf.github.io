# Function: <code>bpf_iter_detach_map</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040800,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:147",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589762784,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:903",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040800,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589762784,
      "name": "bpf_iter_detach_map",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054192,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:147",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589666432,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:903",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054192,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589666432,
      "name": "bpf_iter_detach_map",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279216,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:147",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590423312,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:902",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279216,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071590423312,
      "name": "bpf_iter_detach_map",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573600,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:147",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592022160,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:921",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581573600,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071592022160,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950336,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:147",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593837744,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:891",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950336,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593837744,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138416,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:147",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594212304,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:889",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138416,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594212304,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_detach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285760,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:146",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595009664,
      "name": "bpf_iter_detach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:890",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285760,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071595009664,
      "name": "bpf_iter_detach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void bpf_iter_detach_map(struct bpf_iter_aux_info * aux)
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
