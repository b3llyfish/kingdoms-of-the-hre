# Kingdoms of the HRE 
Mod that changes how Kingdoms are formed in the HRE for both the player and AI.
These changes apply to both existing HRE Kingdoms and creatable ones.

## Key Details
**Kingdoms**
* Kingdoms within the HRE's '_sphere of influence_' can no longer be created manually by vassals of the HRE
* HRE vassals will need to petition the Emperor in order to be granted a Kingdom title
* The Emperor will be given the options to either bestow the Kingdom title or reject the petition, risking further trouble with the vassal
* Improve your change of acceptance by swaying the Emperor, or guarantee it with a strong hook blackmail...
* Form new HRE Kingdoms of Upper Saxony, Lower Saxony or Slavinia
* Flavorization changes rename Kingdoms (with some exceptions) to Principalities to better reflect the structure of the HRE

**Cultures**
* Requires the Royal Court DLC
* Upon gaining a Kingdom characters you are not a cultural head will receive an event to diverge their culture
* See more unique cultures such as Austrian, Swiss, or Lothringian

**Decisions**
* Decisions to form Austria and Switzerland have been removed and instead incorporated into this mod
* As a Saxon prince unite your people to form the Kingdom of Saxony!
* As an archduke of Austria establish your dynasty to gain early access to single heir succession
* As the leader of the Swiss Confederation build cities to receive region wide buffs from the Cantons

**Artifacts**
* Gain a crown to kick-start your reign upon gaining a Kingdom
* Also receive the Golden Bull used to justify your reign as a court artifact

## Petition the Emperor for a Kingdom Decision
New decision for Dukes and Counts that are members of the HRE. 
Select a specific Kingdom to petition the Emperor for, providing the character meets the Kingdom's specific requirements.

### Vassal Options
When sending the decision the vassal will have the options to improve their chances, either by winning a diplomacy check
against the Emperor or spending by gold.

If they have a strong hook against the Emperor they will also have the option to use that which guarantees acceptance, 
but at an extreme cost to your relationship to the Emperor.

Should the Emperor refuse the petition the Vassal may decide it's time to take the Empire for themselves and could gain 
an unpressed claim on the HRE...

### Acceptance Chance
The biggest factor for the Emperor's accept chance is their opinion of you, ranging from -100 to 100.

Other things that can affect the decision are:
* whether the vassal is an elector
* whether the vassal is a powerful vassal
* the vassal options as described above
* how honorable the Emperor's personality is
* the Emperor's Acceptance Modifier game rule

## Existing Kingdoms
The following Kingdoms are considered under the HRE's sphere of influence:
* Bavaria
* Burgundy
* Frisia
* Italy
* Lotharingia
* Bohemia
* Pomerania

The following Kingdoms are considered under the HRE's sphere of influence if they are a de jure part of the HRE when it is formed
* Aquitaine
* Brittany
* France

## Creatable Kingdoms
The decisions to create Switzerland and Austria have been removed and instead combined into the petition decision. Their criteria
have also been stripped to match the rest of the Kingdoms.

Creatable Kingdoms are created in the same way as existing Kingdoms (i.e control the majority of a particular region) with
the following additional criteria:
* Capital must be located in the creatable Kingdom's region (can be disabled via game rules)

### Austria
Control the region comprising the duchies of Osterreich and Steyermark.

The ability to gain extra duchies has been removed as I felt it didn't add anything useful gameplay wise.

No longer gives Primogeniture upon formation and instead this can be gained by using the 'Secure the Archduchy' decision
which requires your dynasty to have a particular renown level (level required is configurable via game rules).

### Switzerland
Control the region comprising the duchies of Transjurania and Currezia.

The ability to gain extra duchies has been removed as I felt it didn't add anything useful gameplay wise.

No longer gives Absolute Crown Authority upon formation (an exceedingly dull bonus in my opinion). Instead, the 'Empower the Cantons'
decision has been added which will give a development and build speed/cost reduction across all counties in Switzerland should
you build enough city holdings.

### Lower Saxony
Control the region comprising the duchies Angria, Holstein, Ostfalen and Westfalen.

Requires Saxon (or child of) culture (can be disabled via game rules).

Gains access to the 'Unite the Saxons' decision.

