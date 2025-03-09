# Function: <code>kfence_init_pool</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool kfence_init_pool()
```

```json
{
  "name": "kfence_init_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615401282,
      "name": "kfence_init_pool",
      "external": false,
      "loc": "mm/kfence/core.c:428",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615401282,
      "name": "kfence_init_pool",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 531
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
long unsigned int kfence_init_pool()
```

```json
{
  "name": "kfence_init_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707376,
      "name": "kfence_init_pool",
      "external": false,
      "loc": "mm/kfence/core.c:540",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/kfence/core.c:kfence_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707376,
      "name": "kfence_init_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
long unsigned int kfence_init_pool()
```

```json
{
  "name": "kfence_init_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233040,
      "name": "kfence_init_pool",
      "external": false,
      "loc": "mm/kfence/core.c:539",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/kfence/core.c:kfence_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233040,
      "name": "kfence_init_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
long unsigned int kfence_init_pool()
```

```json
{
  "name": "kfence_init_pool",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450608,
      "name": "kfence_init_pool",
      "external": false,
      "loc": "mm/kfence/core.c:567",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/kfence/core.c:kfence_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450608,
      "name": "kfence_init_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
long unsigned int kfence_init_pool()
```

```json
{
  "name": "kfence_init_pool",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645104,
      "name": "kfence_init_pool",
      "external": false,
      "loc": "mm/kfence/core.c:571",
      "file": "mm/kfence/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_init_late",
        "mm/kfence/core.c:kfence_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645104,
      "name": "kfence_init_pool.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071583645744,
      "name": "kfence_init_pool",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool kfence_init_pool()
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
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
