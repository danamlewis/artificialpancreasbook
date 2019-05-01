# Glossary

Explanations of words, phrases, abbreviations, and acronyms referenced throughout the book:

**AndroidAPS** - an open source implementation of an APS where the Android phone is the controller and holds a version of the OpenAPS algorithm, and communicates via Bluetooth to a Bluetooth-enabled insulin pump.

**APS or AP -** Artificial Pancreas System. A term for a closed-loop automated insulin delivery system in which insulin dosing is adjusted to keep or return BG to target.

**basal -** baseline insulin level that is pre-programmed into your pump and mimics the insulin your pancreas would give throughout the day and night

**BG** - Blood Glucose

**bolus** - extra insulin given by a pump, usually to correct for a high Blood Glucose \(BG\) or for carbohydrates. Differentiated from “basal” or baseline insulin delivery

**CGM -** Continuous Glucose Monitor, a temporary glucose sensor that is inserted into your skin \(with a self- retracting needle\) and provides BG readings approximately every 5 minutes. Different models exist in the market with various calibration requirements varying from no calibrations to 2 a day, and official sensor lifetimes varying from 6-10 days.

**closed-loop** - closed-loop systems make automatic adjustments to basal delivery, without needing user- approval, based on an algorithm. Also known as APS. There are different types, from “hybrid” \(where the user is still expected to enter information and manually dose for meals\) to “fully” closed loops \(where the user does minimal interactions with the system\).

**carb ratio, or CR** - carbohydrate ratio - the amount of carbohydrates that are covered by one standard unit of insulin. Example: 1 U of insulin for 10 carbs.

I**OB** - Insulin On Board, or insulin active in your body.

Note that most commercially available pumps calculate IOB based on bolus activity only. Some APS may also consider only bolus insulin to be part of IOB. However, the DIY community uses “net” IOB to calculate positive or negative insulin activity relative to your baseline, basal amounts. If evaluating an APS \(DIY or commercial\), make sure you understand how IOB is calculated.

**loop or “looping”** - note the lowercase use of this word, meant to describe using a closed loop/APS.

**Loop** - note the uppercase use of this word, meant to describe one of the DIY systems that holds the algorithm on an iPhone and requires the user to carry a radio device \(e.g. “Rileylink”\) to bridge communications between the pump and the phone.

**negative IOB** – when your netIOB is less than zero, which can occur when your temporary basal rate adjustments are less than your typically scheduled basal amount at that time. If you frequently get negative IOB at the same time of day on a regular basis, some of your settings may need adjusting.

**net IOB** - amount of Insulin On Board, taking into account any adjusted \(higher or lower\) basal rates \(see basal IOB above\) plus bolus activity.

**NS, or Nightscout** - a cloud-based visualization and remote-monitoring tool, designed by and for the diabetes community.

**OpenAPS** - refers to the open source artificial pancreas movement, as well as a specific DIY system. An OpenAPS system has a small computer controller, a “rig”, that holds the algorithm and has a radio to communicate with the insulin pump and CGM.

**open loop** - open-loop systems will suggest recommended adjustments to insulin dosing, but will not enact those suggestions. It’s a decision support system, but not a closed loop.

**oref0 -** another name for the main algorithm used in OpenAPS

**Time in Range \(TIR\)** – a newer, standardized way of reporting CGM data, in addition to the A1c metric. Typical TIR for research studies is a range from 80-180 mg/dL, although different studies and different individuals may report or strive for different ranges.

{% hint style="info" %}
Looking for a word you don't see here? Make sure to also check out the [T1D/Diabetes Tech Dictionary](https://www.winchcombe.org/t1resources/dictionary.aspx). 
{% endhint %}

