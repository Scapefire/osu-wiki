---
tags:
  - online song offset
---

# Online offset

*For other uses, see [Offset (disambiguation)](/wiki/Disambiguation/Offset).*

**Online offset** is an offset that can be applied to a [beatmap](/wiki/Beatmap) after it is initially [ranked](/wiki/Beatmap/Category#ranked). This is usually done when a beatmap needs small timing changes to correctly line it up with the song. Online offset values are applied on top of a player's [universal offset](/wiki/Client/Options/Universal_offset) and [local offset](/wiki/Glossary/Local_song_offset) values.<!--technically it's universal offset -> online offset -> local offset but that's probably not worth mentioning here-->

All online offset values are stored locally for later use. This allows the values to be applied even if a player is playing offline as long as they have been connected to the internet prior to importing or playing the beatmap.

## History

::: Infobox
![](img/beatmap-management-panel.jpg "Beatmap management panel, old website")
:::

::: Infobox
![](img/beatmap-management-panel-new.png "Beatmap management panel, new website")
:::

Online offset was implemented in September 2008[^changelog-add] for the [Beatmap Appreciation Team](/wiki/Modding/Beatmap_Appreciation_Team) to make it possible to fix a beatmap's timing without unranking. Over the course of time, it was accessible to the members of different teams overseeing the ranking process, such as the [Quality Assurance Team](/wiki/Modding/Quality_Assurance_Team) (QAT), [Nomination Assessment Team](/wiki/People/The_Team/Nomination_Assessment_Team) (NAT), and the [Global Moderation Team](/wiki/People/The_Team/Global_Moderation_Team) due to similar user group permissions.

In May 2019, NAT has declared during the QAT restructuring follow-up[^qat-restructuring-follow-up-pr] that an invalid offset required a beatmap unrank and could not have been fixed via the respective website controls. Regardless, the whole map management panel was made visible to [Beatmap Nominators](/wiki/People/The_Team/Beatmap_Nominators).

In April 2022, online offset controls were added[^new-website-offset] to the new website, but were restricted only to administrators a week after to prevent misuse.[^new-website-offset-restriction]

## References

[^changelog-add]: [Forum post by peppy (2008-09-16)](https://osu.ppy.sh/community/forums/posts/50194)
[^qat-restructuring-follow-up-pr]: ["BN Rules: Disqualifications", pull request by MoMan (2019-05-05)](https://github.com/ppy/osu-wiki/pull/2160)
[^new-website-offset]: ["Add offset edit to beatmapset metadata controls", pull request by venix12 (2021-04-12)](https://github.com/ppy/osu-web/pull/7474)
[^new-website-offset-restriction]: ["Only allow admin to edit beatmap offset", pull request by nanaya (2022-04-22)](https://github.com/ppy/osu-web/pull/8834)
