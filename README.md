Fantasy Grounds Extention to roll spell attack rolls versus target DC on PFRPG2

## SpellAttack VsDc
This is a special trait similar to the monster automation VsDC. It actually uses the PF2 VsDC system as a base already present in Fantasy Grounds. When this trait is added to spell attacks traits it will replace the spell attack roll with a skill check vs targets apropiate save/skill DC.

The trait template is "SKILLVS:*skill_name*:VS:*dc_type*". You can put any Skill name starting with a capital letter in place of "*skill_name*" (i.e. Diplomacy, Intimidation) . Youcan put any skill name or Save type in place of "*dc_type*" ( i.e. REF,WILL, Perception)

*Example:* **SKILLVS:Intimidation:VS:WILL**. With this the caster will roll diplomacy skill check against the Will save DC of his target

In addion to spell attacks. If you perform an attack while holding down the "Ctrl" key and the weapon you are using has suitable VsDc taits ( i.e trip, disatm etc.) the system will replace the attack roll with a VsDC skill check suitable to the weapon trait (i.e Athletics skill check Vs targets Ref dc if the weapon has "trip" trait)


## Shield Up Effect condition
When "sieldup" keyword is used on condition check ( see: https://www.fantasygrounds.com/wiki/index.php/PFRPG2_Effects) it will activate the following effect if the char shield is raised. You can add this condiyional effects on characters, feat or item automations

*Example:* **IF:sieldup;SAVE:2 reflex** will give tha character +2 reflex save bonus if/when shield is raised 
