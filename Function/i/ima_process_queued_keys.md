# Function: <code>ima_process_queued_keys</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584206099,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:127",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205856,
      "name": "ima_process_queued_keys.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071584206384,
      "name": "ima_process_queued_keys",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584324531,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:132",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584324288,
      "name": "ima_process_queued_keys.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071584324816,
      "name": "ima_process_queued_keys",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584359040,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:133",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584359040,
      "name": "ima_process_queued_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584752182,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:133",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592309843,
      "name": "ima_process_queued_keys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071584752128,
      "name": "ima_process_queued_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585433226,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:133",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594092169,
      "name": "ima_process_queued_keys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071585433152,
      "name": "ima_process_queued_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586190234,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:133",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103082,
      "name": "ima_process_queued_keys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071586190160,
      "name": "ima_process_queued_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586427962,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:133",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596626188,
      "name": "ima_process_queued_keys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071586427888,
      "name": "ima_process_queued_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ima_process_queued_keys()
```

```json
{
  "name": "ima_process_queued_keys",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586693114,
      "name": "ima_process_queued_keys",
      "external": true,
      "loc": "security/integrity/ima/ima_queue_keys.c:133",
      "file": "security/integrity/ima/ima_queue_keys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_queue_keys.c:ima_keys_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597531830,
      "name": "ima_process_queued_keys.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071586693040,
      "name": "ima_process_queued_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ima_process_queued_keys()
```
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
