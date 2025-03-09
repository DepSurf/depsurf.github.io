# Function: <code>klp_shadow_get</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905681,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:95",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905584,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939941,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:95",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939856,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579987029,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:95",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986944,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028656,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028656,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079376,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079376,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138608,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138608,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580115856,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115856,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119440,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119440,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261952,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261952,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580432039,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431472,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580674135,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673504,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580750471,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749840,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580835591,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834960,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284203488,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284203488,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048112,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048112,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993424,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993424,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039648,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039648,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void * klp_shadow_get(void * obj, long unsigned int id)
```

```json
{
  "name": "klp_shadow_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090368,
      "name": "klp_shadow_get",
      "external": true,
      "loc": "kernel/livepatch/shadow.c:83",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090368,
      "name": "klp_shadow_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void * klp_shadow_get(void * obj, long unsigned int id)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * klp_shadow_get(void * obj, long unsigned int id)
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
