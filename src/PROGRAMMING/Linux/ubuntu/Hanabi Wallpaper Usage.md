Links: [HD2 Omens](<https://moewalls.com/games/helldivers-2-omens-of-tyranny-live-wallpaper/>), [HD2 Escalation](<https://moewalls.com/games/helldivers-2-escalation-of-freedom-live-wallpaper/>), [Vib-ribbon](<https://www.youtube.com/watch?v=HXD5pfonpNs>), [Kirby in pond](<https://moewalls.com/fantasy/yellow-kirby-floating-on-the-pond-live-wallpaper/>), [Bocchi the Rock](<https://moewalls.com/anime/kessoku-band-live-show-bocchi-the-rock-live-wallpaper/>)
___

```dataview
TABLE WITHOUT ID
    link(file.link, title) as Title,
    "<progress max=" + 100 + " value=" + cpu_usage + "> </progress> " + round(cpu_usage/100*100) + "%" as "CPU Usage",
    "<progress max=" + ram_total + " value=" + ram_usage + "> </progress> " + round(ram_usage/ram_total*100) + "%" as "Ram Usage"
FROM #process_progress
SORT cpu_usage ASC
```
[[Vib-ribbon]], [[Kirby in Pond]], [[Bocchi The Rock]], [[HellDivers 2 Omens]], [[HellDivers 2 Escalation]]

#dataview/progress #hanabi