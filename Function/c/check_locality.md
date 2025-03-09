# Function: <code>check_locality</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584253527,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:139",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tis_int_handler"
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
int check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592688,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:59",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592688,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584773984,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:59",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584773984,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863216,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:59",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863216,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585282176,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:61",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585282176,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519568,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:122",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519568,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585643664,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:122",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585643664,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585868240,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868240,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586010800,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010800,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586748848,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586748848,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842800,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842800,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723264,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723264,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587274720,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:119",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274720,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588585600,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:119",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585600,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590041264,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:119",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041264,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590350656,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:151",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590350656,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590692192,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:151",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590692192,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498808560,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498808560,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231420284,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231420284,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292003680,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    },
    {
      "addr": 13835058055292020480,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_i2c_infineon.c:312",
      "file": "drivers/char/tpm/tpm_i2c_infineon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292003680,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 13835058055292020480,
      "name": "check_locality.isra.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276308128,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276308128,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585771776,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771776,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630960,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630960,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585960816,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585960816,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool check_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "check_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068560,
      "name": "check_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:118",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068560,
      "name": "check_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int check_locality(struct tpm_chip * chip, int l)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
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
