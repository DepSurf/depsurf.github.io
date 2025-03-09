# Function: <code>selinux_free_mnt_opts</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583129584,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:396",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129584,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583316560,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:397",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316560,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583421856,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583421856,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583777084,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:353",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762176,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583897772,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:354",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881968,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583923758,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:383",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908368,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584289418,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:360",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272080,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584905857,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:349",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584888704,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585614136,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:351",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585595856,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585845156,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:347",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826800,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586095974,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:383",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586065440,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495178848,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495178848,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228566204,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228566204,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289118224,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289118224,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274419734,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274419734,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390592,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390592,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327680,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327680,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374368,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374368,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void selinux_free_mnt_opts(void * mnt_opts)
```

```json
{
  "name": "selinux_free_mnt_opts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583467952,
      "name": "selinux_free_mnt_opts",
      "external": false,
      "loc": "security/selinux/hooks.c:399",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467952,
      "name": "selinux_free_mnt_opts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void selinux_free_mnt_opts(void * mnt_opts)
```
</details>
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
