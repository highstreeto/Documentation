# Clan

Assembly: `TaleWorlds.CampaignSystem.dll` 

Namespace: `TaleWorlds.CampaignSystem`

[Heros](hero.md) are typically part of a larger group called a clan. A clan has a leader and typically a few members. But there are clans that have no members except the leader.

## Constructors

They are primarily loaded from an XML file. See TODO.

## Properties

| Name           | Type          | Description                                                                                       |
| -------------- | ------------- | ------------------------------------------------------------------------------------------------- |
| `Name`         | TextObject    | Name of this clan                                                                                 |
| `InformalName` | TextObject    | Shorter name of this clan (mostly the same as `Name` but for mercenary companies this is shorter) |
| `FullName`     | TextObject    | Full name of this clan, adds a appropriate suffix to `Name`                                       |
| `Culture`      | CultureObject | Culture of this clan. Can be changed.                                                             |

## Functions

