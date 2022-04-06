This extension started as a tool to make my PFRPG2 campaign more easy to run. 

Configuration:
For ease of development I outputted the Debug logs chat or console. You can configure this from the settings. Plus you can turn of logging totally ( no need for logs while actually playing the game session)

## Features:
**SpellAttack VsDc:** I used spell attacks to implement VsDC functionality because most of the VsDC checks I used in our campaign included attacks ( trip, shove etc.).  it has a easy usage by ctrl + double click weapon roll to use the appropriate skill decided by the weapon trait

**Shield Up Effect Condition:** Idea came up when players found a "Dragon Slayer Shield" since there were some other fighter feats doing the same thing I developed this.



## SpellAttack VsDc
This is a special trait similar to the monster automation VsDC. It actually uses the PF2 VsDC system as a base already present in Fantasy Grounds. When this trait is added to spell attacks traits it will replace the spell attack roll with a skill check vs targets appropriate save/skill DC.

The trait template is "SKILLVS:*skill_name*:VS:*dc_type*". You can put any Skill name starting with a capital letter in place of "*skill_name*" (i.e. Diplomacy, Intimidation) . You can put any skill name or Save type in place of "*dc_type*" ( i.e. REF,WILL, Perception)

In addition to this, if your weapon has the appropriate trait ( like trip or shove) ctrl + double clicking attack roll on the actions tab (on character sheet) will roll the suitable VsDC skill check against your target

### How to Use: 
Add a spell to the character on shar sheet on Actions tab.
Open the cast action details and type VsDC keyword to the spell traits.

![Cast Action](http://burcinsayin.xyz/cast_action.png)

![Cast Action Details](http://burcinsayin.xyz/cast_action_details.png)

**SKILLVS:Intimidation:VS:WILL**. With this the caster will roll diplomacy skill check against the Will save DC of his target

In addition to spell attacks. If you perform an attack while holding down the "Ctrl" key and the weapon you are using has suitable VsDc traits ( i.e trip, disarm etc.) the system will replace the attack roll with a VsDC skill check suitable to the weapon trait (i.e Athletics skill check Vs targets Ref dc if the weapon has "trip" trait)


## Shield Up Effect Condition
When "sieldup" keyword is used on condition check ( see: https://www.fantasygrounds.com/wiki/index.php/PFRPG2_Effects) it will activate the following effect if the char shield is raised. You can add this conditional effects on characters, feat or item automations

*Example:* **IF:sieldup;SAVE:2 reflex** will give the character +2 reflex save bonus if/when shield is raised 

![Shield with Shield Up Cond.](http://burcinsayin.xyz/dragon_slayer_shield.png)

*Example:* In above example when shield is equipped and raised character gets +2 reflex save bonus