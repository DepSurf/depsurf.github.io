# Function: <code>bpf_get_current_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 bpf_get_current_comm(u64 r1, u64 size, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580382112,
      "name": "bpf_get_current_comm",
      "external": false,
      "loc": "kernel/bpf/helpers.c:161",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382112,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
u64 bpf_get_current_comm(u64 r1, u64 size, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442192,
      "name": "bpf_get_current_comm",
      "external": false,
      "loc": "kernel/bpf/helpers.c:161",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442192,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496544,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:155",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496544,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525248,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:155",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525248,
      "name": "bpf_get_current_comm",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587664,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:155",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587664,
      "name": "bpf_get_current_comm",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683168,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:155",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683168,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754048,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:196",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754048,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836832,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836832,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887856,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887856,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581026768,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:206",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026768,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033840,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:217",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033840,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045424,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:218",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045424,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268624,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:218",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268624,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:237",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960175,
      "name": "bpf_get_current_comm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071581560176,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932912,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:252",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932912,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116176,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:253",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116176,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582256512,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:257",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256512,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492213368,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492213368,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226110760,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226110760,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285434944,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285434944,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272362078,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272362078,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856656,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856656,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802816,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802816,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847904,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847904,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
u64 bpf_get_current_comm(u64 buf, u64 size, u64 __ur_1, u64 __ur_2, u64 __ur_3)
```

```json
{
  "name": "bpf_get_current_comm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906192,
      "name": "bpf_get_current_comm",
      "external": true,
      "loc": "kernel/bpf/helpers.c:191",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906192,
      "name": "bpf_get_current_comm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 buf</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
