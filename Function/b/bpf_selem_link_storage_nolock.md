# Function: <code>bpf_selem_link_storage_nolock</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581138879,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:159",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137760,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581095300,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:160",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094160,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581324660,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:160",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323408,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581628252,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:189",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626816,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582015100,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:198",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013568,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582206908,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:370",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205488,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_link_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582356120,
      "name": "bpf_selem_link_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:370",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354752,
      "name": "bpf_selem_link_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void bpf_selem_link_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem)
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
