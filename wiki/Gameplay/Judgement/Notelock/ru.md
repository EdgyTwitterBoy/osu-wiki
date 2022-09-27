---
tags:
  - note lock
  - jittering notes
  - shaking notes
  - нотлок
  - нот лок
  - нота трясется
---

# Нотлок

![](img/notelock.gif "Проявление нотлока: на вторую ноту нельзя нажать")

**Нотлок** (англ. *notelock*, букв. *блокировка ноты*) — неформальное название игровой механики [osu!](/wiki/Game_mode/osu!), которая может помешать нажать на игровой объект. Она срабатывает, если одновременно выполнены **два** условия:

1. [Окна попадания](/wiki/Beatmapping/Overall_difficulty#тайминг) этих объектов пересекаются.
2. Попадание по первому объекту не было оценено, и он ещё активен (по нему можно попасть).

В этом случае говорят, что первый объект блокирует (или *лочит*) второй. osu! будет игнорировать любые попытки игрока нажать на второй объект, пока активно окно попадания от первого. Нотлок мешает играть только тогда, когда игрок по какой-то причине не может попасть по первому объекту и тем самым разблокировать остальные. Это может привести к цепной реакции, когда игрок не может вовремя нажать на остальные объекты, потому что первые два ещё не пройдены, и т.д., и в итоге промахивается до тех пор, пока у него не закончится [здоровье](/wiki/Gameplay/Health), что влечёт за собой проигрыш карты.

Внешне нотлок проявляется в том, что нажимаемая нота трясётся на месте, а нажатие не засчитывается. Слайдеры и спиннеры в случае нотлока остаются неподвижными.

## Причина

Нотлок — часть системы тайминга osu!, которая срабатывает, когда у двух объектов пересекаются окна попадания. С ним можно столкнуться на картах с низким [OD](/wiki/Beatmapping/Overall_difficulty) или высоким [BPM](/wiki/Beatmapping/Beats_per_minute), потому что окна у нот на таких картах пересекаются чаще, чем на остальных.

Поскольку задумка игры состоит в том, что игрок должен проходить карты, взаимодействуя с объектами в порядке их появления, нотлок обычно играет положительную роль:

- Игрок не может взять и пропустить часть карты, проходя лишь отдельные объекты.
- На быстрых картах высокой сложности нотлок не даёт сбиться с ритма и начать нажимать ноты как попало.

## Предотвращение

Нотлок можно предотвратить при маппинге, подобрав OD карты для [сложности](/wiki/Beatmap/Difficulty) в соответствии с её плотностью объектов и BPM песни. При BPM от 200 и выше рекомендуется использовать OD от 5 и выше. Подробнее см. в руководстве [Avoiding notelock at high BPM](https://osu.ppy.sh/community/forums/topics/334458).