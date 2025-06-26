+++
title = "Choosing the right backup tool"
date = 2025-05-03
+++

{{ img(id="https://ik.imagekit.io/7to9r88cx/1746298650030.jpg?updatedAt=1750459532109", class="textCenter") }}

#### What Open-Source tools you can use to backup your files in 2025

Choosing the right backup tool is key to protecting your data. You would like to store videos of your cat as long and as secure as possible, right?)

I’ve been researching user-friendly backup tools that fit personal or small-scale use. I excluded enterprise-focused tools like **Bareos** and **Amanda**, as they’re less suited for simple backups.

To streamline the process, I used **Grok** to create a table comparing key features of popular backup tools. Check it out below to find the best fit for your needs!

<details class="spoiler">
    <summary>Table with clickable links </summary>

| *Tool*         | GitHub Repo             | Language | License      | GUI | Encryption | Stars | Commits  | Year |
|--------------|-------------------------|----------|--------------|-----|------------|-------|----------|------|
| **Restic**       | [restic/restic](https://github.com/restic/restic)           | Go       | BSD 2-Clause | No  | Yes        | 27.3k | 3,900+   | 2014 |
| **Rustic**       | [rustic-rs/rustic](https://github.com/rustic-rs/rustic)        | Rust     | Apache 2.0/MIT | No  | Yes        | 1.7k  | 1,200+   | 2021 |
| **Kopia**        | [kopia/kopia](https://github.com/kopia/kopia)             | Go       | Apache 2.0   | Yes | Yes        | 8.3k  | 2,800+   | 2019 |
| **Duplicity**    | [duplicity/duplicity](https://gitlab.com/duplicity/duplicity)     | Python   | GPL 2.0      | No  | Yes        | 1.1k  | 2,400+   | 2002 |
| **Duplicati**    | [duplicati/duplicati](https://github.com/duplicati/duplicati)     | C#       | LGPL 2.1     | Yes | Yes        | 10.8k | 6,600+   | 2008 |
| **Duplicacy**    | [gilbertchen/duplicacy](https://github.com/gilbertchen/duplicacy)   | Go       | Proprietary (EULA) | Yes | Yes        | 5.6k  | 1,600+   | 2016 |
| **rdiff-backup** | [rdiff-backup/rdiff-backup](https://github.com/rdiff-backup/rdiff-backup) | Python | GPL 2.0     | No  | No         | 1.1k  | 2,300+   | 2000 |
| **bup**          | [bup/bup](https://github.com/bup/bup)                 | Python   | GPL 2.0      | No  | No         | 7.1k  | 2,100+   | 2010 |
| **Bupstash**    | [andrewchambers/bupstash](https://github.com/andrewchambers/bupstash) | Rust     | MIT          | No  | Yes        | 1.2k  | 600+     | 2020 |
    
</details>

{{ img(id="https://ik.imagekit.io/7to9r88cx/1746295788916.png?updatedAt=1750459530198", class="textCenter") }}

If you want to see that I have filtered, see this great resource -> [https://github.com/restic/others](https://github.com/restic/others)

In my next post, I might explore backup wrappers like [Déjà Dup](https://apps.gnome.org/DejaDup/) and [Backupninja](https://0xacab.org/liberate/backupninja). Or tell more about each tool listed in the table)
