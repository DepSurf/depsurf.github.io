# Function: <code>tty_audit_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tty_audit_log(const char * description, int major, int minor, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009744,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:63",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_buf_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009744,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341504,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:62",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341504,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523344,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:62",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523344,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584606848,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:62",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606848,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585019376,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585019376,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585253568,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585253568,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372992,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372992,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586784,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586784,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585727696,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727696,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586458640,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586458640,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572976,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572976,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457840,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:61",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457840,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586984768,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:61",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984768,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588282096,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:61",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588282096,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697888,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:61",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697888,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
void tty_audit_log(const char * description, dev_t dev, const unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590002576,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:61",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590002576,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void tty_audit_log(const char * description, dev_t dev, const u8 * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590340944,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:61",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_push",
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590340944,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498426416,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498426416,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231092492,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231092492,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291609024,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291609024,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276077952,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276077952,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585488720,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488720,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585358560,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358560,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678096,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678096,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void tty_audit_log(const char * description, dev_t dev, unsigned char * data, size_t size)
```

```json
{
  "name": "tty_audit_log",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585786128,
      "name": "tty_audit_log",
      "external": false,
      "loc": "drivers/tty/tty_audit.c:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_audit.c:tty_audit_tiocsti",
        "drivers/tty/tty_audit.c:tty_audit_buf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786128,
      "name": "tty_audit_log",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t dev</code>
</li>
<li>
<b>Param removed. </b>
<code>int major</code>
</li>
<li>
<b>Param removed. </b>
<code>int minor</code>
</li>
<li>
<b>Param reordered. </b>
<code>description, major, minor, data, size</code> ➡️ <code>description, dev, data, size</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char * data</code> ➡️ <code>const unsigned char * data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char * data</code> ➡️ <code>const u8 * data</code>
</li>
</ul>
</details>
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
