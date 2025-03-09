# Function: <code>kdb_register_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104800,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2692",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104800,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138656,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2692",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138656,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179024,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2691",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179024,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186592,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2694",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186592,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237968,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2694",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_init",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237968,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580301568,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2679",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301568,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351264,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2659",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351264,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403920,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403920,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452688,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452688,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540592,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2663",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540592,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580528368,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2663",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528368,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580532352,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2635",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532352,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491729920,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491729920,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225675984,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225675984,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284751376,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284751376,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580421488,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421488,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580368560,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368560,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580412736,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412736,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```

```json
{
  "name": "kdb_register_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580468320,
      "name": "kdb_register_flags",
      "external": true,
      "loc": "kernel/debug/kdb/kdb_main.c:2658",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_inittab",
        "kernel/debug/kdb/kdb_main.c:kdb_register",
        "kernel/debug/kdb/kdb_main.c:kdb_defcmd2",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/debug/kdb/kdb_bp.c:kdb_initbptab",
        "kernel/trace/trace_kdb.c:kdb_ftrace_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468320,
      "name": "kdb_register_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int kdb_register_flags(char * cmd, kdb_func_t func, char * usage, char * help, short int minlen, kdb_cmdflags_t flags)
```
</details>
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
