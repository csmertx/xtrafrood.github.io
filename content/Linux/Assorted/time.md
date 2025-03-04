---
title: 💻 Time
author: Chris Schammert (csmertx -- Christopher Schammert )
published: 2023-01-30
weight: -20
---

<!-- The content of this website was written by Christopher Schammert aka Chris Schammert -->

<br />

## Set Local Time

- Easy

    - ```tzselect```

        > Userland

    - ```sudo tzselect```

        > Global

    - ```reboot```

        > If VM, then reboot host too

- Normal

    - ```sudo cp /usr/share/zoneinfo/America/New\_York /etc/localtime```

    - ```vim /etc/sysconfig/clock```

        - ```++ ZONE="America/New_York"```

    - ```sudo hwclock --utc -s```

    - ```reboot```

        > if VM, then reboot host too

## Resources

- [Linuxize: Linux Time Command](https://linuxize.com/post/linux-time-command/)

- [nixCraft: How To Format Date For Display or Use In a Shell Script](https://www.cyberciti.biz/faq/linux-unix-formatting-dates-for-display/)

<br />

<div style="text-align: center; font-size:12px; color:dimgray">
    Created: 01/07/2023 • Edited: 02/09/2025 • Author: Chris Schammert (csmertx) • 
    <a href="https://github.com/csmertx/csmertx.github.io/commits/main/content/Linux/Assorted/time.md" 
       title="Github.com | csmertx \ csmertx.github.io \ commits \ main \ content \ Linux \ Assorted \ Time">
       History 🕵️
    </a>
</div>
