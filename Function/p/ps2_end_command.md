# Function: <code>ps2_end_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554016,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:66",
      "file": "drivers/input/serio/libps2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554016,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950516,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:65",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947872,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586138932,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:65",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136320,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586227876,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:65",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586225248,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586691156,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:65",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586688528,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586957498,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:113",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953920,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587118362,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:113",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114784,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587383002,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379360,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587584938,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587581280,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588446408,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588442736,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588476376,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588472720,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588358488,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588354928,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589022117,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589018352,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590460228,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590457440,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592102612,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:110",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099696,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592526340,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:141",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592523344,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593270932,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:141",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593267936,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500726252,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500722064,
      "name": "ps2_end_command",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233248452,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233246224,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294171308,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294166064,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277571938,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277568572,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587277754,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274096,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587046186,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042576,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587536186,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532528,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void ps2_end_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_end_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587646506,
      "name": "ps2_end_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:109",
      "file": "drivers/input/serio/libps2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/input/serio/libps2.c:ps2_sliced_command",
        "drivers/input/serio/libps2.c:ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587644336,
      "name": "ps2_end_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
