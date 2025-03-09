# Function: <code>ps2_begin_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585553968,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:57",
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
      "addr": 18446744071585553968,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950467,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:57",
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
      "addr": 18446744071585947824,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586138883,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:57",
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
      "addr": 18446744071586136272,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586227827,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:57",
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
      "addr": 18446744071586225200,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586691107,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:57",
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
      "addr": 18446744071586688480,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586957387,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:105",
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
      "addr": 18446744071586953872,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587118251,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:105",
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
      "addr": 18446744071587114736,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587382891,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071587379312,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587584827,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071587581232,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588446284,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071588442688,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588476252,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071588472672,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588358364,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071588354880,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589021996,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071589018304,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590460108,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071590457392,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592102492,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:102",
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
      "addr": 18446744071592099632,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592526220,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:129",
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
      "addr": 18446744071592523280,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593270812,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:129",
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
      "addr": 18446744071593267872,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500726152,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446603336500722008,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233248332,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 3233246176,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294171172,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 13835058055294165952,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277571830,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446743936277568502,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587277643,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071587274048,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587046075,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071587042528,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587536075,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071587532480,
      "name": "ps2_begin_command",
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
void ps2_begin_command(struct ps2dev * ps2dev)
```

```json
{
  "name": "ps2_begin_command",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587646395,
      "name": "ps2_begin_command",
      "external": true,
      "loc": "drivers/input/serio/libps2.c:101",
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
      "addr": 18446744071587644288,
      "name": "ps2_begin_command",
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
