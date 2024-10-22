# freebsd_timezone

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

## Requirements

None.


## Variables

Review the defaults and examples in vars.


## Workflow

1) Change shell to /bin/sh

```
shell> ansible srv.example.com -e 'ansible_shell_type=csh ansible_shell_executable=/bin/csh' -a 'sudo pw usermod freebsd -s /bin/sh'
```

2) Install role

```
shell> ansible-galaxy install nholuong.freebsd_timezone
```

3) Fit variables

```
shell> editor nholuong.freebsd_timezone/vars/main.yml
```

4) Create playbook

```
shell> cat freebsd-timezone.yml

- hosts: srv.example.com
  roles:
    - nholuong.freebsd_timezone
```

5) Configure the timezone

```
shell> ansible-playbook freebsd-timezone.yml
```


## References

[How time is affected by the ntpd and /etc/localtime](http://serverfault.com/questions/303517/how-time-is-affected-by-the-ntpd-and-etc-localtime)


# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
