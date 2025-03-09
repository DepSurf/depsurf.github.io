# Function: <code>do_fchmodat</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558192,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:586",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558192,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643680,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:575",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643680,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760416,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760416,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832624,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832624,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053232,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:624",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053232,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102112,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:614",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102112,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126960,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:616",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126960,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443600,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:613",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443600,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582961648,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:637",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961648,
      "name": "do_fchmodat",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583520224,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:637",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520224,
      "name": "do_fchmodat",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583735664,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:674",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735664,
      "name": "do_fchmodat",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_fchmodat(int dfd, const char * filename, umode_t mode, unsigned int flags)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583937959,
      "name": "do_fchmodat",
      "external": false,
      "loc": "fs/open.c:679",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ],
      "caller_func": [
        "fs/open.c:__ia32_sys_fchmodat2",
        "fs/open.c:__x64_sys_fchmodat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936688,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493295904,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__arm64_sys_chmod",
        "fs/open.c:__arm64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493295904,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226899132,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_chmod",
        "fs/open.c:__se_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226899132,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286834512,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_chmod",
        "fs/open.c:__se_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286834512,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273040838,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_chmod",
        "fs/open.c:__se_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273040838,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801360,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801360,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739024,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739024,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792672,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792672,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```

```json
{
  "name": "do_fchmodat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861808,
      "name": "do_fchmodat",
      "external": true,
      "loc": "fs/open.c:595",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "init/initramfs.c:do_name",
        "fs/open.c:__ia32_sys_chmod",
        "fs/open.c:__x64_sys_chmod",
        "fs/open.c:__ia32_sys_fchmodat",
        "fs/open.c:__x64_sys_fchmodat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861808,
      "name": "do_fchmodat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int do_fchmodat(int dfd, const char * filename, umode_t mode)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
