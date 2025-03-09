# Function: <code>do_quotactl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581424750,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:640",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:SyS_quotactl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581606974,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:696",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:SyS_quotactl"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581695512,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:698",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:SyS_quotactl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749610,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:698",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:SyS_quotactl"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581896714,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:699",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:SyS_quotactl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582079925,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:700",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:kernel_quotactl"
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
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582174023,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:698",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:kernel_quotactl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582336608,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582336608,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435792,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435792,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582730352,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:682",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730352,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1607
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802576,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:764",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802576,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1650
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830480,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:766",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl_path",
        "fs/quota/quota.c:__ia32_sys_quotactl_path",
        "fs/quota/quota.c:__x64_sys_quotactl_path",
        "fs/quota/quota.c:__x64_sys_quotactl_path",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830480,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1546
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162960,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:766",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162960,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1572
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583653696,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:767",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653696,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1669
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259744,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:767",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259744,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1669
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584490096,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:767",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490096,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1688
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584713056,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:767",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__x64_sys_quotactl_fd",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__ia32_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl",
        "fs/quota/quota.c:__x64_sys_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713056,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1688
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494049448,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494049448,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1796
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227509968,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227509968,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1940
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287704256,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287704256,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2028
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273550988,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273550988,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582404528,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582404528,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342224,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342224,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395008,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395008,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
```

```json
{
  "name": "do_quotactl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474544,
      "name": "do_quotactl",
      "external": false,
      "loc": "fs/quota/quota.c:684",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:kernel_quotactl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474544,
      "name": "do_quotactl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
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
int do_quotactl(struct super_block * sb, int type, int cmd, qid_t id, void * addr, const struct path * path)
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
