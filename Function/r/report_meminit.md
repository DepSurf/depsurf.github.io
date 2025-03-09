# Function: <code>report_meminit</code>

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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604641484,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604653745,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
void report_meminit()
```

```json
{
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609004442,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:781",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609004442,
      "name": "report_meminit",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612069098,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:793",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614207243,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:794",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615125610,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:809",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616887465,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:802",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627477635,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:807",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619620718,
      "name": "report_meminit",
      "external": false,
      "loc": "mm/mm_init.c:2691",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621924862,
      "name": "report_meminit",
      "external": false,
      "loc": "mm/mm_init.c:2679",
      "file": "mm/mm_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510803656,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243249248,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302365120,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270601092,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604580017,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604571729,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604657841,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
  "name": "report_meminit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604657841,
      "name": "report_meminit",
      "external": false,
      "loc": "init/main.c:524",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel"
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
void report_meminit()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void report_meminit()
```
</details>
</li>
</ul>
