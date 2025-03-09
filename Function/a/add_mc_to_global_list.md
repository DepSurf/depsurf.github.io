# Function: <code>add_mc_to_global_list</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586561460,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:628",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587028996,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:628",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587327476,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:630",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587505861,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:628",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587779877,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:628",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587984581,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int add_mc_to_global_list(struct mem_ctl_info * mci)
```

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:590",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588839120,
      "name": "add_mc_to_global_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071588844257,
      "name": "add_mc_to_global_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int add_mc_to_global_list(struct mem_ctl_info * mci)
```

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:594",
      "file": "drivers/edac/edac_mc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588855296,
      "name": "add_mc_to_global_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071591593750,
      "name": "add_mc_to_global_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588742692,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:594",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589433156,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:597",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590911251,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:522",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592608871,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:521",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593039431,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:521",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593790855,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:522",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501229004,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233732780,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294757824,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277923594,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587615557,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587383573,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587940725,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
  "name": "add_mc_to_global_list",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588056005,
      "name": "add_mc_to_global_list",
      "external": false,
      "loc": "drivers/edac/edac_mc.c:621",
      "file": "drivers/edac/edac_mc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
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
int add_mc_to_global_list(struct mem_ctl_info * mci)
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
int add_mc_to_global_list(struct mem_ctl_info * mci)
```
</details>
</li>
</ul>
