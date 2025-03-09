# Function: <code>wb_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580606832,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:342",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:bdi_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606832,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580712368,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:342",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712368,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580778192,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:343",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778192,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814000,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:353",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814000,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904096,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:366",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904096,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581039984,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:356",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039984,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581118240,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:356",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118240,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187449,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:343",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182192,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071581187449,
      "name": "wb_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581241280,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241280,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581430032,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:346",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430032,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473280,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:335",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473280,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493424,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:334",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493424,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752368,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:344",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752368,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132688,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:334",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132688,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609776,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:461",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609776,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582818560,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:466",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582818560,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993040,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:464",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993040,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492637680,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492637680,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226481768,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226481768,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285954720,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285954720,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272654876,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272654876,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581210128,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210128,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156880,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156880,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581201328,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201328,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void wb_shutdown(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581263680,
      "name": "wb_shutdown",
      "external": false,
      "loc": "mm/backing-dev.c:347",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:bdi_unregister",
        "mm/backing-dev.c:cgwb_release_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263680,
      "name": "wb_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
