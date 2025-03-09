# Function: <code>scsi_initialize_rq</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438848,
      "name": "scsi_initialize_rq",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1114",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438848,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585882169,
      "name": "scsi_initialize_rq",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1149",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869232,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586128624,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1186",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115600,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586271152,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1117",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261616,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586514830,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506080,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586662830,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653968,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587461936,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1083",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449440,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587529984,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1113",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517600,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587412000,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1085",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399200,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587984367,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1085",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969184,
      "name": "scsi_initialize_rq",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325568,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1116",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_init_command",
        "drivers/scsi/scsi_lib.c:__scsi_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325568,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590891808,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1121",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_init_command",
        "drivers/scsi/scsi_lib.c:__scsi_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590891808,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591235232,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1122",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_init_command",
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235232,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591582480,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1121",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_init_command",
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582480,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499563136,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499551328,
      "name": "scsi_initialize_rq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232024868,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232015676,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292858728,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292845968,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276759472,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276751174,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586353310,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344448,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586194638,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185776,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586610798,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601936,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_initialize_rq(struct request * rq)
```

```json
{
  "name": "scsi_initialize_rq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586723246,
      "name": "scsi_initialize_rq",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:1082",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_init_command"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714208,
      "name": "scsi_initialize_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void scsi_initialize_rq(struct request * rq)
```
</details>
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
