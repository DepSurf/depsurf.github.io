# Function: <code>mmc_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585948896,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:583",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948896,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586354176,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:587",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586354176,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586563168,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563168,
      "name": "mmc_switch",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586687263,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:598",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687056,
      "name": "mmc_switch",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587171695,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:599",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587171488,
      "name": "mmc_switch",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587471491,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:599",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471280,
      "name": "mmc_switch",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587651795,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:599",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651584,
      "name": "mmc_switch",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587929866,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:601",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929648,
      "name": "mmc_switch",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588135770,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588135552,
      "name": "mmc_switch",
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588999153,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:632",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588998832,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589008977,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:632",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589008656,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588896444,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:612",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896016,
      "name": "mmc_switch",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589600647,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:629",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589600224,
      "name": "mmc_switch",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591097367,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:659",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591097008,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592816247,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:659",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815776,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593252935,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:660",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593252432,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594008183,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:660",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable",
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:_mmc_flush_cache",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_hs400es",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/mmc.c:__mmc_select_powerclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594007680,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501388448,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501388120,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233877844,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_reset",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233877576,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294949040,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294948672,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277997108,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width",
        "drivers/mmc/core/block.c:mmc_blk_remove",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_reset",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd",
        "drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277996872,
      "name": "mmc_switch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587757338,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587757120,
      "name": "mmc_switch",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588090298,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090080,
      "name": "mmc_switch",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_switch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588207834,
      "name": "mmc_switch",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:603",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_init_card",
        "drivers/mmc/core/mmc.c:mmc_select_timing",
        "drivers/mmc/core/mmc.c:mmc_select_hs400",
        "drivers/mmc/core/mmc.c:mmc_select_bus_width"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588207616,
      "name": "mmc_switch",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int mmc_switch(struct mmc_card * card, u8 set, u8 index, u8 value, unsigned int timeout_ms)
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
