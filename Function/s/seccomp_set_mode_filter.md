# Function: <code>seccomp_set_mode_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580137181,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:764",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580171894,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:729",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580212534,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:728",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580222387,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:821",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580272087,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:844",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580334705,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:850",
      "file": "kernel/seccomp.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580389720,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1246",
      "file": "kernel/seccomp.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442896,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1251",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442896,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580491232,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491232,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1862
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580577776,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1292",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577776,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567248,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1778",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567248,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580570048,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1826",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570048,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580739856,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1808",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739856,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953136,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1837",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953136,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247632,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1837",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247632,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342608,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1837",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342608,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449616,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1901",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449616,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491767672,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491767672,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225716848,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225716848,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284812064,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284812064,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272087534,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272087534,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
    }
  ]
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580460032,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580460032,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1862
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407088,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407088,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1856
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451280,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451280,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1862
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
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```

```json
{
  "name": "seccomp_set_mode_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580506928,
      "name": "seccomp_set_mode_filter",
      "external": false,
      "loc": "kernel/seccomp.c:1274",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580506928,
      "name": "seccomp_set_mode_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1876
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char * filter)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
