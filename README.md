[h1]Kingdoms of the HRE[/h1]
Mod that changes how Kingdoms are formed in the HRE for both the player and AI.
These changes apply to both existing HRE Kingdoms and creatable ones.

[h2]Key Details[/h2]
* Kingdoms within the HRE's 'sphere of influence' can no longer be created in the regular way by vassals of the HRE
* After gaining enough provinces, HRE vassals will need to petition the Emperor in order to be granted a Kingdom title
* The Emperor will be given the options to either accept or reject the petition
* Creatable HRE Kingdoms are now also created via the petition decision, including the previously unimplemented Kingdom of Saxony 

[h2]Petition the Emperor for a Kingdom Decision[/h2]
New decision for Dukes and Counts that are members of the HRE. 
Select a specific Kingdom to petition the Emperor for, providing the character meets the Kingdom's specific requirements.

[h3]Vassal Options[/h3]
When sending the decision the vassal will have the options to improve their chances, either by winning a diplomacy check
against the Emperor or spending by gold.

If they have a strong hook against the Emperor they will also have the option to use that which guarantees acceptance, 
but at an extreme cost to your relationship to the Emperor.

Should the Emperor refuse the petition the Vassal may decide it's time to take the Empire for themselves and could gain 
an unpressed claim on the HRE...

[h3]Acceptance Chance[/h3]
The biggest factor for the Emperor's accept chance is their opinion of you, ranging from -100 to 100.

Other things that can affect the decision are:
* whether the vassal is an elector
* whether the vassal is a powerful vassal
* the vassal options as described above
* how honorable the Emperor's personality is
* the Emperor's Acceptance Modifier game rule

[h2]Existing Kingdoms[/h2]
The following Kingdoms are considered under the HRE's sphere of influence:
* Bavaria
* Burgundy
* Frisia
* Italy
* Lotharingia

The following Kingdoms are considered under the HRE's sphere of influence if they become a de jure part of the HRE
* Aquitaine
* Bohemia
* Brittany
* France

[h2]Creatable Kingdoms[/h2]
The decisions to create Switzerland and Austria have been removed and instead combined into the petition decision.

The Principality of Saxony, a defined but unimplemented Kingdom, has also been added.

[h3]Austria[/h3]
The core duchies required have remained the same, as well as the duchies that can be added if controlled.

The requirement differences from the original decision are:
* Liege no longer needs to directly be the Emperor (prevents a soft-lock issue should the Kingdom of Bavaria form)
* Prestige requirement lowered to Distinguished
* New dynasty level of Reputable requirement (to justify the Primogeniture law gain, can be adjusted in game rules) 
* Removed need for strong hook
* Removed need for High or Absolute Crown authority
* Remove dynasty cannot be same as Emperor block

This mod also will make duchies of Krain and Istria a de jure part of the Kingdom of Austria should the player fully 
control the duchy of Carinthia (as opposed to offloading them to the non HRE Kingdom of Croatia).

[h3]Switzerland[/h3]
The core duchies required have remained the same, as well as the duchy that can be added if controlled.

The requirement differences from the original decision are:
* Liege no longer needs to directly be an Emperor (prevents a soft-lock issue should the Kingdom of Burgundy form)
* Prestige requirement lowered to Distinguished
* New requirement to improve the development of the core Swiss provinces

[h3]Saxony[/h3]
New Kingdom that be can be formed using the duchies of Anhalt, Lausitz, Meissen and Thuringia.

The requirements are:
* Fully controls the duchy of Anhalt and at least one other Saxony duchy
* Prestige requirement of Distinguished
* A specific military strength
* Has Saxon culture (can be disabled via game rules)

[h2]867 Start Date[/h2]
This mod has largely been designed around start dates with an established HRE, however there has been some attempt to 
cater for the 867 start date. Specifically the situation where all of Francia becomes de jure part of the HRE. 
In this scenario Brittany, France and Aquitaine can only be formed via the petition decision.

[h2]Game Rules[/h2]

[h3]Culture Check[/h3]
Whether to impose a culture requirement for certain Kingdoms. 
Options: Required (default), Not Required.

[h3]Emperor's Acceptance Modifier[/h3]
Whether to modifier the Emperor's accept petition chance, making it easier or harder to form a Kingdom. 
Options: Halved, No modifier (default), Doubled 

[h3]Austria Renown Level[/h3]
The dynasty renown level required for the Austria petition. 
Options: Noteworthy, Reputable (default), Well-Known

[h2]Flavorization[/h2]
This mod applies the following flavorization to HRE vassals holding HRE Kingdoms:
* Kingdom Title -> Principality
* Kingdom Title Holder (Male) -> Prince
* Kingdom Title Holder (Female) -> Princess

The exception to this rule is Bohemia, which historically was allowed to be the only Kingdom in the HRE.

The mod also enables the Switzerland flavorization, which already existed in game but for whatever reason was disabled.

[h2]Compatibility[/h2]
This mod will likely be incompatible with mods in the following areas:
* mods that update the Kingdom definitions of the HRE Kingdoms
* mods that change the form Austria or Switzerland decisions (though the underlying scripted effects are untouched)
* mods that change flavorization of the HRE Kingdoms

[h3] Similar Mods [/h3]
These mods do similar things and could be use an alternative. They are assumed to be incompatible with this mod.
* [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2412107778&searchtext=saxony]Restore Saxony[/url] - Implements the Kingdom of Saxony
* [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2420327048&searchtext=hre+kingdoms]No HRE Kingdoms[/url] - Prevents the AI from forming HRE Kingdoms

[h2] Localization [/h2]
Localization for supported locales has been provided by using [url=https://github.com/b3llyfish/CK3_LocalizationChanger].

[h2] Bug/Issues [/h2]
This mod has been tested to the best of my abilities. If any bugs or issues are found please described them in a comment.