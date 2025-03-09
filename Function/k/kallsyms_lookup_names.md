# Function: <code>kallsyms_lookup_names</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int kallsyms_lookup_names(const char * name, unsigned int * start, unsigned int * end)
```

```json
{
  "name": "kallsyms_lookup_names",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924288,
      "name": "kallsyms_lookup_names",
      "external": false,
      "loc": "kernel/kallsyms.c:214",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:kallsyms_on_each_match_symbol",
        "kernel/kallsyms.c:kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924288,
      "name": "kallsyms_lookup_names",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int kallsyms_lookup_names(const char * name, unsigned int * start, unsigned int * end)
```

```json
{
  "name": "kallsyms_lookup_names",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581011584,
      "name": "kallsyms_lookup_names",
      "external": false,
      "loc": "kernel/kallsyms.c:210",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:kallsyms_on_each_match_symbol",
        "kernel/kallsyms.c:kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581011584,
      "name": "kallsyms_lookup_names",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
int kallsyms_lookup_names(const char * name, unsigned int * start, unsigned int * end)
```

```json
{
  "name": "kallsyms_lookup_names",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107456,
      "name": "kallsyms_lookup_names",
      "external": false,
      "loc": "kernel/kallsyms.c:208",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:kallsyms_on_each_match_symbol",
        "kernel/kallsyms.c:kallsyms_lookup_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107456,
      "name": "kallsyms_lookup_names",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int kallsyms_lookup_names(const char * name, unsigned int * start, unsigned int * end)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
