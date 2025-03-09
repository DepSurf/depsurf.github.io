# Struct: <code>atkbd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    u32[24] function_row_physmap;
    int num_function_row_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    u32[24] function_row_physmap;
    int num_function_row_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    u32[24] function_row_physmap;
    int num_function_row_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    u32[24] function_row_physmap;
    int num_function_row_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    struct vivaldi_data vdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    struct vivaldi_data vdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    struct vivaldi_data vdata;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
    struct vivaldi_data vdata;
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
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[16] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
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
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct atkbd {
    struct ps2dev ps2dev;
    struct input_dev * dev;
    char[64] name;
    char[32] phys;
    short unsigned int id;
    short unsigned int[512] keycode;
    long unsigned int[8] force_release_mask;
    unsigned char set;
    bool translated;
    bool extra;
    bool write;
    bool softrepeat;
    bool softraw;
    bool scroll;
    bool enabled;
    unsigned char emul;
    bool resend;
    bool release;
    long unsigned int xl_bit;
    unsigned int last;
    long unsigned int time;
    long unsigned int err_count;
    struct delayed_work event_work;
    long unsigned int event_jiffies;
    long unsigned int event_mask;
    struct mutex mutex;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32[24] function_row_physmap</code>
</li>
<li>
<b>Field added. </b>
<code>int num_function_row_keys</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct vivaldi_data vdata</code>
</li>
<li>
<b>Field removed. </b>
<code>u32[24] function_row_physmap</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_function_row_keys</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[8] force_release_mask</code> ➡️ <code>long unsigned int[16] force_release_mask</code>
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
