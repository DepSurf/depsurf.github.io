# Function: <code>extcon_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int extcon_set_state(struct extcon_dev * edev, u32 state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586114272,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:344",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:state_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114272,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int extcon_set_state(struct extcon_dev * edev, u32 state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586528458,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:332",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:state_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586528224,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool cable_state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709200,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:523",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709200,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool cable_state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833488,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:537",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833488,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587321264,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:529",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321264,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587624096,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:530",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587624096,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587753536,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:530",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587753536,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588058208,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588058208,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264112,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264112,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589144418,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143952,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071589144256,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589143362,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589142896,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071589143200,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589033474,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032912,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
    },
    {
      "addr": 18446744071589033312,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589749571,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748608,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071592686830,
      "name": "extcon_set_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071589749104,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591261925,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:523",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591261504,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071594572249,
      "name": "extcon_set_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071591261856,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593017397,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:533",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593016944,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071596320031,
      "name": "extcon_set_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071593017312,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593468917,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:543",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593468512,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071596849674,
      "name": "extcon_set_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071593468832,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594216005,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:543",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594215600,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071597774495,
      "name": "extcon_set_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071594215920,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501725736,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501725736,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234254608,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234254608,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 3234255028,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295172624,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295172624,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 13835058055295173248,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278140358,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278140358,
      "name": "extcon_set_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446743936278140816,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875808,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875808,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588201168,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588201168,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```

```json
{
  "name": "extcon_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588336464,
      "name": "extcon_set_state",
      "external": true,
      "loc": "drivers/extcon/extcon.c:522",
      "file": "drivers/extcon/extcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/extcon/extcon.c:extcon_set_state_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588336464,
      "name": "extcon_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
<code>unsigned int id</code>
</li>
<li>
<b>Param added. </b>
<code>bool cable_state</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool state</code>
</li>
<li>
<b>Param removed. </b>
<code>bool cable_state</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int extcon_set_state(struct extcon_dev * edev, unsigned int id, bool state)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
