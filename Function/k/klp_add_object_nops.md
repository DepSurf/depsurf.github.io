# Function: <code>klp_add_object_nops</code>

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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580024729,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580075706,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int klp_add_object_nops(struct klp_patch * patch, struct klp_object * old_obj)
```

```json
{
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132512,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:503",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132512,
      "name": "klp_add_object_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int klp_add_object_nops(struct klp_patch * patch, struct klp_object * old_obj)
```

```json
{
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110736,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:503",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_enable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110736,
      "name": "klp_add_object_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580114545,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:502",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_add_nops"
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580256785,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:502",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_add_nops"
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580425953,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:502",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_add_nops"
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580665985,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:526",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_add_nops"
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580742161,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:541",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_add_nops"
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580827125,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:541",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_add_nops"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284198064,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580044442,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579989754,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580035978,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "klp_add_object_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580086682,
      "name": "klp_add_object_nops",
      "external": false,
      "loc": "kernel/livepatch/core.c:481",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
int klp_add_object_nops(struct klp_patch * patch, struct klp_object * old_obj)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int klp_add_object_nops(struct klp_patch * patch, struct klp_object * old_obj)
```
</details>
</li>
</ul>
