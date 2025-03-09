# Function: <code>acpi_ut_get_mutex_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621724,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:426",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621724,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584847441,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847441,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950818,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950818,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153827,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153827,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585290189,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290189,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996651,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996651,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119497,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119497,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996206,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996206,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586485608,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586485608,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739891,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739891,
      "name": "acpi_ut_get_mutex_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589063488,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589063488,
      "name": "acpi_ut_get_mutex_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589354800,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354800,
      "name": "acpi_ut_get_mutex_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589661648,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:388",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589661648,
      "name": "acpi_ut_get_mutex_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497607096,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497607096,
      "name": "acpi_ut_get_mutex_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585129989,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585129989,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585045244,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045244,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585241773,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241773,
      "name": "acpi_ut_get_mutex_name",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```

```json
{
  "name": "acpi_ut_get_mutex_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585347933,
      "name": "acpi_ut_get_mutex_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:387",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_release_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/utmutex.c:acpi_ut_acquire_mutex",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_locks",
        "drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347933,
      "name": "acpi_ut_get_mutex_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const char * acpi_ut_get_mutex_name(u32 mutex_id)
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
