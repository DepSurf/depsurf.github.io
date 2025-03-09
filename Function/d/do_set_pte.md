# Function: <code>do_set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_set_pte(struct vm_area_struct * vma, long unsigned int address, struct page * page, pte_t * pte, bool write, bool anon)
```

```json
{
  "name": "do_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674240,
      "name": "do_set_pte",
      "external": true,
      "loc": "mm/memory.c:2810",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674240,
      "name": "do_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```

```json
{
  "name": "do_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604240,
      "name": "do_set_pte",
      "external": true,
      "loc": "mm/memory.c:3822",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604240,
      "name": "do_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```

```json
{
  "name": "do_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870432,
      "name": "do_set_pte",
      "external": true,
      "loc": "mm/memory.c:3967",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870432,
      "name": "do_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```

```json
{
  "name": "do_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582265824,
      "name": "do_set_pte",
      "external": true,
      "loc": "mm/memory.c:4283",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582265824,
      "name": "do_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```

```json
{
  "name": "do_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582757168,
      "name": "do_set_pte",
      "external": true,
      "loc": "mm/memory.c:4284",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582757168,
      "name": "do_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```

```json
{
  "name": "do_set_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582973056,
      "name": "do_set_pte",
      "external": true,
      "loc": "mm/memory.c:4316",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pages",
        "mm/memory.c:finish_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973056,
      "name": "do_set_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void do_set_pte(struct vm_area_struct * vma, long unsigned int address, struct page * page, pte_t * pte, bool write, bool anon)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void do_set_pte(struct vm_fault * vmf, struct page * page, long unsigned int addr)
```
</details>
</li>
</ul>
