# Function: <code>bpf_iter_attach_map</code>

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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041104,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:101",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589762816,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:873",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041104,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071589762816,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054496,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:101",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589666464,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:873",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054496,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071589666464,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279520,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:101",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590423344,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:872",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279520,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071590423344,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573936,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:101",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592022496,
      "name": "bpf_iter_attach_map",
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
      "addr": 18446744071581573936,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071592022496,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950752,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:101",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593838144,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:861",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950752,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071593838144,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138832,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:101",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594212704,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:859",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138832,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071594212704,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
```

```json
{
  "name": "bpf_iter_attach_map",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286240,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "kernel/bpf/map_iter.c:100",
      "file": "kernel/bpf/map_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595010064,
      "name": "bpf_iter_attach_map",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:860",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286240,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071595010064,
      "name": "bpf_iter_attach_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int bpf_iter_attach_map(struct bpf_prog * prog, union bpf_iter_link_info * linfo, struct bpf_iter_aux_info * aux)
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
