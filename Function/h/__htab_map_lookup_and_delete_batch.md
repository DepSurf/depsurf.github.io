# Function: <code>__htab_map_lookup_and_delete_batch</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042464,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1342",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042464,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051408,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1405",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051408,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2112
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
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066912,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1405",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066912,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2118
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
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289616,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1585",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289616,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589184,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1614",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589184,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2447
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973264,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1641",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973264,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163904,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1654",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163904,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3487
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
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```

```json
{
  "name": "__htab_map_lookup_and_delete_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582312592,
      "name": "__htab_map_lookup_and_delete_batch",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1676",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_lookup_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582312592,
      "name": "__htab_map_lookup_and_delete_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3443
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map * map, const union bpf_attr * attr, union bpf_attr * uattr, bool do_delete, bool is_lru_map, bool is_percpu)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
