# Function: <code>misc_cg_cancel_charge</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, long unsigned int amount)
```

```json
{
  "name": "misc_cg_cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421984,
      "name": "misc_cg_cancel_charge",
      "external": false,
      "loc": "kernel/cgroup/misc.c:116",
      "file": "kernel/cgroup/misc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421984,
      "name": "misc_cg_cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, long unsigned int amount)
```

```json
{
  "name": "misc_cg_cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580585381,
      "name": "misc_cg_cancel_charge",
      "external": false,
      "loc": "kernel/cgroup/misc.c:116",
      "file": "kernel/cgroup/misc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585344,
      "name": "misc_cg_cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071592162044,
      "name": "misc_cg_cancel_charge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, long unsigned int amount)
```

```json
{
  "name": "misc_cg_cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580787566,
      "name": "misc_cg_cancel_charge",
      "external": false,
      "loc": "kernel/cgroup/misc.c:116",
      "file": "kernel/cgroup/misc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786784,
      "name": "misc_cg_cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071593935123,
      "name": "misc_cg_cancel_charge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, long unsigned int amount)
```

```json
{
  "name": "misc_cg_cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581071630,
      "name": "misc_cg_cancel_charge",
      "external": false,
      "loc": "kernel/cgroup/misc.c:116",
      "file": "kernel/cgroup/misc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070800,
      "name": "misc_cg_cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071596000341,
      "name": "misc_cg_cancel_charge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, long unsigned int amount)
```

```json
{
  "name": "misc_cg_cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581161303,
      "name": "misc_cg_cancel_charge",
      "external": false,
      "loc": "kernel/cgroup/misc.c:116",
      "file": "kernel/cgroup/misc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161216,
      "name": "misc_cg_cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071596518826,
      "name": "misc_cg_cancel_charge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, u64 amount)
```

```json
{
  "name": "misc_cg_cancel_charge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581266855,
      "name": "misc_cg_cancel_charge",
      "external": false,
      "loc": "kernel/cgroup/misc.c:116",
      "file": "kernel/cgroup/misc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge",
        "kernel/cgroup/misc.c:misc_cg_try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266768,
      "name": "misc_cg_cancel_charge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071597419176,
      "name": "misc_cg_cancel_charge.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg * cg, long unsigned int amount)
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int amount</code> ➡️ <code>u64 amount</code>
</li>
</ul>
</details>
</li>
</ul>
