# Function: <code>seq_put_decimal_ull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void seq_put_decimal_ull(struct seq_file * m, char delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581143696,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:683",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_put_decimal_ll",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143696,
      "name": "seq_put_decimal_ull",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void seq_put_decimal_ull(struct seq_file * m, char delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581308320,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:686",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_put_decimal_ll",
        "fs/seq_file.c:seq_put_decimal_ll",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308320,
      "name": "seq_put_decimal_ull",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386912,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:693",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386912,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581443168,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:679",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581443168,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581585120,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:683",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585120,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745008,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745008,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831536,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:711",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831536,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955824,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955824,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028544,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028544,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263280,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:699",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_all_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263280,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313024,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:715",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/io_uring.c:io_uring_show_cred",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_all_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313024,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340672,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:737",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/base/power/domain.c:genpd_summary_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340672,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661216,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:746",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/base/power/domain.c:genpd_summary_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661216,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583201280,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:730",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/base/power/domain.c:genpd_summary_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583201280,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583777520,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:730",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/base/power/domain.c:genpd_summary_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777520,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994768,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:730",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/base/power/domain.c:genpd_summary_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994768,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207472,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:730",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "drivers/pmdomain/core.c:genpd_summary_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207472,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493552688,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493552688,
      "name": "seq_put_decimal_ull",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227101556,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227101556,
      "name": "seq_put_decimal_ull",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287123760,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287123760,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273213230,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273213230,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997280,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997280,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934848,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934848,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988560,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988560,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void seq_put_decimal_ull(struct seq_file * m, const char * delimiter, long long unsigned int num)
```

```json
{
  "name": "seq_put_decimal_ull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059024,
      "name": "seq_put_decimal_ull",
      "external": true,
      "loc": "fs/seq_file.c:723",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:pidfd_show_fdinfo",
        "mm/vmstat.c:vmstat_show",
        "fs/proc/task_mmu.c:show_vma_header_prefix",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:proc_pid_statm",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:proc_pid_status",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/array.c:task_state",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat",
        "fs/proc/stat.c:show_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059024,
      "name": "seq_put_decimal_ull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char delimiter</code> ➡️ <code>const char * delimiter</code>
</li>
</ul>
</details>
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
