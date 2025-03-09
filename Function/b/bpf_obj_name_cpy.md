# Function: <code>bpf_obj_name_cpy</code>

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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542704,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:361",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542704,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626768,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:410",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626768,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580687216,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:438",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687216,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754160,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:470",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754160,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804752,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804752,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937088,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:712",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937088,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933792,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:719",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933792,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936496,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:720",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936496,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140336,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:736",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140336,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414608,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:857",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414608,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768736,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:956",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768736,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581930528,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:955",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930528,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int bpf_obj_name_cpy(char * dst, const char * src, unsigned int size)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057040,
      "name": "bpf_obj_name_cpy",
      "external": true,
      "loc": "kernel/bpf/syscall.c:985",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057040,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492120528,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492120528,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226021352,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226021352,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285328256,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285328256,
      "name": "bpf_obj_name_cpy",
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272291868,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272291868,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773552,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773552,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719728,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719728,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764800,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764800,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int bpf_obj_name_cpy(char * dst, const char * src)
```

```json
{
  "name": "bpf_obj_name_cpy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822960,
      "name": "bpf_obj_name_cpy",
      "external": false,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822960,
      "name": "bpf_obj_name_cpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int bpf_obj_name_cpy(char * dst, const char * src)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int size</code>
</li>
</ul>
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
