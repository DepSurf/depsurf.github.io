# Struct: <code>phy_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct phy_driver * drv;
    struct mii_bus * bus;
    struct device dev;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    bool is_c45;
    bool is_internal;
    bool is_pseudo_fixed_link;
    bool has_fixups;
    bool suspended;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int addr;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    int link;
    u32 interrupts;
    u32 supported;
    u32 advertising;
    u32 lp_advertising;
    int autoneg;
    int link_timeout;
    int irq;
    void * priv;
    struct work_struct phy_queue;
    struct delayed_work state_queue;
    atomic_t irq_disable;
    struct mutex lock;
    struct net_device * attached_dev;
    u8 mdix;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    bool is_c45;
    bool is_internal;
    bool is_pseudo_fixed_link;
    bool has_fixups;
    bool suspended;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    int link;
    u32 interrupts;
    u32 supported;
    u32 advertising;
    u32 lp_advertising;
    int autoneg;
    int link_timeout;
    int irq;
    void * priv;
    struct work_struct phy_queue;
    struct delayed_work state_queue;
    atomic_t irq_disable;
    struct mutex lock;
    struct net_device * attached_dev;
    u8 mdix;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    bool is_c45;
    bool is_internal;
    bool is_pseudo_fixed_link;
    bool has_fixups;
    bool suspended;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    int link;
    u32 interrupts;
    u32 supported;
    u32 advertising;
    u32 lp_advertising;
    u32 eee_broken_modes;
    int autoneg;
    int link_timeout;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    int irq;
    void * priv;
    struct work_struct phy_queue;
    struct delayed_work state_queue;
    atomic_t irq_disable;
    struct mutex lock;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    bool is_c45;
    bool is_internal;
    bool is_pseudo_fixed_link;
    bool has_fixups;
    bool suspended;
    bool sysfs_links;
    bool loopback_enabled;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    int link;
    u32 interrupts;
    u32 supported;
    u32 advertising;
    u32 lp_advertising;
    u32 eee_broken_modes;
    int autoneg;
    int link_timeout;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    int irq;
    void * priv;
    struct work_struct phy_queue;
    struct delayed_work state_queue;
    atomic_t irq_disable;
    struct mutex lock;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    bool is_c45;
    bool is_internal;
    bool is_pseudo_fixed_link;
    bool has_fixups;
    bool suspended;
    bool sysfs_links;
    bool loopback_enabled;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    int link;
    u32 interrupts;
    u32 supported;
    u32 advertising;
    u32 lp_advertising;
    u32 eee_broken_modes;
    int autoneg;
    int link_timeout;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct work_struct phy_queue;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    u32 interrupts;
    u32 supported;
    u32 advertising;
    u32 lp_advertising;
    u32 eee_broken_modes;
    int link_timeout;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct work_struct phy_queue;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[1] supported;
    long unsigned int[1] advertising;
    long unsigned int[1] lp_advertising;
    u32 eee_broken_modes;
    int link_timeout;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int is_on_sfp_module;
    unsigned int mac_managed_pm;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int is_on_sfp_module;
    unsigned int mac_managed_pm;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int is_on_sfp_module;
    unsigned int mac_managed_pm;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    unsigned int irq_suspended;
    unsigned int irq_rerun;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    u8 mdix;
    u8 mdix_ctrl;
    int pma_extable;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    struct device_link * devlink;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int is_on_sfp_module;
    unsigned int mac_managed_pm;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    unsigned int irq_suspended;
    unsigned int irq_rerun;
    int rate_matching;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    long unsigned int[1] host_interfaces;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    struct pse_control * psec;
    u8 mdix;
    u8 mdix_ctrl;
    int pma_extable;
    unsigned int link_down_events;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    struct device_link * devlink;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int is_on_sfp_module;
    unsigned int mac_managed_pm;
    unsigned int wol_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    unsigned int irq_suspended;
    unsigned int irq_rerun;
    int rate_matching;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    long unsigned int[2] supported_eee;
    long unsigned int[2] advertising_eee;
    bool eee_enabled;
    long unsigned int[1] host_interfaces;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    struct list_head leds;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    struct pse_control * psec;
    u8 mdix;
    u8 mdix_ctrl;
    int pma_extable;
    unsigned int link_down_events;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    struct device_link * devlink;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int downshifted_rate;
    unsigned int is_on_sfp_module;
    unsigned int mac_managed_pm;
    unsigned int wol_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    unsigned int irq_suspended;
    unsigned int irq_rerun;
    int rate_matching;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    long unsigned int[1] possible_interfaces;
    int speed;
    int duplex;
    int port;
    int pause;
    int asym_pause;
    u8 master_slave_get;
    u8 master_slave_set;
    u8 master_slave_state;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    long unsigned int[2] supported_eee;
    long unsigned int[2] advertising_eee;
    bool eee_enabled;
    long unsigned int[1] host_interfaces;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    struct list_head leds;
    int irq;
    void * priv;
    struct phy_package_shared * shared;
    struct sk_buff * skb;
    void * ehdr;
    struct nlattr * nest;
    struct delayed_work state_queue;
    struct mutex lock;
    bool sfp_bus_attached;
    struct sfp_bus * sfp_bus;
    struct phylink * phylink;
    struct net_device * attached_dev;
    struct mii_timestamper * mii_ts;
    struct pse_control * psec;
    u8 mdix;
    u8 mdix_ctrl;
    int pma_extable;
    unsigned int link_down_events;
    void (*)(struct phy_device *, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
    const struct macsec_ops * macsec_ops;
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
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[3] supported;
    long unsigned int[3] advertising;
    long unsigned int[3] lp_advertising;
    long unsigned int[3] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
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
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct phy_device {
    struct mdio_device mdio;
    struct phy_driver * drv;
    u32 phy_id;
    struct phy_c45_device_ids c45_ids;
    unsigned int is_c45;
    unsigned int is_internal;
    unsigned int is_pseudo_fixed_link;
    unsigned int is_gigabit_capable;
    unsigned int has_fixups;
    unsigned int suspended;
    unsigned int suspended_by_mdio_bus;
    unsigned int sysfs_links;
    unsigned int loopback_enabled;
    unsigned int autoneg;
    unsigned int link;
    unsigned int autoneg_complete;
    unsigned int interrupts;
    enum phy_state state;
    u32 dev_flags;
    phy_interface_t interface;
    int speed;
    int duplex;
    int pause;
    int asym_pause;
    long unsigned int[2] supported;
    long unsigned int[2] advertising;
    long unsigned int[2] lp_advertising;
    long unsigned int[2] adv_old;
    u32 eee_broken_modes;
    struct phy_led_trigger * phy_led_triggers;
    unsigned int phy_num_led_triggers;
    struct phy_led_trigger * last_triggered;
    struct phy_led_trigger * led_link_trigger;
    int irq;
    void * priv;
    struct delayed_work state_queue;
    struct mutex lock;
    struct phylink * phylink;
    struct net_device * attached_dev;
    u8 mdix;
    u8 mdix_ctrl;
    void (*)(struct phy_device *, bool, bool) phy_link_change;
    void (*)(struct net_device *) adjust_link;
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
<b>Field added. </b>
<code>struct mdio_device mdio</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mii_bus * bus</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device dev</code>
</li>
<li>
<b>Field removed. </b>
<code>int addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 eee_broken_modes</code>
</li>
<li>
<b>Field added. </b>
<code>struct phy_led_trigger * phy_led_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int phy_num_led_triggers</code>
</li>
<li>
<b>Field added. </b>
<code>struct phy_led_trigger * last_triggered</code>
</li>
<li>
<b>Field added. </b>
<code>u8 mdix_ctrl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool sysfs_links</code>
</li>
<li>
<b>Field added. </b>
<code>bool loopback_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct phy_led_trigger * led_link_trigger</code>
</li>
<li>
<b>Field added. </b>
<code>struct phylink * phylink</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct phy_device *, bool, bool) phy_link_change</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t irq_disable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>bool is_c45</code> ➡️ <code>unsigned int is_c45</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool is_internal</code> ➡️ <code>unsigned int is_internal</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool is_pseudo_fixed_link</code> ➡️ <code>unsigned int is_pseudo_fixed_link</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool has_fixups</code> ➡️ <code>unsigned int has_fixups</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool suspended</code> ➡️ <code>unsigned int suspended</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool sysfs_links</code> ➡️ <code>unsigned int sysfs_links</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool loopback_enabled</code> ➡️ <code>unsigned int loopback_enabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>int link</code> ➡️ <code>unsigned int link</code>
</li>
<li>
<b>Field type changed. </b>
<code>int autoneg</code> ➡️ <code>unsigned int autoneg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct work_struct phy_queue</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 interrupts</code> ➡️ <code>unsigned int interrupts</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 supported</code> ➡️ <code>long unsigned int[1] supported</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 advertising</code> ➡️ <code>long unsigned int[1] advertising</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 lp_advertising</code> ➡️ <code>long unsigned int[1] lp_advertising</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int is_gigabit_capable</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int autoneg_complete</code>
</li>
<li>
<b>Field removed. </b>
<code>int link_timeout</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[1] supported</code> ➡️ <code>long unsigned int[2] supported</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[1] advertising</code> ➡️ <code>long unsigned int[2] advertising</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[1] lp_advertising</code> ➡️ <code>long unsigned int[2] lp_advertising</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int suspended_by_mdio_bus</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[2] adv_old</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int downshifted_rate</code>
</li>
<li>
<b>Field added. </b>
<code>u8 master_slave_get</code>
</li>
<li>
<b>Field added. </b>
<code>u8 master_slave_set</code>
</li>
<li>
<b>Field added. </b>
<code>u8 master_slave_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct phy_package_shared * shared</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff * skb</code>
</li>
<li>
<b>Field added. </b>
<code>void * ehdr</code>
</li>
<li>
<b>Field added. </b>
<code>struct nlattr * nest</code>
</li>
<li>
<b>Field added. </b>
<code>bool sfp_bus_attached</code>
</li>
<li>
<b>Field added. </b>
<code>struct sfp_bus * sfp_bus</code>
</li>
<li>
<b>Field added. </b>
<code>struct mii_timestamper * mii_ts</code>
</li>
<li>
<b>Field added. </b>
<code>const struct macsec_ops * macsec_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct phy_device *, bool, bool) phy_link_change</code> ➡️ <code>void (*)(struct phy_device *, bool) phy_link_change</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int is_on_sfp_module</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int mac_managed_pm</code>
</li>
</ul>
</details>
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
<code>unsigned int irq_suspended</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int irq_rerun</code>
</li>
<li>
<b>Field added. </b>
<code>int pma_extable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_link * devlink</code>
</li>
<li>
<b>Field added. </b>
<code>int rate_matching</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[1] host_interfaces</code>
</li>
<li>
<b>Field added. </b>
<code>struct pse_control * psec</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int link_down_events</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct macsec_ops * macsec_ops</code> ➡️ <code>const struct macsec_ops * macsec_ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int wol_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[2] supported_eee</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[2] advertising_eee</code>
</li>
<li>
<b>Field added. </b>
<code>bool eee_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head leds</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int[1] possible_interfaces</code>
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
<code>long unsigned int[2] supported</code> ➡️ <code>long unsigned int[3] supported</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] advertising</code> ➡️ <code>long unsigned int[3] advertising</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] lp_advertising</code> ➡️ <code>long unsigned int[3] lp_advertising</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] adv_old</code> ➡️ <code>long unsigned int[3] adv_old</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct phy_led_trigger * phy_led_triggers</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int phy_num_led_triggers</code>
</li>
<li>
<b>Field removed. </b>
<code>struct phy_led_trigger * last_triggered</code>
</li>
<li>
<b>Field removed. </b>
<code>struct phy_led_trigger * led_link_trigger</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
