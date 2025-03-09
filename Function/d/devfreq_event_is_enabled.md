# Function: <code>devfreq_event_is_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586108816,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108816,
      "name": "devfreq_event_is_enabled",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586522352,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586522352,
      "name": "devfreq_event_is_enabled",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702048,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702048,
      "name": "devfreq_event_is_enabled",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586828832,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828384,
      "name": "devfreq_event_is_enabled.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071586828448,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587316560,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316112,
      "name": "devfreq_event_is_enabled.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587316176,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587619360,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587618912,
      "name": "devfreq_event_is_enabled.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587618976,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587748928,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:109",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748480,
      "name": "devfreq_event_is_enabled.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587748544,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588053489,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053024,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588053088,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588259457,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258992,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588259056,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589138965,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589138256,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589138133,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137424,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589028165,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589027456,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589743861,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589743088,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591254520,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591253712,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593009224,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593008352,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593460744,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593459872,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594207736,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206816,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501719028,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501718528,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336501718600,
      "name": "devfreq_event_is_enabled",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234242404,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234241936,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3234242000,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295163872,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295163152,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 13835058055295163264,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278134588,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278134172,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446743936278134242,
      "name": "devfreq_event_is_enabled",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587871153,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587870688,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587870752,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587597953,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587597488,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587597552,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588196513,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588196048,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588196112,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool devfreq_event_is_enabled(struct devfreq_event_dev * edev)
```

```json
{
  "name": "devfreq_event_is_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588331809,
      "name": "devfreq_event_is_enabled",
      "external": true,
      "loc": "drivers/devfreq/devfreq-event.c:106",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ],
      "caller_func": [
        "drivers/devfreq/devfreq-event.c:devfreq_event_reset_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_get_event",
        "drivers/devfreq/devfreq-event.c:devfreq_event_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331344,
      "name": "devfreq_event_is_enabled.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588331408,
      "name": "devfreq_event_is_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
