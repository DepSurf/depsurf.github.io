# Function: <code>bpf_hash_map_seq_find_next</code>

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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044528,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1698",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044528,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059088,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1698",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059088,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284112,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1878",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284112,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580000,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1915",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580000,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958032,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1946",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958032,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146480,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1959",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146480,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
```

```json
{
  "name": "bpf_hash_map_seq_find_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295536,
      "name": "bpf_hash_map_seq_find_next",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1981",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_next",
        "kernel/bpf/hashtab.c:bpf_hash_map_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295536,
      "name": "bpf_hash_map_seq_find_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
struct htab_elem * bpf_hash_map_seq_find_next(struct bpf_iter_seq_hash_map_info * info, struct htab_elem * prev_elem)
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
