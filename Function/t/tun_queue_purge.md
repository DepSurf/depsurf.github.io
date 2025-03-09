# Function: <code>tun_queue_purge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585069360,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:503",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585457264,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:518",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457264,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585661312,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:518",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661312,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748368,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:520",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748368,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586185632,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:603",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185632,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586432896,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:672",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432896,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578832,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:672",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578832,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586830384,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830384,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586976464,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586976464,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587804928,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:634",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804928,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862928,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:605",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862928,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587742016,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:613",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587742016,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588337296,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:619",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337296,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589730800,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:624",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589730800,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591351184,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:624",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591351184,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591712960,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:624",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712960,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592456656,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:624",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592456656,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499967464,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499967464,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232511748,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232511748,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293303264,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293303264,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277047324,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277047324,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586733472,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733472,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600688,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600688,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586931024,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586931024,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void tun_queue_purge(struct tun_file * tfile)
```

```json
{
  "name": "tun_queue_purge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587044000,
      "name": "tun_queue_purge",
      "external": false,
      "loc": "drivers/net/tun.c:666",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:tun_detach_all",
        "drivers/net/tun.c:__tun_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044000,
      "name": "tun_queue_purge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void tun_queue_purge(struct tun_file * tfile)
```
</details>
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
