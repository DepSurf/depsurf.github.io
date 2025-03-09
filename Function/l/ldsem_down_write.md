# Function: <code>ldsem_down_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587380528,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:390",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587380528,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587883488,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:390",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883488,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588100240,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:390",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100240,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588325776,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:390",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588325776,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588891888,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:388",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891888,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589270176,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:388",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589270176,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589512736,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:364",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512736,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589971872,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589971872,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590199280,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590199280,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591215792,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591215792,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591710928,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591710928,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591658320,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658320,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592831968,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592831968,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594741184,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594741184,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596493392,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596493392,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597034592,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597034592,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597966560,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597966560,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503946448,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503946448,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236555436,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236555436,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297799696,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297799696,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279809928,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279809928,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801568,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801568,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589524000,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524000,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590244976,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590244976,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int ldsem_down_write(struct ld_semaphore * sem, long int timeout)
```

```json
{
  "name": "ldsem_down_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590296032,
      "name": "ldsem_down_write",
      "external": true,
      "loc": "drivers/tty/tty_ldsem.c:363",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590296032,
      "name": "ldsem_down_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
