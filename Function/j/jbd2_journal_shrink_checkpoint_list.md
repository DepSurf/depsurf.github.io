# Function: <code>jbd2_journal_shrink_checkpoint_list</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t * journal, long unsigned int * nr_to_scan)
```

```json
{
  "name": "jbd2_journal_shrink_checkpoint_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:505",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592274044,
      "name": "jbd2_journal_shrink_checkpoint_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071583801952,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t * journal, long unsigned int * nr_to_scan)
```

```json
{
  "name": "jbd2_journal_shrink_checkpoint_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:505",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594055965,
      "name": "jbd2_journal_shrink_checkpoint_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071584366624,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t * journal, long unsigned int * nr_to_scan)
```

```json
{
  "name": "jbd2_journal_shrink_checkpoint_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:505",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596086166,
      "name": "jbd2_journal_shrink_checkpoint_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071585017856,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t * journal, long unsigned int * nr_to_scan)
```

```json
{
  "name": "jbd2_journal_shrink_checkpoint_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245408,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:409",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245408,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t * journal, long unsigned int * nr_to_scan)
```

```json
{
  "name": "jbd2_journal_shrink_checkpoint_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585478656,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:403",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_journal_shrink_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585478656,
      "name": "jbd2_journal_shrink_checkpoint_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int jbd2_journal_shrink_checkpoint_list(journal_t * journal, long unsigned int * nr_to_scan)
```
</details>
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
