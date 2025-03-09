# Function: <code>unmap_ldt_struct</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060181,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579068015,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579070111,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void unmap_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt)
```

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077232,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077232,
      "name": "unmap_ldt_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579080387,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579087253,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579110341,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579141389,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579185773,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579189831,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579219063,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:349",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579070463,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579003123,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579070047,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
  "name": "unmap_ldt_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579074143,
      "name": "unmap_ldt_struct",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:265",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void unmap_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void unmap_ldt_struct(struct mm_struct * mm, struct ldt_struct * ldt)
```
</details>
</li>
</ul>