### Upper Saxony
Control the region comprising the duchies Anhalt, Lausitz, Meissen and Thuringia. If playing the 867 start date then only
region comprising the duchies Anhalt and Thuringia are needed (the others can be made de jure by controlling them).

Requires Saxon (or child of) culture (can be disabled via game rules).

Gains access to the 'Unite the Saxons' decision.

### Saxony
Cannot be formed via a petition but instead via a the 'Unite the Saxons' decision available to Lower and Upper Saxony.

Merges the Lower and Upper Saxony Kingdoms together and give the Saxon Elective succession law.

### Slavinia
As Pomerania has a Pommeranian culture requirement, Slavinia has been added as a Kingdom for Germanic characters.

Control the region comprising the duchies of Nordmark and Ostmark.

Requires a culture with Central Germanic heritage (can be disabled via game rules).

## Culture
Upon receiving a Kingdom the following check will happen:
* is dlc Royal Court enabled?
* is the character AI and game rule allows AI culture divergence?
* is the character **not** a cultural head?

If the above checks passes another check is done to see if culture divergence is possible. If it is the character will 
be given an event to either trigger culture divergence or not. If culture divergence it not possible then the will get an event
to either convert to local culture or not. Note that the AI will always take the option to either diverge or convert to local culture.

Certain Kingdom titles will have special divergence rules and will their diverged culture will be thematically crafted
(e.g Austrian will have traditions promoting diplomacy and festivities). Otherwise the divergence will happen randomly.

## Event Overrides
The `culture_conversion.0001` event has been overridden and the following adding:
* vassals will be more likely to convert if they hold **no** counties with their old culture
* barony titles are now included in the modifier checks which should encourage barony holders to convert

## 867 Start Date
This mod has largely been designed around start dates with an established HRE, however there has been some attempt to 
cater for the 867 start date. Specifically the situation where all of Francia becomes de jure part of the HRE. 

In this scenario Brittany, France and Aquitaine can only be formed via the petition decision.

The Kingdom of Upper Saxony will have slightly easier requirements in the 867 start due to the existence of Sorbia.

## Game Rules

### Culture Check
Whether to impose a culture requirement for certain Kingdoms. 

Options: Required (default), Not Required.

### Emperor's Acceptance Modifier
Whether to modifier the Emperor's accept petition chance, making it easier or harder to form a Kingdom. 

Options: Halved, No modifier (default), Doubled 

### Austria Renown Level
The dynasty renown level required for the 'Secure the Archduchy' decision. 

Options: Noteworthy, Reputable (default), Well-Known

### Capital Region Check
Whether to require that capitals are in certain regions for certain Kingdoms.
Options: Required (default), Not Required.

## Flavorization
This mod applies the following flavorization to HRE vassals holding HRE Kingdoms:
* Kingdom Title -> Principality
* Kingdom Title Holder (Male) -> Prince
* Kingdom Title Holder (Female) -> Princess

The exception to this rule is Bohemia, which historically was allowed to be the only Kingdom in the HRE.

The mod also enables the Switzerland flavorization, which already existed in game but for whatever reason was disabled.

## Compatibility
This mod will likely be incompatible with mods in the following areas:
* mods that add/change/remove titles related to the HRE Kingdoms defined above
* mods that change the form Austria or Switzerland decisions (though the underlying scripted effects are untouched)
* mods that change flavorization of the HRE Kingdoms

### Similar Mods
These mods do similar things and could be use an alternative. They are assumed to be incompatible with this mod.
* [Restore Saxony](https://steamcommunity.com/sharedfiles/filedetails/?id=2412107778&searchtext=saxony) - Implements the Kingdom of Saxony
* [No HRE Kingdoms](https://steamcommunity.com/sharedfiles/filedetails/?id=2420327048&searchtext=hre+kingdoms) - Prevents the AI from forming HRE Kingdoms

## Localization
Basic localization for supported locales has been provided by using [CK3_LocalizationChanger](https://github.com/b3llyfish/CK3_LocalizationChanger).

I am accepting any localization improvements via mods and will happily link them below. 
If your chosen language is listed below then this mod must be used to support your localization. 

[Chinese Localization Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3090564070) - thanks to [無壹](https://steamcommunity.com/profiles/76561198113539588)

## Bug/Issues
This mod has been tested to the best of my abilities. If any bugs or issues are found please described them in a comment.