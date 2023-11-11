# Sudoers

## /etc/sudoers.d
You can create files in /etc/sudoers.d that will be part of the sudo configuration. Since this doesn’t involve changing groups, you won’t have to log out and back in again. Change your_id to your user ID.
```
your_id ALL=(ALL) NOPASSWD: ALL
```

- [Red Hat Documentation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/9/html/configuring_basic_system_settings/managing-sudo-access_configuring-basic-system-settings)
- [Other Notes](https://developers.redhat.com/blog/2018/08/15/how-to-enable-sudo-on-rhel?source=sso#tl_dr__basic_sudo)
