# Function: <code>cpa_flush_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579297162,
      "name": "cpa_flush_range",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:177",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579296525,
      "name": "cpa_flush_range",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:183",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579312037,
      "name": "cpa_flush_range",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:183",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpa_flush_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309697,
      "name": "cpa_flush_range",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:190",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cpa_flush_range(long unsigned int start, int numpages, int cache)
```

```json
{
  "name": "cpa_flush_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327360,
      "name": "cpa_flush_range",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:190",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327360,
      "name": "cpa_flush_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cpa_flush_range(long unsigned int start, int numpages, int cache)
```

```json
{
  "name": "cpa_flush_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338304,
      "name": "cpa_flush_range",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:208",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:__set_memory_enc_dec",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338304,
      "name": "cpa_flush_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cpa_flush_range(long unsigned int start, int numpages, int cache)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void cpa_flush_range(long unsigned int start, int numpages, int cache)
```
</details>
</li>
</ul>
