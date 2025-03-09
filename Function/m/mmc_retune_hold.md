# Function: <code>mmc_retune_hold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585931664,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:86",
      "file": "drivers/mmc/core/host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931664,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586335659,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:109",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586336528,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586544427,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:109",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586545296,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586667979,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:107",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668880,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587152235,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:107",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153088,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587451729,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:107",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452624,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587631873,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:107",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632768,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587909659,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910560,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588115611,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116528,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588978187,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979088,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588989376,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:106",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588990368,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588875867,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:145",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877808,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589578971,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:163",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580192,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591074203,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:163",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591075424,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592789915,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:163",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592791312,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593226347,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:163",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593227888,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593981231,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:162",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593982784,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501368852,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501369776,
      "name": "mmc_retune_hold",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233858764,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233859600,
      "name": "mmc_retune_hold",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294924236,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294925488,
      "name": "mmc_retune_hold",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277979696,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277980590,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587737179,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738096,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588070139,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071056,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_hold",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588187675,
      "name": "mmc_retune_hold",
      "external": true,
      "loc": "drivers/mmc/core/host.c:104",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588188592,
      "name": "mmc_retune_hold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void mmc_retune_hold(struct mmc_host * host)
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
