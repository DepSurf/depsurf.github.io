# Function: <code>kexec_purgatory_setup_sechdrs</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127918,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:784",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580175230,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:842",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580221313,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:887",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580269585,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:892",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336400,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:879",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336400,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580321712,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:897",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321712,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325200,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:899",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325200,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479408,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:899",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479408,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580673808,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:858",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673808,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580944784,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:862",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944784,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581031824,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:865",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581031824,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130080,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:881",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kexec_load_purgatory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130080,
      "name": "kexec_purgatory_setup_sechdrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284474516,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:892",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580238385,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:892",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580185937,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:892",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580229649,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:892",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
  "name": "kexec_purgatory_setup_sechdrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580282625,
      "name": "kexec_purgatory_setup_sechdrs",
      "external": false,
      "loc": "kernel/kexec_file.c:892",
      "file": "kernel/kexec_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:kexec_load_purgatory"
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info * pi, struct kexec_buf * kbuf)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
