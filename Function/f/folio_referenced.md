# Function: <code>folio_referenced</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int folio_referenced(struct folio * folio, int is_locked, struct mem_cgroup * memcg, long unsigned int * vm_flags)
```

```json
{
  "name": "folio_referenced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "folio_referenced",
      "external": true,
      "loc": "mm/rmap.c:900",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593978339,
      "name": "folio_referenced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582370336,
      "name": "folio_referenced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int folio_referenced(struct folio * folio, int is_locked, struct mem_cgroup * memcg, long unsigned int * vm_flags)
```

```json
{
  "name": "folio_referenced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "folio_referenced",
      "external": true,
      "loc": "mm/rmap.c:896",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596034194,
      "name": "folio_referenced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582871744,
      "name": "folio_referenced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int folio_referenced(struct folio * folio, int is_locked, struct mem_cgroup * memcg, long unsigned int * vm_flags)
```

```json
{
  "name": "folio_referenced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "folio_referenced",
      "external": true,
      "loc": "mm/rmap.c:902",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596556247,
      "name": "folio_referenced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583088576,
      "name": "folio_referenced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int folio_referenced(struct folio * folio, int is_locked, struct mem_cgroup * memcg, long unsigned int * vm_flags)
```

```json
{
  "name": "folio_referenced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "folio_referenced",
      "external": true,
      "loc": "mm/rmap.c:961",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597460485,
      "name": "folio_referenced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071583271008,
      "name": "folio_referenced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int folio_referenced(struct folio * folio, int is_locked, struct mem_cgroup * memcg, long unsigned int * vm_flags)
```
</details>
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
