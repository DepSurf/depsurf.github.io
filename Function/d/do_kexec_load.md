# Function: <code>do_kexec_load</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981536,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:108",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981536,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012032,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:108",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012032,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580019248,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:107",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019248,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066192,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:107",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:compat_SyS_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066192,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:107",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123376,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071580125230,
      "name": "do_kexec_load.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:108",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170512,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071580172487,
      "name": "do_kexec_load.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216432,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071580218409,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264832,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071580266770,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580334272,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334272,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319664,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319664,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323152,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323152,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:87",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477808,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071592160415,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672288,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:87",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672288,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942848,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:87",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942848,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029984,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:87",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029984,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128192,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:87",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128192,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491507768,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__arm64_compat_sys_kexec_load",
        "kernel/kexec.c:__arm64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491507768,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225488924,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__se_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225488924,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284468224,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__se_compat_sys_kexec_load",
        "kernel/kexec.c:__se_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284468224,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233632,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071580235570,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181184,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071580183122,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225104,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071580227042,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```

```json
{
  "name": "do_kexec_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_kexec_load",
      "external": false,
      "loc": "kernel/kexec.c:106",
      "file": "kernel/kexec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277872,
      "name": "do_kexec_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    },
    {
      "addr": 18446744071580279810,
      "name": "do_kexec_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_kexec_load(long unsigned int entry, long unsigned int nr_segments, struct kexec_segment * segments, long unsigned int flags)
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
