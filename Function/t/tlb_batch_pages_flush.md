# Function: <code>tlb_batch_pages_flush</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581331910,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581391318,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581589105,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581635057,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581656673,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581924865,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582330000,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:45",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582330000,
      "name": "tlb_batch_pages_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830032,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:84",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830032,
      "name": "tlb_batch_pages_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583045424,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:84",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045424,
      "name": "tlb_batch_pages_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227488,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:85",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227488,
      "name": "tlb_batch_pages_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492797084,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226611004,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226611004,
      "name": "tlb_batch_pages_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286168000,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272764302,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmu_gather.c:tlb_finish_mmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272764302,
      "name": "tlb_batch_pages_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581360166,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303878,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581351366,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tlb_batch_pages_flush",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581415302,
      "name": "tlb_batch_pages_flush",
      "external": false,
      "loc": "mm/mmu_gather.c:44",
      "file": "mm/mmu_gather.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_flush_mmu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather * tlb)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void tlb_batch_pages_flush(struct mmu_gather * tlb)
```
</details>
</li>
</ul>
