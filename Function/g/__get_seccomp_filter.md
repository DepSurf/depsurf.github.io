# Function: <code>__get_seccomp_filter</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270480,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:477",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270480,
      "name": "__get_seccomp_filter",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330912,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:486",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330912,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580384480,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:547",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384480,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437120,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:552",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437120,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580485888,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485888,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580575328,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:563",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:init_listener",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580564275,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:905",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:init_listener",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580570925,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:910",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580740733,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:913",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580954070,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:919",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581248566,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:919",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581343542,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:919",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581450625,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:928",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491768784,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225717900,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284813588,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272088306,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580454688,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580454688,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580401760,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580401760,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580445936,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445936,
      "name": "__get_seccomp_filter",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```

```json
{
  "name": "__get_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580501568,
      "name": "__get_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:553",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501568,
      "name": "__get_seccomp_filter",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __get_seccomp_filter(struct seccomp_filter * filter)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
