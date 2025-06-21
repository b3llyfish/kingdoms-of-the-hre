# Kingdoms of the HRE 
Mod that changes how Kingdoms are formed in the HRE for both the player and AI.
These changes apply to both existing HRE Kingdoms and creatable ones.

## Key Details
**Kingdoms**
* Kingdoms within the HRE's '_sphere of influence_' can no longer be created manually by vassals of the HRE
* HRE vassals will need to petition the Emperor in order to be granted a Kingdom title
* The Emperor will be given the options to either bestow the Kingdom title or reject the petition, risking further trouble with the vassal
* Improve your change of acceptance by swaying the Emperor, or guarantee it with a strong hook blackmail...
* Form new HRE Kingdoms of Upper Saxony, Lower Saxony, Carinthia or Slavinia
* Flavorization changes rename Kingdoms (with some exceptions) to Principalities to better reflect the structure of the HRE

**Cultures**
* Requires the Royal Court DLC
* Characters who are not culture heads may be given the option to diverge or convert their culture
* See more unique cultures such as Austrian, Lothringian or Upper Saxon

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
The biggest factor for the Emperor's accept chance is their opinion of the character, ranging from -100 to 50 
(positive relations only contribute half their total).

Other things that can affect the decision are:
* whether the character is a powerful vassal
* the vassal options as described above
* how honourable the Emperor's personality is
* the Emperor's Acceptance Base Chance game rule

For example using the default game rules if a character petitioned the Emperor whose opinion of them was 40, then the 
acceptance chance would be somewhere in the range of 25 - 55, depending on whether they were a powerful vassal and how
honourable the Emperor is.
To maximise the acceptance chance the character should look to maximise relations with the Emperor and utilise the Vassal
Options listed above.

There is also a slightly increased acceptance chance for Czech (or child any cultures) rulers petitioning for the 
Kingdom of Bohemia.

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

### Carinthia
Control the region comprising the duchies Carinthia, Krain and Istria.

Included to break up the large Bavaria Kingdom.

## Culture
Upon receiving a Kingdom the following check will happen:
* is dlc Royal Court enabled?
* is the character AI and game rule allows AI culture divergence?
* is the character **not** a cultural head?
* is the characters capital within their new Kingdom?

If these checks pass then the mod will attempt to diverge the character's culture or convert to the local culture. The
aim of this functionality is to diversify the cultures within the HRE.

### Diverge Culture
The culture diverge event will trigger if the character is able to diverge into any of the below cultures:
* Austrian
* Lothringian 
* Lorrainian
* Upper Saxon
* Swiss
* Arpitan
* Burgundian 
* Provancale

Note that some base game rules have been relaxed to allow more unique diverges (see miscellaneous section below).
 
The event has three options:
* randomly diverge culture - performs culture divergence like the AI would. (AI will always choose this)
* gain diverge culture cost reduction - allows the player to defer divergence for later so that they can hand-craft the changes
* stay with your current culture

If either option one or two are picked then **enhanced** culture conversion will happen once the culture diverges. This
is simply a stronger culture conversion effect, and will convert your capital and surrounding lands regardless of the
counties culture. (Note that it will be confined to land within your Kingdom title as well as within your top liege's 
borders). Vassals will be more likely to convert than the base game effect also.

### Convert to Local Culture
This event will trigger if the divergence event above cannot happen and if the character's capital culture lacks a strong
culture head. The event has two options:

* convert to local culture - has the same effect as the base game decision (AI will always choose this)
* stay with your current culture

## 867 Start Date
This mod has largely been designed around start dates with an established HRE, however there has been some attempt to 
cater for the 867 start date. Specifically the situation where all of Francia becomes de jure part of the HRE. 

In this scenario Brittany, France and Aquitaine can only be formed via the petition decision.

The Kingdom of Upper Saxony will have slightly easier requirements in the 867 start due to the existence of Sorbia.

## Game Rules

### Culture Check
Whether to impose a culture requirement for certain Kingdoms. 

Options: Required (default), Not Required.

### Austria Renown Level
The dynasty renown level required for the 'Secure the Archduchy' decision. 

Options: Noteworthy, Reputable (default), Well-Known

### Capital Region Check
Whether to require that capitals are in certain regions for certain Kingdoms.
Options: Required (default), Not Required.

### Emperor's Acceptance Base Chance
The base chance for the Emperor to accept the Kingdom petition. It is possible for this to go lower based on the Emperor's
opinion of the character.

Options: 0%, 5%, 10%, 15%, 20% (default), 25%, 30%

## Flavorization
This mod applies the following flavorization to HRE vassals holding HRE Kingdoms:
* Kingdom Title -> Principality
* Kingdom Title Holder (Male) -> Prince
* Kingdom Title Holder (Female) -> Princess

The exception to this rule is Bohemia, which historically was allowed to be the only Kingdom in the HRE.

The mod also enables the Switzerland flavorization, which already existed in game but for whatever reason was disabled.

## Miscellaneous Changes
* New mayors for cities will now prefer to use the county's culture over their predecessor's culture
* Swiss can now be diverged by any culture with Central Germanic Heritage
* Lothringian/Lorrainian can now be diverged if holding the Kingdom of Lothringian as your primary title
* Provancale culture divergence will now be prioritised over Arpitan
* Saxon Elective Realm Law can now be applied to the Kingdom of Saxony title

## Compatibility
This mod changes the definition files of the HRE Kingdom and so whilst unlikely to cause crashes you will see strange
behaviour with other mods that either:
* add or remove duchies to HRE Kingdoms
* add or remove Kingdoms to the HRE empire (and surrounding empires)

A compatibility mod has been created for Culture Expanded. Subscribe to [this mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3504921484) if you are using it.

## Localization
Localization files for all supported languages has been provided by [ModTranslationHelper](https://github.com/JuryReimis/ModTranslationHelper/blob/master/README.md).

Please note that these files are machine translated and most likely will not be 100% accurate. I welcome any modders out
there to provide language support for this mod.

Below lists mods which provide localization support for this mod. If your preferred language appears below you must use the
associated mod as the machine generated localization will have been removed.

[Chinese Localization Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3090564070) - thanks to [無壹](https://steamcommunity.com/profiles/76561198113539588)

## Bug/Issues
This mod has been tested to the best of my abilities. If any bugs or issues are found please described them in a comment.