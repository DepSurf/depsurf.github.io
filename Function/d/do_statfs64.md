# Function: <code>do_statfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210880,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:148",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_statfs64",
        "fs/statfs.c:SYSC_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210880,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375552,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:148",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375552,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453296,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:148",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453296,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508400,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:151",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508400,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650544,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:152",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_fstatfs64",
        "fs/statfs.c:SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650544,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813168,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:152",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813168,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900160,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:152",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900160,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025600,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025600,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582103584,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582103584,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340592,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340592,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392080,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392080,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419440,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419440,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742256,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742256,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289360,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289360,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872976,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872976,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094736,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094736,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584310880,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:168",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310880,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493642728,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493642728,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227179760,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_sys_fstatfs64",
        "fs/statfs.c:__se_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227179760,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287233152,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287233152,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273276920,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273276920,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072320,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072320,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582009872,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009872,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063600,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063600,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int do_statfs64(struct kstatfs * st, struct statfs64 * p)
```

```json
{
  "name": "do_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135344,
      "name": "do_statfs64",
      "external": false,
      "loc": "fs/statfs.c:166",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_sys_fstatfs64",
        "fs/statfs.c:__do_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135344,
      "name": "do_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
