# Struct: <code>n_tty_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    int minimum_to_wake;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    size_t lookahead_count;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    size_t lookahead_count;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    unsigned int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    u8[4096] read_buf;
    long unsigned int[64] read_flags;
    u8[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    size_t lookahead_count;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
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
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[8] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[128] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
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
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct n_tty_data {
    size_t read_head;
    size_t commit_head;
    size_t canon_head;
    size_t echo_head;
    size_t echo_commit;
    size_t echo_mark;
    long unsigned int[4] char_map;
    long unsigned int overrun_time;
    int num_overrun;
    bool no_room;
    unsigned char lnext;
    unsigned char erasing;
    unsigned char raw;
    unsigned char real_raw;
    unsigned char icanon;
    unsigned char push;
    char[4096] read_buf;
    long unsigned int[64] read_flags;
    unsigned char[4096] echo_buf;
    size_t read_tail;
    size_t line_start;
    unsigned int column;
    unsigned int canon_column;
    size_t echo_tail;
    struct mutex atomic_read_lock;
    struct mutex output_lock;
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
<b>Field removed. </b>
<code>int minimum_to_wake</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t lookahead_count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int num_overrun</code> ➡️ <code>unsigned int num_overrun</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[4096] read_buf</code> ➡️ <code>u8[4096] read_buf</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned char[4096] echo_buf</code> ➡️ <code>u8[4096] echo_buf</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[4] char_map</code> ➡️ <code>long unsigned int[8] char_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[64] read_flags</code> ➡️ <code>long unsigned int[128] read_flags</code>
</li>
</ul>
</details>
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
