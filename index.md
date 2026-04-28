---
layout: default
---

# `$ whoami`

**Yung**. 
Undergraduate (2023 Intake) majoring in Artificial Intelligence @Soochow University.

## `> cat /etc/research_interests`

My current compute bandwidth is allocated to:
* **Time-Series Forecasting**: Pushing the boundaries of long-horizon prediction.
* **Continual Learning**: Cross-domain adaptation, currently iterating on **PICOL-Net** for battery State of Health (SOH) prediction.

## `> neofetch --stdout`

* **OS**: Arch Linux (Wayland/Niri/Hyprland)
* **Editor**: Neovim (LazyVim)
* **Peripherals**: HHKB Professional

---

## `> ls -l ./recent_posts/`
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <span>[{{ post.date | date: "%Y-%m-%d" }}]</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[`./view_archive.sh`](/archive.md)
